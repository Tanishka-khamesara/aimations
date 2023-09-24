# aimations
hosted link-> https://tanishka-khamesara.github.io/aimations/index.html


![Screenshot (123)](https://github.com/Tanishka-khamesara/aimations/assets/127411985/0d55683a-915c-4fe6-95c8-b49f2e5b60bb)
![Screenshot (124)](https://github.com/Tanishka-khamesara/aimations/assets/127411985/52a919b0-b4f2-4e20-b0f9-57dff0170613)
in html i just mae a container div and inserted 3 images.
The * selector selects all HTML elements on the page.
margin: 0; sets the margin of all elements to 0, effectively removing any default margin.
box-sizing: border-box; ensures that the width and height of elements include padding and borders, making it easier to create layouts.
body selects the <body> element of the HTML page.
background: black; sets the background color of the body to black.
display: flex; makes the body a flex container, which allows you to align its children.
justify-content: center; centers its children horizontally.
align-items: center; centers its children vertically.
min-height: 100vh; sets a minimum height of 100% of the viewport height, ensuring that the content is at least as tall as the viewport.
.container selects an element with the class "container."
display: flex; makes the container a flex container.
width: 1100px; sets the container's width to 1100 pixels.
justify-content: space-between; distributes the space between the container's children elements, pushing them to the sides.
-webkit-box-reflect is a CSS property that's used for creating reflections. In this case, it adds a subtle reflection effect below the container using a linear gradient.
.container > img selects the <img> elements that are direct children of the container.
max-width: 350px; limits the maximum width of the images to 350 pixels.
transform-origin: center; sets the transformation origin to the center of the images.
transform: perspective(800px) rotateY(20deg); applies a 3D perspective rotation effect to the images, making them appear tilted.
transition: 0.5s; specifies a smooth transition effect with a duration of 0.5 seconds for any property changes.
border-radius: 5px; rounds the corners of the images with a 5px radius.
box-shadow: 0 0 8px #808080; adds a subtle box shadow to the images for depth and visual effect.
css
.container:hover img {
    opacity: 0.3;
}
When you hover over the container, this rule targets the images inside it.
opacity: 0.3; reduces the opacity of the images to 0.3 (30%) when you hover over the container.
css
.container img:hover {
    transform: perspective(800px) rotateY(0deg);
    opacity: 1;
}
When you hover over the images themselves, this rule triggers.
transform: perspective(800px) rotateY(0deg); resets the perspective and rotation, making the images appear normal.
opacity: 1; sets the opacity of the images to 1 (100%), making them fully visible when hovered.
Overall, this CSS code creates a layout with centered content, a container with images that have subtle 3D tilt and reflection effects, and hover interactions to change the opacity and appearance of the images.
