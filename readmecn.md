# 注意

所谓“free minecraft gift code”只是一个**玩笑网站**，一切内容**都不真实**，请不要相信在此网站上的**一切内容**。

**原网站**：freeminecraftgiftcode.net

看到**有许多人相信这个网站真的能获得礼品码**，所以我开放了它的源代码。

当你点击“Claim Your FREE Minecraft Gift Code”时，发生的是：

```html
<script>  
	function show_alert(){//此函数仅仅只是显示一个alert，没有其他任何作用  
		alert("Oops! Looks like you didn't complete Step 2!");  
	}  
</script>  
<input type="button"  
	onclick="show_alert()"<!--调用show_alert函数-->  
	value="Claim Your FREE Minecraft Gift Code">
 ```
	
无论你何时点击此按钮，它**都**将调用一次alert函数，**无论你是否完成第二步骤。**

声明：此网站不是开源项目，且不属于我。我创建此仓库仅是为了学习与研究
