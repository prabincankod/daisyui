---
title: Carousel
desc: Carousel show images or content in a scrollable area.
published: true
---

<script>
  import Component from "@components/Component.svelte"
</script>

<Component title="Snap to start (default)">
<div class="carousel rounded-box">
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=8B7BCDC2" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=500B67FB" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=A89D0DE6" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=225E6693" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=9D9539E7" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=BDC01094" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=7F5AE56A" alt="Burger">
  </div>
</div>
<pre slot="html">{
`<div class="carousel rounded-box">
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=8B7BCDC2" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=500B67FB" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=A89D0DE6" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=225E6693" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=9D9539E7" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=BDC01094" alt="Burger">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/burger?w=400&h=300&hash=7F5AE56A" alt="Burger">
  </div>
</div>`
}</pre>
</Component>

<Component title="Snap to center">
<div class="carousel carousel-center rounded-box">
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=8B7BCDC2" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=500B67FB" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=A89D0DE6" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=225E6693" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=9D9539E7" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=BDC01094" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=7F5AE56A" alt="Pizza">
  </div>
</div>
<pre slot="html">{
`<div class="carousel carousel-center rounded-box">
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=8B7BCDC2" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=500B67FB" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=A89D0DE6" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=225E6693" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=9D9539E7" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=BDC01094" alt="Pizza">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/pizza?w=400&h=300&hash=7F5AE56A" alt="Pizza">
  </div>
</div>`
}</pre>
</Component>

<Component title="Snap to end">
<div class="carousel carousel-end rounded-box">
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=8B7BCDC2" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=500B67FB" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=A89D0DE6" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=225E6693" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=9D9539E7" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=BDC01094" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=7F5AE56A" alt="Drink">
  </div>
</div>
<pre slot="html">{
`<div class="carousel carousel-end rounded-box">
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=8B7BCDC2" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=500B67FB" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=A89D0DE6" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=225E6693" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=9D9539E7" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=BDC01094" alt="Drink">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/drink?w=400&h=300&hash=7F5AE56A" alt="Drink">
  </div>
</div>`
}</pre>
</Component>

<Component title="Carousel with full width items">
<div class="w-64 carousel rounded-box">
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=8B7BCDC2" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=500B67FB" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=A89D0DE6" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=225E6693" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=9D9539E7" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=BDC01094" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=7F5AE56A" class="w-full">
  </div>
</div>
<pre slot="html">{
`<div class="w-64 carousel rounded-box">
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=8B7BCDC2" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=500B67FB" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=A89D0DE6" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=225E6693" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=9D9539E7" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=BDC01094" class="w-full">
  </div> 
  <div class="w-full carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=7F5AE56A" class="w-full">
  </div>
</div>`
}</pre>
</Component>

<Component title="Vertical carousel">
<div class="h-96 carousel carousel-vertical rounded-box">
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=8B7BCDC2">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=500B67FB">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=A89D0DE6">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=225E6693">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=9D9539E7">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=BDC01094">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=7F5AE56A">
  </div>
</div>
<pre slot="html">{
`<div class="h-96 carousel carousel-vertical rounded-box">
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=8B7BCDC2">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=500B67FB">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=A89D0DE6">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=225E6693">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=9D9539E7">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=BDC01094">
  </div> 
  <div class="carousel-item h-full">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=7F5AE56A">
  </div>
</div>`
}</pre>
</Component>

<Component title="Carousel with half width items">
<div class="w-96 carousel rounded-box">
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=8B7BCDC2" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=500B67FB" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=A89D0DE6" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=225E6693" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=9D9539E7" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=BDC01094" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=7F5AE56A" class="w-full">
  </div>
</div>
<pre slot="html">{
`<div class="w-96 carousel rounded-box">
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=8B7BCDC2" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=500B67FB" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=A89D0DE6" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=225E6693" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=9D9539E7" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=BDC01094" class="w-full">
  </div> 
  <div class="w-1/2 carousel-item">
    <img src="https://api.lorem.space/image/game?w=256&h=400&hash=7F5AE56A" class="w-full">
  </div>
</div>`
}</pre>
</Component>

<Component title="Full-bleed carousel">
<div class="max-w-md p-4 space-x-4 carousel carousel-center bg-neutral rounded-box">
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=8B7BCDC2" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=500B67FB" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=A89D0DE6" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=225E6693" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=9D9539E7" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=BDC01094" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=7F5AE56A" class="rounded-box">
  </div>
</div>
<pre slot="html">{
`<div class="max-w-md p-4 space-x-4 carousel carousel-center bg-neutral rounded-box">
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=8B7BCDC2" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=500B67FB" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=A89D0DE6" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=225E6693" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=9D9539E7" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=BDC01094" class="rounded-box">
  </div> 
  <div class="carousel-item">
    <img src="https://api.lorem.space/image/furniture?w=250&h=180&hash=7F5AE56A" class="rounded-box">
  </div>
</div>`
}</pre>
</Component>

<Component title="Carousel with indicator buttons" desc="This slider works with anchor links so the browser will vertically to the image when you click buttons.">
<div class="w-full carousel">
  <div id="item1" class="w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=8B7BCDC2" class="w-full">
  </div> 
  <div id="item2" class="w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=500B67FB" class="w-full">
  </div> 
  <div id="item3" class="w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=A89D0DE6" class="w-full">
  </div> 
  <div id="item4" class="w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=225E6693" class="w-full">
  </div>
</div> 
<div class="flex justify-center w-full py-2 gap-2">
  <a href="#item1" class="btn btn-xs">1</a> 
  <a href="#item2" class="btn btn-xs">2</a> 
  <a href="#item3" class="btn btn-xs">3</a> 
  <a href="#item4" class="btn btn-xs">4</a>
</div>
<pre slot="html">{
`<div class="w-full carousel">
  <div id="item1" class="w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=8B7BCDC2" class="w-full">
  </div> 
  <div id="item2" class="w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=500B67FB" class="w-full">
  </div> 
  <div id="item3" class="w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=A89D0DE6" class="w-full">
  </div> 
  <div id="item4" class="w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=225E6693" class="w-full">
  </div>
</div> 
<div class="flex justify-center w-full py-2 gap-2">
  <a href="#item1" class="btn btn-xs">1</a> 
  <a href="#item2" class="btn btn-xs">2</a> 
  <a href="#item3" class="btn btn-xs">3</a> 
  <a href="#item4" class="btn btn-xs">4</a>
</div>`
}</pre>
</Component>

<Component title="Carousel with next/prev buttons" desc="This slider works with anchor links so the browser will vertically to the image when you click buttons.">
<div class="w-full carousel">
  <div id="slide1" class="relative w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=8B7BCDC2" class="w-full"> 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide4" class="btn btn-circle">❮</a> 
      <a href="#slide2" class="btn btn-circle">❯</a>
    </div>
  </div> 
  <div id="slide2" class="relative w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=500B67FB" class="w-full"> 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide1" class="btn btn-circle">❮</a> 
      <a href="#slide3" class="btn btn-circle">❯</a>
    </div>
  </div> 
  <div id="slide3" class="relative w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=A89D0DE6" class="w-full"> 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide2" class="btn btn-circle">❮</a> 
      <a href="#slide4" class="btn btn-circle">❯</a>
    </div>
  </div> 
  <div id="slide4" class="relative w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=225E6693" class="w-full"> 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide3" class="btn btn-circle">❮</a> 
      <a href="#slide1" class="btn btn-circle">❯</a>
    </div>
  </div>
</div>
<pre slot="html">{
`<div class="w-full carousel">
  <div id="slide1" class="relative w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=8B7BCDC2" class="w-full"> 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide4" class="btn btn-circle">❮</a> 
      <a href="#slide2" class="btn btn-circle">❯</a>
    </div>
  </div> 
  <div id="slide2" class="relative w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=500B67FB" class="w-full"> 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide1" class="btn btn-circle">❮</a> 
      <a href="#slide3" class="btn btn-circle">❯</a>
    </div>
  </div> 
  <div id="slide3" class="relative w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=A89D0DE6" class="w-full"> 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide2" class="btn btn-circle">❮</a> 
      <a href="#slide4" class="btn btn-circle">❯</a>
    </div>
  </div> 
  <div id="slide4" class="relative w-full carousel-item">
    <img src="https://api.lorem.space/image/car?w=800&h=200&hash=225E6693" class="w-full"> 
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide3" class="btn btn-circle">❮</a> 
      <a href="#slide1" class="btn btn-circle">❯</a>
    </div>
  </div>
</div>`
}</pre>
</Component>