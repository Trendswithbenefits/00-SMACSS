##### How did you determine which rules should be placed in each new CSS file?

Basically, I put anything that pointed at a generic element (h2, div, etc) in the base.css file, anything that pointed to a sub-element and/or that had a child (i.e., div a, ul li, etc.) in the layout.css file, and anything that pointed specifically at individual elements or classes in the modules.css file. I went from least to most specific.
---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I didn't bother with any refactoring for now.