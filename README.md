Hostel Link: https://kaverichougule.github.io/Photo_Gallery/

![image](https://github.com/kaverichougule/Photo_Gallery/assets/101037685/6a375e8b-aa23-4d77-a75a-c60b99ae41cf)
indx.html <br>
'header': Represents the header section. <br>
'h1': Displays the main heading of the page.<br>
'div class="gallery"': Contains the photo gallery. <br>
A series of 'img' elements: Each displays an image with a source URL and alternative text. <br><br>

style.css
*: Applies the box-sizing property to all elements. <br>
 
body: Sets overall styling for the entire page. <br>

margin: Removes default margin. <br>
font-family: Sets the default font.<br>
background: Sets the background color. <br>
.header: Styles the header section. <br><br>

text-align: Centers text horizontally. <br>
text-transform: Makes the text uppercase. <br>
padding: Adds spacing around the content. <br>
background-color: Sets the background color. <br>
color: Sets the text color. <br>
border-bottom: Adds a colored border at the bottom. <br>
.gallery: Styles the photo gallery container. <br><br>

display: flex: Turns the container into a flex container. <br>
flex-direction: row: Arranges items in a row. <br>
flex-wrap: wrap: Allows items to wrap onto the next line. <br>
justify-content: center: Centers items horizontally. <br>
align-items: center: Centers items vertically. <br>
gap: Sets the gap between items. <br>
max-width: Limits the width of the container. <br>
margin: Adds margin around the container. <br> 
padding: Adds spacing inside the container. <br>
.gallery img: Styles the individual images. <br><br>

width: Sets the width of the image. <br>
max-width: Limits the maximum width of the image. <br>
height: Sets the height of the image. <br>
object-fit: Adjusts how the image fits within its container. <br>
border-radius: Adds rounded corners to the image. <br>
.gallery::after: Creates an invisible pseudo-element after the gallery. <br><br>

content: Adds content to the pseudo-element. <br>
width: Sets the width of the pseudo-element (creates a gap on the right).<br>
