# noobient.wordpress

## Synopsys

This role lets you perform various tasks on your WordPress instances.

## Parameters

| Name | Required | Example | Description |
|---|---|---|---|
| `path` | no | `/var/www/html/wordpress` | Path to your WordPress instance. Only optional if `dry_run` is `true`. |
| `dry_run` | no | `true` | If `true`, only the required tools are installed, but the upgrade itself is not performed. Defaults to `false`. |

## Examples

```yml
- include_role:
    name: noobient.wordpress
  vars:
    path: '/var/www/html/wordpress'
    dry_run: false
```

## Return Values

N/A

## Support

| Platform | Support | Status |
|---|---|---|
| Linter | ✅ | [![Lint](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/lint.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/lint.yml) |
| AlmaLinux 8 | ✅ | [![AlmaLinux 8](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/almalinux-8.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/almalinux-8.yml) |
| AlmaLinux 9 | ✅ | [![AlmaLinux 9](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/almalinux-9.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/almalinux-9.yml) |
| Fedora 38 | ✅ | [![Fedora 38](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/fedora-38.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/fedora-38.yml) |
| Fedora 39 | ✅ | [![Fedora 39](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/fedora-39.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/fedora-39.yml) |
| Ubuntu 18.04 | ✅ | [![Ubuntu 18.04](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-18.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-18.04.yml) |
| Ubuntu 20.04 | ✅ | [![Ubuntu 20.04](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-20.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-20.04.yml) |
| Ubuntu 22.04 | ✅ | [![Ubuntu 22.04](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-22.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-22.04.yml) |
