# Fortinet 

---

## CLI

### Interface configuration

```sh
# Show information about interfaces
$ show system interface 

# Edit a specific interface
$ edit <interface_name>

# Static IP configuration
$ config system interface
$ edit <port_number>
$ set mode static
$ set ip <ip_address> <mask>
$ end

# Enable http, ssh, ping access
$ set allowaccess http ssh ping
$ end

# Show details about interface
$ config system interface
$ edit <port_number>
$ get
```

### Use this command only on the VM evaluate licence 

```bash
# Reset the vm on the facoty default configuration
$ exec factoryreset
```
