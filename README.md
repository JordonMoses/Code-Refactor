# Code Refactor for Horiseon #

## Project ##
This is a site for Horiseon Social Solution Services. I worked to ajust elements within the HTML and CSS. The work completed inlcudes alt text for images for the purposes of accesiblity. The CSS was also consolidated into fewer lines. Selectors were listed on the same line when they shared specific attirbutes including font size, margin, and display. 

Additionally, the div tags were changed to section tags to make them more accessible through the semantic elements. 

Lastly, CSS comments were added to help idenitfy the sections of the sebsite. 

<br />

## Screenshot ##
![Horiseon_Screenshot](https://user-images.githubusercontent.com/70240665/95005447-7cc2d300-05be-11eb-99fb-146c8318a78d.png "Horiseon Screenshot")

<br />

## HTML Example ##
    <section class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="SEO doodle inside notebook on desk"/>
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
    </section>

<br />

## CSS Example ##
    .search-engine-optimization, .online-reputation-management, .social-media-marketing {
        margin-bottom: 20px;
        padding: 50px;
        height: 300px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        background-color: #0072bb;
        color: #ffffff;
    }

<br />

## Contribute ## 
Additional CSS consolidation welcome. 