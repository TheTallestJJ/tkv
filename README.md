# TKV - Terminal Key-value

A simple terminal utility to store key-value pairs.

## Commands

```
tkv write <key> <value | @file | ->
```

alias: `w`

//TODO

Write <value> to <key>
Or write contents of @file to <key>
Or write contents of stdin to <key>

```
tkv read <key> 
```

alias: `r`

//TODO

Read from <key>

```
tkv list [key] 
```

alias: `l[s]`

//TODO

List keys and types.

```
tkv edit <key>
```

alias: `e`

//TODO

Edit the value stored in <key> in the editor in $EDITOR

```
tkv namespace <key>
```

alias: `n`

//TODO

Changes the current namespace, basically a pre-fix to the given keys.
