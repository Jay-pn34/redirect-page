Jay Patel's Interactive Portal

Overview

Jay Patel's Interactive Portal is a modern, dark-themed web page that provides quick access to various Term Work Generators and the GitHub Page. It features an elegant UI with smooth animations, making navigation seamless and visually appealing.

Features

Dark Mode Design: A sleek and modern interface with a dark theme.

Smooth Animations: Buttons and text elements fade in for a polished experience.

Quick Access Links: Direct buttons to Term Work Generators (1, 2, and 3) and GitHub.

Easy Link Management: All links are stored in a JavaScript object, making updates simple.

Responsive UI: Works on both desktop and mobile devices.

Technologies Used

HTML5: Structure and content

CSS3: Styling and animations

JavaScript: Dynamic link handling and interactivity

How to Update Links

If you need to update the links for any of the Term Work Generators or the GitHub page, simply modify the links object inside the <script> tag in the HTML file:

const links = {
  github: "NEW_GITHUB_LINK",
  generator1: "NEW_GENERATOR1_LINK",
  generator2: "NEW_GENERATOR2_LINK",
  generator3: "NEW_GENERATOR3_LINK"
};

Replace NEW_GITHUB_LINK, NEW_GENERATOR1_LINK, etc., with the updated URLs.

How to Use

Open the index.html file in a browser.

Click on the desired button to be redirected to the respective Term Work Generator or GitHub page.

Contribution

Contributions are welcome! If you’d like to improve the portal, feel free to fork the repository and submit a pull request.
