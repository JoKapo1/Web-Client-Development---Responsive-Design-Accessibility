                        PLANNING DOCUMENT
----------------------------------------------------------------------
1. Create "draft" sketch of website layout in pencil + annotate
2. Create final sketch of website in color pens and markers + add annotations
3. Create assignment folder: include sketches and README.txt & sub folders(css, html, images)
4. Create pages in html folder (index, about, lessons)

5. Look at assignment 1 and note Perceivable, Operable, Understandable and Robust issues through manual and automated analyses

                ISSUES INDENTIFIED in manual analysis                   
------------------------------------------------------------------------
Perceivable
    1. Table markup (no use of scope)
    2. Forms (fields are not distinguishable; they are not used to organize associated inputs, instead used as decoration)
    3. Color contrast (H1 foreground and background do not pass WCAG AA; the colors fail for color blind)
Operable
    1. Keyboard Navigation (no 'skip to main' function)
    2. No focus styling
Understandable
    No issues
Robust:
    1. Meta tags were incorrect
    2. Links & directory were not working properly (used absolute referencing instead of relative)

                ISSUES INDENTIFIED in automated analysis                   
------------------------------------------------------------------------
1. Missing closing tags
 
6. Work on Small Device (index) html:
    i. in head create META tags & descriptive title & add logo
    ii. in body create header (logo, nav with list where menu items are linked to their related pages), 
        in body create main(sections-> articles-> headings, links that direct to headings->id, use of id and class selectors, paragraphs,
        images->figure, figcaption, alt), and create contact form
    iii. in footer add copyright symbol, your name, and custom content (link to MRU's Instagram, Twitter, and Facebook)
7. Import noramlize.css 
Work on Small Device (index) css:
    i. use pseudo class selector 
    ii. create vertical navigational bar in header
    iii. create form with attribute selectors
8. Work on Small Device (about) html & css:
    i. same as step 7 & step 8
    ii. but use pseudo element selector to style 1st letter of paragraphs 
9. Work on Small Device (lessons) html & css:
    i. same as step 7 & step 8
    ii. but creat a striped table(td, tr, th + merging) using with contextual selector 
10. Work on Medium Device (index, about, lessons):
    i. same as step 6, 7, 8, & 9 
    ii. for index html create a 2X2 grid the middle of the page (1 section -> 4 div-> 1 article)
11. Work on Large Device (index, about, lessons):
    i. same as step 6, 7, 8, & 9 
    ii. for index html create a 2X2 grid the middle of the page (1 section -> 4 div-> 1 article)
    iii. all pages should be centered with a fixed size of 790 px, and the remaining spaces on the side are white

10. Document changes made to fix issues 

                    CHANGES MADE TO FIX ISSUES
------------------------------------------------------------------------
Perceivable
    1. Used scope in table so that screen readers understand the structure of the table (header cell is specified for a column, row, or a group of either two)
    2. Reorganized fieldsets to groups associated inputs. Added "(required)" to labels to make it more clear than hovering over the textbox.  
    3. Changed H1 foreground (font) to black to pass WCAG AA
Operable
    1. Inclued 'skip to main' function so users can jump to main content
    2. Included focus styling in form for textboxes and radio buttons
Robust:
    1. Corrected Meta tags
    2. Changed absolute referencing to relative (../)
    3. Ensured all tags are closed 
    4. Used validators 


12. Cite all sources
13. Validate all pages (html & css)! 


                            CITATIONS
------------------------------------------------------------------------

[1] "Hipster Ipsum." Hipsum.co. Accessed: Mar. 23, 2025. [Online]. Available: https://hipsum.co/ 
[2] "CSS Vertial Bar Divider in a Menu" vincoding. Accessed: Mar. 23, 2025. [Online]. Available: https://vincoding.com/css-vertical-bar-divider-menu/  
[3] "How TO - Social Media Buttons" W3Schools. Accessed: Mar. 29, 2025. [Online]. Available: https://www.w3schools.com/howto/howto_css_social_media_buttons.asp
[4] "Accessibility Skip links" W3Schools. Accessed: Mar. 26, 2025. [Online]. Available: https://www.w3schools.com/accessibility/accessibility_skip_links.php
[5] "How much do cello lessons cost?" Lessons. Accessed: Mar. 27, 2025. [Online]. Available: https://lessons.com/costs/cello-lessons-cost
[6] "How to Add a Shadow to an Element?" GeeksforGeeks. Accessed: Apr. 2, 2025. [Online]. Available: https://www.geeksforgeeks.org/how-to-add-a-shadow-to-an-element/
