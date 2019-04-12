# An incomplete map of mouse cell lineages
### Install Graphviz
```bash
sudo apt-get install graphviz
```

### Render
```bash
dot -Tps lineages.dot -o lineages.dot.ps
ps2pdf lineages.dot.ps
```
