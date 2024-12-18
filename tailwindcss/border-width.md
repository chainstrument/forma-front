
## border width 

- border
- border-0
- border-2
- border-4
- border-8
- border-x-0 (border-left-0, border-right-0)
- border-x-2 (border-left-2, border-right-2)

``` html
<div class="border-2 ..."></div>
```
 
 ``` js

 module.exports = {
  theme: {
    borderWidth: {
       DEFAULT: '1px',
      '0': '0',
      '2': '2px',
      '3': '3px', //added
      '4': '4px',
      '8': '8px',
    }
  }
}

```

#### arbitrary values

``` html
<div class="border-t-[3px]">
  <!-- ... -->
</div>
```