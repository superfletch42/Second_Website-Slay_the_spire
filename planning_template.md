# planning.md - Website Planning Document

**Your Name:** [Daniel Fletcher]  
**Date Started:** [3rd of April 2026]  
**Topic:** [A fan site about Slay the spire(1)?]

---

## Instructions

Complete this template **before you start coding**. Your planning demonstrates your design thinking and earns 20% of your project grade. Answer each question - they guide you through the design process.

---

## 1. Foundation

### What is your website about?

**In 2-3 sentences, describe your website:**

[Example: "My website showcases local Dublin coffee shops. It includes reviews, maps, photos, and brewing tips. The target audience is Dublin residents looking for their next favorite café."]

Your answer:
My website is on Slay the spire (The first game) and it's characters.
I want to show off the characters and their cards.


### Who is this website for?

**Describe your target audience:**

Think about: Age range? Technical knowledge? What do they want from your site?

[Example: "Young professionals and students in Dublin (20-35 years old) who enjoy specialty coffee and want to discover new cafés. They're comfortable with websites and want quick, visual information with good photos."]

Your answer: It's for players of the game and those interested in that game. While gaming doesn't really have an age specification, I'd say its targeted at teens and young adults.


### What should your website accomplish?

**List 3-4 specific objectives:**

[Example objectives:
- Help visitors discover 10+ coffee shops with honest reviews
- Provide practical information (location, hours, price range)
- Share brewing tips for home coffee makers
- Create a visually appealing experience with quality photos]

Your objectives:
1. Show visitors the playable characters
2. Have a complete compendium of the cards specific to each character
3. Give a brief description of the character and the playstyles
4. Make it visuelly nice to view.

---

## 2. Site Structure

### What pages will you have?

**List your 5+ pages and what goes on each:**

[Example structure:
1. index.html - Landing page with featured cafés and introduction
2. reviews.html - Detailed reviews of 10 coffee shops
3. map.html - Interactive area guide showing locations
4. brewing.html - Coffee brewing tips and techniques
5. about.html - About this project and contact form]

Your pages:
1. index.html - Home page that states this is a fan page and shows the 6 playable characters
2. [Ironclad] - Info on The Ironclad
3. [Silent] - Info on The Silent
4. [Defect] - Info on The Defect
5. [Watcher] - Info on The Watcher


### How do your pages connect?

**Draw or describe your site map:**

[Example:
```
index.html (hub)
    â"œâ"€â"€ reviews.html
    â"œâ"€â"€ map.html  
    â"œâ"€â"€ brewing.html
    â""â"€â"€ about.html
(All pages link back to index and to each other via navigation)
```
]

Your site map:
index.html (home)
├── 1_ironclad.html
├── 2_silent.html
├── 3_defect.html
└── 4_watcher.html

(All pages are connected through the navigation bar at the top)


### What navigation will you use?

**Describe your navigation structure:**

Where will navigation appear? [Example: "Horizontal navigation bar at top of every page"]

What links will it include? [List them]

How will users know which page they're on? [Example: "Current page link will be bold with different color"]

Your navigation plan:

Navigation appears as a horizontal bar at the top of every page.

Links include: Home, Ironclad, Silent, Defect, Watcher.

The current page is highlighted using a different colour in the navigation bar.

---

## 3. Design System

### Color Scheme

**Choose your colors and explain why:**

[Example:
- Primary: Deep brown (#3E2723) - coffee/warmth
- Secondary: Cream (#FFF8E1) - coffee with milk  
- Accent: Burnt orange (#FF6F00) - energy, highlights
- Background: White (#FFFFFF) - clean, readable
- Text: Dark gray (#212121) - easier to read than pure black

Why these colors work: They evoke coffee while staying professional and readable. The warm tones create a cozy feeling appropriate for café culture.]

Your colors:
- Primary: Black - rgba(0,0,0,0.7)
- Secondary: Grey / Silver — #888888
- Accent: Ironclad: red — #dd1515 | Silent: green — #2ecc71 | Defect blue: — #3498db | Watcher: purple — #7b2cbf
- Background: No colour, Custom image of Slay the spire 2 background (Even though its about the first game, this looks way better!)
- Text: White - #ffffff

Why these colors work for your topic:
I think for the primary and secondary they look good against the custome background.
For the accent colours they all represent the colour associated with these characters and their card boarders.


### Typography

**Choose your fonts:**

[Example:
- Headings: 'Playfair Display' serif - classic, elegant
- Body: 'Open Sans' sans-serif - clean, readable
- Code/Data: 'Courier New' monospace - if needed

Why these fonts: Playfair gives sophistication for café names and headings. Open Sans is highly readable for reviews and information.]

Your fonts:
- Headings: Trebuchet MS Arial, sans-serif
- Body text: Ariel Helventica, Sans-serif
- Special text (if needed): None

Why these fonts work:

They look nice

---

## 4. Design Principles

### How will you apply design principles?

**Contrast:**
How will you create visual hierarchy and make important elements stand out?

[Example: "Featured cafés will have larger cards with photos. Section headings will be larger and darker than body text. Call-to-action buttons will use the accent color."]

Your approach:
I'm using a darker background with some transparency. The text is in white and stands out easily against it. All the headings are largers.
All the character pages usee their own unique accent colours to highlight the tables and lists as well as a being used for picture frames.

**Repetition:**
What elements will repeat across pages to create consistency?

[Example: "Same navigation bar on every page. Café reviews all use same card layout with photo, name, rating, and description. Color scheme consistent throughout."]

Your approach:

Every page has a navigation bar.
All four of the character pages have a very similar layout of having the character at the top left and some brief text on them.
under that section is either a table / list of some of the best cards these characters have.

**Alignment:**
How will you organize content on the page?

[Example: "All content will be center-aligned in a max-width container. Text will be left-aligned within sections. Navigation items will be evenly spaced."]

Your approach:

Everything is centered withing the midbox. For headings the text is in the middle and for paragrapghs it is alighned left.

**Proximity:**
How will you group related information?

[Example: "Each café's info (photo, name, address, hours, rating) will be grouped in a card. Related brewing tips will be in same section with clear spacing between different topics."]

Your approach:

All the content are in boxes. All character pages keep the images and description together at the top.
The card tables and lists are placed in their own sections.
00000000000000<img width="774" height="613" alt="Character pages" src="https://github.com/user-attachments/assets/c0b11d04-18e3-4265-a563-0e5ff5af7f6f" />


---

## 5. Page Layouts

### Sketch your layouts

**Create wireframes for at least 2 pages:**

You can:
- Hand-draw and take a photo
- Use a tool like Excalidraw, Figma, or Mockplus
- Describe in detail with ASCII art

[Example of what to show:
```
Desktop Layout (index.html):
â•"â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•—
â•' Header + Navigation  â•'
â•šâ•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•
â•"â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•—
â•'  Hero Image + Title   â•'
â•šâ•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•
â•"â•â•â•â•â•â•—  â•"â•â•â•â•â•â•—  â•"â•â•â•â•â•â•—
â•' Caféâ•'  â•' Caféâ•'  â•' Caféâ•'
â•' Card â•'  â•' Card â•'  â•' Card â•'
â•šâ•â•â•â•â•â•â•  â•šâ•â•â•â•â•â•â•  â•šâ•â•â•â•â•â•â•
â•"â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•—
â•'      Footer         â•'
â•šâ•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•â•
```
]

Your wireframes:
Pictures are in the planning folder

---

## 6. Technical Planning

### HTML Elements You'll Use

**Where will you use required HTML elements?**

Don't just list elements - explain WHERE and WHY on your site:

[Example:
- Table: On the map page for a comparison table of café features (WiFi, outlets, seating, etc.)
- Form: On the about page for visitors to submit their favorite cafés
- Lists: On brewing page for step-by-step instructions (ordered list) and equipment needed (unordered list)
- Semantic sections: Each page will have header (site title + nav), main (content), sections (topic areas), footer (copyright + social links)]

Your plan:
- Tables: at least 1 table for a character
- Forms: contact box on main page
- Lists: at least one ordered and unordered list on the character pages 
- Semantic HTML: Each page uses header for title/navigation, section for content areas, and footer for credits to improve structure and readability.
- Images: on the homepage, inside tables, lists and background
- Special characters: In the footer

### CSS Approach

**What CSS techniques will you use?**

You must use both CSS Flexbox and CSS Grid somewhere in your site. Plan where and why:

**CSS Flexbox - Where will you use it?**

[Example: "I'll use Flexbox for:
- Navigation bar: Horizontal flex row with space-between, converts to column on mobile
- Café cards: Flex container that wraps cards into rows, changes from 3 columns to 2 to 1 based on screen size
- Card internals: Flex layout for image and text side-by-side"]

Your Flexbox plan:

It is used in the toolbar

**CSS Grid - Where will you use it?**

[Example: "I'll use Grid for:
- Main page layout: 2-column grid on brewing page (text and images), becomes 1 column on mobile
- Café comparison table alternative: Grid layout for feature comparison
- Gallery section: 3-column grid of café photos that adapts to 2 then 1 column"]

Your Grid plan:
I'll use grid for the main layouts of the homepage.

**Other CSS techniques:**

[Example:
- Responsive: Media queries at 768px for tablet, 480px for mobile
- Cards: border-radius, box-shadow for depth
- Hover effects: Cards scale slightly, links change color
- Code reuse: Create classes like .card, .button, .section-header for consistency]

Your other CSS plans: 
- Media queries for responsiveness on smaller screens
- Hover effects on buttons and character cards
- Border-radius and box-shadow for visual depth
- Reusable classes for frames, tables, and lists

---

## 7. Content Planning

### What content do you need?

**List what content you need to create or gather:**

[Example:
- Text: Write 10 café reviews (200-300 words each), brewing guides
- Images: Need 10+ café photos (can I take them? use with permission? find free stock photos?)
- Data: Collect café addresses, hours, prices for table
- Other: Maybe embedded Google Maps if I can figure that out]

Your content needs:
- Text: Write 4 short character briefs explaning them
- Images: four character images as well as 5 images of my own personal favourite cards
- Data: Relevent info on the cards and characters
- Other: 

### Content Sources

**Where will you get your content?**

[Example:
- Café information: Visit cafés, check their websites
- Photos: Take my own with phone, ask café owners for permission to use theirs
- Brewing tips: Based on my knowledge + citing sources like James Hoffmann's guides
- All sources will be credited in footer or about page]

Your sources:
I'll get pictures from the game and edit them in paint.net to remove their background and make them transparent if needed.

**If using others' content (images, text, etc.):**
How will you credit them?

I will leave credit in the footer to the game makers.

---

## 8. Development Plan

### Build Order

**What order will you build things?**

[Example:
Week 1: Build index.html structure, create styles.css with colors and fonts, add navigation
Week 2: Build reviews.html and map.html, add café content
Week 3: Build brewing.html and about.html, add form
Week 4: Refine styling, test everything, complete documentation]

Your plan:

No set timeline.
But I will start with the homepage and work on each individual character page in their in game unlock order (Ironclad, Silent, Defect, Watcher)

### Anticipated Challenges

**What might be difficult?**

[Example:
Challenge: Making the café cards look good and align properly
Plan: Use Flexbox, test with different amounts of text
Resources: MDN Flexbox guide, class examples

Challenge: Getting good café photos
Plan: Visit cafés this weekend with camera, ask permission
Backup: Use free stock photos from Unsplash with attribution]

Your challenges:

**Challenge 1:**
- What: Positioning images inside frames
- Why it's challenging: Images were not showing the correct part when resized
- Your plan: Use object-fit and object-position to control cropping

**Challenge 2:**
- What: Making navigation highlight the current page
- Why it's challenging: CSS alone doesn’t know the current page
- Your plan: Use separate classes (active-home, active-ironclad, etc.)


**Challenge 3:**
- What: 
- Why it's challenging: 
- Your plan: 

---

## 9. Tools

### What tools will you use?

**Development tools:**

[Example:
- Editor: VS Code with HTML/CSS extensions
- Browser testing: Chrome (main), Firefox, Safari
- Wireframes: Drew by hand, scanned
- Version control: Git + GitHub
- Validation: W3C HTML and CSS validators]

Your tools:
- Editor: Visual studo Code
- Browsers for testing: Firefox
- Wireframes/mockups: Paint to make a simple layout
- Version control: Github
- Other tools: Paint.net to edit pictures

### Code Generators

**Will you use any code generators (like W3Schools generator, etc.)?**

If yes:
- Which ones? 
- For what purpose? 
- What are the benefits? 
- What are the limitations? 
- How will you make sure you understand the generated code? 

If no:
- Why not? 

Your answer:

I'll mostly just reference my previous project and adjust it.
last time I found great references and tutorials here:
https://www.khanacademy.org/computing/computer-programming
https://quickref.me/html
https://www.theodinproject.com/paths/foundations/courses/foundations


---

## 10. Research: HTML and CSS Evolution

**This section demonstrates your understanding of web standards.**

### HTML Evolution

**Research and explain (in your own words) how HTML has evolved:**

What versions of HTML have existed? What were major changes? How have HTML5 semantic elements (like <nav>, <section>, <article>) improved web development?

[Aim for 150-200 words. Cite your sources.]

Your explanation:

HTML stands for Hyper Text Markup Language.

It's a markup language that lets web browsers interprety and compose text, images and more.

It was made in 1993.

HTML has seen many changes and evolutions since it's early days. Early HTML was more focused on structure and basic text having no real integration with media like we do now. Modern HTML allows us to embed videos, audio and similar things. This has all come from HTML 5.

The previous version of HTML, HTML4 introduced tables, Styles and scripts. These would allow devs to better organise and improve presentation of their websites.

Modern HTML that we have today introduces more semantic elements like <nav>, <section> and <footer> With these it makes looking at the code for a website much easier to traverse and understand what does what and where.

Sources: 
W3Schools
Wikipedia


### CSS Evolution

**Research and explain (in your own words) how CSS has evolved:**

What were major CSS developments? How have features like Flexbox and responsive design changed web development?

[Aim for 150-200 words. Cite your sources.]

Your explanation:


Sources:
W3Schools
Wikipedia

### Why Standards Matter

**Why is W3C validation important?**

[Example: "W3C validation ensures my code follows web standards, which means it will work consistently across different browsers and devices. Valid code is also more accessible and maintainable. It's like following grammar rules in writing - it helps everyone understand clearly."]

Your explanation:

CSS stands for Cascading Style sheets. It was first introduced in 1996.

These sheets where made to help manage code more easily by allowing developers to use classes and id's in their html files instead of having to repeat the same design choices into the html code.

Early versions of CSS focused mainly on basic styling. This would be coloursm fonts and spacing. Mordern CSS has more advanced features like Flexbox and Grid to better organise and present text, images and more.


Sources:
W3Schools
Wikipedia
---

## Planning Checklist

Before you start coding, have you:

- [ Yes ] Clearly defined your website's purpose and audience
- [ Yes ] Planned all 5+ pages with specific content for each
- [ No ] Created a site map showing page relationships  
- [ Yes ] Designed your navigation structure
- [ Yes ] Chosen a color scheme with rationale
- [ Yes  ] Selected appropriate fonts
- [ Yes  ] Explained how you'll apply all four design principles
- [ Yes  ] Created wireframes for at least 2 pages
- [ Yes ] Planned where required HTML elements will be used
- [ Yes ] Planned your CSS approach
- [ ] **Planned where you'll use CSS Flexbox**
- [ ] **Planned where you'll use CSS Grid**
- [ Yes ] Identified content needs and sources
- [ No ] Created a build schedule
- [ Yes ] Identified potential challenges with solutions
- [ Yes ] Listed all tools you'll use
- [ Yes ] Researched HTML and CSS evolution
- [ Yes ] Explained importance of web standards

---

## Final Notes

**Anything else to note about your planning?**

[Space for additional thoughts, questions, or concerns]


---

**Planning completed:** [Date]  
**Ready to start coding:** Yes / No  
**First step:** [What will you build first?]
