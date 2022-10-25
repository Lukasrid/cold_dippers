# Cold Dippers

Cold Dippers is a website for a Brighton based cold water immersion community. The purpose of the website is to bring like mided people together who want to reap the benifits of exposure to the cold. It is there to provide support and information to anyone who may be interested. 

![Website displayed on different screen sizes](./images/am-i-responsive-cold-dippers.PNG)

## Features

### Existing Features

- #### Logo and Navigation Menu
    - The Cold Dippers logo and the three different pages available are displayed on the top of each page in the exact same way on each page for easy navigation.
    - A small description of who the Cold Dippers are is displayed under the logo.
    - Clicking the logo will bring you back to the homepage from any of the three pages.
    -The current page you are on will have the page name underlined in the navigation menu.

![logo and navigation menu](./images/Logo.PNG)

- #### Homepage Image and Description
    - The first thing on the homepage is a picture of the Brighton sea with a community description to let the user know what the aim of the website is as well as a glimpse into the environment they will be getting into.
    - The image is made with a parallax scrolling effect to give the sense that it is a window looking out to Brighton sea to draw in the user.

![Homepage picutre and community description](./images/homepage-image.PNG)

- #### Homepage Information
    - The homepage information starts of with a few questions to see if this communiity is something new potential members may be interested in.
    - The homepage then goes on to a section where some information about the benefits of this practice is given. 
    - Some motivaional words are presented through this section to help encourage people to join.
    - At the very bottom of the hompage you will find logos of different social media platforms that each link to the specified social platform for the Cold Dippers community. These logos and links can be found at the bottom of each page within the website in the exact same style.

![Homepage information and social media links](./images/homepage-info.PNG)

- #### Community Images and Values
    - At the top of the community page there are some images displayed of the Brighton sea and members taking part in the cold water swimming. 
    - A set of values is labeled and displayed under the community images to let the users know what the values the community likes to promnote and finds most important.

![Community Images and Values](./images/community-pic-values.PNG)

- #### Get In Touch Form
    - At the bottom of the community page a 'Get in touch' form can be found that lets users type in their e-mail, message, reason for contact and check a box if they would like to recive a weekly newsletter from the community.
    - A group picture of the Cold Dippers community is located next to the form in order to provide some sense of who they are contacting. 
    - The send button has a hover effect turning it a different color.

![Get in touch form and community group photo](./images/get-in-touch.PNG)

- #### Times, Location and Important Informatiuon
    - At the top of the information page the meet up days and times can be found followed by a description of the location.
    - A map is embeded next to meet-up times with the meet-up location pin pointed.
    - Additional important information can be found next to the map and how to find extra information on social platforms incase of unforseen events.

![Meet-up times, meet-up location and additional information](./images/info%2Blocation.PNG)


- #### About Us
    - The bottom of the information page an about section contains a more detailed description about the origins of the community and the goals it aims to achieve.

![A detailed description of the community origins and goals](./images/about-us.PNG)

- #### Additional Features
    - All links within the webpage will open in new tabs for easy navigation.
    - All links within normal text are blue and underlined for easy identification that they are links.
    - A blue gradient effect has been added to the background of all pages to give off the sense that you are submerging into cold water as you scroll down.
    - Certain words and phrases have been accentuated with color change, being made bold or made italicised where emphasis is deemed important.

### Features Left to Implement
 - The community values on the information page, when each value is clicked a box or a link to another page will open describing each value more in detail and how the community works to keep them up.
 - A contact page will be added where all relevant contact information will be collected including the get in touch from from the community page.
 - A log in function will be added for members to have their own personal profile. 
 - On the community page a discussion board will be added where members can post threads and comments. 

 ## Testing
  - ### Screen Sizes
    - Media queries have been added to all parts of the code that did not resize well when the screen size was made smaller. This includes: 
        - The positioning of certain elements such as the "Come get wet with the Cold Dippers" circle on the homepage. 
        - The resizing of margins and paddings to create a nicer visiual experience such as the margins of the community values on the community page.
        - The resizing of the message box in the "Get in touch!" form for different screen sizes.
    - The website now works and looks good on screen sizes down to 285px.
    - When the website is very zoomed out the blue gradient background will repeat after a while. *(Update: this was fixed with an added background-repeat: no-repeat; function in the css file.)
    ![Reapeating gradient background](./images/background-repeat.PNG) 

- ### Form
    - The "Get in touch!" form on the community page works, all the fields need to be filled in in order for the form to be allowed to be sent including having the appropriate email format. The newsletter checkbox is however optional.
    ![Form filled in](./images/form-filled.PNG)![Form data processed](./images/form-sent.PNG)
    - In the future as "Success" message will appear on the screen rather than being redirected to the input data.

- ### Links
    - All links have been tested that they work and open up in new tabs. 

- ### Lighthouse
    - Home page: gave a good score across all areas

    ![Lighthouse score for home](./images/lighthouse-home.PNG)

    - Community page: gave good scores except in the performane area

    ![Lighthouse score for community](./images/lighthouse-community.PNG)

    This was thought to be due to the pictures involved being too large so a different format was tried. All the files were converted from JPEG to webp files. This however lowered the performance score

    ![lighthouse score for community with .webp image files](./images/lighthouse-community-webp.PNG)

    The image files were then inserted in as JPEGs but in a compressed format to try and improve the performance score

    ![Lighthouse score for community with compressed JPEGs](./images/lighthouse-community-compressed.PNG)

    This improved the score slightly but not by much which suggests there is another underlying problem bringing down the performance score which has not been found. It may perhaps be the form or unoptimized code written for the page.

    - Information page: gave a good score across all areas

    ![Lighthouse score for information](./images/lighthouse-info.PNG)

## Validator Testing
- ### HTML
No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Flukasrid.github.io%2Fcold_dippers%2F)
- ### CSS
No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Flukasrid.github.io%2Fcold_dippers%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)


