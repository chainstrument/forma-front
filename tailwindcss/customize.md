### tailwindcss.config.js



```js
module.exports = {
  purge: {
    enabled: true,
    content: [
      './src/**/*.html',
      './src/**/*.js',
      './src/**/*.jsx',
      './src/**/*.ts',
      './src/**/*.tsx',
      './src/**/*.vue',
      './src/**/*.php',
      './src/**/*.twig',
    ],
  },
  theme: {
    extend: {
        fontFamily: {
            display: 'Oswald, ui-serif', // Adds a new `font-display` class
        }
    },
    fontSize: {
      sm: '0.8rem',
      base: '1rem',
      xl: '1.25rem',
      '2xl': '1.563rem',
      '3xl': '1.953rem',
      '4xl': '2.441rem',
      '5xl': '3.052rem',
    }
  },
  variants: {},
```
  ## add screen variant 

  ``` js
  /** @type {import('tailwindcss').Config} */
module.exports = {
  theme: {
    extend: {
      screens: {
        '3xl': '1600px', // Adds a new `3xl:` screen variant
      }
    }
  }
}

```

uses it 
``` html
<blockquote class="text-base md:text-md 3xl:text-lg">
  Oh I gotta get on that internet, I'm late on everything!
</blockquote>
```