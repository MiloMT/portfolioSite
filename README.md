# T1A2 - Portfolio Site

[Published Portfolio Site](https://portfolio-site-nine-dusky.vercel.app/)  
[Github Repository](https://github.com/MiloMT/portfolioSite)  
[Presentation](toBeUpdated)

## Purpose

The purpose of this site is to provide an avenue to market myself as both a developer and IT professional to external parties. The site contains information about myself, my work and how to get into contact with me, aswell as displaying a personalised yet professional aesthetic to viewers.

## Functionality / Features

The website is designed responsively to handle a variety of device sizes up to a maximum of 1280px wide.

Semantic tags are used throughout to add meaning to the various document components and to cater for accessibility when the site is traversed via a variety of means. Careful thought has also been given to the color scheme to ensure that there is a high level of clarify for the content on the page.

The preferred methodology for layout and organisation throughout the site has been flexbox. Nested flexboxes are used extensively throughout in order to manage the content desirably across a variety of screen sizes as mentioned above.

The main host pages in the site are:

- Home Page
- About / Resume
- Portfolio
  - Project Pages
- Blog Home Page
  - Blog Pages
 
In order to account for the variety of pages, a single SCSS/CSS document has been developed as a custom framework for all the pages. SCSS helps this process tremendously with the advantages it has over native CSS. The largest components contained within the SCSS/CSS document are:

- Background containers: The mixin and light / dark version of this backing container are the backbone of the site. This provides the highest level of organisation and through the use of the mixin, and the 3 classes (light, dark & solo), dictate how the content is organised across the variety of pages.
- Internal containers: These are the main form of nested containers within the primary background containers. These are designated generally for two heading types and than optionally paragraph and button. These come in three main forms (left, right and center) depending on the justification required of the content.
- Cards: The three main versions of the cards are contactCard, service & blog. Each of these cards achieves slightly different purposes and each card acts as a mini-container, split between the different use types depending on the required layout objective.
- Figure Image Containers: There are a variety of figure containers spread throughout designed to function within nested flexboxes. The position and size is a variable based on screen size and media requirements.
- Nav Bar: Designed to be simple. Clear and concise text always anchored to the top right corner so the user never loses their place and is self explanatory.
- Home Page Hero Images: Feature images used to drag the user into either the portfolio or blog content. Down the track will be designed to cycle through a variety of posts or featured work to excite the viewer.
- Blog Header: Unique amongst the other header types. Careful throught has been given so that media sizes plays a heavy role in how the feature blog article are displayed. In total the blog header contains 2 nested levels of flex-box that change direction dependent on media size.

## Sitemap

![Site Map](./docs/portfolioSiteMap.jpg)
*Note that the Github Project Link and Contact Forms are not operational - JS required for popup form and project links added as needed*

## Wireframes

*Contact Buttons not functional throughout - JS needed for popup forms and tracking*
![Home Page](./docs/portfolioWireframe_Homepage.jpg)
*Home Page*

![Resume](./docs/portfolioWireframe_Resume.jpg)
*Resume*

![Portfolio](./docs/portfolioWireframe_Portfolio.jpg)
*Portfolio - Project Image non functional, JS needed for hover different project anchors to change image*

![Blog Home](./docs/portfolioWireframe_BlogHome.jpg)
*Blog Home*

![Project / Blog Page](./docs/portfolioWireframe_ProjectBlogPage.jpg)
*Project / Blog Page*

## Screenshots



## Target Audience

This website is targeted towards a few types of individuals:
- Potential Employers
- Other Industry Professionals
- Myself as a personal development tool and testing ground

## Tech Stack

- Wireframes and Site Map: Figma
- Website: HTML & CSS/SCSS
- Deployment: Vercel
