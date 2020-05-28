
The SharepointScrollingBanner is a way to have a carousel of pictures come up within a Sharepoint site.  These pictures are clickable and can have text below them.

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

## Other Information
The United States Department of Commerce (DOC)and the United States Patent and Trademark Office (USPTO) GitHub project code is provided on an ‘as is’ basis without any warranty of any kind, either expressed, implied or statutory, including but not limited to any warranty that the subject software will conform to specifications, any implied warranties of merchantability, fitness for a particular purpose, or freedom from infringement, or any warranty that the documentation, if provided, will conform to the subject software.  DOC and USPTO disclaim all warranties and liabilities regarding third party software, if present in the original software, and distribute it as is.  The user or recipient assumes responsibility for its use. DOC and USPTO have relinquished control of the information and no longer have responsibility to protect the integrity, confidentiality, or availability of the information. 

User and recipient agree to waive any and all claims against the United States Government, its contractors and subcontractors as well as any prior recipient, if any.  If user or recipient’s use of the subject software results in any liabilities, demands, damages, expenses or losses arising from such use, including any damages from products based on, or resulting from recipient’s use of the subject software, user or recipient shall indemnify and hold harmless the United States government, its contractors and subcontractors as well as any prior recipient, if any, to the extent permitted by law.  User or recipient’s sole remedy for any such matter shall be immediate termination of the agreement.  This agreement shall be subject to United States federal law for all purposes including but not limited to the validity of the readme or license files, the meaning of the provisions and rights and the obligations and remedies of the parties. Any claims against DOC or USPTO stemming from the use of its GitHub project will be governed by all applicable Federal law. “User” or “Recipient” means anyone who acquires or utilizes the subject code, including all contributors. “Contributors” means any entity that makes a modification. 

This agreement or any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not in any manner constitute or imply their endorsement, recommendation or favoring by DOC or the USPTO, nor does it constitute an endorsement by DOC or USPTO or any prior recipient of any results, resulting designs, hardware, software products or any other applications resulting from the use of the subject software.  The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, including USPTO, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC, USPTO  or the United States Government.

<br />
<br />
<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/USPTO/TrademarkPublicData">https://github.com/USPTO/TrademarkPublicData</a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">Trademark Public Data</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="https://github.com/USPTO/TrademarkPublicData">
  United States</span>.
</p>
