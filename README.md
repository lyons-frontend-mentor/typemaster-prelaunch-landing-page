# Frontend Mentor - Typemaster pre-launch landing page solution

This is a solution to the [Typemaster pre-launch landing page challenge on Frontend Mentor](). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Create a responsive pre-launch landing page for a product based on designs in Figma.

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- HTML
- CSS

## Reflection

Prior to this challenge I nearly finished the GitHub user search challenge, but when in the last couple steps where I attempted to get the tablet and mobile layouts working, I struggled to implement the qualitative layout changes (beyond just stretching/contracting of dimensions). I found that my HTML markup wasn't well-adapted to the necessary layout changes between devices. With this in mind, I decided to start another challenge that would allow me to focus on implementing layouts (i.e. no interactivity).

That decision led me to this challenge, which I chose because of the clear layout changes between devices. Starting from mobile, where everything flows in one column, elements gradually merge into rows as the device width increases. For example, the three images and two of the text components go from taking up four columns to taking up only two, with text and images occupying the same row. This meant that I would need to change various layout properties for my Flexboxes/CSS Grids depending on the screen size.

Whereas in previous challenges I started with the desktop layout and applied changes as the screen shrunk, this time I took the opposite approach, starting with the mobile layout and then applied changes to take into account an enlarging screen. I found this approach much easier, as it felt more intuitive to code new additions to the layout (e.g. adding code to make a text component jump into the same row as an image) rather than implement "negative" changes (splitting up images and text as the dimensions narrowed). This approach also made it more intuitive to code my media queries, as each subsequent media query worked additively, as in adding "positive" changes to the design.

Another change I made to my process was taking the first 1-2 hours to pore over the Figma document and write down every change I could see, including precise margin/padding changes. I started by writing out the general components common to all the designs (a header, some introductory text, the keyboard images, etc.), after which I cross-referenced the design system with these components to see where each color/font style was used.

Upon completing this, I then worked from smallest screen-size to largest, writing down the margins and padding on each component, as well as any other features (e.g. text alignment, border-radius, etc.). Importantly, in subsequent layouts I tried not to write any dimensions which were already in the mobile layout (e.g. if a bottom-margin stays the same, I'd leave that out). For each of the three layouts I wrote distinguishing features in each one, making note of the changes between the designs. Only once I had inspected the entire design in-detail did I begin my HTML.

I found that this prior inspection greatly improved my productivity while coding, as this initial time with the design made writing my markup and styles much easier. This process also made the CSS easier since leaving out dimensions which remained constant from the mobile design simplified writing the media queries: in writing them, I could focus only on what changed between designs, and rely on formatting code for previous layouts to hold for future layouts whenever possibly.

### Continued development

Suffice it to say that I'm quite pleased with these two changes to my approach to these challenges. Over the next few challenges I'll focus on refining these approaches, as I'm sure I can optimize both processes. Once I've had a bit more practice, I'll finish up the GitHub user search challenge which I had previously struggled with.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
