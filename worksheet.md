---
typora-root-url: ./
---

# SPECTRAL TUTORIAL

###### Or how I stopped worrying and learned to love templates


---


![](images/html5.png)





This guide will show you how to use an HTML5 UP template to create a website, the HTML 5 symbol will be used when we are writing code.

![octocat](images/octocat.png)

You will also learn how to save your project and all the changes you make to GitHub. The Octocat symbol will be used when we are interacting with our repository.



## Things to set up

1. Get your favorite text editor out.
   - We recommend **Visual Studio Code** or **Sublime Text**
2. Open a web browser
   - We recommend **Google Chrome**



### Things to remember

- Refresh you browser often to check what your website looks like

- Save regularly

  

#### Get comfy. Lets begin

---

## ![octocat](images/octocat.png)1. Create a new repository


Open **GitHub desktop** and Sign in (create an account if you haven’t got one already).

Choose **Create a New Repository on your hard drive**

![](images/createNew.jpg)

Set the name to be "**Spectral-Alpacas**" and the description to "**HTML5 Alpaca website**"

Choose a suitable location on your hard drive and click **Create repository**.

![](images/create.jpg)

#### You have Just Created a new local repository!



---

## ![octocat](images/octocat.png)2. Open the repository folder


At the bottom right of the screen Click **Show in Finder** (**show in Explorer** on a PC), this will take you to where the repository is stored on your computer. 

![](images/show.jpg)

You should see a folder called **Spectral-Alpacas,** this is where you will put your all the code and assets for this worksheet.



---

##  ![](images/html5.png)3. Download the Spectral template from HTML5 UP

Go to https://html5up.net/

Scroll down to Spectral and click “**Free Download**” 

![](images/spectral.jpg)

*You can use another template for your coursework, but for this worksheet we will be using Spectral*

**Unzip or Extract** this zip file, and put the contents **inside** the **Spectral-Alpacas** folder you found in step 2. 

You should now have a folder called **Spectral-Alpacas** which contains the following files:

![](images/folder.jpg)

---

## ![octocat](images/octocat.png)4. Commit the code to your local repository
On **GitHub desktop** you should now see a list of all the files you have added.

On the left you will see the files.

On the right you will see what has changed in each of those files.



![](images/initial_commit.jpg)



Write "**initial commit**" in the summary field and press **Commit to master.**



#### You have now committed your code to your **local repository**!

---

## ![octocat](images/octocat.png)5. Publish your repository
Press **Publish Repository**

![](images\publish.jpg)

This will upload your files to your account on GitHub.com

#### You have now published your code to your remote repository on GitHub!



---

## ![octocat](images/octocat.png)6. View your repository on GitHub
Click on **View on GitHub**

![](images/view.jpg)

This will open a browser window and show you your repository on Github.com

Now that it is on the remote repository your work is safe, even if you lose your computer you can just clone a new copy of your work from this repository.

You can also share your code with others and see exactly what changes have been made.

Throughout the rest of this worksheet we will be making changes to our files on our machines, committing those changes to the **local repository** and then pushing to the **remote repository**. This way we make sure our remote repository is kept up to date.



---



## ![](images/html5.png)7. Edit the title
Phew, now that we have setup GitHub we can now start editing the code.

Open **index.html** on your web browser.

![](images\specral_screenshot.jpg)



Open **index.html** on your text editor

In the index.html file, you will see the `<title></title>` tag. This changes the text in the tab title of your website.

Change the tile from:

`<title>Spectral by HTML5 UP</title> `

to:

**`<title>ALPACAS FOREVAH</title> `**

**Save**

**Refresh your browser to see the change** 

![](images/alpacas_title.jpg)



---

## ![octocat](images/octocat.png)8. Commit changes
Now look at GitHub desktop, it will show you what you have changed.

This is only a small change but we will add it to our repository

Change the summary message from:

`Update index.html!`

to:

**`Updated title`**

Press Commit to Master to add this change to your local repository

![](images/commit.jpg)

We will wait to push to the remote repository until we have a few more changes.



---

## ![](images/html5.png)9. Change the main heading
The main heading of a page is in the heading tag

`<header id="header" class="alt"> `

In this case it is hidden until the user scrolls the page.

In index.html, change the heading text from:

`<h1><a href="index.html">Spectral</a></h1>`

to:

`<h1><a href="index.html">Lamas Are Cool</a></h1> `

Save

Refresh your browser and find what has changed (HINT: you may need to scroll)



---

## ![octocat](images/octocat.png)10. Commit changes on GitHub desktop
Change the summary message from:

`Update index.html!`

to:

`Changed H1 contents`

Commit this change to your local repository as you did before

![](images/commit.jpg)



---

## ![](images/html5.png)11. Change the menu
We are going to make a few text changes to the main menu.

`<div id="menu">`

Look at the menu in your browser before you make the changes.

Then find it in the code and see how it is structured. 

`<li >` is a list item.

`<a href=` is a link tag. This template has two separate pages, which we will look at soon.

`#` is a local link, it doesn't go anywhere

First let’s remove some of the  items. and change the text on others.  

Right now we will link them to the generic page template. 

change:

```html
<div id="menu">
	<ul>
		<li><a href="index.html">Home</a></li>
		<li><a href="generic.html">Generic</a></li> 
	 	<li><a href="generic.html">Generic</a></li> 
	 	<li><a href="generic.html">Generic</a></li> 
	 	<li><a href="elements.html">Elements</a></li> 
	 	<li><a href="#">Sign Up</a></li> 
	 	<li><a href="#">Log In</a></li>
	</ul> 
</div>
```
to:

```html
<div id="menu"> 
	<ul> 
		<li><a href="index.html">Home</a></li> 
		<li><a href="generic.html">History</a></li> 
		<li><a href="generic.html">Fleece</a></li> 
		<li><a href="generic.html">Contact</a></li> 
	</ul>
</div> 
```

Save

Refresh the browser to see your changes



![octocat](images/octocat.png)

Commit this change to your local repository as you did before, adding a suitable summary message

![](images/commit.jpg)



---

## ![](images/html5.png)12. Change the banner

Have a look at how this section works. We are going to personalise this a bit and make it more on concept.

We currently have:

```
<section id="banner"> 
	<div class="inner"> 
		<h2>Spectral</h2>
		<p>Another fine responsive<br /> site template freebie<br /> crafted by <a href="http://html5up.net">HTML5 UP</a>.</p> 
		<ul class="actions special">
			<li><a href="#" class="button primary">HTML5UP</a></li>
		</ul>
	</div> 
 	<a href="#one" class="more scrolly">Learn More</a> 
</section> 
```



Change the header from:

`<h2>Spectral</h2>`

to:

**`<h2>ALPACAS RULE</h2>`**

Then change the paragraph text from:

`<p>Another fine responsive<br /> site template freebie<br /> crafted by <a href="http://html5up.net">HTML5 UP</a>.</p> `

to:

**`<p>This is a template<br />that is all about Alpacas<br /> made by<a href="put your wordpress url here">Your name here</a>.<br />And with thanks to</p> `**

Try taking out the `<br/>` tags, or moving them around, what changes?

Then lastly, change the link from:

`<li><a href="#" class="button primary">HTML5UP</a></li>`

to

**`<a href="https://html5up.net/" class="button primary">HTML5UP</a>`**

Save and refresh



![octocat](images/octocat.png)

Commit this change to your local repository as you did before

![](images/commit.jpg)



---

## ![octocat](images/octocat.png)13. Publish

You have now made a few commits to your **local repository**. 

However, this means that your **remote repository** is now out of sync.

Go to GitHub desktop and press **Push origin**

![push](images\push.jpg)

Your **local** changes have now been sent to the **remote repository** where they are safely stored 

To see the files on github.com click "**view on Github**"

![view](images/view.jpg)



---

## ![](images/html5.png)14. Edit section One

In HTML you can write a comment by using the angle brackets with an exclamation mark.

`<!-- this is a comment -->`

find the comment in index.html that shows you where section one starts

`<!-- one-->`

First change the `<h2>` title to:

**`<h2>With Alpacas, you have a friend indeed. <br />Here are some fun facts about our South American Camelid friends</h2> `**

Next change the  paragraph `<p>` text to:

**`<p>From their water and flame resistant fleece to their ability to guard <br />chickens, alpacas are excellent, ancient, domesticated animals</p>`**

We will remove the icons in this section. 

comment them out:

**`<!-- <ul class="icons major">`** 

​	... 

**`</ul> -->`**  



![octocat](images/octocat.png)

Commit this change to your local repository as you did before

![](images/commit.jpg)



---

## ![octocat](images/octocat.png)15. Revert a mistake

### We have made a mistake...

Looking back at the changes we have made, we realized that in section **9** we accidentally used the word Lamas!

As this is a small issue it would be easy to just change the text and then commit the changes BUT there is another way.

We can remove individual commits from our repository. This can be very useful if you have published a large change that you now want to undo.

On GitHub desktop, click on the history tab 

![history](images/history.jpg)

Scroll down and select the commit you made when you added "**Lamas are cool**".

It should be called **"Changed H1 contents"**

Right click and select **Revert this commit** 

![revert](images/revert.jpg)

Go back to the Changes tab and press **Push origin**

![push](/images/push.jpg)

If you refresh your browser, it should now display the old header



---

## ![](images/html5.png)16. Changer the header (again)

Now go back to the header at the top and change the H1 tag again

Change:

`<h1><a href="index.html">Spectral</a></h1>`

to:

`<h1><a href="index.html">Alpacas Are Cool</a></h1>`



![octocat](images/octocat.png)



Commit this change to your local repository as you did before

![](images/commit.jpg)



---

 

