# Pizzeria Garofoli Website
Stream One Project: User-Centric Frontend Development - Code Institute

This is a responsive website for a traditional italian pizzeria. It's a front end site only and allows visitors to:
1.	Enter the atmosphere of the restaurant
2.	Reserve a table
3.	See the images in the gallery

## Demo

A demo of this site is available [here](https://chris92vr.github.io/Pizzeria-Garofoli).
 
## UX

#### User stories:

* As a user I would like to be able to view the Pizzeria internally.

* As a user I would like to be able to view the site on any device, including mobile, tablet and desktop.

* As a user I would like to be able to see pictures of dishes and restaurant in the gallery.

* As a user I would like to be able to view the associated social pages.

* As a possible customer I would like to be able to reserve a table.

* As a possible customer I would like to be able to contact Pizzeria for any questions.

* As a possible customer I would like to be able to find information about the address.

### Design and colors:

#### Fonts:

I used Lato, from Google Fonts.


#### Colors:

* ![#008c45](https://placehold.it/15/008c45/000000?text=+) rgb(0, 140, 69) - part of the italian flag on the header

* ![#F2F4F5](https://placehold.it/15/F2F4F5/000000?text=+) rgb(244,245,240) - part of the italian flag on the header

* ![#ff212a](https://placehold.it/15/ff212a/000000?text=+) rgb(255,33,42) - part of the italian flag on the header

* ![#000000](https://placehold.it/15/000000/000000?text=+) black - all the text




This website is designed for people who want information about the pizzeria and in the event the possibility of being able to reserve a table. 
My goal in the design was to recall the italian tradition to be able to easily access the basic contact information of the restaurant.
The main purpose of the site is to provide users with the presentation of the pizzeria in order to obtain new possible customers.

## Features
Each page features a responsive header divided into three, colored to look like the Italian flag. In the center an icon which recalls catering.
Under the flag there is a simple responsive navbar with the navigation elements on the right and the name of the pizzeria on the left.
Each page has a footer with contact information and social media icons.

##### Homepage
Contains a bootstrap carousel showing the interior view of the restaurant, with a description and a button to reserve a table.  

##### Reservation
In this page there is a responsive form in which you can reserve a table. It has been realized  with the bootstrap’s class form-row.

##### Gallery
Contains grouped images sorted by using the bootstrap row class.

### Existing Features

- Header Navigation Bar - Exists on every page and allows users to simply browse the pages of the entire site.
- Footer Address and Contact Info - Exist on every page, very useful for users interested in more information.
- Footer Social Icons - Exist on every page and allows all users to access the social platforms that the restaurant uses.
- [Carousel](index.html) - Slideshow of three images with text box in which there is a button to reserve a table. Designed to capture the attention of a possible customer. 
- [Gallery](gallery.html) - Allows all visitors to the website to view images of the pizzeria and its dishes.
- [Reservation form](reservation.html) - Allows potential customers on the Reservation page to enter the information needed to reserve a table.

### Features Left to Implement
In the future, I would like to implement the gallery by adding interactivity with javascript.

### Skeleton
[Index wireframe](https://github.com/chris92vr/Pizzeria-Garofoli/blob/master/projectdocumentation/wireframe/index.jpg)

[Gallery wireframe](https://github.com/chris92vr/Pizzeria-Garofoli/blob/master/projectdocumentation/wireframe/gallery.jpg)

[Reservation Page wireframe](https://github.com/chris92vr/Pizzeria-Garofoli/blob/master/projectdocumentation/wireframe/reservation.jpg)

[Index-mobile wireframe](https://github.com/chris92vr/Pizzeria-Garofoli/blob/master/projectdocumentation/wireframe/index-mobile.jpg)

[Gallery-mobile wireframe](https://github.com/chris92vr/Pizzeria-Garofoli/blob/master/projectdocumentation/wireframe/gallery-mobile.jpg)

[Reservation-mobile wireframe](https://github.com/chris92vr/Pizzeria-Garofoli/blob/master/projectdocumentation/wireframe/reservation-mobile.jpg)


## Technologies Used

  -  HTML 5
  -  CSS 3
  -  BootstrapCDN 
    - The project uses Bootstrap4 to simplify the structure of the website and make the website responsive easily.
    - The project also uses BootstrapCDN to provide icons from FontAwesome(https://www.bootstrapcdn.com/fontawesome/)
  -  jQuery 
    - The project uses its to reference Javascript needed for the responsive navbar.
  - Popper.js
    - The project uses its to reference Javascript needed for the responsive navbar.
  -  Google Fonts
          

## Testing
Several tests were carried out to verify the correct functioning of the project with positive results.
The functionality of the site is optimal. Any link and button is active and leads to the corresponding destination.
Browser compatibility is verified for Firefox, Chrome and Edge. The responsiveness of the pages is suitable on desktop screens, tablets and mobile phones.
In the folder [projectdocumentation/screenshots](https://github.com/chris92vr/Pizzeria-Garofoli/tree/master/projectdocumentation/screenshots), there are screenshots that show browser compatibility and responsiveness tests.


In order to to check the validity of the website code, I have used the following:

    - HTML Validation: https://validator.w3.org/ - no errors identified.
    - CSS Validation: https://jigsaw.w3.org/css-validator/ - Identified issues with bootstrap not with my project. 

#### Functionality Test
|Test Description | Expected Outcome | Pass/Fail
| ---|:-----------------------------------------:| :---: | 
| interact with the navbar | each element (home, gallery, reserve a table!) must lead to the corresponding page| pass
| carousel buttons         | the right and the left controls work as expected                                  | pass
| hover effect | hover effect on navbar, social link and reservation form works | pass
| form validation for required fields | the required fields (name, email, telephone, date, time and adult number) must be valid in order to send the form | pass
| social link | social links work, and open in a background tab | pass
| header image animation | the image in the center of the flag in the header is enlarged when the page is opened | pass


## Deployment  

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/chris92vr/Pizzeria-Garofoli), the following steps were taken: 
1. Log into GitHub. 
2. From the list of repositories on the screen, select **chris92vr/Pizzeria-Garofoli**.
3. From the menu items near the top of the page, select **Settings**.
4. Scroll down to the **GitHub Pages** section.
5. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
6. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
7. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.
 

### How to run this project locally

To clone this project from GitHub:
1. Follow this link to the [Project GitHub repository](https://github.com/chris92vr/Pizzeria-Garofoli).
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository. 
4. In your local IDE open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/USERNAME/REPOSITORY
```
7. Press Enter. Your local clone will be created.

## Author

**Christian Garofoli** 


## Credits

### Code

   - The shaded effect of the text box in the carousel I took inspiration from the following link:
     http://www.w3bai.com/it/css/css_image_transparency.html

### Images 
   - Images supplied by Pixbay, Upsplash, Pexels. The icon in the center of the header I have integrated it for free from http://icons8.com

Development time 20 days. 