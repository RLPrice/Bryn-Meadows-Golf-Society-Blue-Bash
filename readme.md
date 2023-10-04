# **Bryn Meadows Blue Bash Golf Society**

![Society Logo](assets/readme-images/bluebash.jpg)

Welcome to the Bryn Meadows Blue Bash Golf Society, a community of golf enthusiasts dedicated to enjoying the game and fostering camaraderie. Our society is all about bringing together players of different skill levels who share a passion for golf and a desire to have fun on the course.

<!--omit in Table of Contents-->

## **Table Of Contents**

- [**Bryn Meadows Blue Bash Golf Society**](#bryn-meadows-blue-bash-golf-society)
  - [**Table Of Contents**](#table-of-contents)
  - [**Project Scope**](#project-scope)
  - [**User-Centric Design**](#user-centric-design)
    - [**User Scenarios**](#user-scenarios)
      - [**First Time User Goals**](#first-time-user-goals)
      - [**Social Interaction Goals**](#social-interaction-goals)
      - [**Frequent Visitor Goals**](#frequent-visitor-goals)
  - [**Structure**](#structure)
  - [**Visual Elements**](#visual-elements)
    - [**Colour Palette**](#colour-palette)
      - [**Colour Psychology**](#colour-psychology)
      - [**Colour Usuage**](#colour-usuage)
    - [**Font-Choices**](#font-choices)
      - [**Primary Font: Montserrat**](#primary-font-montserrat)
      - [**Secondary Font: Lato**](#secondary-font-lato)
      - [**Accent Font: Great Vibes**](#accent-font-great-vibes)
      - [**Font Pairing Strategy**](#font-pairing-strategy)
      - [**Font Psychology**](#font-psychology)
    - [**Visual Assets**](#visual-assets)
      - [**Photography**](#photography)
      - [**Iconography**](#iconography)
      - [**Logo and Branding**](#logo-and-branding)
      - [**Layout and Design Elements**](#layout-and-design-elements)
      - [**Visual Consistency**](#visual-consistency)
    - [**BluePrints**](#blueprints)
    - [**Design Distinctions**](#design-distinctions)
      - [**Photography \& Images**](#photography--images)
      - [**Iconography**](#iconography-1)
      - [**Logo \& Branding**](#logo--branding)
      - [**Layout \& Design Elements**](#layout--design-elements)
      - [**Responsive**](#responsive)
      - [**Limitations**](#limitations)
      - [**Current Functionalities**](#current-functionalities)
      - [**Pending Features**](#pending-features)
    - [**Technologies**](#technologies)
    - [**Testing**](#testing)
      - [**User Story Testing**](#user-story-testing)
    - [**Automated Testing**](#automated-testing)
    - [**Issues and Resolutions**](#issues-and-resolutions)
    - [**Deployment**](#deployment)
    - [**How to run the Project Locally**](#how-to-run-the-project-locally)
      - [**Clone the Repository**](#clone-the-repository)
      - [**Download the Repository Manually**](#download-the-repository-manually)
    - [**Credits**](#credits)
    - [**Media**](#media)
    - [**Code**](#code)
    - [**Acknowledgements**](#acknowledgements)

## **Project Scope**

The scope of this project encompasses the creation of a website, which serves as the designated solution for accomplishing the inaugural Milestone Project mandated by the Code Institute's Full Stack Developer program. The project scope extends to the utilization and application of acquired knowledge from modules such as HTML, CSS, and User-Centric Design. For an exhaustive compilation of the technologies harnessed for the project's execution, kindly consult the technologies section within this documentation.

## **User-Centric Design**

### **User Scenarios**

Here are some user scenarios for the "Bryn Meadows Blue Bash Golf Society" webpage, considering different types of users and their goals.

#### **First Time User Goals**

Jane is an avid golfer who just heard about the Bryn Meadows Blue Bash Golf Society from a friend. She visits the website to learn more and considers joining the society.

Jane wants to understand the benefits of the society, find information about upcoming events and tournaments, course and facilities and find contact information to inquire about membership.

> For first time users the webpage needs to have a straight forward comprehension of the primary purpose of the webpage and a chance to gain deeper insights in to the society. The webpage needs to have seamless navigation across the webpages, allowing users to conveniently explore its content and locate the information they seek. Finally, the webpage needs to be accessible from a mobile device with ease and clarity, ensuring that the content is presented in a user-friendly manner.

#### **Social Interaction Goals**

John, a sociable member, logs in to the website to connect with other golf society members.

John wants to participate in forum discussions about recent events and matches, find out if any members are looking for playing partners, share his own golfing experience and insights and access member profiles to get to know fellow golfers.

> The web page would need to implement a secure user authentication system to allow members to log into their account. This can involve username/password authentication or even integration with social media accounts. The webpage would need a dedicated forum section where mebers can engage in discussions about recent events and matches. Each discussion thread should be categorized for easy navigation. The webpage will ensure the user interface is intuitive and easy to navigate, with clear labels, buttons, and menus so members can easily access the desired features. Also, ensure the entire structure is mobile-responsive to allow members to access the community and its features seamlessly from their mobile device.

#### **Frequent Visitor Goals**

Sarah frequently visits the golf course and uses the website to book tee times for her rounds.

Sarah wants to be able to view the tee time schedule for the next week, choose a suitable tee time slot and reserve the tee time and recieve a confirmation.

> The webpage design will require a dedicated section that displays the tee time schedule for the upcoming week minimum. The schedule should provide available tee time slots and the available number of slot for each tee time. There will need to be a reservation page so the chosen tee time can be reserved with a confirmation email.

## **Structure**

Webpages will contain a navigation bar at the top of each page, allowing users to navigate to a new page for the desired content. This will be collapsable on smaller devices to accomodate the following user story.

> The webpage needs to have seamless navigation across the webpages, allowing users to conveniently explore its content and locate the information they seek. Finally, the webpage needs to be accessible from a mobile device with ease and clarity, ensuring that the content is presented in a user-friendly manner.

The homepage will feature an about section explain the goals and objectives of the society. This will be to facilitate the following user story.

> She visits the website to learn more and considers joining the society. Jane wants to understand the benefits of the society

There will be a golf course page explaining Bryn Meadows Golf Course and all of it's facilities and features. This is to accomodate the follwing user stories.

> Learn about the golf course and facilities

There will be a fixtures and results page to allow user to find information and upcoming and past events. This will fullfill the following user sotries.

> find information about upcoming events and tournaments,

The final page will be a link to an external source to allow users to view and book tee times. This will aid the following user stories. There will also be an additional link provided in the footer

> Sarah wants to be able to view the tee time schedule for the next week, choose a suitable tee time slot and reserve the tee time and recieve a confirmation.

The footer will be available across all pages and will contain a link to the Bryn Meadows Golf Course where the contact information and membership information is availble. This will fullfill the following user story.

> find contact information to inquire about membership.

The footer will also contain links to social media site. This will allow users to join social groups associated with Bryn Meadows Golf Course to allow users to communicate with members. This will accomodate the following user story.

> John wants to participate in forum discussions about recent events and matches, find out if any members are looking for playing partners, share his own golfing experience and insights and access member profiles to get to know fellow golfers.

Custom CSS and/or Bootstrap will be applied to ensure the website's responsiveness, utilizing media queries and/or the Bootstrap Grid system.

The layouts of all pages will adapt based on screen size, ensuring that content is visually appealing, images are correctly presented, and content is not compressed too tightly, resulting in illegibility.

## **Visual Elements**

### **Colour Palette**

The Colour palette chosen for the "Bryn Meadows Blue Bash Golf Society" webpage is carefully curated to reflect the spirit of the golfing community while maintaining a visually appealing and user-friendly interface. The colours have been selected to evoke a sense of elegance, vibrancy, and connection with the nauural beauty of the golf course.

| \*\*Primary colours |         |
| ------------------- | ------- |
| Deep Teal:          | #006D77 |
| Grass Green:        | #3EB489 |
| Cloud White:        | #FFFFFF |

| **Accent Colours** |         |
| ------------------ | ------- |
| Golden Sun:        | #FFD166 |
| sky Blue:          | #93C6EO |

#### **Colour Psychology**

- **Deap Teal** conveys stability, trustworthiness, and a sense of depth, aligning with the golf society's reliability and commitment to the sport.
- **Grass Green** symbollises growth, harmony, and a connection to nature, reflecting the golfing experience and the beautiful golf course.
- **Cloud White** cultivates an atmosphere of clarity. professionalism, adn tranquility, enhancing the overall user experience and aligning with the society's values.
- **Golden Sun** adds a touch of warmth, optimism, and energy, enhancing the overall inviting atmosphere.
- **Sky Blue** elicits a feeling of tranquility and openness, enhancing the user's comfort while navigating the webpage.

#### **Colour Usuage**

- **Deep Teal** serves as the primary background colour providing a solid and grounding base for the webpage.
- **Grass Green** is used sparingly to highlight important elements, such as buttons, call-to-action sections, and active links.
- **Cloud White** is employed for text and content backgrounds, ensuring readability and a clean, crisp appearance.
- **Golden Sun** is used for speacial highlights and interactive elements that need to draw attention.
- **Sky Blue** complements the colour scheme and is utilised for subtle accents that add a touch of freshness.

The colour palette has been chosen with careful consideration for accessibility, ensuring that text remains easily readable against various background colours. This cohesive palette enhanves the user experience and reinforces the visual identit of the "Bryn Meadows Blue Bash Golf Society" webpage.

### **Font-Choices**

The selection of fonts for the "Bryn Meadows Blue Bash Golf Society" webpage plays a pivotal role in establishing a cohesive and visually appealing brand identity. The chosen fonts have been thoughtfully considered to ensure optimal readability, complement the website's design, and convey the society's essence.

#### **Primary Font: Montserrat**

- **Typeface:** Sans-serif
- **Description:** Montserrat offers a modern and elegant appearance, making it a suitable choice for headings, titles, and prominent text. Its clean lines and versatility align well with the golf society's professional and approachable image.

#### **Secondary Font: Lato**

- **Typeface:** sans-serif
- **Description** Lato is a highly legible font that works excellently for body text, paragraphs, and longer content. Its balanced proportions and comfortable readability enhances user experience while navigating the website.

#### **Accent Font: Great Vibes**

- **Typeface:** Script
- **Description:** Great Vibes adds a touch of elegance and uniqueness to special elements such as quotes, featured events, or headings requiring a more decorative apperance. It injects personality while maintaining a sense of sophistication.

#### **Font Pairing Strategy**

The pairing of Montserrat and Lato ensures a harmonious blend of modernity and readability. Montserrat's geometric elegance contrasts well with Lato's rounded shapes, creating a visually appealing hierarchy that guides users through the content seamlessly.

#### **Font Psychology**

- **Montserrat:** It's clean lines and structured design convey professionalism and reliability, aligning with the golf society's commitment to excellence and organisation.
- **Lato:** The balanced and approachable nature of Lato fosters a sense of inclusivity and openness, reflecting the friendly and welcoming atmosphere of the society.
- **Great Vibes** The use of Great Vibes for accent elements adds a touch of elegance and sophistication, enhancing the user's experience and capturing the essence of special occasions and events.

The combination of these fonts contributes to the overall aesthetic and user experience of the "Bryn Meadows Blue Bash Golf Society" webpage, ensuring that content in not only readable but also visually engaging.

### **Visual Assets**

The visual assets used on the "Bryn Meadows Blue Bash Golf Society" webpage have been thoughtfully curated to enhance the user experience, convey the society's identity, and provide a visually engaging presentation of content.

#### **Photography**

High-quality photographs capture the essence of the golfing experience and the natural beauty of the golf course. These images are strategically placed throughout the website to provide visual context and evoke a sense of connection with the golf society's offerings.

#### **Iconography**

A collection of carefully selected icons has been integrated to enhance navigation, highlight features, and make the user interface more intuitive. These icons are utilised in menus, buttons, and sections to visually communicate information efficently.

#### **Logo and Branding**

The golf society's logo serves as a corner stone of its visual identity. It is prominently displayed on the website to establish brand recognition and create a consistent visual presence. The logo's colours and design align with the overall aesthetics of the site.

#### **Layout and Design Elements**

The layout of the website incorporates grids, sections, and visual hierarchy to guide users seamlessly through the content. Consistent design elements such as buttons, headers, and backgrounds contribute to a visually pleasing and user-friendly interface.

#### **Visual Consistency**

Maintaining visual consistency across the webpage ensures a unified and coherent user experience. The careful integration of photography, iconography, branding, typography, and colours creates an enviroment that resonates with the users and reinforces the golf society's brand identity.

### **BluePrints**

Home Page Computer
![Home Page Computer](./assets/readme-images/Home-Page-Computer.jpg)

Golf Course Page Computer
![Golf Course Page Computer](./assets/readme-images/Golf-Course-Computer.jpg)

Fixture Page Computer
![Fixtures Computer](./assets/readme-images/Fixtures-Computer.jpg)

Home Page Tablet

![Wireframe Tab Home](./assets/readme-images/Ipad-Home.png)

Golf Course Page tablet

![Wireframe Tab Course](./assets/readme-images/Golf-Course-Ipad.png)

Fixtures Page Tablet

![Wireframe tab Fix](./assets/readme-images/Fixtures-Ipad.png)

Home Page Smartphone

![Wireframe SP Home](./assets/readme-images/home-phone.png)

Golf Course Page Smartphone

![Wireframe SP Course](./assets/readme-images/golf-course-phone.png)

Fixtures Page Smartphone

![Wireframe SP Fic](./assets/readme-images/fixtures-phone.png)

### **Design Distinctions**

#### **Photography & Images**

Photography and Images play a pivotal role in my web page's design. I incorporated a diverse range of photographs and images, carefully selected to align with my project's narrative and branding. These visuals go beyond aesthetics; they are instrumental in conveying my story to the audience and reinforcing my brand identity. The high quality and resolution of these images not only ensure a visually appealing presentation but also enhance user engagement. By integrating these visuals thoughtfully, i aim to create a captivating and immersive user experience that resonates with our project's core message and values.

![Home Page Background](./assets/readme-images/Community-golf.jpg)

#### **Iconography**

Iconography is a fundamental component of my web page's design, serving to enhance user navigation and content comprehension. utilizing a variety of icons, each meticulously chosen for its specific purpose in improving the user experience. These icons act as visual cues, aiding users in quickly identifying and interacting with different features and functions on my page. To maintain visual consistency and align with my project's theme. Through these thoughtful icon choices, I aim to streamline user interactions and make content consumption more accessible and user-friendly.

![Icons](./assets/readme-images/icons.png)

#### **Logo & Branding**

My project's logo plays a pivotal role in establishing the brand identity and creating a lasting visual impression. The logo's design incorporates carefully selected colors and imagery that resonate with the essence of my project. Placed prominently within the web page, it serves as a cornerstone of our branding efforts, ensuring that users readily recognize and associate it with my project.

![Logo](assets/readme-images/bluebash.jpg)

#### **Layout & Design Elements**

My web page features a carefully crafted layout that ensures optimal user experience. Content is strategically placed to guide users seamlessly through the page, with headers and footers providing clear navigation and context. I have employed a responsive grid system to adapt the layout to different screen sizes, maintaining visual appeal and readability across devices. Design elements, including dividers and decorative elements, enhance the overall aesthetics and organization of our content. These elements not only improve visual appeal but also contribute to a consistent and cohesive user experience. By thoughtfully integrating layout and design elements, we've created an environment that resonates with users, reinforcing our project's visual identity and making the web page both engaging and accessible.

#### **Responsive**

The Bryn Meadows Blue Bash Golf Society's website has been meticulously designed to offer a responsive and user-friendly experience on all devices. Whether you're accessing the site from a desktop computer, laptop, tablet, or smartphone, the web page seamlessly adapts to various screen sizes and resolutions. This responsiveness ensures that users can enjoy the same high-quality content, stunning visuals, and intuitive navigation, regardless of the device they choose. From exploring the golf course details to booking tee times or accessing fixtures, the website's layout and design elements dynamically adjust to provide optimal readability and usability, making it accessible to a wide range of audiences and enhancing the overall user experience.

#### **Limitations**

The contact form on the Bryn Meadows Blue Bash Golf Society website primarily relies on Bootstrap (utilizing JavaScript and JQuery) for its functionality. However, it's important to note that due to the absence of additional JavaScript functionality beyond Bootstrap, the contact form does not have the capability to store submitted data or send email requests. While Bootstrap facilitates the display and interaction of the contact form through a modal interface, it lacks the backend processes required for data storage and email transmission. Therefore, users should be aware that any information entered into the contact form may not be stored or result in email notifications, as these advanced functionalities typically necessitate server-side scripting or backend development, which is not implemented in this specific form.

#### **Current Functionalities**

- **Contact Form** :- The functionality of the contact form on the Bryn Meadows Blue Bash Golf Society website allows visitors to interact with the website and send inquiries or messages to the website administrators or customer support team.
- **Booking Button** :- The link button to the booking form on the Bryn Meadows Blue Bash Golf Society website serves as a direct pathway for users to access and book tee times or other golf-related services.
- **GolfBreaks, Golf Lessons & Golf Facilities Buttons** :- The link buttons to "Golf Breaks," "Golf Lessons," and "Golf Facilities" on the Bryn Meadows Blue Bash Golf Society website provide specific functionalities tailored to different aspects of the golfing experience.
- **Find Us Button** :- The "Find Us" link on the Bryn Meadows Blue Bash Golf Society website provides functionality related to locating the physical address and geographical position of the golf course.
- **Socials Buttons** :- The social links on the Bryn Meadows Blue Bash Golf Society website provide functionality related to connecting with the golf society and its community through various social media platforms.

#### **Pending Features** 

- **Members Login** :- The intention of implementing a members login function is to enhance the user experience and provide a personalized and secure environment for registered members of the Bryn Meadows Blue Bash Golf Society website.
- **Scorecard & Handicapp Tracker** :- Integrate a digital scorecard system that allows golfers to record their scores, track their handicaps, and view historical performance data.
- **Golf Coursr Maps and Hole Overviews** :- Provide detailed maps and hole-by-hole overviews of the golf course, helping golfers plan their rounds and understand course layout.

### **Technologies**

- **HTML** :- HTML serves as the primary language utilised to construct the websites fundamental structure.
- **CSS** :- This projectemploys custom-written CSS to design and style the website.
- **Bootstrap v5.2.3** :- Throughout this project, the Bootstrap framework is utilised for both layout structuring and styling purposes.
- **Fontawesome** :- Font Awesom icons are employed for the social media links found within the website's navigation and footer sections.
- **Google Fonts** :- The project utilises Google Fonts to import the Montserrat and Lato fonts across the website, with Sans Serrif as the default.
- **GitHub** :- GitHub serves as the hosting platform for storing the source cose of the website, while Git Pages is employed for deploying the live site.
- **Git** :- Git serves as the version control software for commiting and pushing code to the GitHub repository, which stores the source code.
- **Google Chrome Developer Tools** :- The built-in developer tools of Google Chrome are utilised for inspecting page elements, aiding in debugging site layout issues, and experimenting with various CSS styles.
- **balsamiq wireframes** :- This tool was employed to generate wireframes during the "The Skeleton Phase" of UX design.
- **WebP Converter** :- This was employed to convert JPG files to WebP files for better loading times.
- **Google Chromes Lighthouse** :- Google Chrome's Lighthouse was used to evaluate accessibility.
- **W3C HTML Markup Validator** :- This was employed for HTML code validation.
- **W3C Jigsaw CSS Validator** :- This was utilised to valifate CSS Code.

### **Testing**

#### **User Story Testing**

**Expectation**
For first time users the webpage needs to have a straight forward comprehension of the primary purpose of the webpage and a chance to gain deeper insights in to the society. The webpage needs to have seamless navigation across the webpages, allowing users to conveniently explore its content and locate the information they seek. Finally, the webpage needs to be accessible from a mobile device with ease and clarity, ensuring that the content is presented in a user-friendly manner.

  **Realisation**
  
- The website's primary purpose, which is to introduce and provide information about the Bryn Meadows Blue Bash Golf Society, is prominently communicated on the homepage through clear headings and introductory text.
- The use of descriptive headings and visuals (such as images of golf courses) helps users quickly understand the nature of the society.
- Key sections like "Welcome to Bryn Meadows Blue Bash Golf Society!" provide deeper insights into the society's mission and offerings.
- The website features a well-structured navigation menu with clear labels, making it easy for users to find their way around.
- Navigation items like "Golf Course," "Fixtures," and "Contact Us" provide logical access to specific content areas.
- The use of hover effects on navigation items enhances user interactivity.
- The website is designed to be responsive, ensuring that it adapts to different screen sizes, including mobile devices.
- Mobile versions of hero images are provided to improve performance on smaller screens.
- The Bootstrap framework used in the website's design supports mobile responsiveness.

**Expectation**
 The web page would need to implement a secure user authentication system to allow members to log into their account. This can involve username/password authentication or even integration with social media accounts. The webpage would need a dedicated forum section where mebers can engage in discussions about recent events and matches. Each discussion thread should be categorized for easy navigation. The webpage will ensure the user interface is intuitive and easy to navigate, with clear labels, buttons, and menus so members can easily access the desired features. Also, ensure the entire structure is mobile-responsive to allow members to access the community and its features seamlessly from their mobile device.
  
**Realisation**

- Currently, the website does not have the implementation of a user authentication system. To meet this expectation, the website would need to develop a secure user authentication system that allows members to log into their accounts.
- The website does not have a dedicated forum section for members to engage in discussions as there is no user authrentication system. Implementing a forum section would require creating discussion threads, categorizing them, and providing a platform for members to interact and discuss recent events and matches. However, the website does have social links taking users to media platforms such as Facebook, Twitter and Instagram which allows users to use the forum sections for these platfroms.

**Expectation**
The webpage design will require a dedicated section that displays the tee time schedule for the upcoming week minimum. The schedule should provide available tee time slots and the available number of slot for each tee time. There will need to be a reservation page so the chosen tee time can be reserved with a confirmation email.

**Realisation**

- the expectation is to have a dedicated section displaying the tee time schedule for the upcoming week. There is apage displaying the fixtures for the upcoming month with a link to take tyou to the golf course teetime booking page. The website does not currently display a tee time schedule on the pages available for review but provides a link to an external page that does.
- The expectation includes a reservation page where users can reserve their chosen tee time slots and receive a confirmation email. This is not present on the website page but a link to an external booking website provides these functionlaities.

### **Automated Testing**

1. **W3C Markup Validation**

index.html was run through validator. Three errors were identified.

![Index.html Test Results](./assets/readme-images/index.html-Validator-Results.jpg)

Once errors had been corrected no further issues were found.

golf-course.html was run through validator. 17 errors were identified.

![golf-couse.html Test Results](./assets/readme-images/golf-course.html-results.jpg)

Once errors had been corrected no further issues were found.

fixtures.html was run through validator. Two errors were identified.

![fixtures.html Test Results](./assets/readme-images/fixtures.html-results.png)

Once errors had been corrected no further issues were identified.

2. **W3C CSS Validator**

style.css was put through a validator and no issues were found.

![style.css Test result](./assets/readme-images/style.css-result.jpg)

3. **Google Lighthouse**

Home Page Computer

![Computer Homepage](./assets/readme-images/computer-homepage.png)

Golf Course Computer

![Computer Golf Course Page](./assets/readme-images/golf-course-computer.png)

Fixtures Computer

![Fixtures Page Computer](./assets/readme-images/fixtures-computer.png)

Homepage Tablet

![Tablet Homepage](./assets/readme-images/tablet-home.png)

Golf Course Page Tablet

![Tablet Golf Coursr Page](./assets/readme-images/tablet-golf.png)

Fixtures Page Tablet

![Tablet Fixtures Page](./assets/readme-images/tablet-fixture.png)

Smartphone Homepage

![Smartphone Homepage](./assets/readme-images/phone-home.png)

Smartphone Golf course Page

![Smartphone Golf Course Page](./assets/readme-images/phone-golf.png)

Smartphone Fixtures Page

![Smartphone Fixtures Page](./assets/readme-images/phone-fix.png)

### **Issues and Resolutions**

- The validator picked up an issue with the hamburger drop down menu. The aria-controls section of the button tag wasn't targeting anything. I had not added the correct tag to the id of the dropdown. Once added this issue was resolved.
-  The validator picked up some / typos in the code. These were removed.
-  Once testing was vompleted an issue developed on the browser page were the heading and nav bar disappeared. I managed to work out by disabling the custom CSS that it had disappeared behinf the header banner colour. This was resolved by adding a z-index of 100 to the .header and .nav css instructions.

![Heading Issue](./assets/readme-images/heading-issue.png)

![Heading Issue Fix](./assets/readme-images/heading-issue-fix.jpg)

### **Deployment**

This project has been successfully deployed on GitHub Pages. To deploy your project, follow these steps:

1. Login to GitHub: Start by logging into your GitHub account.
2. Select the Repository: Locate project repository from the list.
3. Access Repository Settings: Within your repository, click on the "Settings" tab located amoung the sub-headings.
4. Configure Pages: In the left-side menu, find and select "Pages" from the "Code and Automation" section.
5. Choose Source: Under the "Source" heading, click the dropdown menu and select "main" as the source branch.
6. Set Default Path: Ensure that the second dropdown menu remains at the default value, which is (/root)/
7. Save Changes: Save your configuation settings.
8. Deployment Confirmation: You will recieve a message indicating that your website id ready to be deployed.
9. Refresh the Page: Refresh the page, and you will find a green sub-section at the top of the page with a link to your deployed site.
10. visit the Deployed Site: Click in the link to access and view your live deployed website.

### **How to run the Project Locally**

#### **Clone the Repository**

1. Visit the GitHub Repository at oks-erm/sofing.
2. Click on the "Code" drop-down menu.
3. Select "HTTPS" from the "Clone" heading.
4. Copy the provided link.
5. Open your preferred Integrated Development Environment (IDE) such as VSCode, Atom, or Komodo.
6. In a terminal, navigate to your desired directory and type git clone, then  paste the copied link.
7. Execute the command, and a clone of the repository will be created on your local machine.

#### **Download the Repository Manually**

1. Visit the GitHub Repository at rlprice-bryn-meadows-gol-hjxkvm140k.
2. Click on the "Code" drop-down menu.
3. Select "Download ZIP."
4. Download the ZIP file to your computer.
5. Locate the ZIP file and extract its contents into the directory where you wish to store the repository.
6. Open your chosen IDE (e.g., VSCode, Atom, Komodo).
7. Navigate to the directory where you extracted the repository.
8. You now have the entire project available offline on your machine.

### **Credits**

### **Media**

- Background Images from www.pexels.com
- Icons from www.fontawesome.com
- logo was created by myself
- Font styles from www.fonts/google.com

### **Code**

- Grid layout was from www.getcootstrap.com
- Code was created by myself with research from www.youtube.com, www.codeinstitute.net and other internet based resources.

### **Acknowledgements**

I want to express my gratitude to my mentor, Ronan McClelland, for his unwavering guidance, moral support, inspiration, invaluable advice, and wonderful sense of humor.


- 
- 
