
# Usage
### Step 1
Copy sp_colour_slider folder to your "Site Assets" folder in SharePoint

### Step 2
* Open "img" folder
* Replace all slider images with your custom photos/graphics. Images must be 1200x400 resolution and must retain the slide_1, slide_2, etc. naming convention.

### Step 3
* Open bootstrap_sp_colur_slider.html (Make the necessary edits below)
* Replace link "href" with your SharePoint url /SiteAssets/sp_colour_slider/css/bootstrap.min.css
* Replace script "src" with your SharePoint url /SiteAssets/sp_colour_slider/js/jquery.min.js
* Replace script "src" with your SharePoint url /SiteAssets/sp_colour_slider/js/bootstrap.min.js
* Replace all \<h3\> tags with appropriate slider header text
* Replace all paragraph tags with appropriate text
* Replace all img "src" with your photos/graphics SharePoint url /SiteAssets/sp_colour_slider/img/slider_1.png
* Replace all href "#" with your links/SP urls

### Step 4 
* Edit any SharePoint Page and add a new app web-part called "Content Editor"
* Edit web-part and copy/paste your SharePoint slider url: "YourURL"/SiteAssets/sp_colour_slider/bootstrap_sp_colour_slider.html (Into the Content Link)
* Apply, Save, and publish page
* Test all links and images
