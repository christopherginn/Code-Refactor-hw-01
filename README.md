# Code-Refactor-hw-01
Code Refactor

## Description

I wanted to make an existing web site for Horiseon more accessible for screen reader technology as well as reduce redundant code for easier modification or editing at a later if needed.

The site originally did not contain any semantic elements or alt text for images. 

To solve this, I added semantic elements to the HTML code to easily create a layout of the page and added alt text to all images. This required some changes to the CSS code to ensure formatting and styling were maintained. When connecting styling to the new semantic tags, I discovered a lot of repeating styles for similar elements. I consolidated these to single elements that were being reused on the page while maintaining the original design of the web site.

One link was broken on the page. This was easily fixed by added the an id attribute to the desired destination. All links work on the index.html page now.

The title for index.html was not specific and vague so I updated it to a theme that more aligns with company and content.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

This web site uses an external CSS file for styling as well as image assets. All must be deployed in order for the content to display correctly on any view port.

All assets have been grouped in one folder for easy deployment along with the index.html. The assets folder contains a folder for the css file and a folder for images.

Place the index.html file and assets folder in the same repository on Github for easy deployment.

While in the repository, select Settings and then select Pages that appears on the left side. 

On the Github pages screen, select the Branch drop down menu under the Source section and select 'main.' Then click Save. A URL with appear where the site has been published.

## Usage

The site has minimal function and is more desgined to be informative. That being siad, the funciton it does have is that you can use links to navigate to sections of the page. Below are the links circled in red.

![Screenshot 1](./assets/images/coderefactor_screenshot1.png)

When you click on one of the links circled in red, the ppage will jump to the section containing that ID associated with the link. The screenshot below is after the user has selected the Online Reputation Management link at the top of the page.

![Screenshot 2](./assets/images/coderefactor_screenshot2.png)

As indicated by my markup of the screenshot, the user was easily navigated to the section corresponding to the link for easy page navigation.

## Credits
All image assets were provided by Horiseon/GT Bootcamp and none were added.

All source code was provided by GT Bootcamp and modified by Chris Ginn.

To learn how to add alt text to an image defined in CSS, I discovered this solution on stackoverlow.com that goes over the aria-label and establishing the role for divs.

https://stackoverflow.com/questions/4216035/css-background-image-alt-attribute

## License

[GNU General Public License v3.0](/COPYING.txt)

