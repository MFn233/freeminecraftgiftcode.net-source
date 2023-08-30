# Notice

The so-called "**Free Minecraft gift code**" is just a **joke** and it's **not real**, so please do not believe **everything** on this website.

**Original Website**: freeminecraftgiftcode.net

I saw that **many people believe that this website can really obtain gift codes**, so I opened its source code.

When you click on 'Claim Your FREE Minecraft Gift Code', what happens is:

```html
<script>  
	function show_alert(){//The function only displays an alert on the screen and has no other function  
		alert("Oops! Looks like you didn't complete Step 2!");  
	}  
</script>  
<input type="button"  
	onclick="show_alert()"//call show_alert function  
	value="Claim Your FREE Minecraft Gift Code">
```
	
**Whenever** you click this button, it will call the alert function once, **no matter whether you have completed the second step**.

btw: This website is not an open source project and does not belong to me. I created this repo solely for learning and research purposes
