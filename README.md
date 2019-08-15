# Update Packages

This role will update all packages installed on the system, then schedule a reboot.

## Requirements

No prerequisites

## Role Variables

Right now, there are two variables:

- `debian_apt_cache_valid_time` is the number of seconds for which the apt cache is valid.
- `restart_time` is the time when the computer should be rebooted.

## Dependencies

No dependencies

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - bitsandbooks.update-packages

## License

BSD
