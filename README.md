Creating the project from zero

```
mkdir sample-mcp-server && cd sample-mcp-server
npm init -y
npm install -D typescript @types/node
npx tsc --init
```

Downgrade ts to 5.8.x

```
npm install -D typescript@5.8.3
```

Add linter:

```
npm install -D eslint @eslint/js typescript-eslint
```

Start the MCP inspector

```
npx tsc && npx @modelcontextprotocol/inspector
```
