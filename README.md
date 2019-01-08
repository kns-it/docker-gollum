# Gollum Wiki within Docker

## Usage

The easiest way to use the container image is to define an Bash alias:

```bash
alias gollum='docker run --rm -ti --name gollum -u `id -u` -v `pwd`:/work -p 127.0.0.1:4567:4567 knsit/gollum'
```
