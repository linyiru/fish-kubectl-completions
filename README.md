# kubectl completion for fish shell

## Install

```fish
$ mkdir -p ~/.config/fish/completions
$ cd ~/.config/fish
$ git clone https://github.com/linyiru/fish-kubectl-completions
$ ln -s ../fish-kubectl-completions/kubectl.fish completions/
```

## Environment Variables

### `FISH_KUBECTL_COMPLETION_TIMEOUT`

This is used to pass the `--request-timeout` flag to the `kubectl` command.
It defaults to `5s`.

> Non-zero values should contain a corresponding time unit (e.g. 1s, 2m, 3h).
> A value of zero means don't timeout requests.

## Author

Evan Lucas

## License

MIT
