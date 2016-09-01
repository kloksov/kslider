# KSlider jQuery

Простой слайдер изображений на jQuery.

## \[ [Посмотреть как это выглядит. DEMO](https://kloksov.github.io/kslider/) \]

## Быстрый старт

Для начала работы подключите файлы слайдера, создайте контейнер для слайдера, поместите туда изображения и вызовите скрипт слайдера:

```html
<script src="src/jquery-2.2.4.min.js"></script>
<link rel="stylesheet" type="text/css" href="src/kslider.css" />
<script src="src/kslider.js"></script>

<div class="kslider" id="kslider">
	<img src="imgs/img1.jpg" />
	<img src="imgs/img2.jpg" />
	<img src="imgs/img3.jpg" />
</div>

<script>
  $('#kslider').kslider();
</script>
```

## Настройки слайдера

Можно применить следующие настройки:
- *width* - Ширина слайдера
- *height* - Высота слайдера
- *count_img* - Количество видимых изображений
- *margin_item* - Расстояние между изображениями
- *time_animate* - Время анимации
- *size_img* (string) - Размер изображений. Принимает значения *original* - оригинальный размер, *stretch* - изображение растягивается по высоте и ширине
- *size_img* (object) - Объект с указанием высоты и ширины изображения. Пример: { width: 100, height: 100 }

## Примеры

Указываем ширину, высоту и количество видимых изображений
```js
$('#kslider').kslider({
	width: 800,
	height: 400,
	count_img: 2
});
```

Растягиваем изображения и задаем отсупы и время анимации
```js
$('#kslider').kslider({
	width: 800,
	height: 120,
	count_img: 5,
	size_img: 'stretch',
	margin_item: 2,
	time_animate: 200
});
```

## \[ [Посмотреть как это выглядит. DEMO](https://kloksov.github.io/kslider/) \]

:)
