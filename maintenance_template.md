# maintenance.md - Website Maintenance Plan

**Your Name:** [Daniel Fletcher]  
**Website:** [Slay the spire fansite]  
**Date:** [24 / 04 / 26]

---

## Instructions

Complete this template after finishing your website. This demonstrates your understanding of ongoing website maintenance and earns 10% of your project grade.

---

## 1. Regular Maintenance Tasks

### What should be checked regularly?

**List 5+ maintenance tasks and how often they should be done:**

[Example:
1. **Check all links monthly** - Verify internal and external links still work. Fix or remove broken links.
2. **Update content quarterly** - Review all text for accuracy, update outdated information.
3. **Test in new browser versions monthly** - As browsers update, test site still works correctly.
4. **Check image loading monthly** - Verify all images still display, check load times.
5. **Review and respond to contact form submissions weekly** - If using a form, check for messages.
6. **Backup site files monthly** - Keep copies of all files in case of problems.]

Your maintenance tasks:
Your maintenance tasks:

1. **Check all links** - Monthly - Ensures all navigation and external links still work and don’t lead to errors

2. **Review content accuracy** - Every few months - Makes sure character info and descriptions are still correct and relevant

3. **Test website in browser** - Monthly - Ensures the site still displays correctly after browser updates

4. **Check images** - Monthly - Makes sure all images load properly and haven’t been moved or broken

5. **Backup project files** - Monthly - Prevents data loss if files are deleted or corrupted

6. **Update styling if needed** - Occasionally - Improve design or fix layout issues found over time

6. **[Additional tasks]**

---

## 2. Updating Content

### How would you update specific content?

**Adding new content:**

[Example: "To add a new café:
1. Open reviews.html in editor
2. Copy the HTML structure of an existing café card
3. Update image src, café name, description, details
4. Add corresponding image to images folder
5. Update comparison table on map.html with new café's features
6. Test that layout still works
7. Commit changes to Git
8. Push to GitHub (automatically updates live site)"]

Your process for adding content:

1. Open the relevant HTML page in Visual Studio Code  
2. Copy an existing section (table row, list item, or character block)  
3. Update the text, image source, and details  
4. Add the new image to the correct images folder  
5. Check layout and styling still work correctly  
6. Save and test the page in browser  
7. Commit updated version to GitHub

**Updating existing content:**

[Example: "To update café information:
1. Open the relevant HTML file
2. Find the section to update using Find feature
3. Change the text/information
4. If updating image, replace file in images folder with same name
5. Test page displays correctly
6. Commit and push changes"]

Your process for updating content:
 
1. Open the correct HTML file  
2. Use Find to locate the content  
3. Edit the text or replace the image  
4. Save changes  
5. Refresh the page in browser to check it works  
6. Commit updated version to GitHub  


**Removing outdated content:**

[Example: "To remove a café that closed:
1. Delete café card section from reviews.html
2. Remove café from comparison table on map.html  
3. Remove café image from images folder (or keep for archive)
4. Update featured cafés on index.html if it was featured
5. Check no broken links remain
6. Commit and push changes"]

Your process for removing content:

1. Open the relevant HTML file  
2. Delete the section (table row, list item, or image)  
3. Remove any related images from the folder if not needed  
4. Check layout still looks correct  
5. Make sure no broken links or gaps remain  
6. Save, test, and commit changes  

---

## 3. Technical Maintenance

### Keeping the site working properly

**If a page breaks, how would you troubleshoot?**

[Example:
1. Check browser console for errors (F12 in most browsers)
2. Validate HTML/CSS to find syntax errors
3. Check if recent change caused it - revert if needed using Git
4. Test in different browser to see if it's browser-specific
5. Check that all file paths are correct
6. Search error message if you get one
7. Compare with last working version to see what changed]

Your troubleshooting approach:

1. Check the page in the browser and see what looks broken  
2. Look for errors in Visual studio code (red underlines or warnings)  
3. Check file paths for images, CSS, or links  
4. Review recent changes to see what caused the issue  
5. Test in the browser again after fixing  
6. Compare with another working page if needed  



**If you wanted to change the design:**

[Example: "Changing colors:
1. Update color variables/values in styles.css
2. Test on all pages to ensure sufficient contrast
3. Check text is still readable on new backgrounds
4. Test hover effects still visible
5. Commit change"]

How you'd approach design changes:

1. Open styles.css  
2. Update colours, spacing, or layout values  
3. Save and refresh the browser to see changes  
4. Check all pages to make sure nothing breaks  
5. Adjust if needed until it looks consistent  
6. Commit changes  


**If you wanted to add a new page:**

[Example: "Adding a new page:
1. Create new HTML file (e.g., events.html)
2. Copy HTML structure from existing page for consistency
3. Update page title and meta description
4. Add page content
5. Add link to new page in navigation on ALL existing pages
6. Add new page link to sitemap
7. Test navigation works both ways
8. Validate HTML
9. Test responsive design
10. Commit and push"]

Your process for new pages:

1. Create a new HTML file  
2. Copy structure from an existing page  
3. Update the title and headings  
4. Add new content (text, images, etc.)  
5. Add the page to the navigation bar on all pages  
6. Test links and layout in browser  
7. Make sure it works on smaller screens  
8. Save and commit changes  

---

## 4. Website Health Checks

### What should be monitored?

**Performance:**
- [ ] Do pages load quickly? (Goal: under 2 seconds)
- [ ] Are images optimized? (Not too large)
- [ ] Does site work on slow connections?

How you'd improve performance if needed:

I would reduce image file sizes to make them load faster and avoid using unnecessarily large images. I would also remove any unused code in the CSS and HTML to keep the site efficient. Testing the site in the browser would help check if pages are loading slowly and identify any issues.


**Accessibility:**
- [ ] Are all images still using alt text?
- [ ] Are links descriptive?
- [ ] Is contrast still sufficient?
- [ ] Does site work with keyboard navigation?

How you'd improve accessibility if needed:

I would make sure all images have clear alt text so they can be understood if they don’t load or for screen readers. I would use clear and descriptive link text so users know where they are going. I would also check that text contrasts well with the background so it is easy to read.

**Standards compliance:**
- [ ] Does HTML still validate?
- [ ] Does CSS still validate?
- [ ] Does site work in current browsers?

How you'd maintain standards:

I would use Visual Studio Code to check for errors and fix any issues that appear. I would also regularly test the website in a browser to make sure everything still works correctly. Keeping the code clean and properly structured helps ensure it follows web standards.

---

## 5. Tools and Resources

### What would you need to maintain this site?

**Essential tools:**

[Example:
- Text editor (VS Code) to edit files
- Git for version control
- GitHub account for hosting
- Web browser with developer tools for testing
- W3C validators for checking code
- Image editor if updating photos]

Your essential tools:

- text editor: Visual Code Studio
- Github for version control
- Visual Code Studio extension to launch website live temporary to test
- Used Firefox to check
- Paint and Paint.net for image editting when needed


**Helpful resources:**

[Example:
- MDN Web Docs for HTML/CSS reference
- Can I Use to check browser support for features
- GitHub documentation for deployment help
- Original planning documents for design reference]

Your resources:

-  **https://www.khanacademy.org/computing/computer-programming** 
-  **https://quickref.me/html** 
-  **https://www.theodinproject.com/paths/foundations/courses/foundations**

**Skills needed:**

[Example:
- Basic HTML editing
- CSS modification
- Using Git (commit, push)
- Browser developer tools
- Image optimization basics
- FTP or GitHub deployment]

Skills for maintenance:

- Basic HTML editing
- CSS modification
- Using Git (commit, push)
- image optimzain basics and tools
---

## 6. Common Problems and Solutions

### Document potential issues and how to fix them

**Problem 1:**

[Example:
**Problem:** New image doesn't display
**Possible causes:** Wrong file path, file name typo, image not uploaded
**Solution:** Check file path matches folder structure, verify spelling matches exactly (case-sensitive), confirm file is in repository]

Your documented problems:

Problem 1:

Problem: Images not displaying on the page  

Possible causes: Incorrect file path, wrong folder name, or file name mismatch  

Solution: It was an extension hiding them


Problem 2:

Problem: Navigation not highlighting the current page  

Possible causes: No styling applied to indicate active page  

Solution: Add specific classes (e.g. active-home, active-ironclad) and style them in CSS


Problem 3:

Problem: Images inside frames not positioned correctly  

Possible causes: Default image positioning or incorrect sizing  

Solution: Use object-fit: cover; and object-position to control how the image fits and what part is visible




[Add more problems you anticipate or encountered]

---

## 7. Version Control

### Using Git for maintenance

**How would you use Git for safe updates?**

[Example: "Before making changes:
1. Pull latest version from GitHub
2. Make changes to local copy
3. Test changes locally
4. Commit with clear message describing change
5. Push to GitHub
6. Check live site updated correctly

If something breaks:
1. Use Git log to find last working version
2. Revert to that commit
3. Identify what caused problem
4. Fix properly and commit again"]

Your Git workflow for maintenance:

I mainly worked locally on the project using Visual Studio Code. Changes were made and tested directly in the browser before saving.

For important updates, I uploaded versions to GitHub as a backup. This allowed me to keep a copy of the project and restore files if something went wrong.

If an issue occurred, I would use a previous saved version of the project to restore the working state and then reapply changes carefully. 

**What makes a good commit message?**

[Example: "Good: 'Updated café hours for three locations', 'Fixed navigation hover effect', 'Added new café review for Roasted Brown'
Bad: 'Updates', 'Fixed stuff', 'Changes'

Good commit messages are specific and explain WHAT changed."]

Your commit message approach: I think a brief self explanitory title with more indept notes make a good commit message


---

## 8. Future Enhancements

### If you continued developing this site, what would you add?

**Content additions:**

[Example:
- Add more café reviews (expand to 20+ locations)
- Add café owner interviews
- Create blog section with coffee news
- Add events calendar for coffee festivals]

Your ideas:
- Add Slay the spire two character
- Add more cards and go into detail on builds and synergies



**Feature additions:**

[Example:
- Add search functionality to filter cafés
- Include embedded Google Maps for locations
- Add user reviews/comments system
- Create favorites feature using localStorage
- Add dark mode toggle]

Your ideas:
- Add all cards for each character so they can be searched by colour / Energy cost / Strategy
- functional contact box

**Technical improvements:**

[Example:
- Convert to use CSS Grid more extensively
- Add animations to page transitions
- Optimize images better (use WebP format)
- Add service worker for offline access
- Improve mobile navigation with hamburger menu]

Your ideas:

- Drop down menus for cards to go into more detial
- Gifs of the charactes moving in game would be nice

---

## 9. Maintenance Schedule

### Create a maintenance calendar

**Weekly tasks:**
- Check that all pages load correctly in the browser
- Review any contact form submissions (if used)
- If Slay the two spire characters are added, I'd have to check the games current build version and update info 

**Monthly tasks:**
- Check all links and navigation still work
- Test the site in the browser to ensure layout is still correct
- Check images are loading properly


**Quarterly tasks:**
- Review and update content if needed
- Improve styling or fix any layout issues


**Yearly tasks:**
- Review entire website for improvements
- Update design or content if needed


**After major browser updates:**
- Test the website in the browser to ensure everything still works correctly

**After adding content:**
- Check layout, images, and links work correctly
- Test the page in the browser and fix any issues

---

## 10. Website Builders Comparison

### Research: Modern Maintenance Tools

**Research how website builders (WordPress, Wix, Squarespace, etc.) handle maintenance differently than hand-coded sites:**

**Advantages of website builders:**

[Example:
- Automatic updates handled by platform
- Built-in backups
- Don't need to know code
- Easier to add content through visual editor
- Mobile responsive automatically
- Security updates automatic]

Your research:

- Automatic updates handled by the platform
- Built-in backups and security features
- No coding knowledge required
- Easy to edit content using visual editors
- Mobile responsiveness is usually built-in
- Hosting is included

**Disadvantages of website builders:**

[Example:
- Monthly costs (hand-coded sites can be free on GitHub Pages)
- Less control over exact design
- Can't customize as precisely
- Harder to migrate to different platform
- May include builder branding
- Page load can be slower]

Your research:

- Monthly or yearly cost
- Less control over design and layout
- Limited customization compared to coding
- Can include branding or restrictions
- Sites can be slower due to extra features
- Harder to move to another platform later

**When would a website builder be better than hand-coding?**

[Example: "For someone who needs to update content frequently but doesn't want to learn HTML/CSS, a builder makes sense. For business owners who need simple sites quickly. For sites that need backend features like e-commerce or user accounts."]

Your analysis:

Website builders are better for users who don’t know how to code and need a website quickly. They are useful for small businesses, personal sites, or projects that need frequent content updates without technical knowledge.


**When is hand-coding better?**

[Example: "When you need complete control over design. When you want to learn web development. When you want free hosting. When you want a fast, lightweight site. When you want to customize every detail."]

Your analysis:

Hand-coding is better when you want full control over design and functionality. It is also better for learning web development, creating custom layouts, and building lightweight websites without unnecessary features.

Sometimes a personal touch makes it better than templates and standard designs

**Sources for this research:**
- https://www.wix.com/
- https://en.wikipedia.org/wiki/Web_hosting_service

---

## Maintenance Checklist

- [ Yes ] Listed 5+ regular maintenance tasks with frequency
- [ Yes ] Explained process for adding new content
- [ Yes ] Explained process for updating existing content  
- [ Yes ] Explained process for removing content
- [ Yes ] Described troubleshooting approach
- [ Yes ] Explained how to make design changes
- [ Yes ] Explained how to add new pages
- [ Yes ] Identified performance monitoring needs
- [ Yes ] Identified accessibility monitoring needs
- [ Yes ] Listed essential tools for maintenance
- [ Yes ] Documented common problems and solutions
- [ Yes ] Described Git workflow for updates
- [ Yes ] Proposed future enhancements
- [ Yes ] Created maintenance schedule
- [ Yes ] Researched website builders vs hand-coding

---

## Final Thoughts

**What did you learn about website maintenance?**

[2-3 paragraphs reflecting on what maintaining a website involves and what surprised you about maintenance planning]

Your reflection:

Website maintenance seems to be a constant task with no set end date as information changes, browsers evolve and even newer and better versions of HTML and CSS release.

All of those possibilites could lead to outdated info, images breaking or sizing differently or just a total lack of website functionality.

---
