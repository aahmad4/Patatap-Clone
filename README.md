<h1 align="center">Patatap Clone</h1> 

<p align="center">
A clone of the Patatap website, recreated with Paper.js. I created this project for fun in my spare time to learn Paper.js, and make a nice project in the mean time. The website is very functional and easy to use. 
</p>

<p align="center">
A link to an online demo version can be found here: <a href="https://paperjspatatap.netlify.app" target="_blank">paperjspatatap.netlify.app</a>
</p>

## How It Works
The concept of the website is fairly straightforward. It follows a lot of the same concepts in the original Patatap website. Each key you hit holds a specific shape, color, and sound value. Also, each key holds a specific animation and effect. You can hit as many keys as you want and there will be different effects, visuals, and soudns played on each tap. It's a fun project that I encourage you to dabble around with.

## Setup
#### Clone
```
git clone https://github.com/aahmad4/Patatap-Clone
```

#### Implementation

The `"keyData"` object contains all the associations with color, animation, and sound for each key. Simply swap these around to your interest.
```html
<script type="text/paperscript" canvas="myCanvas">
	var keyData = {
		q: {
			sound: new Howl({
			urls: ['sounds/bubbles.mp3']
			}),
			color: '#1abc9c'
		},
```    

#### Usage
```
cd Patatap-Clone
```
Launch Webpage. All letters A-Z are associated with a specific animation and sound. Click on any of these keys to start the magic. Make sure your volume is on for the best experience.
```
index.html
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
