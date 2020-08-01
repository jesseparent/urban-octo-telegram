# Code Refactor Starter Code
In this project, existing code was examined for the Horiseon Web site. Changes were made to: 
1. Match the image mock-up (which appears to target 1152 x 864 browser size)
2. Eliminate redundant CSS markup
3. Make the HTML in the Web page more accessible

## HTML Changes
- Added comments and whitespace throughout for each section
- Changed title text to Horiseon
- Changed divs to semantic elements
- Added alt tags to images for accessibility (100 characters or less)
- Fixed all image tags to be self closing
- Removed footer content to match mock-up
- Added ID to Search Engine Optimization div so navigation link worked
- Removed classes on each content div because they are all styled the same
- Removed classes on each benefit div because they are all styled the same

## CSS Changes
- Comments for each section
- Organized general styles for tags together
- Changed classes to work for new semantic elements
- Simplified path to seo span since there is only one in the header
- Moved floating images below content section since that is the only area that uses them
- Consolidated content classes since they all use the same styling
- Consolidated benefit classes since they all use the same styling
- Changed footer padding to match mock-up
- Removed unnecessary footer h2 styling

## Deployed Application
- The web page can be found at [https://jesseparent.github.io/urban-octo-telegram/Develop/](https://jesseparent.github.io/urban-octo-telegram/Develop/)

## Screenshot
- The screenshot of the final work: ![Image](./screenshot.png)