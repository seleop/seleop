

```javascript
const whoAmI = {
	name : "HeedoJung",
	age : 26,
	sex : "male",
	city : "Gimhae, Korea",
	favorits : ["cats", "computer"],
	dateforPublishing : () => {
		let date = 90 //learning publishing after 08. 31. 2024
		let time = 24 * 60 * 60 *  1000  // hours * minute * second
		setInterval(() => {
		date += 1;
		}, time)
		console.log(`${date}`);
	},
	myHobby : ["doing Markup", "playing game", "going cafe", "watching Movies, animes and Dramas"]
}



const contactMe = {

	phoneNumber : "010 - 2262 - 4564",
	eMail : " seleop@naver.com ",

}
```
