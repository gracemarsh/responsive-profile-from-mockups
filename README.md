# profile
[Techdegree Project 2 - Responsive Profile from Mockups on github pages](https://gracemarsh.github.io/responsive-profile-from-mockups/)

Beginning with three mockup images for a responsive website for mobile, tablet and desktop, I began by creating a file system and copying the content and layout from the mobile mockup image to the index.html file. I also linked a normalize file to rest from any user default designs. https://cdnjs.com/libraries/normalize 
Next, I tried to choose a matching font on google fonts and linked it to the index.html file and css stylesheet. 
I then began using the stylesheet to imitate the mockup as closely as possible. 

The typography was difficult to match and I found https://css-tricks.com/almanac/properties/f/font-size/ useful in using absolute keywords and values. 
To find the same colours as the mockup I used "digital colour meter".

One difficulty I found was the padding from the "user agent stylesheet" that I thought normalize would have reset but didn't. I had to debug the problem and set padding: 0; in the header and footer. I also found it difficult copying the header buttons design. I then found that it worked creating a grey background for header, and then grey borders around the white buttons.

I needed any easier way to compare my document with the mockup image instead of switching between the live preview mode in Visual Studio Code, the document view on browser, and the image mock-up. So, I created mockup.html and made the mockup image the background so that I could easily compare my live code on the browser with the mockup.html on the other tab. In the inspect mode I used the Toggle Device Toolbar set to "Responsive" at the same specs as the mockup image 320x1249 px so that the comparison was more accurate. 

To make "Student name" on the left and "BACK TO TOP" on the right of the footer I used the float property.

This more accurate comparison revealed many differences in the typography and font sizing which had to be addressed. This made me change my mind about using the absolute keywords and valuces and I converted all the font-size values to the px unit to more accurately mimic the mock-up.

Problem: line above ".below-footer" don't know how to stop it short and keep in line with left-nav and right-nav (deleted padding, added margin to left and right)

After I was happy with my mobile design I then added media queries for table & desktop size then changed the mockup.html to the respective images to create new rules for these sizes. 
In the browser using chrome dev tools I then changed the responsive to the right px.

Used flexbox to adjust the page layout.
