FILES
- index.html holds the entire content
- css/styles.css custom css styling
- js/scripts.js custom js code with settings for countdown timer, particles and more
- images folder contains all the images


PLUGINS
- Bootstrap https://getbootstrap.com/
- jQuery https://jquery.com/ 
- jQuery Easing https://jqueryui.com/easing/
- Magnific Popup https://dimsemenov.com/plugins/magnific-popup/
- Swiper https://swiperjs.com/
- Particles https://vincentgarreau.com/particles.js/
- The Final Countdown http://hilios.github.io/jQuery.countdown/
- Font Awesome for icons https://fontawesome.com/


IMAGES
All images are included in the download package and can be reused in your projects. The ones mentioned below come for outside resources. The ones not mentioned come from inside resources. Either way you can use them for free in your project if you want.
- 03-lightbox-form background: https://www.splitshire.com/blackred-bodypainting/
- 06-video-background video background: https://www.videvo.net/video/flying-over-forest-3/4650/ converted with https://www.freefileconvert.com/file/4_reqmqP4rdG compressed with https://www.videosmaller.com/
- 08-video-in-header video: https://www.pexels.com/photo/close-up-photo-of-woman-using-phone-1452130/


-----------------------------------------------------


Update The Date Of The Countdown Timer
- Open for editing js/scripts.js
- Find the section /* Countdown Timer - The Final Countdown */
- Then find the following line of code:
$('#clock').countdown('2021/12/27 08:50:56') /* change here your "countdown to" date */

- Here update the date according to the following format: Year/Month/Day HH:MM:SS 


-----------------------------------------------------


Adding Self Hosted Video To The Video Background Version

- You need two elements, first is the actual video which works best in mp4 format with 1920x1080 (full HD) resolution. Second is a preview image file which is displayed until the video has loaded and usually is a screenshot of the first frame of the video. Same resolution 1920 x 1080 pixels
- Place the video file named e.g. forest-video.mp4 in the video folder and the image file named e.g. header-background.jpg in the images folder
- Now open for editing index.html
- Find the Header section
- Then find this piece of code:

<!-- Video Background -->
<video autoplay loop muted id="video-background" poster="images/header-background.jpg"> <!-- poster image used if video doesn't play-->
  <source src="video/forest-video.mp4" type="video/mp4" />
</video>
<!-- end of video background -->

- And instead of images/header-background.jpg and video/forest-video.mp4 place your own files
- Now save the file and refresh the browser window and see the result
- Keep in mind the video should be no more then 15MB in order to not keep the user waiting too long and cause him to use a lot of data credit (if he's on mobile)
- This is a great free tool to compress your files online: http://www.videosmaller.com/
- And the following are great source for free videos: https://videos.pexels.com/, https://www.videvo.net/