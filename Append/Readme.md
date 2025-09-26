# An example without any particular problems
![1](https://github.com/user-attachments/assets/64e6e08a-7e25-4a44-8056-9932593b7a40)
### 1. Run everything as default
#### DOM Group: 810/834
- 810 : blog-details.html, blog.html, portfolio-details.html, services-details.html
- 834 : index.html

There are differences between the header and nav, and only the common parts are output to the base layout. The differences are output to the child view using @section...@endsection.
The contents of the differences are the class and page title.

### 2. Separate into subview at hierarchical level 6
#### DOM Group: 810/834
- 810 : blog-details.html, blog.html, portfolio-details.html, services-details.html
- 834 : index.html

Only the footer can be separated into a subview.
There is a difference between the header and nav, and there is no sidebar to begin with.

For example, if your source code is nested like this:
```html
<header>
:
<nav>
:
</nav>
:
</header>
```
nav is considered a header element and not an independent nav. Currently, BCH+ cannot extract and separate that part into a subview.


