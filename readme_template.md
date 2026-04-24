# readme.md - Project Documentation

**Your Name:** [Daniel Fletcher]  
**Project:** [Slay the spire Fansite]  
**Repository:** [[Link to your GitHub repo](https://github.com/superfletch42/Second_Website-Slay_the_spire)]  
**Live Site:** [GitHub Pages URL if deployed]  
**Completion Date:** [24/04/26]

---

## Instructions

Complete this template **after finishing your website**. This documents what you built and how it works. Write clearly as if explaining to someone who hasn't seen your site.

---

## 1. Project Overview

### What did you build?

**Describe your complete website in 3-4 sentences:**

[Example: "I built a website showcasing ten Dublin coffee shops. It includes five pages: a landing page, detailed reviews, an area guide with a comparison table, coffee brewing tips, and an about page with a contact form. The site uses a warm color palette inspired by coffee culture and is designed for young professionals looking to discover new cafés."]

Your website:

I made a dedicated fan website to slay the spire. On this website it features the main four characters and my own personal favourite cards each of these unique characters has.

### How do the pages work together?

[Example: "The landing page introduces the concept and features three highlighted cafés. Users can navigate to the full reviews page, check the area guide to see all locations and compare features, learn brewing techniques, or contact me through the about page. Navigation is consistent across all pages for easy movement."]

Your explanation:

On the homepage I've given some detail as to what slay the spire is and what I personally like about it. It also has a toolbar as well as four buttons that directly lead to the other 4 pages about the characters.

---

## 2. Page Descriptions

**Briefly describe what's on each page:**

### index.html
Purpose: Brief intro to the game and website content
Content: Brief description of the game and what I like
Special features: contact box

### [1_ironclad.html]
Purpose: Showcase Ironclad
Content: Describes Ironclad and some of my favourite cards they have
Special features: Table

### [2_silent.html]
Purpose: Showcase Silent
Content: Describes Silent and some of my favourite cards they have
Special features: Ordered List

### [3_defect.html]
Purpose: Showcase Defect
Content: Describes Defect and some of my favourite cards they have
Special features: Unordered list

### [4_watcher.html]
Purpose: Showcase Watcher
Content: Describes Watcher and some of my favourite cards they have
Special features: Table

### [Additional pages if you have more than 5]

---

## 3. Technical Implementation

### HTML

**Key HTML techniques you used:**

[Example:
- Semantic structure: Every page uses header, nav, main, sections, footer for clear structure
- Tables: Café comparison table on map page showing features (WiFi, outlets, seating) for all locations
- Forms: Contact form on about page with text inputs, email input, textarea, and submit button
- Lists: Ordered lists for brewing steps, unordered lists for equipment needed
- Images: Alt text describes each café photo for accessibility]

Your implementation:
- Semantic structure:Every page uses a header, footer, nav and section to stay organised and maintain clear structure
- Tables: Both the Ironclad and Watcher pages use a table to display info on the cards
= Forms: A contact form is included on the homepage. There the user can submit their name, email and comment
- Lists: two lists are used. an ordered lsit on the SIlents page for the cards and an unordered on the Defects page. There is also an unordered list on the homepage
- Images: They are used all over the website. They display the characters, their cards and one for the background
**How did you structure your code?**

[Example: "Each page follows same structure: header with logo, nav bar, main content divided into semantic sections, footer with credits. Code is indented consistently. Comments mark major sections."]

Your approach:

All pages have a consistent structure of putting the navigation bar at the top and credits in the footer. The main content is put into the centre box (midbox) across all 5 pages.

### CSS

**Your CSS organization:**

[Example:
- Global styles first (colors, fonts, resets)
- Layout styles (container, flexbox for cards and nav)
- Component styles (buttons, cards, forms)
- Page-specific styles  
- Media queries for responsive design at end]

How you organized styles.css:

- Global styles first (body, fonts, background image, base colours)
- Layout styles (navigation bar, midbox container, grid layouts)
- Component styles (tables, lists, forms, Picture frames)
- Character-specific styles (colour-coded tables and borders for each character)
- Reusable classes used across all pages for consistency

  
**Key CSS techniques:**

[Example:
- Flexbox for navigation bar and café cards (wraps to column on mobile)
- CSS Grid for brewing page layout (two columns on desktop, one on mobile)
- Hover effects on cards (scale and shadow) and links (color change)
- Border-radius and box-shadow for cards
- Media queries at 768px and 480px for responsive design
- Custom classes: .cafe-card, .brew-step, .contact-form for reusability]

Your techniques:


**CSS Flexbox - How did you use it?**

[Example: "Used Flexbox for:
- Navigation: flex container with space-between for even spacing
- Café cards: flex-wrap container that adjusts from 3 to 2 to 1 column
- Footer: flex row with space-between for left and right content
Why Flexbox worked: Perfect for one-dimensional layouts and items that need to wrap"]

Your Flexbox implementation:

Used Flexbox for:
- Navigation bar (.toolbar): flex container with centered items, spacing using gap, and wrapping on smaller screens
- Content alignment (.character-top .box): flex column used to vertically center text beside images

Why Flexbox worked:
Flexbox was useful for simple one-dimensional layouts like aligning navigation items and centering content vertically within sections.

**CSS Grid - How did you use it?**

[Example: "Used Grid for:
- Brewing page: Two-column grid (instructions | images) with gap
- Gallery: Three-column grid of photos with auto-flow
- About page: Grid layout for contact info sections
Why Grid worked: Best for two-dimensional layouts with rows and columns"]

Your Grid implementation:

Used Grid for:
- Homepage layout (.gridbox): two-column grid displaying character links evenly
- Character pages (.character-top): two-column grid with image on one side and text on the other

Why Grid worked:
Grid was ideal for structuring page layouts with rows and columns, making it easy to organise content into clean, balanced sections.

### Responsive Design

**How does your site adapt to different screens?**

[Example:
- Desktop (>768px): Navigation horizontal, café cards in 3 columns, two-column layouts
- Tablet (768px-480px): Navigation still horizontal, café cards in 2 columns, single column layouts  
- Mobile (<480px): Navigation becomes vertical menu, everything single column, images stack
- All text remains readable, tap targets are large enough for touch]

Your responsive approach:

- Desktop (>768px): Navigation is horizontal using Flexbox, and layouts use two columns (gridbox and character-top)
- Tablet (768px and below): Layout switches to a single column using a media query, making content easier to read
- Mobile: Navigation wraps onto multiple lines using flex-wrap, and all sections stack vertically

Images scale using width: 100% and object-fit, so they resize correctly on all screen sizes. The main content is contained in a max-width container, keeping text readable.

Overall, the layout adapts by switching from multi-column to single-column and allowing elements to wrap, improving usability on smaller screens I hope.

---

## 4. Design Choices

### Visual Design

**Color Scheme:**
- Primary: #000000b3 - Used for main containers to create a dark, readable overlay on top of the background
- Secondary: #888888 - Used for borders to separate content and keep a consistent structure
- Accent: #dd1515 (Ironclad), #2ecc71 (Silent), #3498db (Defect), #7b2cbf (Watcher) - Used to match each character’s theme and highlight important elements like tables, lists, and frames

**Typography:**

- Headings: Trebuchet MS, Arial, sans-serif - It'a Bolder than the body text
- Body: Arial, Helvetica, sans-serif - Easy to read.

**Why this design works for your topic:**

I made the entire thing a bit darker to be easier on the eyes. The colours also don't clash with the background and using a unique colour for each character adds a bit more personality.

**Contrast:**
How did you create it?
[Example: "Café names in large, bold headings. Featured cafés have darker cards. Accent color used sparingly for CTAs."]

I used dark transparent boxes with a white text. All headings are larger and easy to identify

**Repetition:**
What repeats consistently?
[Example: "Same navigation on all pages. Café cards all use identical layout. Consistent spacing and padding throughout."]

The navigation bar is the same on every page, creating consistency. Each character page follows the same layout with an image on the left and description on the right, followed by a table or list of cards.

The same colours, spacing, borders, and box styles are reused across all pages, making the site feel consistent and organised.


**Alignment:**
How is content organized?
[Example: "All content in centered container with max-width. Text left-aligned within sections. Navigation items evenly spaced."]

All content is placed inside a centered container with a max-width, keeping everything aligned and readable. Headings are centered, while paragraphs are left-aligned for better readability.

Grid is used to align images and text side by side, and Flexbox is used to align content within sections.


**Proximity:**
How did you group information?
[Example: "Each café's photo, name, description, and details stay together in a card. Related brewing steps grouped in same section."]

Content is grouped together in sections. Each character’s image and description are placed together at the top, while their cards are grouped below in either a table or list.

Content is also placed inside boxes to visually separate different sections and make the layout easier to understand.


---

## 5. Content

### Content Sources

**Where did your content come from?**

Text:  Written by myself based on my knowledge of Slay the Spire and what I could see in game
Images: I got them in game and edited them in paint.net
Data: All data was gotten from in game and my own experience using them in game
Other: The background image is actually from the second game as I think it looked nicer than the original spire design

### Credits

**Attributions for any content you didn't create:**

Images:
- All images belong to Mega Crit: https://www.megacrit.com/

Text/Information:
- Based on my gameplay knowledge and in-game content from Slay the Spire

Fonts:
- Arial, Helvetica, Trebuchet MS 

Other:
- [What]: [Source]

---

## 6. Navigation

### Navigation Structure

**Describe your navigation:**

Type: Horizontal navigation bar at the top of every page

Links: 0_homepage.html
       1_ironclad.html
       2_silent.html
       3_defect.html
       4_watcher.html
       
Current page indication: The title says which page they are on. As well as that the toolbar buttons change colour per page, White for home and red, green, blue, purple for the characters.

**Why this navigation works:**

It's pretty obvious, at least to me. A highlighted toolbar button seems like an easy way to tell.

---

## 7. Viewing the Site

### Repository Structure

```
[Show your folder organization]

Example:
repository-name/
â"œâ"€â"€ index.html
â"œâ"€â"€ reviews.html
â"œâ"€â"€ map.html
â"œâ"€â"€ brewing.html
â"œâ"€â"€ about.html
â"œâ"€â"€ styles.css
â"œâ"€â"€ images/
â"‚   â"œâ"€â"€ cafe1.jpg
â"‚   â"œâ"€â"€ cafe2.jpg
â"‚   â""â"€â"€ ...
â"œâ"€â"€ planning.md
â"œâ"€â"€ readme.md
â""â"€â"€ maintenance.md
```

Your structure:

Picture folder (seperated into 5 sections for each page)
Planning folder that contains concept pics and a word doc talking about them
0_homepage.html
1_ironclad.html
2_Silent.html
3_Defect.html
4_Watcher.html
Maintenance_template
Planning_template
Readme_template
Styles
Project brief

### How to View Locally

1. Clone the repository:
   ```bash
   git clone [your-repo-url]
   ```

2. Navigate to the folder:
   ```bash
[Second_Website-Slay_the_spire](https://github.com/superfletch42/Second_Website-Slay_the_spire)

3. Open in browser:
   - Double-click `index.html`, or
   - Use a local server if you prefer

### Live Site

**GitHub Pages URL:** [URL if deployed]

---

## 8. Development Process

### Build Process

**How did you build this?**

[Example: "Started by creating HTML structure for all pages with navigation. Added CSS for layout and colors. Then added content page by page. Tested after each page. Finally refined styling and tested responsiveness. Made about 30 commits throughout development showing progress."]

Your process:

I looked at my previous project as a reference. I took and renamed most things to fit my purpose. I started with the html onthe homepage and added styles to it after.
Once I was done with the homepage I made a template page for the character pages and went from there.


### Git Workflow

**How did you use version control?**

Commits: My commits we're mostly all done as of the last week having left most of this on my own pc.


Commit messages: I used the titles for the commits to describe what changed and additional notes when needed

Branches: No, I worked on the single branch to keep things simple

---

## 9. Challenges and Solutions

**What problems did you encounter and how did you solve them?**

### Challenge 1
**Problem:** 
After I added the background image it did not appear
**What you tried:** 
I removed the image temporarly for a colour which appeared. I then again checked the image and it didn't appear.
I double checked the file path and eventually tried checking on a different browser (I used firfox regularly). 
On Chrome it would appear but not on Firefox
**Solution:** 
My extension, Dark reader was hiding the image and giving me a black background.
**What you learned:** 
Disable extensions like that next time.
(pretty sure I had the same problem last time)

### Challenge 2
**Problem:** 
The iamges on the character pages we're cut off or not focused on the character
**What you tried:** 
I tried moving the image using object position
**Solution:** 
After some playing around with different % I found good spots for all pictures
**What you learned:** 
To seperate each picture frame box as one solution doesn't fit all typically. It also helped when I decided to give the frames their own colour for consistenacy

### Challenge 3
**Problem:** 
avigation didn’t clearly show which page the user was on.

**What you tried:** 
I just copy pasted my old projects version in to find out what was wrong

**Solution:** 
I had a slight typo that was messing with it

**What you learned:** 
Slow down and read classes/ids more

### Additional Challenges
[Add more if needed]

---

## 10. Testing

### Validation

**HTML Validation:**
- Tool: W3C HTML Validator
- Results: [Pass/Fail for each page, any remaining warnings?]

**CSS Validation:**
- Tool: W3C CSS Validator  
- Results: [Pass/Fail, any warnings?]

### Browser Testing

**Browsers tested:**

[Example:
- Chrome 120 (Windows): All pages work perfectly
- Firefox 121 (Windows): All pages work perfectly
- Safari 17 (Mac): Minor font rendering difference, acceptable
- Edge 120 (Windows): All pages work perfectly]

Your results:

*HTML Validation:**
- Tool: Visual Studio Code
- Results: Errors and warnings were identified using Visual Studio Code and fixed during development.

**CSS Validation:**
- Tool: Visual Studio Code
- Results:  Errors and warnings were identified using Visual Studio Code and fixed during development.

### Browser Testing

**Browsers tested:**
- Firefox (Windows): All pages display correctly and function as expected at the end

### Responsive Testing

**Screen sizes tested:**

[Example:
- Desktop (1920x1080): Optimal layout, 3-column café cards
- Laptop (1366x768): Good layout, 3-column café cards
- Tablet (768x1024): 2-column layout works well
- Mobile (375x667): Single column, navigation stacks, all content readable]

Your results:
 I've only tested desktop (1920X1080) and everything looks like I would want it too.

### Functionality Testing

**What did you test?**

- [ Yes ] All navigation links work
- [ Yes  ] All internal links work
- [ Yes ] All images load with alt text
- [ Form exists but saves no where ] Form validation works (if applicable)
- [ I don't think so] No broken links
- [ Only locally, It's not been live] Site works without internet (local testing)
- [ None ] [Other tests you performed]

**Issues found and fixed:**


---

## 11. Learning Reflection

### What did you learn?

**HTML skills:**

[Example: "I got much better at using semantic HTML. At first I used divs for everything, but I learned that nav, section, article make the structure clearer. Tables were tricky but made sense once I understood thead, tbody, tr, td hierarchy. Forms are more complex than I expected with all the input types and validation."]

Your HTML learning:
I improved my understanding of semantic HTML and how to structure a full website properly using header, nav, section and footer. I was already pretty familiar with tables and lists from the last project, but got to put them into practice.

**CSS skills:**

I learned how to use Flexbox for layouts like the navigation bar and how Grid works for structuring sections of a page. I


[Example: "Flexbox finally clicked for me when building the café cards. I learned that padding and margin make huge difference in clean layouts. Media queries seemed scary but are actually straightforward. I spent a lot of time learning about specificity when my styles weren't applying - now I understand the cascade better."]

Your CSS learning:


**Design skills:**

[Example: "I learned that less is more - my first version was too busy. Consistent spacing matters more than I thought. Choosing a color scheme that actually works together was harder than expected. Learned about colour contrast for readability."]

Your design learning:

My original version lacked a lot of the colour it has now on each character page. I think once added it gave a but more life to each page.

**Web development workflow:**

[Example: "I learned to commit more often - made mistakes easier to fix. Building mobile-first would have been easier than retrofitting responsive design. Testing as I go saves time versus testing everything at the end. Planning really does make coding easier."]

Your workflow learning:

I mostly kept this on my local pc and updated it there. I can see how Github can be useful, but I still personally prefer to keeps things local and on the cloud.

### What would you do differently next time?

[Example: "I'd plan my CSS organization better from the start - I rewrote sections multiple times. I'd test in multiple browsers earlier instead of waiting. I'd take more time on wireframes so I knew exactly what to build. I'd build mobile layout first, then scale up to desktop."]

Your thoughts:

Firstly, I'd want to make a note for starting off as well as a basic template to work from. One much needed note is to disable extensions next time. I got such a headache from the background problem.

### What are you most proud of?

[Example: "The café cards with hover effects look really professional. I figured out a flexbox layout that works on all screen sizes. My color scheme is subtle but effective. I solved the navigation highlighting problem myself using the developer tools."]

Your proud moment(s):

I'm pretty happy with the changing colours of the toolbar.

I'm very happy with how it doesn't feel cluttered. and how perfectly the spire appears on the right side.

---

## 12. Future Improvements

### If you continued working on this site, what would you add or change?

**Content additions:**
I'd add in Slay the sprie two characters.

I'd also go into more detail for each character and their respective cards / builds

**Technical improvements:**
I think being able to fitler cards by rarity, energy cost and maybe my own build types would be amazing.

**Design enhancements:**
I tested it early on, and tried a gradient background for the boxes of the character colours and wasn't a major fan. One thing I would like is a simple button to press to hide all the boxes and toolbar to just view the background.

---

## Final Thoughts

**Overall reflection on this project (2-3 paragraphs):**

[Write about: What was this experience like? What did you learn? How did this project develop your skills? How do you feel about what you created?]

Your reflection:

Overall I'm very happy with how my project came out. The website looks clean and I've discovered nothing that doesn't work in my testing.

I think my biggest take away from the project is using grid and flex box. While I didn't use much Flex box It does look to function somewhat simillary to grid so I'm sure it must have some other unique or niche usses that only it solves, or at least solves better.

---

**Documentation completed:** [24/04/26]

**Total development time:** [27 if I include going over previous tutorials]

**Final statistics:**
- Total pages: 5
- Total commits: 
- Lines of HTML: [If you want to count]
- Lines of CSS: [If you want to count]
