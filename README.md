DEMO LINK - https://vijayalakshmiblue8508-maker.github.io/image/image.html

PPT LINK - https://1drv.ms/p/c/61e1845cf34c237d/IQCNLLepBqKLRLBm6lCDUM7cASqK2KkDbwSL6K6jO5KZOTs?e=siQmgS

**Image Slider / Carousel**

This project is a simple and responsive Image Slider / Carousel built using HTML, CSS, and JavaScript.

**It allows users to:**

View multiple images in a sliding format
Navigate using previous/next buttons
Use navigation dots
Automatically slide images every 3 seconds


**Features**


Responsive image slider
Smooth sliding animation
Previous & Next navigation buttons
Clickable indicator dots
Auto-slide functionality
Clean UI design


**Technologies Used**


HTML5
CSS3
JavaScript (Vanilla JS)


**Project Structure**
image.html

The entire slider is contained in a single HTML file.

**How It Works**

**HTML**

Creates:

Slider container
Image section
Navigation buttons
Dots indicator
CSS

**Handles:**

Layout styling
Button design
Image sizing
Animation effects
JavaScript

**Controls:**

Slide movement
Dot activation
Auto-slide timing
Previous/Next functionality
Main Functions
showSlide(i)

Displays the selected slide.

nextSlide()

Moves to the next image.

prevSlide()

Moves to the previous image.

currentSlide(i)

Opens a specific slide using dots.

Auto Slide
setInterval(() => {
  nextSlide();
}, 3000);

Automatically changes slides every 3 seconds.

Image Source

**Images are loaded from:
**
https://picsum.photos/

You can replace them with your own image URLs.

**Example:**

<img src="your-image.jpg" alt="Image">
Customization
Change Slider Size
.slider{
  width:700px;
  height:400px;
}
Change Auto Slide Time
}, 3000);

Replace 3000 with your preferred milliseconds.

Future Improvements
Add touch/swipe support
Add fade transition effect
Make fully mobile responsive
Dynamic image loading
Pause on hover
