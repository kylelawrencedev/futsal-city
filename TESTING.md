# General (Site Testing of Live site)

### Navbar & Header
* Clicked club logo and confirmed it went back to home back from other pages.
* Clicked hamburger menu button, confirmed dropdown menu appeared showing other pages to navigate to.
* Clicked on links in hamburger dropdown menu and confirmed links went to the correct respective pages. Such as when on home page and clicking on Season 20/21 from the menu that respective page would load with all the relevant content.

### All alt links on live site (External & Internal)
#### External
Clicked all external alt links and confirmed that opened in a new tab in browser
1. Old trafford (Home page)
1. Further information about statement (Home page)
1. All location links for social events (Home page)
1. Next 5 Fixtures Home & Away links, and confirmed all Home fixtures opened to the same location (Season 20/21)
1. Captain and Managers comments link at end of each statement (Season 20/21)
1. Stadium Address and Social media links in footer on all pages 

#### Internal
1. Club logo links back to home page when Clicked
1. Contact Us in footer goes to contact us page
All internal links load the required page without opening a new tab in the browser.

### Body Home Page
* Confirmed that clubs news section is scrollable on smaller screens

### Body Season 20/21 Page
* Confirmed that both Captains Comments and Managers Comments are scrollable on smaller devices.

### Body Contact Page
* Confirmed that when a either "Full Name", "Email" and "Type your message here" are not filled in that an error message shows up for the relevant section of form say, "Please fill in this field"
* Confirmed when submit message button is clicked the page reloads and the fields are left empty again. 

# Responsive Pages
I used Google Chrome Simulator to test the responsiveness of my pages.

All pages needed to be responsive due to the amount of people using their mobile phones as well as laptops and computers. 

Header responsiveness when on mobile the elements in the header shift to the middle of the screen with the logo above the dropdown menu.

For index.html this meant the first element, Next Fixture needed to be responsive as the layout looked horrible when it stayed the same on mobile as when on desktop. When on mobile the text needed to be aligned in the centre as this looked more visually appealing. 

assets/testing-images/index-html-next-fixture-mobile.JPG. 

And then when in desktop view the text would be split into columns. So there would be two pieces of text on each side of the desktop screen. With the text aligned to the left and right respectively.

When on mobile the club news section becomes scroll able if there is a lot of writing. this makes sure all the content fits onto the screen nicely and stops the section from taking up a lot of the screen. 

For the Season 20/21 page the first element is very similar to the first element on the index.html page. And the same needs to happen to this content as did the content in index.html. When on desktop on element will be on the left and one on the right. But when it is on mobile the elements both go to the middle with the text-aligned in the centre. The Last 5 results go on top and the next 5 fixtures go below.

## Responsive Pages Testing
* DevTools - Screen sizes tested widths: Galaxy Fold(280px) | Moto 4G(360px) | Pixel 2(411px) | iPhone 6/7/8(375px) | iPad(768px) | iPad Pro(1024px) | Surface Duo(540px) | And responsive option  | 
* Browsers Used - Opera | Google chrome | Firefox | Safari on iPhone
* Physical Devices tested on : Samsung a70 | Samsung a20e | iPhone 7 | Huawei p20
* [Auto-Fixer](https://autoprefixer.github.io/)

### Moto 4G

Screen size 360 x 640

![moto-4g index.html top](assets/testing-images/moto-g4-360-640-index-top.JPG) ![moto-4g index.html middle](assets/testing-images/moto-g4-360-640-index-middle.JPG) ![moto-4g index.html bottom](assets/testing-images/moto-g4-360-640-index-bottom.JPG)

![moto-4g season.html top](assets/testing-images/moto-g4-360-640-season-top.JPG) ![moto-4g season.html middle 1](assets/testing-images/moto-g4-360-640-season-middle.JPG)

![moto-4g season.html middle 2](assets/testing-images/moto-g4-360-640-season-middle-2.JPG) ![moto-4g season.html bottom](assets/testing-images/moto-g4-360-640-season-bottom.JPG)

![moto-4g contact.html top](assets/testing-images/moto-g4-360-640-contact-top.JPG) ![moto-4g contact.html bottom](assets/testing-images/moto-g4-360-640-contact-bottom.JPG)

### Pixel 2

Screen size 411 x 731

![pixel-2 index.html top](assets/testing-images/pixel-2-411-731-index-top.JPG) ![pixel-2 index.html middle](assets/testing-images/pixel-2-411-731-index-middle.JPG)

![pixel-2 index.html bottom](assets/testing-images/pixel-2-411-731-index-bottom.JPG) ![pixel-2 index.html menu](assets/testing-images/pixel-2-411-731-index-menu.JPG)

![pixel-2 season.html top](assets/testing-images/pixel-2-411-731-season-top.JPG) ![pixel-2 season.html middle 1](assets/testing-images/pixel-2-411-731-season-middle.JPG)

![pixel-2 season.html bottom](assets/testing-images/pixel-2-411-731-season-bottom.JPG) ![pixel-2 season.html menu](assets/testing-images/pixel-2-411-731-season-menu.JPG)

![pixel-2 contact.html top](assets/testing-images/pixel-2-411-731-contact-top.JPG) ![pixel-2 contact.html bottom](assets/testing-images/pixel-2-411-731-contact-bottom.JPG) ![pixel-2 contact.html menu](assets/testing-images/pixel-2-411-731-contact-menu.JPG)

![pixel-2 contact.html name warning](assets/testing-images/pixel-2-411-731-contact-name-warning.JPG) ![pixel-2 contact.html email warning](assets/testing-images/pixel-2-411-731-contact-email-warning.JPG) ![pixel-2 contact.html](assets/testing-images/pixel-2-411-731-contact-text-warning.JPG)

### Samsung Galaxy fold

Screen size 280 x 653

![Galaxy fold unresponsive index.html](assets/testing-images/samsung-fold-280-653-social-events.JPG) ![Galaxy fold responsiveness improved](assets/testing-images/samsung-fold-280-653-social-events-updated.JPG)

Whilst testing the responsiveness of my site i noticed that when the site was on a Galaxy fold the social-events section would push the content down causing two of the divs to stay on the same line whilst the third div went below the other two. The font was also to large and it was not fitting into each div properly.
I changed the width from 29% to 28% as well as changing the sizing of the font to fit look more appealing. Making sure your site looks good on all devices is important and with the chances of foldable phones becoming more popular it is important a site is ready for the potential demand.

# Test Cases

I checked to make sure all links worked and opened onto another page. I was able to see that I had not added the target=_blank to the links for the locations on the index.html page for the social events. The links opened in the same window.

![_blank added](assets/testing-images/index-html-_blank-added.JPG) ![_blank added](assets/testing-images/index-html-_blank-not-open.JPG)

All links for next 5 fixtures on the Season20/21 page open in a new window, and all Home matches go to the same location. All away games go to different locations. The links in the footer all open up in a new window and the stadium address in the footer opens up to the same address as the Home game links. The social-media icons all open to their respective sites in a new window. 

When you go to send a message on the contact page a warning comes up saying that you need to fill-in that specific section of the form.

![Contact Page Warning](assets/testing-images/contact-page-warning.JPG)

Making sure the warning shows is important because if the warning did not show this may lead to visitors becoming annoyed because they might not know what they are doing wrong. 

Another test was to make sure that when the clubs logo is clicked that the visitor is taken back to the home page and when tested on the contact form page I was taken back to the home page.

# Testing Writeup
## Websites used to validate 
### W3C HTML & CSS
[W3C HTML.](https://validator.w3.org/#validate_by_input)

[W3C CSS.](https://jigsaw.w3.org/css-validator/#validate_by_input)

W3C is used to validate HTML and CSS.
Using the W3C CSS validator i was able to find a mistake with my code. There was a warning of ".section-header	Value Error : padding-top Too many values or values are not recognized : 10px 0". I had by accident not changed padding-top to just padding.

![code warning for css](assets/testing-images/code-warning-for-css.JPG)

I then put my html code for each of my pages into the W3C html validator and it came back saying there were no errors for all three pages. This showed me that my code was fine and that my pages had good technical quality for the web. 

# Lighthouse

By getting the best lighthouse score possible will help improve the sites reach ability as the site looks good to the search engine and will be higher up on the search engines search pages.

Whilst I was busy improving the lighthouse score I was also able to improve and test the site. This included testing all the sites links when I was improving the performance and security of the site for the 'a' tags.

By improving the sites accessibility I was also able to improve the code for the headings. The headers had not been put into the proper order as i went from having h1 to h3 heading and after reading the google devs website I found out that this was a typical trait for new programmers. I was then able to properly order the headings and I then styled the headings in style.css and this made improved the code as well as the sites lighthouse performance. 

### Google Lighthouse 

Using Lighthouse from the inspect page and used the Lighthouse option to test my pages and see how they did. I used Lighthouse to test both on mobile and desktop. Google Lighthouse was used on chrome
#### Lighthouse Mobile : index.html

![lighthouse mobile test](assets/testing-images/lighthouse-mobile-test.JPG)

![lighthouse mobile test performance](assets/testing-images/lighthouse-mobile-test-performance.JPG) ![lighthouse mobile accessibility](assets/testing-images/lighthouse-mobile-acces.JPG)

![lighthouse mobile best practice](assets/testing-images/lighthouse-mobile-best-prac.JPG)
 
When using lighthouse i was able to see that my image file sizes were pretty large as I had not compressed their sizes. Using a free image compressor I will be able to make their file sizes smaller, which in turn should improve the performance.

['a' tag performance improvement](https://web.dev/external-anchors-use-rel-noopener/?utm_source=lighthouse&utm_medium=devtools)

[aria-label accessibility improvement](https://web.dev/button-name/?utm_source=lighthouse&utm_medium=devtools)

## 'a' Tag Improvement
![season.html mobile 'a' links](assets/testing-images/season-html-lighthouse-mobile-a-links.JPG) ![season.html mobile 'a' links passed](assets/testing-images/season-html-lighthouse-mobile-a-links-passed.JPG)

![Lighthouse mobile 'a' links](assets/testing-images/lighthouse-mobile-a-links.JPG) ![Lighthouse mobile 'a' links passed](assets/testing-images/lighthouse-mobile-a-links-passed.JPG)
Adding rel-noreffer to the 'a' tags for links help to add to the security of the site. As stated on the google devs website, "When you link to a page on another site using the target="_blank" attribute, you can expose your site to performance and security issues:

'The other page may run on the same process as your page. If the other page is running a lot of JavaScript, your page's performance may suffer.
The other page can access your window object with the window.opener property. This may allow the other page to redirect your page to a malicious URL.
Adding rel="noopener" or rel="noreferrer" to your target="_blank" links avoids these issues." Improving the sites performance and security is always important. And by improving security site visitors will be safer and the site will be less susceptible to malicious redirects when clicked.'

Paraphrased from [Google Webdev](https://web.dev/external-anchors-use-rel-noopener/)
## Site SEO
![index.html mobile seo](assets/testing-images/index-html-lighthouse-mobile-seo.JPG) ![index.html mobile seo passed](assets/testing-images/index-html-lighthouse-mobile-seo-passed.JPG)

![Lighthouse mobile seo](assets/testing-images/lighthouse-mobile-seo.JPG)


By adding a better description to the link text helps the search engine better understand what the link is for. This also improves the appearance of the site for visitors as they know what the link goes to. 

