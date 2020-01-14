
## Default Variables

### java_package

Package to install

#### Default value

```yaml
java_package: oracle-jdk
```

### java_user

User to run user-specific commands

#### Default value

```yaml
java_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
