
## border

### border radius 
- rounded-none
- rounded
- rounded-sm
- rounded-md
- rounded-lg
- rounded-xl
- rounded-2xl
- rounded-3xl

``` html
<button class="rounded-full ...">Save Changes</button> 
```

#### rounded sides separately 

- rounded-t-none
- rounded-t-lg
- rounded-t-xl
- rounded-t-2xl

``` html
<div class="rounded-t-lg ..."></div>
<div class="rounded-r-lg ..."></div>
<div class="rounded-b-lg ..."></div>
<div class="rounded-l-lg ..."></div>
```

Apply conditionally
``` html
<div class="rounded hover:rounded-lg">
  <!-- ... -->
</div>
```


#### customizing our theme
``` js 
module.exports = {
  theme: {
    borderRadius: {
      'none': '0',
      'sm': '0.125rem',
      DEFAULT: '0.25rem',
      DEFAULT: '4px',
      'md': '0.375rem',
      'lg': '0.5rem',
      'full': '9999px',
      'large': '12px',
    }
  }
}

```