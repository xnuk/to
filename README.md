# to.fish
Use `cd` and `ls` at same time

## Install

### [Chips](https://github.com/xtendo-org/chips)

Update your `~/.config/chips/plugin.yaml`:

```
github:
  - xnuk/to
```

And just use `to` instead of `cd`.

## Additional Feature
- If you used `pushd`, then `$ to` works as `popd; ls`.
- Or if you are in git directory, then it goes to git root.
- Or it goes to `$HOME`.
- `$ to path/to/filename` works as `cd path/to/; eval $EDITOR filename`.
