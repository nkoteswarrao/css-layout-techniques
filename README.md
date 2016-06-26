"# css-layout-techniques" 
 In this site I have added a Reset CSS components from  the link below.
        "http://meyerweb.com/eric/tools/css/reset/"
Which make's all browser default css to ZERO. and we can start from the scratch. 




To resize the document to 90% just uncomment this under Page Styles.

/* Page Styles
================================ */

.main-wrapper {
	width: 90%;
	margin: auto;

}

If you want to show the banner in-small screens too you can just remove the display value under Media Quries

.main-banner {
		display: none;
	}
