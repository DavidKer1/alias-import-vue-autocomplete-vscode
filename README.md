# Configuration to autocomplete vue with alias ( @/ )
- jsconfig.json
```javascript
{
    "allowJs": true,
    "compilerOptions": {
        "baseUrl": ".",
        "paths": {
            "@/*": ["./src/*"]
        }
    },
    "include": ["src/**/*"],
    "exclude": ["node_modules"]
}
```
- .vscode/settings.json:
```javascript
{
    "path-intellisense.mappings": {
      "@": "${workspaceRoot}/src"
    }
}
```
