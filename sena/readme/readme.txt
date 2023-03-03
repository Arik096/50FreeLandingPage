FILES
- index.html holds the entire content
- css/styles.css custom css styling
- js/scripts.js custom js code with settings for sliders, filterable grid and more
- images folder contains all the images


PLUGINS
- Bootstrap https://getbootstrap.com/
- Isotope https://isotope.metafizzy.co/
- Swiper https://swiperjs.com/
- Font Awesome for icons https://fontawesome.com/


IMAGES
All images are included in the download package and can be reused in your projects. The ones mentioned below come for outside resources. The ones not mentioned come from inside resources. Either way you can use them for free in your project if you want.
- Projects https://www.pexels.com/photo/macbook-pro-beside-dslr-camera-and-mug-3568521/
- Testimonial authors: https://www.pexels.com/photo/photo-of-people-standing-near-blackboard-3184393/
- Article details image large: https://www.pexels.com/photo/photo-of-imac-near-macbook-1029757/ 
- Article details image small: https://www.pexels.com/photo/apple-office-internet-ipad-38544/
- About page team members: https://www.pexels.com/photo/photo-of-people-standing-near-blackboard-3184393/


CREDITS
- Illustrations by Darko Vujic: https://creativemarket.com/users/graphics4u 
- Images by Pexels: https://www.pexels.com/


-----------------------------------------------------


Updating The Projects Section
The Projects section uses Isotope plugin which can be configured as described here https://isotope.metafizzy.co/

Adding A New Project
To add a new project in the projects section, you need to:
- Open for editing index.html and find the Projects section
- Here focus on the code area just below
<div class="grid">

- You can copy the following piece of code:
<div class="element-item erp">
    <a data-bs-toggle="modal" data-bs-target="#modal1">
        <img class="img-fluid" src="images/project-1.jpg" alt="alternative">
        <p><strong>Orkla Foods</strong> - Complete ERP integration and replacement of legacy</p>
    </a>
</div>

- And paste it wherever you want your project to be in the Show All order
- Now replace the name and the image as per your requirements
- Also add it to a designated category. Now it's set for "erp" as you can see from the code but you can change it to any category you define
- You can also designate it to multiple categories, just add the category as a class name like "erp sfa crm"

Adding A New Category
To add a new project category in the projects section, you need to:
- Open for editing index.html and find the Projects section
- Here in the Filter section duplicate a line like the one below:
<a class="button" data-filter=".erp"><span>ERP</span></a>

- And replace the word "erp" in both locations with your category name
- Then also add it to the project line below
<div class="element-item erp">

- By replacing "erp" with your category name


-----------------------------------------------------


Change Testimonials Slider Properties
- Open for editing js/scripts.js
- Find the section /* Card Slider - Swiper */
- And then fiddle with the settings using the documentation here: https://swiperjs.com/swiper-api


-----------------------------------------------------


Change YouTube Video
- Open for editing index.html
- Find the Video section
- Then the Video Preview section
- And in this line of code
<button type="button" class="video-btn" data-bs-toggle="modal" data-bs-target="#videoModal" data-bs-src="https://www.youtube.com/embed/fLCjQJCekTs">

- Replace the YouTube video ID code "fLCjQJCekTs" with the one of your own video which you will find in the Share - Embed tab on the YouTube video page
- Replacing this image will update the Preview image: "images/video-preview.jpg"