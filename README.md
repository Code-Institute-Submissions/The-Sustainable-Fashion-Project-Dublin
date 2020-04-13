# **The Sustainable Fashion Project Dublin**

![Imgur](https://i.imgur.com/0KtzvQh.png)

## **Aim**
---

## **UX**

#### **Target Demographic**
The target demographic of this website includes but is not limited to:
 - those with an interest in Fashion
 - those who are socially and enviromentally conscious
 - those who are interested in learning more about sustainable fashion
 - those interested in learning more about fast Fashion
 - those who are would like to make more sustainable fashion choices
 - those who are looking for ways and ideas on how they can change their shopping habits

Users of this site are searching for:
 - Clear and easily accessible information on fast fashion
 - Clear and easily accessible information on sustainable fashion
 - Alternative shopping choices to High Street stores/Fast Fashion Brands
 - Real world locations they can shop sustainably

This site is best equipped to help them because:
- Easy to navigate
- Aesthetically pleasing
- Visually interesting 
- Doesn't overload the user with too much information
- Gives them the option to learn more with links to relevant sites

#### **Client Stories**
"As a user of this site, I want to easily find relevant information on fast fashion & sustainable fashion"

"As a user of this site, I want to learn more on fast/sustaianble fashion that is not preachy"

"As a user of this site, I want inspiration and ideas on what I can do to make a difference"

"As a user of this site, I want to learn about practical ways I can become more sustainable"

"As a user of this site, I want to know what alternatives there are to high street and fast fashion brands"

---
#### **Wireframes**
As part of the design process wireframes were created for Desktop, Tablet and Mobile screen sizes using [Balsamiq](https://balsamiq.com/)

#### **Desktop**
![Imgur](https://i.imgur.com/2HE6Qux.png)

#### **Tablet**
![Imgur](https://i.imgur.com/zdeNVvG.png)

#### **Mobile**
![Imgur](https://i.imgur.com/togKaFk.png)

---
## **Features**
The navigation bar is fixed to the top of the page with links to each section, so each part of the page can be easily accessed using the navigation links from anywhere on the site.

#### **Home**
The Home section features a full browser height background image to capture the users attention and spark further interest in the site. 
The website title is overlayed on the image with a subject line enticing the reader to explore the site further.

#### **The Facts**
An image to draw the users attention and a paragraph with some of the definition of fast fashion and facts about the industry. 
It also contains a call-to-action button for users who would like to more detailed information on the fast fashion industry and its ethical and environmental impact it makes.

A second image and paragraph with an overview of what changes users can make to their own habits to lessen their impact on the environment. 
Including links to relevant sites and resourses.

#### **Charity Shops**
An image to draw attention and a paragraph about the benefits of choosing charity shops. 
Includes links to various charity shops and their locations.

#### **Vintage Shops**
An image to draw attention and a paragraph on the benefits of shopping in vintage shops. 
Includes links to vintage shops in Dublin.

#### ** Repair & Upcycle**
An image to draw attention and a paragraph extolling the benefits of repairing/upcycling clothes.
Includes a link to sewing tutorials for beginners.

#### **Lookbook**
Photo gallery to showcase looks created using pieces of clothing bought in vintage/charity shops.
The purpose of the gallery is the hightlight the fact that users don't need to buy new clothes to create stylish, unique and on trend looks.

#### **Events**
List of events users of the site would have an interest in attending.
Option to book places and get more information about the events.

#### **Sign Up**
Call to action to sign up to the sites newsletter 
clicking the SignUp button which deploys a modal with the required attribute for the email address input.

Links to social media pages.

#### **Footer**
Contains copyright information.

---
### **Future Features to be Implemented**
- Add pages for Projects based on other major cities in Ireland (Galway, Cork, Belfast) initially, with a view to setting up projects for UK & European cities in the long term.
- An interactive gallery that will allow:

    * users to submit their own images of 
     outfits and looks they've created from clothing bought from charity/vintage shops
    * owners to review submissions before they are posted to the site 
    * owners to set criteria for submissons - location, suitability, where it was purchased etc.

- A curated directory of sites, articles and resources users of the site would be interested in.
- Submissions from hosts of relevant events that will be promoted on the site.
- A News section that can be updated easily and regularly by owners.
---
## **Technologies Used**
- HTML & CSS programming languages
- [Bootstrap 4](https://getbootstrap.com/) and [BootstrapCDN](https://www.bootstrapcdn.com/) - To simplify the structure and make the website responsive.
- [Google Fonts](https://fonts.google.com/) - Oswald & Poppins styles
- [Font Awesome](https://fontawesome.com/) - for social media icons
- [jQuery](https://code.jquery.com/) - for navbar and modal
- [Popper.js](https://popper.js.org/) - for navbar and modal
- [Gitpod](https://gitpod.io/) - IDE for local development
- [Github](https://github.com/) - version control
- [Github Pages](https://pages.github.com/) - for deployment of the website
---
## **Testing**
Testing was carried out throughout the build process to ensure site was responsive at relevant breakpoints using [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools).

The below tools were used at various points throughout the build:
- [W3C Markup Validation](https://validator.w3.org/#validate_by_input) - to validate HTML
- [W3C CSS Validation](https://jigsaw.w3.org/css-validator/) - to vaildate CSS Code
- [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln/related) to identify any overflow issues

Manual Testing:
- Navigation links tested to ensure they worked and that they linked to the correct part of the page
- Links to external sites & pages tested to ensure they worked correctly and opened in new tabs.
- Sign Up call to action opened modal and email address was required in order to sign up
- Ran site on Chrome, Mozilla Firefox & Internet Explorer.

---

### **Issues and Resolutions**
The following bugs were identified and rectified during the build process.

- Background images not displaying:
   - File path was incorrect

- Collapse icon on navbar not displaying on mobile screen sizes:    
   - Although the icon was there and clickable the burger icon was not displaying.
   - Resolved by adding the ```navbar-dark```  to the navbar class.

-  When navbar dropdown menu was activated and link clicked, the menu didn't collapse up again:
   - Resolved by adding ```data-toggle="collapse" data-target=".navbar-collapse.show"``` to each list item

- Cards in the Events section pushing down below background image and into  sections below it on mobile screen sizes:
   - Resolved by removing set ```height: 100vh``` on background image

- The Facts section not displaying correctly at tablet screen size:
   - Resolved by changing column width from ```col-md-6``` to ```col-lg-6```

- Images and paragraphs in The Facts section not displaying in the desired order:
   - Resolved by adding Bootstrap **order class** - ```order-lg-2``` & ```order-lg-1``` to affected images and paragraphs
---
## **Deployment**

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/aineon/The-Sustainable-Fashion-Project-Dublin)
1. From the menu items near the top of the page, select **Settings**.
2. Scroll down to the **GitHub Pages** section.
3. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
4. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
5. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.
 

#### **How to run this project locally**

To clone this project from GitHub:

1. Under the repository name, click "Clone or download".
2. In the Clone with HTTPs section, copy the clone URL for the repository. 
3. In your local IDE open Git Bash.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type `git clone` and then paste the URL you copied in Step 3.
```console
git clone https://github.com/aineon/The-Sustainable-Fashion-Project-Dublin.git
```
6. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).

---
## **Credits**

### **Content**
- In **Did You Know?** paragraph:
   - Fast Fashion definition taken form [Good on You](https://goodonyou.eco/what-is-fast-fashion/) website.
   - Ireland facts paragraph taken from [Oxfam Ireland](https://www.oxfamireland.org/blog/impact-fast-fashion-our-climate) website.
   - Global fast fashion facts taken from [7billion for 7seas](https://7billionfor7seas.com/fast-fashion-facts/) website.

- Text in **Vintage** paragraph:
   - taken from [Readers Digest](https://www.readersdigest.co.uk/lifestyle/fashion-beauty/5-reasons-to-shop-vintage) website.

### **Media**
- All images taken from:
   - [Unsplash](https://unsplash.com/)

### **Acknowledgements**
I would like to thank everyone on the code institute slack channels. 

- My mentor 
---
## **Disclaimer**
All images and content on this website is for educational purposes only