# noobient.wordpress

## Synopsys

This role lets you perform various tasks on your WordPress instances. Currently the only supported task is update.

## Parameters

| Name | Required | Example | Description |
|---|---|---|---|
| `path` | no | `/var/www/html/wordpress` | Path to your WordPress instance. Only optional if `dry_run` is `true`. |
| `user` | no | `nginx` | User to perform the action as. Defaults to `root`. |
| `dry_run` | no | `true` | If `true`, only the required tools are installed, but the upgrade itself is not performed. Defaults to `false`. |

## Examples

```yml
- include_role:
    name: noobient.wordpress
  vars:
    path: '/var/www/html/wordpress'
    user: nginx
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
| AlmaLinux 10 | ✅ | [![AlmaLinux 10](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/almalinux-10.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/almalinux-10.yml) |
| Fedora 42 | ✅ | [![Fedora 42](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/fedora-42.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/fedora-42.yml) |
| Fedora 43 | ✅ | [![Fedora 43](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/fedora-43.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/fedora-43.yml) |
| Ubuntu 22.04 | ✅ | [![Ubuntu 22.04](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-22.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-22.04.yml) |
| Ubuntu 24.04 | ✅ | [![Ubuntu 24.04](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-24.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-24.04.yml) |
| Ubuntu 26.04 | ✅ | [![Ubuntu 26.04](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-26.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-wordpress/actions/workflows/ubuntu-26.04.yml) |
