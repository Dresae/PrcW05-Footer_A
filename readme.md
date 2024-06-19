
# Simple Footer
Lets make a simple and responsive Footer template.


## Branches dev1 and dev2
In these branches the code is split in two parts, the HTML one which was developed on the dev1 branch and the style on the dev2 branch.

## Branches joint, QA and Main
These Branches were merged and will look as follow:

![screenshot](pics/screenshot1.png)

![screenshot](pics/screenshot2.png)

# Code analysis

## HTML File

### Summary:
This creates a basic footer sctructure comprised of 4 sections each and listing several options for the user to navigate through the website. 

### Code:

We start defining the **footer** class for our base footer which will contain all the elements.
The four Unordered lists have been encapsulated into the **footer-top** class, allowing to apply the same style to each of the **footer-list** classes

The second main part is defined by the bottom section under the **footer-bottom** class that was used to place the company title, copyright and the social media icons that were placed using the List  **(li)** HTML element.

## CSS File

### Code:

- <b>*</b>
 >> This selector targets all elements on the page and sets their margin, padding, and box-sizing properties.

- <b>html</b>
 >> This selector targets the HTML element and sets its font-size to 62.5%

 - <b>body</b>
 >> This selector targets the body element and sets its display to flex, flex-direction to column, justify-content to space-between, height to 100vh, font-family to sans-serif, font-size to 1.6rem, and background-color to #12131c.

- <b>i</b>
 >> This selector targets elements with the "i" tag and sets their font-size to 2.4rem.

- <b>.footer</b>
 >> This selector targets elements with the class "footer" and sets their padding-block to 5rem, background-color to #151823, and color to #666873.

- <b>.footer-container:</b>
 >>  This selector targets elements with the class "footer-container" and sets their max-width to 116rem, margin to auto, padding to 0 1.5rem, overflow to hidden, and resize to horizontal.

- <b>.footer-top:</b>
 >>  This selector targets elements with the class "footer-top" and sets their display to grid, grid-template-columns to repeat with auto-fit and a minimum width of 20rem, and row-gap to 2rem.

- <b>.footer-title: </b>
 >> This selector targets elements with the class "footer-title" and sets their font-size to 1.8rem, color to #fff, font-weight to 500, and margin-bottom to 2rem.

- <b>.footer-list:</b>
 >>  This selector targets elements with the class "footer-list" and sets their display to flex and flex-direction to column with a gap of 2rem.

- <b>.footer-list-item: </b>
 >> This selector targets elements with the class "footer-list-item" and removes the default list-style.

- <b>footer-list-link:</b>
 >>  This selector targets elements with the class "footer-list-link" and sets their text-decoration to none, color to inherit, and transition to color with a duration of 0.25s.


- <b>.footer-list-link:hover:</b>
 >> This selector targets elements with the class "footer-list-link" when hovered and sets their color to #fff.

- <b>.footer-bottom: </b>
 >> This selector targets elements with the class "footer-bottom" and sets their display to flex, justify-content to space-between, gap to 2rem, and flex-wrap to wrap.

- <b>.footer-bottom .footer-list: </b>
 >> This selector targets elements with the class "footer-list" inside elements with the class "footer-bottom" and sets their flex-direction to row.

***

![reading...](https://media.giphy.com/media/Tf3mp01bfrrUc/giphy.gif?cid=ecf05e47wajghtrc5targr7mju7coe0avdyurnehrr1krgdt&ep=v1_gifs_search&rid=giphy.gif&ct=g "Pokemon reading")