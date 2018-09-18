# tips

## Docker

Increase docker constainer shell columns [link](https://github.com/moby/moby/issues/33794#issuecomment-380969582)

```bash
docker exec -e COLUMNS="`tput cols`" -e LINES="`tput lines`" -ti container bash
```

## Linux

When the system is very slow or not responding use the following key combinations:

```bash
# Wait 1 second between each letter key press
# Maintain the CTRL + ALT + SysRQ pressed
CTRL + ALT + SysRQ r e i s u b
```
