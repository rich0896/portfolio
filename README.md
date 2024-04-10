# Web Development II Final - Portfolio
### *Reference can be found in the files as UX_Wireframe_Mockup.pdf or by visiting [Figma](https://www.figma.com/file/z4Pb56RruVUq6xy37sJhhi/UX-Wireframe?type=design&node-id=0%3A1&mode=design&t=eq7Y6e73B84zhXsh-1).*

> *"Tell us about your process, challenges you faced during development and how you overcame those changes. What have you learned by creating your web portfolio?"*

I started with the foundation. Luckily my portfolio design at it's core is fairly simple; nav with a row of buttons and a logo, rectangle for banner image and text, spot for body content, footer with row of social media icons. When it came to making the custom shapes for the elements, Tailwind made it significantly easier, and allowed me to use custom colours and other modifiers to make it even more streamlined.

Once I got the core site styling made, I noticed an issue in regards to my carousel, as the way I had designed the cards had made it extremely difficult to get the carousel to function (and vice versa, make it work while keeping the desired look) even while using the powerful bootstrap carousel system. Plus the design was redundant anyway, as no other cards than the cards that were visible on screen existed, meaning there was no point in a carousel in the first place. So it was removed to reduce clutter and page slowdown from unnecessary elements.

Once the index and all of it's styling and elements had been made, with all accessibility added, responsiveness verified and CSS / HTML / JS validated, I duplicated the HTML to all other pages and removed all elements that did not get used on each page. Then I modified things like the page titles, links and styling and added their unique elements, before once again verifying responsiveness and adding accessibility. The only other change to the content I made at this point was adding more text to the informational block in the aside on the Contact Us page, as the text felt basic (almost like placeholder on it's own) and like more should go in it's place. So I added location and phone info, which also gave me something to add Schema to.

By creating my web portfolio I have learned better how to design these things in mockups, and have a better sense of what will and will not work, as the software (in my case Figma) can do a lot more than the code can a lot easier.

### Credits

All images are my own (Created in Photoshop / Illustrator or by taking a photo with my camera, or a screenshot like the 'Our Services' image), except for those used on portfolio pages (Our Designs, Our Services, Testimonials), where [placeholder images](https://picsum.photos/) were used. Frameworks used include [Bootstrap](https://getbootstrap.com/), [Tailwind](https://tailwindcss.com/), and [Pushbar.js](https://github.com/oncebot/pushbar.js). Font used is [Jost](https://fonts.google.com/specimen/Jost), it is the same one I used on Figma and I found and sourced it on Google Fonts. Social Media Icons were sourced from a variety of icon libraries, but were pulled from a [consolidator](https://iconify.design/), with the SVG tags being used and modified afterwards to maintain styling.
