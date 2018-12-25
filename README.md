# CMPT-hyperlinker
A Google Chrome extension that highlights and hyperlinks any paragraph text that matches the 'CMPT XXX' format. The inserted link redirects to the course description for the current academic term on the SFU CS website. Hovering over the course code also displays a tooltip showing the title of the course (ie: "Data Structures and Algorithms").

This project helped me learn about JavaScript and DOM traversal.

A future version may include support for courses in other departments at SFU, and performance improvements. I would also like to add an "Options" page where the user can change the colour (or turn off) the highlighting for the hyperlinked text.

With Course Hyperlinker Activated:
<img width="1014" alt="screen shot 2018-12-17 at 1 23 21 pm" src="https://user-images.githubusercontent.com/18518784/50116972-93891180-0200-11e9-9a37-c7fece6300f2.png">

Without Course Hyperlinker Activated:
<img width="821" alt="screen shot 2018-12-17 at 1 30 31 pm" src="https://user-images.githubusercontent.com/18518784/50116976-9552d500-0200-11e9-950a-7a9aa748263a.png">

## Getting Started

After following installation steps (below), proceed to one of the following URLs to see the extension in action:
* https://www.reddit.com/r/simonfraser/comments/9c4exg/cmpt_courses_with_no_finals/
* http://www.sfu.ca/computing/current-students/undergraduate-students/programs/computing-science-major.html

### Notes
* If using the extension on Reddit or Facebook, you may notice that the script will occasionally appear to stop working. If so, simply reload the current page and the script will be reactivated. This is an issue I am looking to fix.

* The script can easily be modified to support any other department at SFU.

### Prerequisites

Google Chrome web browser

### Installing

To install:
1) Download remote to local
2) Navigate to chrome://extensions
3) Enable developer mode (top-right)
4) Select the "LOAD UNPACKED" option (top-left)
5) Specify the location of the downloaded repository
6) The extension will be added; ensure that the toggle switch is in the "on" position

## Built With

* JavaScript

## Authors

* **Kyle Moss**

## License

This project is licensed under the MIT License

## Acknowledgments

* Thanks to helpful posts on StackOverflow
