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
```vim
$npm install vite-tsconfig-paths
```
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
      "Utilities/*": ["./src/Utilities/*"],
      "Types/*": ["./src/Types/*"]
    },
...
}
```
#### Run
```vim
$npm run dev
```
