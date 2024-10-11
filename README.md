To get started, run the following:

```
curl --proto '=https' --tlsv1.2 -sSf -L \
  https://install.determinate.systems/nix | sh -s -- install
```
```
curl -sfL https://direnv.net/install.sh | bash
direnv allow
```
```
$ nix run
Hello, world!

$ application
Hello, world!

$ docker build . --tag nixdock
$ docker run nixdock
Hello, world!
```
