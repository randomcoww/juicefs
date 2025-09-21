### Container build for Juicefs

https://github.com/juicedata/juicefs

Latest release

```bash
curl -s https://api.github.com/repos/juicedata/juicefs/releases/latest | grep tag_name | cut -d '"' -f 4 | tr -d 'v'
```