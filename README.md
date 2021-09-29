# Suki Meditation

The Suki Meditation website is built to service all walks of life to provide balance in peoples lives through the use of three different classes Meditation, Yoga and Qigong throughout the week, plus therapy sessions in Birmingham, England.

[View the live Suki Meditation page here](https://jeromepg.github.io/suki-meditation)

![website on diffrent monitor devices](https://user-images.githubusercontent.com/88581233/135259372-4de0eee9-4908-48cd-b322-7a267698ca15.jpg)


## Design

- _Colour Scheme_
- The two main colours used are Gold and grey. I chose these two colours to give the site a sacred zen feel to it, like a temple built by dark grey stone with precious gold ornaments in it. 

- _Typography_
- For the headings, the for 'Lora' is used to set the feeling of teh website along with its complimentart font for the rest of the content 'Source Sans Pro'

- _Imagery_
- Background images are used all throughout the site with a coloured tint on them to ensure that the text over them is readable.

- _Videos_
-YouTube videos have been included to two of the sections to further explain and give examples of the content.

## Features

- The website consists of three pages, Home, About and Sign Up page. With the homepage, I have included multiple sections specific to each of the classes held at Suki Meditation. To make it easier to locate the different classes, I've added a section of buttons at the top of the homepage that locate to the specific section of the page. For example, the Yoga button will take you to teh yoga section which gives a brief explanation of the class.

- The site is responsive to all device sizes ensuring each user has a friendly useable experience

- The page that teh user is currently on is highlighted in the navigation with it being a different font and colour.

![section-navigation](https://user-images.githubusercontent.com/88581233/135284917-07046d9f-cf79-4fbf-ab0c-9cf625abc470.PNG)

### Times

- Each section on the homepage has a time table giving specific days and times for each of the classes
- when in full width, ive sectioned the time tables by giving them a background colour to separate it from the rest of the content
- on a more narrow screen, I decided that sectioning it like this wasnt necessary so I removed their backgrounds
- as well as this, i=on a narrow screen, to make it more organised, I added hr tags in between each day so that they are easily read.

## Technologies used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)

## Frameworks, Libraries & Programs Used

1. [Google Fonts](https://fonts.google.com/)
- Google fonts were used to import the 'Lora' and 'Source Sans Pro' fonts which are both used all throughout the site

1. [Font Awesome](https://fontawesome.com/)
- Font Awesome is used to display the social media icons in the footer

1. [Git](https://git-scm.com/)
- Git is used to build and update content usimg the Gitpod terminal to commit and push its content onto Github

1. [Github](https://github.com/)
- Github is used to store safely the site content pushed from Git


## Testing

1. When testing the site as a whole, I wanted to ensure that there was a consistency of cleanliness and easy readability throughout the site. This included revisiting all the pages and ensuring to resize them to see if they worked and looked well on all sizes.

	1. When on a standard width computer monitor the text appears besides the image or video, on a condensed screen, the text stacks on top of the image.

	2. I decided to drop the background images on a smaller screen. This is because you cant really make out much of what the image was, so it didn't make sense having it there, so instead, when they are scaled down, the background image is replace with a colour that matches the specific section's colour theme.

2. For a first time user. I want to enter the site having a clear idea what the purpose of the site is and how to utilise it
	1. I displayed this by including welcome content in the hero section by including an introduction and and navigation section which directs the user to the specific classes held and a brief explanation on each of them.
	2. The About page further explains the purpose of the company and how it came to be.

### known issues

on screens 360 pixels and less, I noticed a white gap would appear on the right. I realised that this was due to the round image in the meditation section. I tried to scale it down by using Percentage sizes but because the image being equalatral, it wasn't easy and would cause more hasstle creating more media queries for each specific size width beneathe 360 pixels, so I instead decided to remove the image for screens 360 pixels wide and shorter.

### Overcome issues

When on a standard width computer monitor, the brand logo appears on the left with the navigation buttons "Home, About and Sign Up" appear on the right. When tested on a mobile phone, I noticed that the logo and the navigation buttons appeared too close to each other and out of line. To sort this, I stacked the logo on top of the navigation links and both central.

![nav-full-width](https://user-images.githubusercontent.com/88581233/135328269-c3f94b1a-c85a-43fb-b178-68ddef77ee85.PNG)
![nav-narrow](https://user-images.githubusercontent.com/88581233/135328319-b0dbd1b1-f2c7-4a09-9f61-0c0d4da5bf7f.PNG)

for the Sign Up page, Due to the form being absolute to its parent, it did not affect the height of the page. when testing on a smaller screen, the form would get chopped off at the bottom. to solve this, a height for the background was specified further for a smaller screen.