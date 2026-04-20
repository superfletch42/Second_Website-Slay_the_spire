# readme.md - Project Documentation

**Your Name:** [Name]  
**Project:** [Website title]  
**Repository:** [Link to your GitHub repo]  
**Live Site:** [GitHub Pages URL if deployed]  
**Completion Date:** [Date]

---

## Instructions

Complete this template **after finishing your website**. This documents what you built and how it works. Write clearly as if explaining to someone who hasn't seen your site.

---

## 1. Project Overview

### What did you build?

**Describe your complete website in 3-4 sentences:**

[Example: "I built a website showcasing ten Dublin coffee shops. It includes five pages: a landing page, detailed reviews, an area guide with a comparison table, coffee brewing tips, and an about page with a contact form. The site uses a warm color palette inspired by coffee culture and is designed for young professionals looking to discover new cafés."]

Your website:


### How do the pages work together?

[Example: "The landing page introduces the concept and features three highlighted cafés. Users can navigate to the full reviews page, check the area guide to see all locations and compare features, learn brewing techniques, or contact me through the about page. Navigation is consistent across all pages for easy movement."]

Your explanation:


---

## 2. Page Descriptions

**Briefly describe what's on each page:**

### index.html
Purpose: 
Content: 
Special features: 

### [Page 2 name]
Purpose: 
Content: 
Special features: 

### [Page 3 name]
Purpose: 
Content: 
Special features: 

### [Page 4 name]
Purpose: 
Content: 
Special features: 

### [Page 5 name]
Purpose: 
Content: 
Special features: 

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


**How did you structure your code?**

[Example: "Each page follows same structure: header with logo, nav bar, main content divided into semantic sections, footer with credits. Code is indented consistently. Comments mark major sections."]

Your approach:


### CSS

**Your CSS organization:**

[Example:
- Global styles first (colors, fonts, resets)
- Layout styles (container, flexbox for cards and nav)
- Component styles (buttons, cards, forms)
- Page-specific styles  
- Media queries for responsive design at end]

How you organized styles.css:


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


**CSS Grid - How did you use it?**

[Example: "Used Grid for:
- Brewing page: Two-column grid (instructions | images) with gap
- Gallery: Three-column grid of photos with auto-flow
- About page: Grid layout for contact info sections
Why Grid worked: Best for two-dimensional layouts with rows and columns"]

Your Grid implementation:


### Responsive Design

**How does your site adapt to different screens?**

[Example:
- Desktop (>768px): Navigation horizontal, café cards in 3 columns, two-column layouts
- Tablet (768px-480px): Navigation still horizontal, café cards in 2 columns, single column layouts  
- Mobile (<480px): Navigation becomes vertical menu, everything single column, images stack
- All text remains readable, tap targets are large enough for touch]

Your responsive approach:


---

## 4. Design Choices

### Visual Design

**Color Scheme:**
- Primary: [Hex] - [Why]
- Secondary: [Hex] - [Why]
- Accent: [Hex] - [Why]

**Typography:**
- Headings: [Font] - [Why]
- Body: [Font] - [Why]

**Why this design works for your topic:**


### Design Principles Applied

**Contrast:**
How did you create it?
[Example: "Café names in large, bold headings. Featured cafés have darker cards. Accent color used sparingly for CTAs."]


**Repetition:**
What repeats consistently?
[Example: "Same navigation on all pages. Café cards all use identical layout. Consistent spacing and padding throughout."]


**Alignment:**
How is content organized?
[Example: "All content in centered container with max-width. Text left-aligned within sections. Navigation items evenly spaced."]


**Proximity:**
How did you group information?
[Example: "Each café's photo, name, description, and details stay together in a card. Related brewing steps grouped in same section."]


---

## 5. Content

### Content Sources

**Where did your content come from?**

Text: 
Images: 
Data: 
Other: 

### Credits

**Attributions for any content you didn't create:**

Images:
- [Image description]: [Source and license]

Text/Information:
- [What information]: [Source]

Fonts:
- [Font name]: [Source]

Other:
- [What]: [Source]

---

## 6. Navigation

### Navigation Structure

**Describe your navigation:**

Type: [Horizontal bar? Vertical menu? Hamburger on mobile?]

Links: [List all navigation links]

Current page indication: [How users know where they are]

**Why this navigation works:**


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


### How to View Locally

1. Clone the repository:
   ```bash
   git clone [your-repo-url]
   ```

2. Navigate to the folder:
   ```bash
   cd [repository-name]
   ```

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


### Git Workflow

**How did you use version control?**

Commits: [How many total? How often did you commit?]

Commit messages: [What was your approach?]

Branches: [Did you use branches? Why or why not?]

---

## 9. Challenges and Solutions

**What problems did you encounter and how did you solve them?**

### Challenge 1
**Problem:** 

**What you tried:** 

**Solution:** 

**What you learned:** 


### Challenge 2
**Problem:** 

**What you tried:** 

**Solution:** 

**What you learned:** 


### Challenge 3
**Problem:** 

**What you tried:** 

**Solution:** 

**What you learned:** 


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


### Responsive Testing

**Screen sizes tested:**

[Example:
- Desktop (1920x1080): Optimal layout, 3-column café cards
- Laptop (1366x768): Good layout, 3-column café cards
- Tablet (768x1024): 2-column layout works well
- Mobile (375x667): Single column, navigation stacks, all content readable]

Your results:


### Functionality Testing

**What did you test?**

- [ ] All navigation links work
- [ ] All internal links work
- [ ] All images load with alt text
- [ ] Form validation works (if applicable)
- [ ] No broken links
- [ ] Site works without internet (local testing)
- [ ] [Other tests you performed]

**Issues found and fixed:**


---

## 11. Learning Reflection

### What did you learn?

**HTML skills:**

[Example: "I got much better at using semantic HTML. At first I used divs for everything, but I learned that nav, section, article make the structure clearer. Tables were tricky but made sense once I understood thead, tbody, tr, td hierarchy. Forms are more complex than I expected with all the input types and validation."]

Your HTML learning:


**CSS skills:**

[Example: "Flexbox finally clicked for me when building the café cards. I learned that padding and margin make huge difference in clean layouts. Media queries seemed scary but are actually straightforward. I spent a lot of time learning about specificity when my styles weren't applying - now I understand the cascade better."]

Your CSS learning:


**Design skills:**

[Example: "I learned that less is more - my first version was too busy. Consistent spacing matters more than I thought. Choosing a color scheme that actually works together was harder than expected. Learned about color contrast for readability."]

Your design learning:


**Web development workflow:**

[Example: "I learned to commit more often - made mistakes easier to fix. Building mobile-first would have been easier than retrofitting responsive design. Testing as I go saves time versus testing everything at the end. Planning really does make coding easier."]

Your workflow learning:


### What would you do differently next time?

[Example: "I'd plan my CSS organization better from the start - I rewrote sections multiple times. I'd test in multiple browsers earlier instead of waiting. I'd take more time on wireframes so I knew exactly what to build. I'd build mobile layout first, then scale up to desktop."]

Your thoughts:


### What are you most proud of?

[Example: "The café cards with hover effects look really professional. I figured out a flexbox layout that works on all screen sizes. My color scheme is subtle but effective. I solved the navigation highlighting problem myself using the developer tools."]

Your proud moment(s):


---

## 12. Future Improvements

### If you continued working on this site, what would you add or change?

**Content additions:**


**Technical improvements:**


**Design enhancements:**


---

## Final Thoughts

**Overall reflection on this project (2-3 paragraphs):**

[Write about: What was this experience like? What did you learn? How did this project develop your skills? How do you feel about what you created?]

Your reflection:


---

**Documentation completed:** [Date]

**Total development time:** [Approximate hours]

**Final statistics:**
- Total pages: 
- Total commits: 
- Lines of HTML: [If you want to count]
- Lines of CSS: [If you want to count]
