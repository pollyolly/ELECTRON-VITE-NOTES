### ELECTRON-VITE-NOTES

#### Installation
```vim
$npm create electron-vite
Project Name: electron-portfolio
$cd electron-portfolio
$npm install

```
#### Setup
vite.config.ts

$npm install vite-tsconfig-paths
```javascript
import tsconfigPaths from 'vite-tsconfig-paths'
export default defineConfig({
  plugins: [
    tsconfigPaths(),
    ...
  ],
})
```
tsconfig.json
```json
{
  "compilerOptions": {
...
"baseUrl": "",
    "paths": {
      "@/*":[
        "src/*"
      ],
      "Components/*": ["./src/Components/*"],
      "Interface": ["./src/Utilities/*"],
    },
...
}
```
