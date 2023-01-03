# Ikshana
This project is based on a life coaching service named Ikshana. Ikshana meaning: *sight, care and superintendence but also refers to eye, sight, seeing, viewing, aspect, caring for, looking after, regarding.*

 This life coaching service offers support and guidance in reaching personal and professional goals in particular for individuals who find themselves in a situation where a loved one is afflicted with a disability. The serrvice provides guidance, empathy, accountability and support in providing clarity and focus and achieviving goals to individuals engaging with the service.

## Features

### Existing Features
* Navigation Bar
  * Featured on all pages of the website the reposive navigation bar allows users to easily and seamlessly navigatte to all areas of the site. 
   * Allows users to move from one page to another without having to use the back browser button 
   
   ![Navbar Full screen](https://user-images.githubusercontent.com/116117302/210172768-053b6b72-7116-448c-9070-7061f566a150.PNG)
    * The navbar is fully responsive and changes to a hamburger style when screen sizes go to 800px or below allowing ease of navigation with minimal space constraints.
  
  ![Navbar small screen](https://user-images.githubusercontent.com/116117302/210172881-529bd679-d17b-4d40-95fb-dc6a801c3dc5.PNG)
  
 * Landing Page
    * The landing page is an image of a person sitting on a hill in front of beautiful scneney and a winding path below. I really like this image as it can be perceived either as resting and admiring the end of a journey or contemplating the start of an exciting adventure. I wanted the image to be ignite users imaginations and inspire them that life coaching and self exploration can be an exciting, rewarding adventure as well as a challenge ans accomplishment.
    * The landing page also has zoom animation which further lends the page appeal to capture the users interest.
 <p align = "center">
<img src="https://user-images.githubusercontent.com/116117302/210173427-06fe660b-ac9f-42ce-98b4-5e9cf02e0e08.PNG">
</P>

* About Me page
  * The about me page talks about Carolines background and her journey to becoming a life coach. it features a picture of Caroline and a description of who she is 
  * A **read more** link was introduced on this page as there is a lot of text and this method allows the user to read more or less as they wish.
  
![aboutme](https://user-images.githubusercontent.com/116117302/210176582-8afeb279-5c1c-429f-8d6f-d9082c7b17ca.PNG)
![aboutme less](https://user-images.githubusercontent.com/116117302/210176586-69a4d039-c2b1-45ce-9736-29c1ffcce5cd.PNG)

* Services Page
  * On this page we describe the services provided with Ikshana coaching.
  * Images relevant to the contant were used to reflect the services provided and help to engage the user.

  <img src="../images/servicessmallscreen.png"/>
  <img src="/images/servicessmallscreen.png">

  * Text and images are displayed in column format on smaller screens and side by side on larger screens.


* Work With Me page
  * This page is designed to make it easy for the user to get in touch. On smaller screens the contact form takes the wisth of the page whereas on larger screens flex was used to stack the contact me section alongside the form.
  * The form is fully validated and the user must enter the correct details for the form.
  
  <p float= "left">
 <img height="277" width="235" src="https://user-images.githubusercontent.com/116117302/210178144-836b48e9-01e9-41bb-a636-b1338de216a9.PNG"/>
 <img height="277" width="235" src="https://user-images.githubusercontent.com/116117302/210177993-d3344c97-5ce5-4ae1-be1f-f6398287c27e.PNG"/>
 <img  height="277" width="235"src="https://user-images.githubusercontent.com/116117302/210177995-14e0a27f-1a54-44ac-b9a5-f06a2dc26332.PNG"/>
</p>

* Footer
  * The footer element is designed to provide easy navigation to the social networks of Ikshana coaching for the user. 
  * It is fully responsive and when cliked each link opens in a new window allowing the user to easily navigate back to the webpage.


  ![image of footer](assets/images/footer.PNG)


## Features left to implement

A feature I would like to implement is a booking system allowing users to see a calendar of available times and dates to book an appointment. This is outside of my resources and scope for this project but is something I would like to implement in the future.

## Testing



* HTML Validation

The code was passed through the W3C Markup Validator and returned no errors

![image of W3C HTML Validation](assets/images/HTML%20Validation%20Index%20page.PNG)

* CSS Validation

The code was passed through the CSS Validation Service and no errors were found

![image of CSS Validation message](assets/images/css%20validation.PNG)

* Lighthouse 

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

  * Desktop Results:

    * Home page:
    Desktop

    ![image of home page Lighthouse report](assets/images/readmeimages/homepagedesktop.PNG)

    Mobile

    ![image of home page Lighthouse report](assets/images/readmeimages/homepagemobile.PNG)

    * About Me page:

    Desktop

    ![image of about me page Lighthouse report](assets/images/readmeimages/aboutmepagedesktop.PNG)

    Mobile

    ![image of about me page Lighthouse report](assets/images/readmeimages/aboutmepagemobile.PNG)

    * Services page

    Desktop

    ![image of services page Lighthouse report](assets/images/readmeimages/servicespagedesktop.PNG)

    Mobile

    ![image of services page Lighthouse report](assets/images/readmeimages/servicespagemobile.PNG)

    * Contact page

    Desktop

    ![image of contact page Lighthouse report](assets/images/readmeimages/contactmedesktop.PNG)

    Mobile

    ![image of contact page Lighthouse report](assets/images/readmeimages/contactpagemobile.PNG)

    The lighthouse reports for performance were affected by images being in .png and .jpg format, which is something I will consider changing in the future to overcome this performance issue.

    ### Further Testing

    * The project was tested on the following browsers with success, Google Chrome, Safari and Firefox.

    * Project was manually tested on an iPhone 11 and an Ipad mini with success.

    * I used Google Chrome Developer Tools throughout the project to test responsiveness and to debug.

    * Google Chrome Tools emulated devices such as:

        * Apple iPad
        * Apple iPhone X
        * Apple iPhone 6/7/8 Plus
        * Apple iPhone 6/7/8
        * Apple iPhone 5/SE
        * Google Pixel 2/2 XL
        * Samsung Galaxy S5
        * Motorola G4
        * Microsoft Surface Duo
        * Apple iPad Pro

  ## Known bugs and fixes

  I dealt with many bugs while working on my project but was able to resolve most. Here are the details of what I encountered:
  
  * My styling was completely absent in my live website. This occured because I had implemented absolute file path in my css style sheet link.
    I corrected this by making my file path relative.
  * Images would not load on my live website. This occured as I had places my images folder outside of my assets folder. I corrected this but my images still would not load. Again this occured because of absolute file paths. I amended this by making all my image filepaths relative.

  * My gitpod console stopped updating my commits because of work done remotely. This occured because I wrote some of my readme file within GitHub instead of within Gitpod and needed to pull the file in to update it.

  ![picture of gitpod error](assets/images/readmeimages/gitproblem.PNG)


  This was a worrying error for me as I was afraid my work would not be saved but it got resolved with help from the gitpod channel in the slack coomunity.

  * Lighthouse performance score is sub optimal for my site pages. I will look at methods to amend this.

  * There is a gap between my footer element and the main part of my pages which does not look good. I am working to amend this.

  

## Deployment

### Github

This project was deployed sing GitHub pages with the following process:

**Deploying a GitHub repository via GitHub Pages**

1. In your *Repository section*, select the Repository you wish to deploy.
2. In the top horizontal Menu, locate and click the *Settings* link.
3. Inside the Setting page, around halfway down locate the GitHub Pages Section.
4. Under *Source*, select the None tab and change it to *Master* and click *Save*.
5. Finally once the page resets scroll back down to the GitHub Pages Section to see the following message *"Your site is ready to be published at (Link to the GitHub Page Web Address)"*. It can take time for the link to open your project initially, so please don't be worried if it does not load immediately.

**Forking the GitHub Repository**

You can fork a GitHub Repository to make a copy of the original repository to view or make changes without it affecting the original repository.

1. Find the GitHub repository you want to fork.
2. Click the Code button.
3. Copy the link shown.
4. In Gitpod, change the directory to the location you would like it to be.
5. Type git clone, and paste the link you copied in step 3.
6. Press Enter to have the clone created.









