# PWA Text Editor <!-- omit from toc -->
by Sheila Hanson ![Github license](https://img.shields.io/badge/license-MIT-blue.svg)  
![alt text](Develop/client/src/images/logo.png)
## Description <!-- omit from toc -->
  This is a text editor app that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

## Table of Contents <!-- omit from toc -->
  
- [Installation](#installation)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
- [Usage](#usage)
  - [Testing](#testing)
- [Challenges](#challenges)
- [Contributing](#contributing)
- [Questions](#questions)
- [License](#license)
- [Badges of Technologies Used](#badges-of-technologies-used)
    

## Installation
- Clone the repository to get your starter code  
- Install the source code  
- npm install  
- npm start  
- Navigate to localhost:3001  
- Click the install button  
  
### User Story  
*  AS A developer  
  
    I WANT to create notes or code snippets with or without an internet connection  
    SO THAT I can reliably retrieve them for later use     
### Acceptance Criteria
* GIVEN a text editor web application  
  
    WHEN I open my application in my editor  
    THEN I should see a client server folder structure  

    WHEN I run `npm run start` from the root directory  
    THEN I find that my application should start up the backend and serve the client  

    WHEN I run the text editor application from my terminal  
    THEN I find that my JavaScript files have been bundled using webpack  
    
    WHEN I run my webpack plugins  
    THEN I find that I have a generated HTML file, service worker, and a manifest file  

    WHEN I use next-gen JavaScript in my application  
    THEN I find that the text editor still functions in the browser without errors  

    WHEN I open the text editor  
    THEN I find that IndexedDB has immediately created a database storage  

    WHEN I enter content and subsequently click off of the DOM window  
    THEN I find that the content in the text editor has been saved with IndexedDB  

    WHEN I reopen the text editor after closing it  
    THEN I find that the content in the text editor has been retrieved from our IndexedDB  

    WHEN I click on the Install button  
    THEN I download my web application as an icon on my desktop  

    WHEN I load my web application  
    THEN I should have a registered service worker using workbox  

    WHEN I register a service worker  
    THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets  

    WHEN I deploy to Render  
    THEN I should have proper build scripts for a webpack application  

      
## Usage  
  - Once you have installed and run through local host, it is as easy as entering the text you would like. It will be saved locally by IndexedDB.  

  ** ADD IMAGE
  
### Testing  
- Since a large portion of the code was provided, testing was done through localhost through the src-sw.js and webpack.config.js files.

## Challenges  
 


## Contributing
[NPM](https://docs.npmjs.com/cli/v9/commands/npm-install)  
[Inquirer](https://www.npmjs.com/package/inquirer/v/8.2.4)  
[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web)    
[Stack Overflow](https://stackoverflow.com/?newreg=67d94556b887449fa2885dadf54a5439)   
[W3school](https://www.w3schools.com/)   
[Shields](https://shields.io/)    
[YouTube](https://youtube.com)  
[Coding Bootcamp](https://coding-boot-camp.github.io/full-stack/render/render-deployment-guide)  
[Webpack](https://webpack.js.org/guides/asset-management/)  
[Render](https://render.com/)  

## Questions
![Ask me anything](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)
If you have any questions, or additional feedback, please feel free to email me and I will respond as soon as possible.
    
* Github -
[pwa-text-editor](https://github.com/Sheila-Ha/pwa-text-editor)

* [Deployed to Render](ADD_LINK_HERE)

* Email -
slhanson11@live.com

## License 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



## Badges of Technologies Used
![MDN Web Docs](https://img.shields.io/badge/MDN_Web_Docs-black?style=for-the-badge&logo=mdnwebdocs&logoColor=white)  ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)  ![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)  
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)  ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)   
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)  ![W3schools](https://img.shields.io/badge/W3Schools-04AA6D?style=for-the-badge&logo=W3Schools&logoColor=white) ![JSON](https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=red)  ![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=white)  
![Prettier](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E) ![Zoom](https://img.shields.io/badge/Zoom-2D8CFF?style=for-the-badge&logo=zoom&logoColor=white) ![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)  ![Google Chrome](https://img.shields.io/badge/Google_chrome-4285F4?style=for-the-badge&logo=Google-chrome&logoColor=white)  
![Stack Overflow](https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)  ![Lenovo](https://img.shields.io/badge/lenovo%20laptop-E2231A?style=for-the-badge&logo=lenovo&logoColor=white)  ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?logo=express&logoColor=%2361DAFB)

