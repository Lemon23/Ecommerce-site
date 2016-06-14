# Ecommerce-site
To simulate an e-commerce site, from the layout to the dynamic after some tests, there is still need to continue to improve.

**Result:**
 ![image](https://github.com/Lemon23/Ecommerce-site/raw/master/pic/pic1.jpeg)

In this exercise, the first time I used the `jQuery`，very confused at the beginning. After writing, I basically master grammar. Among them, also adopted the initialization style of Taobao net.

##Detailed analysis:
Explain in detail into blocks  > > >

###Top-search:
  When I write ‘search-input’ and ‘submit-button’ code, I found between them will appear void and staggered. Is this bug? After that, by understanding, I add `vertical-align: middle` attributes for them in the style. So the issue could be resolved. 
  
  Personally think that the search box is still to be improved positioning. And did not do the browser style compatibility.
###Left-nav:
  On the left side of the merchandise category navigation, using the `mouseover` and `mouseout` events, when triggered, details will appear or hide.
###Advertising scroll:
  Although before writing picture carousel function, but this time try to use jQuery to write, still a bit of a headache.
  
`function a(x){`
		`$("#ad a").attr("href",newhref).find("img").eq(x).stop(true, true).fadeIn().siblings().fadeOut();`
		`$("#stu a").eq(x).addClass("selected").siblings().removeClass("selected");`
`}`

After you can add more humanized mouse events. 
