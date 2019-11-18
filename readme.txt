The images are located in the “images” folder and by default have 15 photos in them, their names are:
img_1.jpg
img_2.jpg
img_3.jpg
img_4.jpg
img_5.jpg
img_6.jpg
img_7.jpg
img_8.jpg
img_9.jpg
img_10.jpg
person_1.jpg
person_2.jpg
person_3.jpg
person_4.jpg
person_5.jpg

on the index page, ie. “Home” , the first 10 photos sycle through on a loop,
person_4.jpg appears on the “about me” page in a profile like format, 

To add more photos:
1. Copy and paste this code block into the index.html file

<div class="col-6 col-md-6 col-lg-4" data-aos="fade-up">
          <a href="images/img_1.jpg" class="d-block photo-item" data-fancybox="gallery">
            <img src="images/img_1.jpg" alt="Image" class="img-fluid">
            <div class="photo-text-more">
              <span class="icon icon-search"></span>
            </div>
          </a>
        </div>

2. Change all instances of “img_1.jpg” to the file name of the photo