FILES
- index.html holds the entire content
- css/styles.css custom css styling
- js/scripts.js custom js code with settings for sliders, countdown timer and more
- images folder contains all the images


PLUGINS
- Bootstrap https://getbootstrap.com/
- jQuery https://jquery.com/ 
- jQuery Easing https://jqueryui.com/easing/
- Magnific Popup https://dimsemenov.com/plugins/magnific-popup/
- Swiper https://swiperjs.com/
- The Final Countdown http://hilios.github.io/jQuery.countdown/
- Font Awesome for icons https://fontawesome.com/


IMAGES
All images are included in the download package and can be reused in your projects. The ones mentioned below come for outside resources. The ones not mentioned come from inside resources. Either way you can use them for free in your project if you want.
- Header slider: https://www.pexels.com/photo/people-working-in-front-of-the-computer-3184357/ 
- Header slider: https://www.pexels.com/photo/man-wearing-yellow-dress-shirt-using-silver-laptop-3184315/ 
- Header slider: https://www.pexels.com/photo/man-in-blue-sweater-sitting-on-beanbag-chair-beside-woman-wearing-eyeglasses-3184318/ 
- Instructor: https://www.pexels.com/photo/photo-of-man-wearing-eyeglasses-3184611/
- Audience: https://www.pexels.com/photo/photo-of-woman-writing-on-blackboard-3184644/
- Lightbox: https://www.pexels.com/photo/people-taking-group-picture-3184398/  
- Video preview: https://www.pexels.com/photo/people-inside-room-3184657/ 
- Testimonial authors: https://www.pexels.com/photo/photo-of-people-standing-near-blackboard-3184393/
- Invitation: https://www.pexels.com/photo/white-wooden-table-with-chairs-set-416320/ 
- Article details image large: https://www.pexels.com/photo/photo-of-imac-near-macbook-1029757/ 
- Article details image small: https://www.pexels.com/photo/apple-office-internet-ipad-38544/ 


CREDITS
- Images by Pexels: https://www.pexels.com/


-----------------------------------------------------


Update The Date Of The Countdown Timer
- Open for editing js/scripts.js
- Find the section /* Countdown Timer - The Final Countdown */
- Then find the following line of code:
$('#clock').countdown('2021/12/27 08:50:56') /* change here your "countdown to" date */

- Here update the date according to the following format: Year/Month/Day HH:MM:SS 


-----------------------------------------------------


Changing The Video Section Video
- Open for editing index.html
- Find the Video section
- Then find the following lines of code:

<!-- Video Preview -->
<div class="image-container">
  <div class="video-wrapper">
    <a class="popup-youtube" href="https://www.youtube.com/watch?v=fLCjQJCekTs" data-effect="fadeIn">
      <img class="img-fluid" src="images/video-preview.svg" alt="alternative">
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
- In the lines of code above replace video-preview.svg with your own image which you have previously saved in the images folder