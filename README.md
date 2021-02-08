# Changes to the index.html file
+ Gave the website a new title: Horiseon (renamed from Website)  
+ Replaced header, footer, nav, content, and benefits div classes with HTML tags to comply with semantic web standards    
+ Added alt tags to all images, as required  
+ Added additional meta tags to the head for SEO
+ Updated the copyright year in the footer
+ Fixed header levels so that h1 is the page title and each section starts at h2
+ Removed div IDs that were not referenced in style sheet
  
# Changes made to the CSS style sheet
+ Added link styling to the nav links only (in case more links are added to the paragraph text)
+ Consolidated redundant CSS classes
+ Added clear: both and overflow: auto to clear the floats in previous sections
+ Created a smaller screen menu that drops the navigation links below the site title
+ Created a responsive top navigation menu that reduces to a hamburger icon on tablet and mobile - code taken from w3schools tutorial: https://www.w3schools.com/howto/howto_js_topnav_responsive.asp
+ Created media queries that stacks the aticle and aside (vs. putting them side-by-side) in the tablet and mobile screen sizes
+ Made adjustments to the padding and margins, as needed
+ Used https://webaim.org/resources/contrastchecker/ to check the contrast for accessibility - the colors in the header worked but the paragraph text needed more contrast. I fed the header color into mycolor.space and picked out some suggested colors with enough contrast and updated the style sheet

# Future changes
There are a few changes that I'd still like to make to this project that I didn't have time to get to:
+ I'd like to make the hamburger function properly - at the moment it works but it isn't styled nicely and jumps around on the screen when clicked - would like to position it over the site title
