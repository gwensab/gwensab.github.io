# Decision log

Your methods section. About one page total.

Answer these as you go, not the night before it is due.
Specifics beat polish - a short honest answer is worth more than a long vague one.

Delete these instructions when you are done, or leave them. It does not matter.

---

## 1. What did you set out to build, and what changed?

What you wanted at the start, and what is actually live now.
Name one thing you dropped or added along the way, and why.

Before starting, I wanted to build a clean website that that was essentially a resume with multiple pages that had more detail than my resume alone. Ultimately I had to make some sacrifices by adding less information to make the pages look clean and organized. Additionally I decided to use one main page for the primary resume sections because it has a better flow for the website. I still included some other pages for more specific information I did not want visible on the main page like the about me sections and projects. 

...

---

## 2. A fork in the road

Name one real choice where you could have gone two ways.
Plain HTML or a framework. One page or several. Your own CSS or someone's template.
What goes on the front page and what does not.

Say which you picked, what the alternative was, and what you gave up by not taking it.

"There was no alternative" is not an answer. Find the fork.

My initial idea was to use multiple pages for each section I wanted on the website. However, after some brief testing, I realized I did not have enough information in each section to make it worth having its entire own page. So instead I decided to use one main page that contains the primary sections I wanted on my site. There are still some secondary pages that act as support to those primary sections but this layout overall gives the website a cleaner look while maintaining logical user interface.

---

## 3. Where you overruled the agent

One time Claude suggested, wrote, or claimed something and you did not take it.

What did it do? How did you notice? What did you do instead?

If it genuinely never happened, say so plainly, and then say what you would have had to
check in order to notice. Being honest here costs you far less than a story you cannot
defend when you record your video.

Most of the things I overruled Claude on were minor design choices and formatting issues. After asking Claude to adjust image sizing and positioning without seeing my desired results, I manually edited the code to position, crop, and size images the way I wanted them to display on the page. Additionally, Claude continuously tried to add more fonts and at one point ended up with 8 different fonts on the same page. I redirected it to only use two fonts, and bold or itallicize them for emphasis or to create visual differences on the page.

---

## 4. How you know it works

What check did you run, and what did it tell you?

Then the real question: **what would have made this check fail?**
A check that could not have failed is not a check.

Link to your `verification/` folder.

*Your answer here.*

---

## 5. What is still wrong

One thing on your own site that is not right, not finished, or that you do not
fully understand.

What would you do next, and how would you find out?

One thing that I could not get to implement correctly was dropdown menus for the primary sections that contained subsections. Despite ongoing troubleshooting, these dropdown menus remained permanently open. Ultimately I made the design decision to remove them and only allow access to those separate pages from buttons within the actual section. In the future I will research more into what could be causing this issue and approach it in a different way. Claude got caught in a loop of asking the same clarifying questions about the issue without providing new reasons or potential fixes. 