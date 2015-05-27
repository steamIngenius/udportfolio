## Website Performance Optimization portfolio project

To get started, check out the repository and follow these instructions:

### Getting started

Some useful tips to help you get started:

1. Check out the repository
1. Start a local web server:

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080

### Some Optimizations Performed:

1. Moved loading Google analytics to the bottom of index.html and set to load asynchronously
1. Optimized images where appropriate - stripped metadata, adusted Huffman Tables and scaled
1. Optimized render-blocking CSS on index.html
    * Critical CSS inlined
    * Non-Critical CSS loaded asynchronously
1. Optimized in-loop calculations in Javascript
    * Pizza resize is much faster
    * Scrolling is much faster