# packages

# Add repo
```bash
curl -s --compressed "https://edgexr.github.io/packages/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/edgexr.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://edgexr.github.io/packages/my_list_file.list"
sudo apt update
```

# Install package

```bash
sudo apt install mobiledgex
```
