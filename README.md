# Custom domain name server

## Build
```bash
go build -ldflags "-X main.version=$(git rev-parse --short HEAD)" .
```
## Usage
```bash
dnss <IP to resolve to>
```