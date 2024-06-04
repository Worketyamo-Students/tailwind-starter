# Wedding Project

## Initialisation 
##### 1. Ajout du lien CDN dans notre projet 

```html
  <script src="https://cdn.tailwindcss.com"></script>
```
##### 2. Creation du fichier de configuration

```bash 
touch tailwind.config.js
```
##### 3. Creation de configuration 
EXEMPLE : 

```js 
/** @type {import('tailwindcss').Config} */
module.exports = {
    content: ['./src/**/*.{html,js}'],
    theme: {
      colors: {
        'blue': '#1fb6ff',
        'purple': '#7e5bef',
        'pink': '#ff49db',
        'orange': '#ff7849',
        'green': '#13ce66',
        'yellow': '#ffc82c',
        'gray-dark': '#273444',
        'gray': '#8492a6',
        'gray-light': '#d3dce6',
      },
      fontFamily: {
        sans: ['Graphik', 'sans-serif'],
        serif: ['Merriweather', 'serif'],
      },
      extend: {
        spacing: {
          '8xl': '96rem',
          '9xl': '128rem',
        },
        borderRadius: {
          '4xl': '2rem',
        }
      }
    },
  }
```

##### 4. Importation de la configuration

```html 
<script src="./tailwind.config.js"></script>
```

#### Notions à retenir 
- Framework 
- Initialisation de tailwindCss 
- Configuration de Tailwind css 
- installation des extensions 