# ANCHOR

```yaml
name: &name "Mike"  # define; anchor name doesn't have to be same as key
id: *name           # access; if value of key 'name' changed, this changes automatically
```

## Key-Value Pair

```yaml
base: &base
  bar1: 1

foo:
  <<: base
  bar2: 2
# foo has bar1 and bar2
```
