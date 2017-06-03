#Semantic Ecommers
**All About ecommers html with Semantic UI**
@[Authors | Deri Kurniawan | Hacktiv8]
**Semantic Ecommers** Adalah sebuah web terancang secara statis yang ditujukan untuk pembelajaran membuat sebuah web site degan menggunakan **Semantic UI**

- **Semantic UI** - menggunakan CDNJS yag merupakan pengenerate link CSS dari Semantic official ini ditujukan untuk membuat aplikasi tersebut berjalan ringan dibanding harus meng-***include*** file css tersebut kedalam file

- **Semantic JQuery** - Menggunakan CDNJS juga
- **NodeJs** - menggunakan NPM milik NodeJS dengan perintah `npm install --save semantic-ui` lalu menggunakan `gulp build`

[TOC]

##Semantic Button
###Semantic Button Regular
**Introducting**
>Semantic Button adalah sebuah tampilan sederhana menggunakan semantic framework ui css kita bisa menambahkan berbagai hal bahkan sampai animasi kepada button tersebut

``` html
<body>
	<div class="ui container">
		<button class="ui basic button">Hi! Click Me</button>
	</div>
</body>
```
**Untuk meng-custom warna**
```html
<body>
	<div class="ui red container"> <!-- 'red'dapat diganti dengan warna apapun -->
		<button class="ui basic button">Hi! Click Me</button>
	</div>
</body>
```
**Dapat menggunakan secara continue**
```html
<body>
	<div class="ui red container"> <!-- 'red'dapat diganti dengan warna apapun -->
		<button class="ui basic button"><i class="arrow icon"></i></button>
		<button class="ui basic button"><i class="arrow icon"></i></button>
		<button class="ui basic button"><i class="arrow icon"></i></button>
	<!-- icon digunakan menggunakan tag i 'basic' dapat diganti dengan primary-->
	</div>
</body>
```
###Semantic Button Animations
```html
<body>
    <div class="ui container">
      <button type="button" name="button" class="ui animated button">
        <span class="visible content">Next</span>
        <span class="hidden content"><i class="right arrow icon"></i></span>
      </button>
    </div>
  </body>
```
>animation pada Semantic dapat dirubah menggunakan beberapa animasi tertentu semisal `class="ui fade animated button"`

atau dapat menggunakan cara seperti ini : (variasi)
```htmlbars
<body>
    <div class="ui container">
      <div class="ui buttons">
	      <!-- dibungkus div ui buttons untuk efek menyatu -->
        <button class="ui button"><i class="pause icon"></i></button>
        <button class="ui button"><i class="play icon"></i></button>
        <button class="ui button"><i class="stop icon"></i></button>
      </div>
    </div>
  </body>
```
dapat menggunakan basic untuk custom warna
```htmlbars
<body>
    <div class="ui container">
      <div class="ui buttons">
	      <!-- dibungkus div ui buttons untuk efek menyatu -->
        <button class="ui basic red button"><i class="pause icon"></i></button>
        <button class="ui basic blue button"><i class="play icon"></i></button>
        <button class="ui basic green button"><i class="stop icon"></i></button>
      </div>
    </div>
  </body>
```
> Basic dan Primary digunakan utuk meng-custom warna dari button
> Basic digunakan ketika ingin mewarnai button pada garis tepinya saja
> Sedang Primary utuk memberikan warna secara keseluruhan
