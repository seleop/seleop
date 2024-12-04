

```javascript
const whoAmI = {
	name : "HeedoJung",
	age : 26,
	sex : "male",
	city : "Gimhae, Korea",
	favorits : ["cats", "computer"],
	dateforPublishing : () => {
		let date = 90 //learning publishing after 08. 31. 2024
		let time = 24 * 60 * 1000  // hours * minute * second
		setInterval({
		date += 1;
		}, time)
		return date;
	},
	myHobby : ["doing Markup", "playing game", "going cafe", "watching Movies, animes and Dramas"]
}

```
