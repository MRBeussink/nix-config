install `nix`

```sh
curl --proto '=https' --tlsv1.2 -sSf -L https://install.determinate.systems/nix | sh -s -- install
```

rebuild

```sh
darwin-rebuild switch --flake ~/nix#air 
```
