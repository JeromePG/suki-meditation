# Suki Meditation

The Suki Meditation website is built to service all walks of life to provide balance in peoples lives through the use of three different classes Meditation, Yoga and Qigong throughout the week, plus therapy sessions in Birmingham, England.

[View the live Suki Meditation page here](https://jeromepg.github.io/suki-meditation)

![website on diffrent monitor devices](https://user-images.githubusercontent.com/88581233/135259372-4de0eee9-4908-48cd-b322-7a267698ca15.jpg)

## Design

- ### Colour Scheme
- The two main colours used are Gold and grey. I chose these two colours to give the site a sacred zen feel to it, like a temple built by dark grey stone with precious gold ornaments in it. 

- ### Typography
- For the headings, the font 'Lora' is used to set the feeling of the website along with its complimental 'Source Sans Pro' font for the rest of the content.

- ### Imagery
- Background images are used all throughout the site with a coloured tint on them to ensure that the text over them is readable.

- ### Videos
-YouTube videos have been included to two of the sections to further explain and give examples of the content topic.

## Features

- The website consists of three pages, Home, About and Sign Up page. With the home page, I have included multiple sections specific to each of the classes held at Suki Meditation. 
- To make it easier to locate the different classes, I've added a section of buttons at the top of the home page that locate to the specific section of the page. For example, the Yoga button will take you to teh yoga section which gives a brief explanation of the class.

- Most of the buttons on the site inclide a transition command on them to add a smooth feel to the useability.

- The site is responsive to all device sizes ensuring each user has a friendly useable experience.

- The page that the user is currently on is highlighted in the navigation with it being a different font and colour.

![section navigation](https://user-images.githubusercontent.com/88581233/135284917-07046d9f-cf79-4fbf-ab0c-9cf625abc470.PNG)

- ### Times

	 - Each section on the homepage has a time table which gives specific days and times for each of the classes.
	 - when in full width, I have sectioned the time tables by giving them a background colour to separate it from the rest of the content.
	 - on a more narrow screen, I decided that sectioning it like this wasnt necessary so I removed their backgrounds.
	 - as well as this, on a narrow screen, to make it more organised, I added hr tags in between each day so that they are easily read.

- ### Footer

     - I added icon links at the bottom right of the footer that link to three social media pages (Facebook, Twitter and Instagram).
     - I ensured that socail media links open on a new tab so that the user can still easily access the main site.
     - When hovered, the icon logos transition from gold to white and slightly increases in size.
     - on the left of the footer is the company copyright text.

![footer](https://user-images.githubusercontent.com/88581233/135395158-e7659e45-c046-476c-96ce-4bc1ba8f8623.PNG)

- ## The About Page
     - The About page contains content that tells a story and explains how the company was founded and its purpose.
     - Below the about information is the address of teh location for the company with the phone number and email address included.

![about page](https://user-images.githubusercontent.com/88581233/135399650-e99ce051-7472-464e-bb95-887644d1f645.PNG)

- ## The Sign Up Form
     - The sign up form includes the main colours of the site including a grey background with a gold heading and gold Submit button
     - The form requires the full name and email address of the user and also a checkbox selection for them to choose which classes they are interested in
     - For the current purpose of not having a page to post the data to, I did not inclide the "method" or "url" in the form element

![signup form](https://user-images.githubusercontent.com/88581233/135396655-e1204230-4b85-456d-8061-7e0361bb7e96.PNG)


## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)

## Frameworks, Libraries & Programs Used

  1. [Google Fonts](https://fonts.google.com/)
     - Google fonts were used to import the 'Lora' and 'Source Sans Pro' fonts which are both used all throughout the site

  1. [Font Awesome](https://fontawesome.com/)
     - Font Awesome is used to display the social media icons in the footer

1. [Git](https://git-scm.com/)
     - Git is used to build and update content usimg the GitPod terminal to commit and push its content onto GitHub

1. [GitHub](https://github.com/)
     - GitHub is used to safely store the site content pushed from Git

## Testing

1. When testing the site as a whole, I wanted to ensure that there was a consistency of cleanliness and easy readability throughout the site. This included revisiting all the pages and ensuring to resize them to see if they worked and looked well on all sizes.

	1. When on a standard width computer monitor, the text appears besides the image or video, on a condensed screen, the text stacks on top of the image.

	2. I decided to drop the background images on a smaller screen. This is because you can't really make out much of what the image was, so it didn't make sense having it there. So instead, when the screen is scaled down, the background image is replace with a colour that matches the specific section's colour theme.

2. For a first time user. I want to enter the site having a clear idea what the purpose of the site is and how to use it.
	1. I displayed this by including welcoming content in the hero section with an introduction and and navigation section which directs the user to the specific classes held and a brief explanation on each of them.
	2. The About page further explains the purpose of the company and how it came to be.

### known issues

On screens 360 pixels and less, I noticed a white gap would appear on the right. I realised that this was due to the round image in the meditation section. I tried to scale it down by using percentage sizes but because the image being equalatral, it wasn't easy and would cause more hasstle by creating more media queries for each specific size width beneathe 360 pixels, so I instead decided to remove the image for screens 360 pixels wide and shorter.

### Overcome issues

- When on a standard width computer monitor, the brand logo appears on the left with the navigation buttons "Home, About and Sign Up" appear on the right. When tested on a mobile phone, I noticed that the logo and the navigation buttons appeared too close to each other and out of line. To sort this, I stacked the logo on top of the navigation links and both central.

![nav-full-width](https://user-images.githubusercontent.com/88581233/135328269-c3f94b1a-c85a-43fb-b178-68ddef77ee85.PNG)
![nav-narrow](https://user-images.githubusercontent.com/88581233/135328319-b0dbd1b1-f2c7-4a09-9f61-0c0d4da5bf7f.PNG)

- for the Sign Up page, Due to the form being absolute to its parent background, it did not affect the height of the page. Because of this, when testing on a smaller screen, the form would get chopped off at the bottom. to solve this, a height for the background was specified further for a smaller screen.

### Valitatior Testing

- HTML
  -No issues were found when passing the site through the [W3 validator](https://validator.w3.org/#validate_by_input)

- CSS
  -No issues were found when passing the site through [Jigsaw W3 validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

![site-validator](https://user-images.githubusercontent.com/88581233/135393409-a501b89d-697e-42df-b563-1c60f883b062.PNG)

### Further Testing

- The website was tested on Google Chrome, Firefox and Microsoft Edge browsers
- The website was further tested on a 17 inch windows laptop, an android phone (landscape and portrait) and on an iPhone X
- for further testing, a friend was asked to view the test and analyse its feel and functionality

## Deployment

1. sign in on the [GitHub site](https://github.com) and select the repository usually located on the left of the page
2. On the top of the repository page is a menu found below the repository name, locate and select the "Settings" button
3. On the Settings page scoll down until you find the heading "GitHub Pages"
4. From there, find the Source section then click the dropdown to select "None" then select masterbranch
5. You will be taken back to the settings page to locate back to the 'GitHub Pages' section, below it will be a yellow box which has a link that reads 'Check it out here!' which will be the link to the website.

## Making a local Clone

1. Sign in on the [GitHub site](https://github.com) and Select the repository
2. Below the navigation bar where the Settings is will be a section of buttons, select the "Code" dropdown button
3. Select "HTTPS" then below this, copy the link given
4. Open up Git Bash
5. in the Bash area type 'git clone' then paste in the link given from step 3
6. Press return (enter) then your local clone will be created

## Credits

### Content

- All content was written by the developer

## Media

- All images were downloaded from Getty Images
- All videos were imported from YouTube

## Acknowledgements

- My mentor, Aaron Sinnot gave great advice and feedback for the progression on building the site