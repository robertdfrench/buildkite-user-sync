# buildkite-user-sync
Sync organizational users to BuildKite teams from an LDAP-like source

## Running tests
```bash
rake build_venv
export BK_TOKEN="<token>"
export BK_ORGANIZATION="<organization>"
rake test
```
