# A good example of how to change the detachment pattern to Subview
![1](https://github.com/user-attachments/assets/4ac45997-0e2c-4bd8-8e90-2759f5fc2788)
### 1. Run everything as default
#### DOM Group: 22/24/26
- 22 : login.html
- 24 : basic_elements.html, basic-table.html, buttons.html, chartjs.html, dropdowns.html, mdi.html, typography.html
- 26 : index.html

Looking at the source code for DOM group 24, you can see that the sidebar, navbar, and footer match perfectly, and can all be separated into subviews.
Alternatively, you could try styles such as outputting the sidebar in a child view, or using either the navbar or footer as the base layout.<br>
you can test the output results of various templates.

### 2. Combine at hierarchy level 1
#### DOM Group: 2
- 2 : basic_elements.html, basic-table.html, buttons.html, chartjs.html, dropdowns.html, index.html, login.html, mdi.html, typography.html

It combines one DOM group, but the extracted hierarchy is too shallow.
Most of the source code is output to the child view, and no matter how you change the specifications, nothing can be separated into subviews.<br>
It doesn't reduce LOC that much, so it's pointless.
