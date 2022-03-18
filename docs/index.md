## Welcome to GitHub Pages

This page explains the project for CSE 455 Computer Vision courses. 

## grainboundary
Finding a grain boundary in images of perovskite thin films

Grainboundary is a package to analyze grain boundary in details directly from electron microscopy images!

To use it, just import the grainboundary package and upload your SEM image and you will get a grain boundary summary and interactive plots showing the size feautures of your particles.

This is a very handy tools for scientists working with perovskite thin films. Knowing the size distribution of the perovskite is crucial for solar cell applications.

Let's walk together through the step that will bring from your electron microscopy image to the size analysis of your perovskite thin films.
In this study, I have used different edge detector:
- Difference of Gaussian
- Canny Edge Detection
- Sobel filter
- Threshold edges
- U-NET (CNN)

```markdown
#Import Some library to use as a edge detector
import matplotlib.pyplot as plt
import numpy as np
from skimage.filters import difference_of_gaussians, window
from skimage.filters import try_all_threshold


```
### Example Images

![examples](https://github.com/yamanmy/grain_boundary.github.io/blob/main/example_images/example2.png)

### Ground Truth Images

![ground](/docs/assets/ground_truth2.png)

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/yamanmy/grain_boundary.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
