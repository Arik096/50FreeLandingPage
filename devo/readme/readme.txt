FILES
- index.html holds the entire content
- css/styles.css custom css styling
- js/scripts.js custom js code with settings for sliders, rotating text and more
- images folder contains all the images


PLUGINS
- Bootstrap https://getbootstrap.com/
- jQuery https://jquery.com/ 
- jQuery Easing https://jqueryui.com/easing/
- Magnific Popup https://dimsemenov.com/plugins/magnific-popup/
- Swiper https://swiperjs.com/
- Morphtext https://morphext.fyianlai.com/
- Font Awesome for icons https://fontawesome.com/


IMAGES
All images are included in the download package and can be reused in your projects. The ones mentioned below come for outside resources. The ones not mentioned come from inside resources. Either way you can use them for free in your project if you want.
- Mobile app UI kit used in screenshots: https://dribbble.com/shots/2398307-Phoenix-UI-Vol-1-for-iPhone-6-Free-PSD-Sketch 
- Header section smartphone mockup in the Resources folder: header-smartphone.psd
- Features section and Screenshots section smartphone mockup in the Resources folder: features-smartphone.psd
- Details lightbox: https://www.pexels.com/photo/woman-in-white-t-shirt-holding-smartphone-in-front-of-laptop-914931/
- Screenshots background: https://www.pexels.com/photo/empty-hallway-with-lights-turned-on-1236044/ 
- About background: https://www.pexels.com/photo/photo-of-people-using-gadgets-3183177/
- About video frame: https://www.pexels.com/photo/apps-blur-button-close-up-267350/  
- Download background: https://www.pexels.com/photo/gold-iphone-6-beside-magic-mouse-2265484/ 
- More apps fitness: https://www.pexels.com/photo/purple-dumbbells-in-hands-of-positive-sportswoman-4498294/ 
- More apps dating: https://www.pexels.com/photo/couple-standing-near-buildings-3775553/
- More apps finance: https://www.pexels.com/photo/person-holding-black-card-holder-928181/
- Article details image large: https://www.pexels.com/photo/photo-of-imac-near-macbook-1029757/ 
- Article details image small: https://www.pexels.com/photo/apple-office-internet-ipad-38544/



CREDITS
- Phoenix Mobile App UI Kit by Adrian Chiran: https://dribbble.com/adrianchiran  
- Images by Pexels: https://www.pexels.com/


-----------------------------------------------------


Changing The About Section Video
- Open for editing index.html
- Find the Video section
- Then find the following lines of code:

<!-- Video Preview -->
<div class="image-container">
  <div class="video-wrapper">
    <a class="popup-youtube" href="https://www.youtube.com/watch?v=fLCjQJCekTs" data-effect="fadeIn">
      <img class="img-fluid" src="images/video.jpg" alt="alternative">
      <span class="video-play-button">
       <span></span>
      </span>
    </a>
  </div> <!-- end of video-wrapper -->
</div> <!-- end of image-container -->
<!-- end of video preview -->

- And replace the video code fLCjQJCekTs with your new one which you can find on YouTube while using the Share option
- Save the file and refresh the browser window to see the changes
- To change the video preview image
- In the lines of code above replace video.jpg with your own image which you have previously saved in the images folder


-----------------------------------------------------


Change Statistics Numbers Values
- Open for editing index.html
- Find the section <!-- Statistics -->
- And then change the value of the data-count tag for each number


-----------------------------------------------------