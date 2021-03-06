<a href = "README.md">Link back to README file</a>

### Testing 
#### Accessibility Check - 08/08/2021
<img src="assets/images/README_images/08082021_V2.png" width="600px">

improved accessibility score based on title and alt update:

<img src= "assets/images/README_images/08082021_V3.png" width="600px">

#### Accessibility Check - 19/08/2021
With the additional elements relating to the form element and additions to the meet us page, the accessibility score has decreased and need updating to ensure screen readers can understand the labels, as shown below <br>
<img src="assets/images/README_images/19082021_V1.png" width = "600px">

Improved accessibility score changing id names on form elements (contact us page) <br>
<img src="assets/images/README_images/21082021_v1.png" width = "600px">


#### W3C HTML Check Results - 31/08/2021
The following images shows some of the initial warnings and errors associated with the three web pages.  I used [W3C HTML validator](https://validator.w3.org/) the following The error message is consistent and will review with support.<br>
<img src="assets/images/README_images/HTML_access_check_31082021.png" width="550px">

#### W3C CSS Check Results - 31/08/2021
The results from the W3C CSS checker showcase no errors in the stylesheet. <br>
<img src="assets/images/README_images/CSS_accessibility_checker_310821.png" width="550px">

<hr>

#### Paul Kemp - Usability Testing - 09/09/2021
Email feedback received (text copied from email): 

<blockquote><p>The three pages are accessible and i can see the images clearly (when you changed the view).  The text is clear on all pages and the form element gives me a page telling me my options.  When i was on the contact us page and made the browser smaller, the feedback box did go over the form and this would need to be adjusted.  All links seem to work ok and i like that the icons change colour when you hoover over them.</p>

<p>Other comments (apologies for the list) 
<li>The video is ok, but could this be in the center of the page, rather than to the left.  You mentioned the idea of the apple website and they seem to have things in the middle, could this be done too? </li>
<li>The number of images on the home page seem alot - could these be reduced and gallery used (to make it reduce the space on the page? </li>
<li>The shape outline for the images on the home and meet us page seem to be different sizes - not a fan of the curved edges - could these be less severe?</li>
<li>On the contact us page - the actual blocks where you enter the information is not that clear and the font size seems really small - could the colour background be changed and font made bigger? </li></p>
<p>Many thanks and best of luck with this project and hope you do well. </p>
</blockquote>

#### Brian Macharia - Technical Feedback Evidence - 16/09/2021
After our technical meeting, Brian kindly noted the advised adjustments to make to the website, in order to comply with usability.  The feedback was valued and does also cross reference the notes made from usability testing:<br>
<img src = "assets/images/README_images/B_Feedback1.png" width = "550px"><br>
<img src = "assets/images/README_images/B_Feedback2.png" width = "550px">

#### Kate Tuck - Grammaratical Support - 19/09/2021
The following notes were made from the discussion with Kate:
<blockquote>There are a few readability issues on the home page in the first paragraph. Otherwise the other two webpages are ok. 
My advice, use a website called [Grammarly](https://www.grammarly.com/), you can set your readability targets and you can make the necessary adjustments to each paragraph to make sure they are understood.  
This is a tool that i recommend GCSE and A-Level students to use before submitting any coursework and does well to identify word placement, grammar and syntax structures.  I would strongly recommend you use this in this website and for future tasks.
Best of luck with the website and hope you do well.  
Do not hesitate to contact if you need any other proof reading advice.   </blockquote>

<hr>

## Changes applied to website based on feedback

### Change 1: Changing gallery style on home page

When reviewing the changes, please refer to the first interation designs (pre-feedback) on the README document to see the updates: <a href = "README.md">README.md</a>

Code snippet used to inspire the changes to the home page from [Raddy.com](https://raddy.co.uk/blog/learn-a-super-cool-effect-using-flexbox-in-under-7min/).
The number of images has been reduced and organised into two sections relating to Leap Valley, being the Thickets and Meadow areas, as shown below:
I did research the idea of using Bootstrap carousel, but applying the bootstrap style sheet at the end to accomodate this meant the styles on the index page clashed with the other stylesheet. In reflection, the design at the start could have accounted for this, so that i could override the bootstrap style to be consistent with the other webpages.  Therefore the flexbox concept was preferred. 

Version 1 changes:

<img src="assets/images/README_images/TESTING_images/Update_gallery1.png" width="550px">

Using the above link for inspiration, i changed the code to apply to my website.  Using all images on the flexbox it looked overcrowded, especially on the smaller screen sizes, so therefore the content needed to be changed to accomodate the smaller screen ratios.  

Version 2 changes:

<img src = "assets/images/README_images/TESTING_images/Update_gallery2.png" width="550px">

The second version places out the images better which gives a larger flexbox for the images, so they are clearer for the user to see, compared to the first version, this was no the case and images were not clear. 

### Change 2: Centering video

Both technical and usability mentioned about the video element looking odd left aligned, so this has been changed to accommodate this change with relevant media access adjustments for ipad and iphone 5 sizes.

The adjustments applied below (when compared to first interation design in the README file).

<img src = "assets/images/README_images/TESTING_images/udated_video.png" width="550px">

### Change 3: Improving contrast between form and background elements

Technical feedback suggested the form element needs padding and increased font sizes.  They also suggested that the input boxes should not have a transparent background, which have been changed below:

I believe the contrast element is better from an accessiblity perspective.  While increasing the font size, post using rem size, to improve accuracy on font size increases on tablet and mobile devices. 

<img src = "assets/images/README_images/TESTING_images/updated_form.png" width="550px">

### Change 4: Extended contrast on header and footer

To ensure consistency in design and high contrast on the header and footer image, these have also been changed with the form background in mind.  This ensure the elements within the div content is clear to view, which should also improve the accessibility score when testing is conducted. 

Header changes below:

<img src = "assets/images/README_images/TESTING_images/updated_header.png" width="550px">

Footer changes below:

<img src = "assets/images/README_images/TESTING_images/updated_footer.png" width="550px">

### Change 5: Black image borders

The lighter green border on the images on the meet us and home page did not contrast well with the background, so the borders have been changed for all image elements to ensure that they stand out against the background, while maintaining the animated elements on the hover over (on the meet us page only).

<img src = "assets/images/README_images/TESTING_images/updated_border.png" width="550px">

### Change 6: Button accessibility colours

The background colours changed on buttons on home and contact us page (form element)

<img src = "assets/images/README_images/TESTING_images/updated_button.png" width="550px">

<hr>

### Lighthouse score from changes 1 to 6

The following image shows the impact of the changes (to date) based on usability feedback.  The benefit of the lighthouse score is that Accessibility has been improved, to the detriment of the Performance, which i require further understanding on, which is a development target.  

<img src = "assets/images/README_images/TESTING_images/updated_lighthouse_score_190921.png" width="550px">

<hr>

### Change 7: Spelling and Grammar Changes

Using Grammarly, i have checked the spelling and grammar to ensure the readability is not compromised or eschew the purpose of the site, which was complete for each page.

An example of one of the highlighted changes recommended using Grammarly below:

<img src = "assets/images/README_images/TESTING_images/updated_grammar_check.png" width="550px">

All changes identified from using this tool have been applied to each of the site pages. 

<hr>

## Browser checks

I checked the website across the following browsers: Safari (preferred as mac owner), Google Chrome and Windows IE (via <a href="https://netrenderer.com/index.php">Net Render</a> selected the Mixed option).  All elements via the Desktop seem to be consistent.  I also checked on the ipad, using TabOS and on an iphone 11 and 12.  The content seemed to be placed as intended.  However, further investigation is needed to identify a website that can list differences on display options.  

## Other Accessibility Checks and Success Criteria Checks

### Check against success criteria

The following success criteria have been checked against the post testing update:

<img src = "assets/images/README_images/TESTING_images/Success_criteria_update2.png" width="750px">

### HTML and CSS Check Reports

The initial errors on the index page were:

<img src = "assets/images/README_images/TESTING_images/Nu_HTML_Check1.png" width="550px">
<br>

<ol>
<li>Final Report for: <a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Flpr78.github.io%2F3-Portfolio1%2F">Home Page </a></li>
<li>Final Report for: <a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Flpr78.github.io%2F3-Portfolio1%2Fmeet.html"> Meet us Page </a></li>
<li>Final Report for: <a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Flpr78.github.io%2F3-Portfolio1%2Fcontact.html"> Contact Us Page </a></li>
<li>Final Report for: <a href="https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Flpr78.github.io%2F3-Portfolio1%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en"> CSS Validation Check </a>
</li>
<li>Final Report for: <a href="https://wave.webaim.org/report#/https://lpr78.github.io/3-Portfolio1/">WAVE</a></li>
</ol>

<hr>

### Responsive Check below post edits:

These are the main elements that have changed since the original ones were taken on the <a href = "README.md"> README.md </a> file

Home Page: <br>
<img src = "assets/images/README_images/TESTING_images/post_home_changes.png" width="550px">

Contact Us Page: <br>
<img src = "assets/images/README_images/TESTING_images/post_form_changes.png" width="550px">

<hr>

### Final Lighthouse since additions:
The performance score has improved slightly, but does need to be considered going into the next project: <br>
<img src = "assets/images/README_images/TESTING_images/final lighthouse.png" width="550px">


Back to <a href="README.md">README </a> file





