Bootstrap FontAwesome Star Rating
========================

![example](https://raw.github.com/gubi/Bootstrap-FA-Star-Rating/master/star-rates.png)

I was looking for a simple star rating system in jQuery for Bootstrap and that uses FontAwesome icons, but seems there's no one.<br />
So I've made this one :)

# Usage
Include the javascript file
```html
<script src="bootstrap-fa-star-rating.js"></script>
```

Add this javascript:
```javascript
$(document).ready(function() {
	$("#rating").rating({
		rate: 2.18, // Start to show this rates when page loads
		total: 7, // Number of total votes
		stars: 5, // Number of stars
		// You can translate in your language
		textVote: "rate",
		textVotes: "rates"
	}, function(selected) {
		// Insert here an ajax call to save the user selection
		alert("Your rate is " + selected + "!");
	});
});
```

Then insert this tag to your html file
```html
<div id="rating"></div>
```
That's it!
