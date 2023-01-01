# landing-page
Odin Project Landing Page.

This is the final project from the Flexbox portion of the course. I just completed the basic outline of my project, so I think it's time to populate this README.

This project was designed to put our new CSS skills to the test. With that, we were supposed to use Flexbox. Some parts of this I completed using margin or padding where I could have used Flexbox instead, but it's my project, so I don't feel too guilty for making things work however they fit.

The header of this project took the most work to sort out. I had some complications with maintaining the spaniel's size. It wanted to be default size, and after setting image width, it wanted to shrink out of screen whenever the screen got smaller. After fixing that, it refused to shrink at all while the text next to it moved. Stubborn dog. I finally figured out that .spaniel needed to have display: block; added to it, and that the containers surrounding the image and the text were how to make the flex items share fairly. Ugh!

As for image credit: Serhat Aktepe https://www.pexels.com/@serhatph/ photographed the spaniel, and Jos van Ouwerkerk https://www.pexels.com/@jos-van-ouwerkerk-377363/ photographed the birds.