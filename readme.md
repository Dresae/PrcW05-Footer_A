#  Simple responsive Footer
Lets make a simple and responsive Footer template with child items and social media icons.


##  Branches dev1 and dev2
In these branches the code is split in two parts, the HTML one which was developed on **_dev1_** and the style on the **_dev2_** branch.


##  Branches joint, QA and Main
These Branches were merged and will look as follow:

![screenshot](pics/screenshot1.png)
![screenshot](pics/screenshot2.png)

#  Code analysis
##  HTML File
###  Summary:

This creates a basic footer structure comprised of 2 main sections; the top one and the bottom one. The first main section also contains 4 child items listed for the user to ease the navigation through some pages, website sections or external resources. At the bottom there are few elements complementing the footer content.

###  Code:
We start defining the **_footer_** class for our base footer, which will contain all the elements of our practice.
Then the code is separated in two main parts; the top one tagged as **_footer-top_** and the bottom one tagged as **_footer-botom_**

The four _Unordered lists_  **_ul_** (the main titles displayed as _TechCompany_) have been encapsulated into the **_footer-top_** div class, allowing us to apply the same style to each of the **_footer-list_** classes.

There is also a divider line tagged as **_hr_**(_Horizontal Ruler_) with the class **_footer-divider_** that works as a simple line between the main footer section and bottom section.

The second main part is defined by the bottom section under the **_footer-bottom_** class that was used to place the company title, copyright and the social media icons that can be found under the List **_li_** tag.

Lastly notice all the elements of our footer are organized and **grouped into a single section** using the **_footer-container_** class, allowing us to separate them as a single element. 
This can be useful when building up an entire web page with other independent and grouped elements.


##  CSS File
###  Code:

-  **The _asterisc_ * selector**
>
```css
*{
}
```
> This selector targets all elements on the page and sets their margin, padding, and box-sizing properties.
***


-  **The _html_ selector**
>
```css
html{
}
```
> This selector targets the HTML element and sets its font-size to 62.5%
***


-  **The _Body_ selector**
>
```css
body{
}
```
> This selector targets the body element and sets its display to flex, flex-direction to column, justify-content to space-between, height to 100vh, font-family to sans-serif, font-size to 1.6rem, and background-color to #12131c.
***


-  **The _i_ selector**
>
```css
i{
}
```
> This selector targets elements with the "i" tag and sets their font-size to 2.4rem.
***


-  **Footer class**
>
```css
.footer{
}
```
> This selector targets elements with the class "footer" and sets their padding-block to 5rem, background-color to #151823, and color to #666873.
***


-  **Sizing and applying margin to the main container**
>
```css
.footer-container{
}
```
> This selector targets elements with the class "footer-container" and sets their max-width to 116rem, margin to auto, padding to 0 1.5rem, overflow to hidden, and resize to horizontal.
***


-  **Delimiting the top division of our footer**
>
```css
.footer-top{
}
```
> This selector targets elements with the class "footer-top" and sets their display to grid, grid-template-columns to repeat with auto-fit and a minimum width of 20rem, and row-gap to 2rem.
***


-  **Styling the titles**
>
```css
.footer-title{
}
```
> This selector targets elements with the class "footer-title" and sets their font-size to 1.8rem, color to #fff, font-weight to 500, and margin-bottom to 2rem.
***


-  **Styling the _lists_**
>
```css
.footer-list{
}
```
> This selector targets elements with the class "footer-list" and sets their display to flex and flex-direction to column with a gap of 2rem.

>
```css
.footer-list-item{
}
```
> This selector targets elements with the class "footer-list-item" and removes the default list-style.

>
```css
.footer-list-link{
}
```
> This selector targets elements with the class "footer-list-link" and sets their text-decoration to none, color to inherit, and transition to color with a duration of 0.25s.

>
```css
.footer-list-link:hover{
}
```
> This selector targets elements with the class "footer-list-link" when hovered and sets their color to #fff.


***


-  **Styling the bottom section**
>
```css
.footer-bottom{
}
```
> This selector targets elements with the class "footer-bottom" and sets their display to flex, justify-content to space-between, gap to 2rem, and flex-wrap to wrap.

>
```css
.footer-bottom  .footer-list{
}
```
> This selector targets elements with the class "footer-list" inside elements with the class "footer-bottom" and sets their **flex-direction** to row.
***


![reading...](https://media.giphy.com/media/Tf3mp01bfrrUc/giphy.gif?cid=ecf05e47wajghtrc5targr7mju7coe0avdyurnehrr1krgdt&ep=v1_gifs_search&rid=giphy.gif&ct=g  "...How could I ever do so unless someone guide me?")

***