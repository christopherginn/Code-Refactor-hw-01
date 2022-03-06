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

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

![Screenshot 1](./assets/images/coderefactor_screenshot1.png)

## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.

## License

The last section of a high-quality README file is the license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, refer to [https://choosealicense.com/](https://choosealicense.com/).
