# Typographie

## font family

- font-sans
- font-mono
- font-serif

pour l'appliquer de manière conditionnelle 
 ```html
<p class="font-sans hover:font-serif">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
</p>

<p class="font-sans md:font-serif">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
</p>
```	

## font size
- text-xs
- text-sm
- text-base
- text-lg
- text-xl
- text-2xl
- text-3xl
- text-4xl
- text-5xl
- text-6xl
- text-7xl
- text-8xl
- text-9xl

``` html
<p class="text-sm ...">The quick brown fox ...</p>
<p class="text-base ...">The quick brown fox ...</p>
<p class="text-lg ...">The quick brown fox ...</p>
<p class="text-xl ...">The quick brown fox ...</p>
<p class="text-2xl ...">The quick brown fox ...</p>
```

## line-height

- leading-3
- leading-4
- leading-5
- leading-x 

``` html
<p class="leading-3">The quick brown fox ...</p>

<p class="leading-[3rem]">The quick brown fox ...</p>


```


## list style image

```html	
<ul class="list-image-[url(checkmark.png)] ...">
  <li>5 cups chopped Porcini mushrooms</li>
  <!-- ... -->
</ul>
```
### hover 
```html
<ul class="list-image-none hover:list-image-[url(checkmark-hover.png)] ...">
  <li>5 cups chopped Porcini mushrooms</li>
  <!-- ... -->
</ul>
```

## list style type

```html
<ul class="list-disc">
  <li>Now this is a story all about how, my life got flipped-turned upside down</li>
  <!-- ... -->
</ul>

<ol class="list-decimal">
  <li>Now this is a story all about how, my life got flipped-turned upside down</li>
  <!-- ... -->
</ol>

<ul class="list-none">
  <li>Now this is a story all about how, my life got flipped-turned upside down</li>
  <!-- ... -->
</ul>
```

