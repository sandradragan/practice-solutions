# README

## Linking Within a Site

### Instructions

1. In this directory are a number of files. First, organize them in the following directory structure. Create the directories, then place the files within them as indicated. *NOTE:* file names have an extension (i.e. .html, .jpg); directories do not.

- black-and-white
  - charlie.html
- css
  - style.css
- images
  - casper.jpg
  - cat-bg.png
  - charlie.jpg
  - cool-cats.jpg
  - flynn.jpg
  - quorra.jpg
  - snuggles.jpg
- index.html
- maine-coon
  - snuggles.html
- tabby
  - flynn.html
  - quorra.html
- white
  - casper.html

  You can do this in Atom (using the project column on the left), but it may be easier using the Finder (macOS) or File Explorer (windows). Be sure you do not move any of these documents outside of the `03-within-a-site` folder. An example of how the directory should look when finished is included in the `examples` folder within `practice-set-04`.

2. All the HTML documents have been coded up ... except for the links and images. Find the tags which have properties such as `href` (for links) or `src` (for images) and link them using **relative paths**. Begin with `index.html`.

3. Check for broken links after you finish.

  You need to be methodical about this, checking every link on every page. Do not click one link in the nav, then move onto the next on the new page. It's possible the links you are *not* checking before moving to the next page are broken!

4. Fix the images and links on each individual cat page and follow the same process in steps 2 and 3.

5. Look at documentation (or a previous example?) for how to add a stylesheet with a `link` tag. Make the styles contained in `style.css` appear on the web page. What properties are necessary to make the stylesheet work?

6. Fix `style.css` so it includes `cat-bg.png` as a background. In `style.css`, look on line 2 for: `background: url("");` What is the path to `cat-bg.png`?

7. Check all the pages to make sure the background image appears. An example of how the pages should look when finished is included in the `examples` folder within `practice-set-04`.

8. [Validate your code](https://validator.w3.org). Make any necessary corrections so the validator returns no warnings or errors. (The validator **will not** tell you if you have broken links or images. This is something you need to do manually.)
