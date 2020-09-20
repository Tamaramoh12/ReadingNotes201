# Images in HTML

### Controlling Sizes Of Images In CSS

You can control the size of an image using the width and height properties in CSS.

Below you find how we specify the width and height of images:

![](img.PNG)

**What is the purpose of specifiying images sizes?**

Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.

### Aligning Images Using CSS

web page authors are increasingly using the float property to align images. 

Example:

![](img1.PNG)


### Centering Images Using CSS

1. By default, images are inline elements. This means that they low within the surrounding text. In order to center an image, it should be turned into a blocklevel element using the display property with a value of block. 

2. Once it has been made into a block-level element, there are two common ways in which you can horizontally center an image:

- On the containing element, you can use the text-align property with a value of center.

- On the image itself, you can use the use the margin property and set the values of the left and right margins to auto.

Example:

![](img2.PNG)

### Background Images

The background-image property allows you to place an image behind any HTMLelement. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box.

The path to the image follows the letters url, and it is put inside parentheses and quotes.

Examples:

![](img3.PNG)

![](img4.PNG)

**What about repeating images?**

1. repeat: The background image is repeated both horizontally and vertically (the default way it is shown if the backgroundrepeat property isn't used).

2. repeat-x: The image is repeated horizontally only.

Example:

![](repeat-x.PNG)

3. repeat-y: The image is repeated vertically only.

4. no-repeat: The image is only shown once

**What if the user want to scroll up and down?**

we use the **background-attachment** property to specify whether a background image should stay in one position or move as the user scrolls up and down the page.

It can have one of two values:

1. fixed: The background image stays in the same position on the page.

Example:

![](fixed.PNG)

2. scroll: The background image moves up and down as the user scrolls up and down the page.

**Background position**

When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be placed. 

This property usually has a pair of values. The first represents the horizontal position and the second represents the vertical.

If you only specify one value, the second value will default to center.

Example:

![](img5.PNG)

**Shorthand Background**

1. background-color

2. background-image

3. background-repeat

4. background-attachment

5. background-position

### Images Rollovers & Spirits

Using CSS, it is possible to create a link or button that changes to a second style when a user moves their mouse over it (known as a rollover) and a third style when they click on it. 

This is achieved by setting a background image for the link or button that has three different styles of the same button (but only allows enough space to show one of them at a time).

When a single image is used for several different parts of an interface, it is known as a sprite.

You can add the logo and other interface elements, as well as buttons to the image.

The advantage of using sprites is that the web browser only needs to request one image rather than many images, which can make the web page load faster.

Example:

![](img6.PNG)

### Some From CSS3 (Gradients)

CSS3 is going to introduce the ability to specify a gradient for the background of a box. The gradient is created using the background-image property and, at the time of writing, different browsers required a different syntax.

Examlple:

![](img7.PNG)

### Contrast of background images

If you want to overlay text on a background image, the image must be low contrast in order for the text to be legible.

Example:

![](img8.PNG)

**Example:**

**Html Code**
```
</head>
<body>
 <div class="wrapper">
 <div class="header">
 <img src="images/title.gif" alt="Galerie Botanique" width="456" height="122" />
 <p>Here is a selection of antique botanical prints held in our collection.</p>
 </div>
 <div class="entry">
 <figure><img src="images/print-01.jpg" alt="Helianthus" />
 <figcaption>Helianthus</figcaption>
 </figure>
 </div>
 <div class="entry">
 <figure><img src="images/print-02.jpg" alt="Passiflora" />
 <figcaption>Passiflora</figcaption>
 </figure>
 </div>
 <div class="entry">
 <figure><img src="images/print-03.jpg" alt="Nyctocalos" />
 <figcaption>Nyctocalos</figcaption>
 </figure>
 </div>
 <div class="entry">
 <figure><img src="images/print-04.jpg" alt="Polianthes" />
 <figcaption>Polianthes</figcaption>
 </figure>
 </div>
 <div class="entry">
 <figure><img src="images/print-05.jpg" alt="Ficus" />
 <figcaption>Ficus</figcaption>
 </figure>
 </div>
 <div class="entry">
 <figure><img src="images/print-06.jpg" alt="Dendrobium" />
 <figcaption>Dendrobium</figcaption>
 </figure>
 </div>
 </div>
</body>
</html>
```

**CSS Code**

```
<!DOCTYPE html>
<html>
<head>
 <title>Images</title>
 <style type="text/css">
 body {
 color: #665544;
 background-color: #d4d0c6;
 background-image: url("images/backdrop.gif");
 font-family: Georgia, "Times New Roman", serif;
 text-align: center;}
 .wrapper {
 width: 720px;
 margin: 0px auto;}
 .header {
 margin: 40px 0px 20px 0px;}
 .entry {
 width: 220px;
 float: left;
 margin: 10px;
 height: 198px;
 background-image: url("images/shadow.png");
 background-repeat: no-repeat;
 background-position: bottom;}
 figure {
 display: block;
 width: 202px;
 height: 170px;
 background-color: #e7e3d8;
 padding: 9px;
 text-align: left;}
 figure img {
 width: 200px;
 height: 150px;
 border: 1px solid #d6d6d6;}
 figcaption {
 background-image: url("images/icon.png");
 padding-left: 20px;
 background-repeat: no-repeat;}
 </style>
 ```

# Practical Information

### Search Engine Optimization (SEO)

Search engine optimization (or SEO) is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.


In order to determine who comes first in the search results, search engines do not only look at what appears on your site. They also consider how many sites link to you (and how relevant those links are). For this reason, SEO is often split into two areas:
**on-page techniques** and **off-page techniques**.

**On-Page Techniques**

are the methods you can use on your web pages to improve their rating in search engines.

The main component of this is looking at keywords that people are likely to enter into a search engine if they wanted to find your site, and then including these in the text and HTML code for your site in order to help the search engines know that your site covers these topics.

**Off-Page Techniques**

Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours.

Search engines also look at the ords between the opening \<a> tag and closing \</a> tag
in the link. If the text in the link contains keywords (rather than just click here or your website address) it may be considered more relevant.

In every page of your website there are seven key places where keywords (the words people might search on to find your site) can appear in order to improve its findability.

1. Page Title

2. URL / Web Address

3. Headings

4. Text

5. Link Text

6. Image Alt Text

![](seo.PNG)

# Domain Names & Hosting

In order to put your site on the web you will need a domain name and web hosting.

**Domain Names**

Your domain name is your web address (e.g. google.com or bbc. co.uk). There are many websites that allow you to register domain names. Usually you will have to pay an annual fee to keep that domain name.

**Web Hosting**

So that other people can see your site, you will need to upload it to a web server. Web servers are special computers that are constantly connected to the Internet. They are specially set up to serve web pages when they are requested.

**Which Hosting Company To Use**

1. Disk space: This refers to the total size of all of the files that make up your site
(all of the HTML and CSS files, images and scripts). 

2. Bandwidth: This is the amount of data the hosting company will send to your site's visitors. If you imagine 10 people looked at every page on your site, then it would be
the equivalent to 10 times the amount of disk space you use.

3. Backups: Check whether the hosting company performs backups on your site (and how often). Some only create backups so that they can restore your website in the event of a server breaking. Others allow access to backups (which can be helpful if you accidentally break the site when updating it).

4. Email accounts: Most hosting companies will provide email servers with their web hosting packages. You will want to check the size of mailbox you are allowed and the number of mailboxes you can use.

5. Server-side languages and databases: If you are using a content management system, it will likely use a server-side programming language and a database (such as PHP with a MySQL database, or ASP.Net with a SQL Server database). Be sure to check that your hosting company supports the technologies your software needs to run.

### FTP & Third Party Tools

To transfer your code and images from your computer to your hosting company, you use something known as File Transfer Protocol.

As the name suggests, File Transfer Protocol (or FTP) allows you to transfer files across the Internet from your computer to the web server hosting your site.

There are many FTP programs that offer a simple interface that shows you the files on your computer alongside the files that are on your web server. These allow you to drag and drop files from your computer to the server or vice versa.











