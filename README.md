# Launch example nix shell

Change directory to git repo and run:

```
docker run -it -v $(pwd):/workdir nixos/nix
```
Let's start the nix shell:

```
cd /workdir && nix-shell
```