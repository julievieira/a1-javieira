Readme
---

Julie Vieira
http://a1-javieira.glitch.me

This project contains a variety of achievements described in the Technical and Design sections. I started by satisfying the requirements as detailed in Step 2 of this assignment and added additional sections in order to explore additional features. The “Non Major Related Projects” section was added so I could learn how to use a link tag, which is connected to OER Commons. In order to list the CS courses I have taken I included a table, another kind of semantic HTML tag. I had to figure out how to structure the table as the row labels are added into HTML the same as cells, just the tag changes from <td> to <th> for the first entry. Additionally, tables do not initially include lines so I manipulated this in the CSS file. Further, I went to Adobe’s website and created a color palette with 5 colors as shown below. The lilac color is used in the gradient as well as the text color. The deep blue is used as the background for the headers. The light blue was used as a transition color between the lilac and seafoam gradient in the background as well as in the gradient from grey to light blue in the animation at the bottom of the page. The grey color was used in the gradient for the animation background and a deeper shade was used for the main text color. Finally, the seafoam color was utilized as the gradient color at the bottom of the page and the color of the blocks in the animation. The animation itself was challenging in the beginning to not only figure out how to make the figure move back and forth as I intended, but how to move it at all. I discovered through research that using the setInterval function we learned in class in combination with incrementing the horizontal and vertical positions at a small enough interval would make it appear as a smooth movement. I started with one block moving across the container, determined I needed a flag variable to change its direction, and applied this logic to the other seven blocks. Each block was unique in its initial positioning and directional movement. Next, I styled the page using CSS rules. I created a rule for the background which created the gradient from lilac to light blue to seafoam. I manipulated the “Information About” label so it now includes a border, the text uses one of the colors from the Adobe palette, a background image was collected by using a url, the text has padding around the edge, and a shadow was included so the text wouldn’t get lost in the image. The h2 rule was similar in that it created a uniform background, text color, and font for the main labels such as “Introduction”. The paragraph has an altered opacity so it is slightly different from the bullet points below it as the paragraph falls on the lilac background and the bullet points stand against a blue background more so. The li rule was used to get rid of the given bullet points and li::before used the unicode for a curled arrow instead. The table rule collapsed the borders so that there would not be duplicates within the cells and on the outside walls. Information was a class I created which contained the bullet points and main headers so there would be a uniform font color, size, and type across the page. I accomplished this using the <div> tag. Finally, I used multiple different fonts from Google in the title, headings, and bullet points.

## Technical Achievements
- **Styled page with CSS**: Added rules for the body, h1/h2, p, li/li::before, table, information as described above
- **JavaScript Animation**: Animation at the bottom of the screen has 8 blocks in a container, 4 of which move diagonally and 4 of which move up and down, in a repetitive manner starting at window onload
- **Semantic HTML Tags**: links and table as stated above
  
### Design Achievements
- **Adobe Color Palette**: I used a color palette with 5 colors (lilac: #CCBEF2; deepBlue: #5D5CFA; grey: #A6B5E3; lightBlue: #AAD2FA; seafoam: #A3DDF0;) throughout this project. Here is the link to the color palette image which is uploaded in the Assets in Glitch: https://cdn.glitch.global/f21d831e-e18d-406f-adc7-76a5c5f58301/Color%20Wheel%20Blues.jpg?v=1693473341934
- **Google Font**: I used 3 Google Fonts in the title (Vollkorn), headers (Cinzel), and bullet points/general text (Stoke)
  