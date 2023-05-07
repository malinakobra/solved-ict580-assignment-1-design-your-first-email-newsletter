Download Link: https://assignmentchef.com/product/solved-ict580-assignment-1-design-your-first-email-newsletter
<br>
<strong>  </strong>Assignment 1

<strong>  </strong>A local restaurant asked you to design an email newsletter. The newsletter should include the restaurant logo, links to the restaurant website, a poster with coupons attached to the end of it. However, the owner wants the same page design as below:

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/831.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/831.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/653.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/653.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Now, it is your turn to code the newsletter and achieved a similar result to the suggested design. Anyway, there are steps to follow when coding someone design. In this assignment, you will practice that and learn how to identify layout, and what type of HTML tags and CSS properties to use. Also, those steps can be used in the course term project; you only need to set your design, and then use similar steps to finish your term project. For now, start working in the “<strong>Instructions</strong>” section.

Page  of 6

&#x25fc; <strong>Instructions </strong>o <strong>Step one:</strong><strong> Set up a project folder: </strong>

The restaurant owner provided you with images and logo (All images can be found on the assignment1_res folder. Download it from D2L under Content → Assignment 1.), and you need to include them on the final project. So, it is a good idea to create a folder for this project. The HTML document “.html” should be in the root folder (the main project folder). For extra resources such as images, create a subfolder called “images”, and for the style sheet files called it “CSS” or “styleSheet”. By now, your final project folder tree should look like this:

–             newsLetter_project (root/main folder)

images (subfolder) o    css (subfolder)

<ul>

 <li><strong>Step two:</strong><strong> create a page layout using HTML: </strong></li>

</ul>

Now, you need to figure out how to structure the HTML page layout. Build the layout based on the  design provided to you. Best way to start a layout is:

<ul>

 <li>First, write the main tags (see the main.html file). Also separate your code using comments when creating a section, block or item/elements (e.g. a start of header section or here article with image item/element).</li>

 <li>Second, work in each section or item/element (header, navigation menu, footer). Look closely at each element structure. For example, the footer has two elements (two coupons), and each element has content with different style, e.g. the “save 50%” element and the “* valid until 15/10/2018” element have different font sizes. To structure that I would use separate tags, so I can have more control over elements and be able to change the font size for each element.</li>

</ul>

After finishing this step, you should have this result:

<ul>

 <li><strong>Step three: style and format the HTML layout</strong><strong>: </strong></li>

</ul>

Now, you need to use CSS to style your HTML layout. Create a new style sheet file “.css” and you can name it “main.css”. To start styling an HTML layout, I would consider first the position and size of every item for example in the middle section, you can see an image at the bottomright corner, so I would use CSS property such as position and set right, bottom values to 0xp. After you get every item in its right position, start working on fonts, color, border …etc.

<em><u>Use these detailed for styling:</u></em> o Document width is 580px. o Left padding or margin should be between 15px to 20px.

<ul>

 <li>Header section background color is #FFDF6B o All sections text Color is #333 o Body section background color is #ffcc11 o Font family type: <strong>“Shadows Into Light</strong>” <a href="https://fonts.google.com/specimen/Shadows+Into+Light">(</a><u><a href="https://fonts.google.com/specimen/Shadows+Into+Light">link</a></u><a href="https://fonts.google.com/specimen/Shadows+Into+Light">)</a> and here how you can attach to your code. In the head tag add this code:</li>

</ul>

<em>&lt;link href=”https://fonts.googleapis.com/css?family=Shadows+Into+Light” rel=”stylesheet”&gt; </em>then attach it to any CSS as follows: <em>font-family: ‘Shadows Into Light’, cursive;</em>

<table width="0">

 <tbody>

  <tr>

   <td width="75">Content</td>

   <td width="199">logo.png</td>

  </tr>

  <tr>

   <td width="75">Style</td>

   <td width="199">You do not need to style it &#x1f642;</td>

  </tr>

 </tbody>

</table>

<table width="0">

 <tbody>

  <tr>

   <td width="75">Content</td>

   <td width="199">Menu, About us, order now!</td>

  </tr>

  <tr>

   <td width="75">Style</td>

   <td width="199">–  Font size is 12px–  Font style is bold–  Border size is 3px</td>

  </tr>

  <tr>

   <td width="75"> </td>

   <td width="199"> </td>

  </tr>

  <tr>

   <td width="75">Content</td>

   <td width="199">&amp;#9832; HOT Tacos, burritos &amp; quesadillas</td>

  </tr>

  <tr>

   <td width="75">Style</td>

   <td width="199">– Font size is 70px</td>

  </tr>

 </tbody>

</table>

<table width="0">

 <tbody>

  <tr>

   <td width="75">Content</td>

   <td width="199">plate.jpg</td>

  </tr>

  <tr>

   <td width="75">Style</td>

   <td width="199">–  image width is 300px–  image height is 229px</td>

  </tr>

 </tbody>

</table>

<table width="0">

 <tbody>

  <tr>

   <td width="75">Content</td>

   <td width="246">&amp;#9873; Lorem’s Tacos &amp;#9751; 13106 Lorem Ave.Lorem CA 2R3 E3B&amp;#9742; 403-123-4567</td>

  </tr>

  <tr>

   <td width="75">Style</td>

   <td width="246">–  Font size is 20px–  Font color is #333</td>

  </tr>

 </tbody>

</table>

<table width="0">

 <tbody>

  <tr>

   <td width="75">Content</td>

   <td width="199">Save 50% or 75%</td>

  </tr>

  <tr>

   <td width="75">Style</td>

   <td width="199">–  Font size is 60px–  Width is 50%</td>

  </tr>

  <tr>

   <td width="75">Content</td>

   <td width="199">*valid until 15/10/2018</td>

  </tr>

  <tr>

   <td width="75">Style</td>

   <td width="199">–  Font size is 10px–  Width is 75%</td>

  </tr>

  <tr>

   <td width="75">General Style</td>

   <td width="199">–  Border size is 3px–  Border style is dashed</td>

  </tr>

 </tbody>

</table>




At the end of this step, you should see a similar result to the below image:

<ul>

 <li><strong>Step four: check code errors</strong><strong>: </strong></li>

</ul>

Now, you need to check errors on your code.

<ul>

 <li>First, check syntax errors, if there is any, fix them.</li>

 <li>Second, look if you have achieved the same result/output of this project, if not. Identify where is the problem for example, if the layout is not on the same order as required, check your HTML code first, then check your CSS code especially the position and display properties.</li>

 <li>If you have tried everything and still not getting a good result, please feel free to <u>email</u> me, and I will be happy to help . o <strong>Step Five: Wrap up your project</strong><strong>: </strong></li>

</ul>

Now, check all project folders and files, make sure they all open fine. Next, zip your main/root folder and only send that zip folder. Here are some links that may help with file formatting:

<ul>

 <li>How to zip a file in Windows 10: <u><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">https://www.laptopmag.com/articles/how</a><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">–</a><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">to</a><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">–</a><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">zip</a><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">–</a><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">files</a><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">–</a><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">windows</a><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">–</a><a href="https://www.laptopmag.com/articles/how-to-zip-files-windows-10">10</a></u></li>

 <li>Free file compressor application for Windows: <u><a href="https://www.7-zip.org/download.html">http://www.7</a><a href="https://www.7-zip.org/download.html">–</a><a href="https://www.7-zip.org/download.html">org/download.html</a></u></li>

 <li>How to zip a file in Mac: <u><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">https://www.lifewire.com/how</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">–</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">to</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">–</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">zip</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">–</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">and</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">–</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">unzip</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">–</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">files</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">–</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">and</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">–</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">folders</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">–</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">on</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">–</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">a</a></u><u><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">mac</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">–</a><a href="https://www.lifewire.com/how-to-zip-and-unzip-files-and-folders-on-a-mac-2260188">2260188</a></u></li>

 <li>Free file compressor application for Mac: <u><a href="https://theunarchiver.com/">https://theunarchiver.com/</a></u></li>

 <li>How to save a pdf in MS Word document: <u><a href="https://www.bettercloud.com/monitor/the-academy/save-word-doc-pdf/">https://www.bettercloud.com/monitor/the</a></u><u><a href="https://www.bettercloud.com/monitor/the-academy/save-word-doc-pdf/">academy/save</a><a href="https://www.bettercloud.com/monitor/the-academy/save-word-doc-pdf/">–</a><a href="https://www.bettercloud.com/monitor/the-academy/save-word-doc-pdf/">word</a><a href="https://www.bettercloud.com/monitor/the-academy/save-word-doc-pdf/">–</a><a href="https://www.bettercloud.com/monitor/the-academy/save-word-doc-pdf/">doc</a><a href="https://www.bettercloud.com/monitor/the-academy/save-word-doc-pdf/">–</a><a href="https://www.bettercloud.com/monitor/the-academy/save-word-doc-pdf/">pdf/</a></u></li>

</ul>

<strong>Please refer to the rubric at the end of this document for evaluation details. </strong>

&#x25fc; Tips: tags and CSS properties you may need to use. Feel free to use any tag that is not listed below:

<table width="0">

 <tbody>

  <tr>

   <td width="103"><strong>Tags </strong></td>

   <td width="94">Tag</td>

   <td rowspan="2" width="45">  </td>

   <td width="123"><strong>CSS </strong></td>

   <td width="159"><strong>CSS </strong></td>

   <td width="157"><strong> </strong></td>

  </tr>

  <tr>

   <td width="103">–                      meta–                      title–                      link–                      img–                      nav–                      h1–                      span –             p </td>

   <td width="94">–          a–          article–          br–          section–          div–          time</td>

   <td width="123">–          font-family–          width–          padding–          color–          text-align–          font-size–          margin-top–          font-family </td>

   <td width="159">–                      background-color–                      overflow–                      position–                      text-align–                      font-size–                      line-height–                      font-height –             border </td>

   <td width="157">–          margin–          vertical-align–          bottom–          right–          left–          top</td>

  </tr>

 </tbody>

</table>





