# tddir

Creates today's work directory (`~/works/YYYY-MM-DD`) and prints its path.

## Usage

```sh
cd $(tddir)
```

```
tddir [-p <prefix>] [-c zsh] [-h]

  -p <prefix>  Use <prefix> as the base directory (default: ~/works)
  -c <shell>   Output completion script (supported: zsh)
  -h           Show this help
```

## Zsh completion

Add to your `.zshrc`:

```sh
eval "$(tddir -c zsh)"
```
