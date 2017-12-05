# ansible-role-sudo

Installs sudo package and adds user to the correct group for default sudo rights

## Requirements

None

## Role Variables

| Variable Name             | Defaults | Description                                                        |
|---------------------------|----------|--------------------------------------------------------------------|
| sudo_users                |None      | list of users to be added to the group for sudo usage              |


## Dependencies

None

## Example Playbook
```
- hosts: servers
  roles:
    - role: gabethecabbage.sudo
      sudo_users:
        - user1
        - user2
```
