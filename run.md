```bash
ibmcloud ce application create   --name mcp-server   --build-source https://github.com/joshuazhou744/test-mcp-ce   --image us.icr.io/sn-labs-joshuazhou/mcp-server   --registry-secret icr-secret   --wait
```

```bash
ibmcloud ce application logs -f --name mcp-server
```

```bash
ibmcloud ce application delete --name mcp-server
```

```bash
ibmcloud ce application list
```

list images

```bash
ibmcloud cr image-list --restrict sn-labs-joshuazhou
```