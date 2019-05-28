# Hilton Assessment for John Bonnot

## Assumptions and Considerations

I spent a long time trying to fine-tune the font with options for spacing and kerning as I could not get it to look exactly like the font in the images; I would assume in a typical project that the font used in a mockup would either be accessible to use or opted out in favor of standardized fonts across the website. I did keep some `scaleY()` in the css to handle making the `>`/`<` symbols more "correct" towards the design.

I changed use of `px` in the css to `rem` in almost all places except for borders and radii, simply due to a quick perusal of "best practices" articles and trying to find a consensus between them.

Originally I had used Grid to position everything but then I found out it was not supported as well as Flex, and I was also using it mainly for single-row positioning, so it made sense to swap it out.

I use a code formatter in VSCode which definitely made the css file easier to read but led to some weirdness in the html file.

Normally I would place files in a directory structure to make more sense and to keep the root directory as uncluttered as possible, but kept things simple for this assessment.

I created a png for the Hilton logo in the header element in order to have a transparent background; I believe it renders acceptably but I could definitely use pointers on modern image optimizations.

I kept the media queries simple, as I felt styling it for mobile first and then desktop/tablet made more sense, but if more would typically be desired in this sort of assessment I can definitely expand the scope of changes, do more changes in the positioning, etc.

## Assessment as given to me

From the original README.txt:

Assessment 1:
--------------
Expected final output:
HTML/CSS/JS/supporting images.

Description:
A hotel details web page is going to be served to web users.  A screenshot of the mobile version is provided of what it should look like (test1-mobile-page.png).  Create a static web page from scratch that matches the screenshot, with some responsiveness for varying phone screen sizes.  (The footer is not illustrated - feel free to cut off however you feel appropriate).  Supporting images for this test can be found in /test1_assets/ directory.

The point of this is to show awareness towards:
- Design detail
- Semantic HTML 
- CSS/responsive design

