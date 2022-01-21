This repo is for testing npm workspaces feature in [Cachito](https://github.com/containerbuildsystem/cachito).<br> 
Package is called npm_test. There is workspace 'a' and into that workspace was installed the dependency abbrev. It was created using commands:

```
npm init -y
npm init -w a
npm install abbrev -w a
```

