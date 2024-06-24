# cyctl delete modules

Delete one or more modules

### Synopsis

The delete modules command allows you to remove one or more modules from the Cyclops API.

```
cyctl delete modules [module_name] [flags]
```

### Examples

```
# Delete a single module
cyctl delete modules module1

# Delete multiple modules
cyctl delete modules module1 module2 module3
```

### Options

```
  -h, --help   help for modules
```

### SEE ALSO

* [cyctl delete](cyctl_delete.md)	 - Delete custom resources like modules, templates, and templateauthrules

###### Auto generated by spf13/cobra on 24-Jun-2024