
<i>8kb js 4kb css kodu ile tam donanımlı carousel kullanın...</i>

# Default kullanımı
  Basit kullanımda ileri ve geri butonları ile kullanımını göreceksiniz. Bu ve diğer kullanımlarını gördükten sonra      carousel'in ne kadar kolay ve performanslı olduğunu göreceksiniz.
<br>[codepen linki](https://codepen.io/by-Meftunca/pen/ZrpRZE)'ne giderek önizleyebilirsiniz...

```html
<div class="carousel-slider" id="basic">
    <div class="carousel-content">
        <aside class="slide-item">slide 1</aside>
        <aside class="slide-item">slide 2</aside>
        <aside class="slide-item">slide 3</aside>
        <aside class="slide-item">slide 4</aside>
        <aside class="slide-item">slide 5</aside>
    </div>
    <button class="carousel-prev-btn"><i class="fa fa-chevron-left" aria-hidden="true"></i></button>
    <button class="carousel-next-btn"><i class="fa fa-chevron-right" aria-hidden="true"></i></button>
</div>
```

# Pagination kullanımı
  Pagination kullanmak için iki yolunuz var.
  - Js içinde özelleştirdiğiniz sliderınıza parametre olarak `pagination:true` eklemeniz 
  - html içinde sliderınızı bulum carousel-content kısmına yeni bir `data-pagination="true"` attr'sini eklemek
 Gördüğünüz gibi pagination'ı aktif etmek bu kadar basit...
<br>[codepen linki](https://codepen.io/by-Meftunca/pen/mXrjJL)'ne giderek önizleyebilirsiniz...

```html
<div class="carousel-slider" id="pagination">
    <div class="carousel-content" data-pagination="true">
        <aside class="slide-item">slide 1</aside>
        <aside class="slide-item">slide 2</aside>
        <aside class="slide-item">slide 3</aside>
        <aside class="slide-item">slide 4</aside>
        <aside class="slide-item">slide 5</aside>
    </div>
    <div class="carousel-pagination stick"></div>
  // stick veya
    <div class="carousel-pagination"></div>//yuvarlak ayarlı olarak kullanın
</div>
```
# Grid kullanımı
  Grid kullanmak için iki yolunuz var.
  - Js içinde özelleştirdiğiniz sliderınıza parametre olarak `grid:{xl:'',lg:'',md:'',sm:''}` eklemeniz 
  - html içinde sliderınızı bulum carousel-content kısmına yeni bir `data-grid="{xl:'',lg:'',md:'',sm:''}"` attr'sini eklemek
 Gördüğünüz gibi grid sistemini aktif etmek bu kadar basit...
<br>[codepen linki](https://codepen.io/by-Meftunca/pen/mXrjJL)'ne giderek önizleyebilirsiniz...

```html
<div class="carousel-slider" id="responsive">
    <div class="carousel-content" data-grid='{"xl":4,"lg":3,"md":2,"sm":1}' data-pagination="true">
        <aside class="slide-item">slide 1</aside>
        <aside class="slide-item">slide 2</aside>
        <aside class="slide-item">slide 3</aside>
        <aside class="slide-item">slide 4</aside>
        <aside class="slide-item">slide 5</aside>
    </div>
    <button class="carousel-prev-btn"><i class="fa fa-chevron-left" aria-hidden="true"></i></button>
    <button class="carousel-next-btn"><i class="fa fa-chevron-right" aria-hidden="true"></i></button>  
    <div class="carousel-pagination stick"></div>
</div>
```

# Autoplay kullanımı
  Autoplay kullanmak için iki yolunuz var.
  - Js içinde özelleştirdiğiniz sliderınıza parametre olarak `autoplay:{playTimer:5000}` eklemeniz 
  - html içinde sliderınızı bulum carousel-slider kısmına yeni bir `data-autoplay="true"` `data-timer="geçiş süresi örnek(5000)"` attr'sini eklemek
 Gördüğünüz gibi Autoplay sistemini aktif etmek bu kadar basit...
<br>[codepen linki](https://codepen.io/by-Meftunca/pen/yvaqoY)'ne giderek önizleyebilirsiniz...

```html
<div class="carousel-slider" id="autoplay" data-autoplay="true" data-timer="4000">
    <div class="carousel-content"  data-pagination="true">
        <aside class="slide-item">slide 1</aside>
        <aside class="slide-item">slide 2</aside>
        <aside class="slide-item">slide 3</aside>
        <aside class="slide-item">slide 4</aside>
        <aside class="slide-item">slide 5</aside>
    </div>
    <button class="carousel-prev-btn"><i class="fa fa-chevron-left" aria-hidden="true"></i></button>
    <button class="carousel-next-btn"><i class="fa fa-chevron-right" aria-hidden="true"></i></button>  
    <div class="carousel-pagination stick"></div>
</div>
```
