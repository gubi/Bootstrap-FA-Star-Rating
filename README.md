Bootstrap-FA-Star-Rating
========================

Bootstrap FontAwesome Star Rating

# Usage

create an html file and insert this tag
```html
<div id="rating"></div>
```

then add this javascript:
```javascript
$("#rating").rating({
	rate: rates.medium_rates,
	total: rates.total
}, function(selected) {
	console.log(selected);
});
```
That's it!
