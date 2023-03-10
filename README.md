# <Refactored-Code-for-Accessibility>

## Description
For this project, I restructured the code for a marketing agency's site to make it more accessible to users. Not only does making a site more accessible improve the user's experience, but it also makes it usable for those who are visually impaired, so that they can benefit from the site's information, and optimize the site for search engine results.

Prior to the restructure, the site's code relied heavily on div tags which, although useful, do not provide any explanation to the content within them. As a result, div tags make it difficult for search engines and assistive technologies to understand the structure of the content, which is especially frustrating for those individuals who rely on this technology. In place of div tags I added semantic HTML elements, such as header, section main, aside, and footer, to better explain the page content and make it easier to interpret.

In addition to incorporating HTML semantic elements, I also added alt text to images making them accessible to the visually impaired. The reference to the background image of the marketing meeting was also included in the style guide, which I pulled into the HTML so that an alt text could be added. In addition to alt attributes, I restructured the order of the header attributes so that they were in an order that made sense for the content. Prior to the code restructure, there was a reference to a second header id element in the footer, after a third header had already been introduced. To make the headers chronical, I removed the second header id and instead added a fourth header attribute.

So that this code can be easily maintained and updated in the future, I add commentary to both the style guide and HTML code. Originally, I included more commentary than necessary, but cleaned it up so that I was not duplicating the code and based on <a href="https://stackoverflow.blog/2021/12/23/best-practices-for-writing-code-comments/">Stack Overflow's Best practices for writing code comments<a>.

Lastly, I changed the generic website title to one that accurately depicted the site's content. I hope to reference this code in the future to make sites more accessible and information available.

## Screenshots
Here are screenshots of the Marketing Agency's site with the refactored code:

![Refactored site,top](/Develop/assets/images/horiseon-refactored-site-top.png)
![Refactored site, middle](/Develop/assets/images/horiseon-refactored-site-middle.png)
![Refactored site,bottom](/Develop/assets/images/horiseon-refactored-site-bottom.png)

## Credits
The starter code that I restructured for this accessibility project came from <a href="https://github.com/coding-boot-camp/urban-octo-telegram">Xandromus</a>. You can access my accessibility-site-refactor repository with this refactored code <a href="https://github.com/MCunha17/accessibility-site-refactor.git">here</a>.

