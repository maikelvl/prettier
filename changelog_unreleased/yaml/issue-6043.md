#### Do not indent YAML seqences. ([issue #6043](https://github.com/prettier/prettier/issues/6043) by [@maikelvl](https://github.com/maikelvl))


<!-- prettier-ignore -->
```yaml
// Input
sequence:
 - one
 - two

// Prettier stable
sequence:
  - one
  - two

// Prettier master
sequence:
- one
- two
```
