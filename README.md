# Karabiner-Elements Schema

JSON schema for config file of [Karabiner-Elements](https://github.com/pqrs-org/Karabiner-Elements).

## Usage

Add `$schema` on your config file.

```diff
// ~/.config/karabiner/karabiner.json

{
+  "$schema": "https://raw.githubusercontent.com/kazuito/karabiner-elements-schema/main/config.json",
   ...
}
```
