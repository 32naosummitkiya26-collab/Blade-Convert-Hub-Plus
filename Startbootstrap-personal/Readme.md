# A good example of merging into a single DOM hierarchy
![1](https://github.com/user-attachments/assets/70ca0fb3-fb3c-4164-a7d7-7833b74a585c)

### 1. Run everything as default
#### DOM Group: 466/468/488
- 466 : contact.html
- 468 : resume.html
- 488 : index.html, projects.html

There's no problem with separating the nav and footer into subviews.
However, I have an idea that if I combine 466/468 into one group, I might be able to create a more efficient template.

### 2. Execute at DOM hierarchy level 2
#### DOM Group: 46/48
Comparing the base layout of each group reveals that they are identical. This leads me to the idea of ​​combining them into one.

### 3. Execute at DOM hierarchy level 1
#### DOM Group: 4
This creates the simplest template. The nav and footer can be separated into subviews, just like the default.

***Not all themes saved in BCH+ can integrate DOM groups so neatly, but it's worth trying different patterns.***
