# Docker Build example

## Commands

### Node commands

1. npm install
2. node app.js

### Docker commands

**Build**
`docker build -t <name> .`

**Run with bind mounted volume**

```
docker run --name "bind-mounted-demo" -d -p 3000:3000 -v <local-folder>:/app <image-name>
```

_Obs!_ Image name must be last command.
