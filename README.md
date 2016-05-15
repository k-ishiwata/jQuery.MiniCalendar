# jQuery.MiniCalendar

```html
<div id="mini-calendar"></div>
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.12.3/jquery.min.js"></script>
<script src="../jquery.minicalendar.js"></script>
```

```javascript
(function($) {
	$(function() {
		$('#mini-calendar').miniCalendar();
	});
})(jQuery);
```

カレンダーに表示するイベントを event.json というファイルで作成します。

```javascript
{
	"year": 2016,
	"month": 5,
	"event": [
		{ "day": "1", "title": "イベント1", "type": "blue" },
		{ "day": "2", "title": "イベント2", "type": "red" },
		{ "day": "3", "title": "イベント3", "type": "green" },
        ...
	],
	"holiday": ["3","4","5"]
}
```