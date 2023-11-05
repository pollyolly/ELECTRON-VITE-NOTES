### ELECTRON-VITE-NOTES

Installation
```vim
$npm create electron-vite
Project Name: electron-portfolio
$cd electron-portfolio
$npm install
```
Setup
```javascript
import tsconfigPaths from 'vite-tsconfig-paths'
// https://vitejs.dev/config/
export default defineConfig({
  plugins: [
    tsconfigPaths(),
  ],
})
```
