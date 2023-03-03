FILES
- index.html holds the entire content
- css/styles.css custom css styling
- js/scripts.js custom js code with settings for sliders, rotating text and more
- images folder contains all the images


PLUGINS
- Bootstrap Datepicker https://github.com/eternicode/bootstrap-datepicker
- Bootstrap https://getbootstrap.com/
- jQuery https://jquery.com/ 
- jQuery Easing https://jqueryui.com/easing/
- Magnific Popup https://dimsemenov.com/plugins/magnific-popup/
- Swiper https://swiperjs.com/
- Font Awesome for icons https://fontawesome.com/


IMAGES
All images are included in the download package and can be reused in your projects. The ones mentioned below come for outside resources. The ones not mentioned come from inside resources. Either way you can use them for free in your project if you want.
- Header slider: https://unsplash.com/photos/vNAZubsDWMg
- Header slider: https://unsplash.com/photos/_uqDYFkrmLM
- Header slider: https://www.pexels.com/photo/woman-leaning-on-handrail-in-room-1838554/
- Description slider: https://unsplash.com/photos/vNAZubsDWMg
- Description slider: https://unsplash.com/photos/_uqDYFkrmLM
- Description slider: https://www.pexels.com/photo/woman-leaning-on-handrail-in-room-1838554/
- Description slider: https://unsplash.com/photos/JWGm_wkbL2o
- Description slider: https://unsplash.com/photos/aKcHgEfsDus
- Description slider: https://unsplash.com/photos/noelDNmA2_U
- Facilities background: https://www.pexels.com/photo/santorini-greece-2291340/
- Facilities tab: https://www.pexels.com/photo/photography-of-a-smiling-woman-831012/
- Facilities tab: https://www.pexels.com/photo/white-concrete-church-near-body-of-water-2249780/
- Facilities tab: https://www.pexels.com/photo/photo-of-people-sitting-on-white-sand-2230346/
- Facilities tab: https://www.pexels.com/photo/children-playing-on-swing-4430308/
- Facilities tab: https://www.pexels.com/photo/gray-car-with-queen-elizabeth-photo-window-visor-poster-776122/
- Rooms: https://unsplash.com/photos/sjvU0THccQA
- Rooms: https://unsplash.com/photos/gwV9eklemSg
- Rooms: https://unsplash.com/photos/vn30_b1ik6s
- Attractions: https://unsplash.com/photos/rFxk_Ea9PME
- Attractions: https://www.pexels.com/photo/parthenon-athens-greece-772698/
- Attractions: https://www.pexels.com/photo/white-painted-house-2668461/
- Attractions: https://unsplash.com/photos/_f1z9NtR2A8
- Testimonials background: https://www.pexels.com/photo/bath-clean-holiday-hotel-221457/
- Testimonial author: https://www.pexels.com/photo/photo-of-people-standing-near-blackboard-3184393/
- Article details large: https://unsplash.com/photos/_uqDYFkrmLM
- Article details small: https://unsplash.com/photos/X-J5ZZZ76sQ
- Balcony room slider: https://unsplash.com/photos/sjvU0THccQA
- Balcony room slider: https://unsplash.com/photos/M6S1WvfW68A
- Balcony room slider: https://unsplash.com/photos/Oc0VgI63s0g
- Panoramic room: https://unsplash.com/photos/gwV9eklemSg
- Panoramic room: https://unsplash.com/photos/jAcKPqCGS5M
- Panoramic room: https://unsplash.com/photos/0w8DUHgGGjs
- Presidential room: https://unsplash.com/photos/vn30_b1ik6s
- Presidential room: https://unsplash.com/photos/gwV9eklemSg


CREDITS
- Images by Pexels: https://www.pexels.com/


-----------------------------------------------------


Changing Datepicker Form Settings
- Please visit the plugin's website for documentation on how to change various settings
https://github.com/eternicode/bootstrap-datepicker

-----------------------------------------------------


Changing The Map
To change the map you need to:
- Open index.html from the template folder
- Find the section Location and then the following lines

<div class="map-responsive">
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6423.841890375458!2d25.435475745356655!3d36.386907765681734!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1499ce86adfd9ff7%3A0xb2a761f740d68afc!2sSantorini!5e0!3m2!1sen!2sro!4v1596106317886!5m2!1sen!2sro" allowfullscreen=""></iframe>
</div> <!-- end of map-responsive -->

- Go to Google Maps in your browser
- Find your desired location
- In the left sidebar click on Share
- In the new window click on Embed a map
- Then copy the provided HTML code
- Replace the original one in the template
- And remove all the additional tags besides allowfullscreen=""
- Save the file and refresh the browser window to see the changes