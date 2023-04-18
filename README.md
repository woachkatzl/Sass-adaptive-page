# Sass-adaptive-page
## Creating an adaptive landing page using SASS pre-processor.
### Description
This is a learning project where I developed a web page based on a Figma template.

My primary focus was on learning to use Sass preprocessor for writing my styles. In particular, the use of `@use` and `@forward` function instead of the `@import` due to its upcoming deprecation. Using Sass allows to quickly and easily modify styles like fonts and colors across the entire project. It also simplifies navigation across the parts of the project.

My other learning focus was on the use of media queries for ensuring an adaptive and responsive behaviour of the page. I developed it using the "mobile first" principle. Creating this page I also deployed a lot of absolute and relative positioning, as well as used CSS grid and Flexbox techniques.

I used [this Figma template](https://buildhtml.ru/template/342) to develop this page.
### Installation
To run and edit this code on your local computer you can take the following steps:
1. Fork this repository by clicking the "Fork" button (it should be located in the top-right corner of the page)
2. Open the forked repository in your GitHub account
3. Click on the "Code" button (it should be green and located towards the top-right of the page) and copy the URL of the repository.
4. Open up your terminal or command prompt and navigate to the directory where you want to clone the repository.
5. Clone the repository to your local computer by running the `git clone` command:
```
git clone https://github.com/username/repository.git
```
6. Once the repository is cloned, navigate into the repository directory (the target folder should take the name of the cloned repository)
7. Install the project dependencies using npm:
```
npm install
```
8. Run the project using the following command:
```
npm start
```
### Usage
To use and navigate the page created in this project follow [this link](https://woachkatzl.github.io/Sass-adaptive-page/)
- Changing the size of your browser window will change the size and placement of the page elements to maintain readable and appealing layout.
- The page has four primary screen size options: mobile, tablet, desktop, and wide-screen desktop.
- The buttons will change appearance when hovered over
- The input fields will be highlighted in green when active
- The phone link in the header will become underlined when hovered over
- The social media links in form of icons will change colors when hovered over
- The links in the footer will become highlighted and circled when hovered over
- Pressing the "Submit" ("Отправить") button in forms will prompt an e-mail application to open with pre-filled infomration from the form and the destination e-mail address
### Credits
When learning to work with Sass I found the following YouTube tutorials helpful:
- [Learn Sass In 20 Minutes](https://www.youtube.com/watch?v=Zz6eOVaaelI)
- [Stop using @import with Sass | @use and @forward explained](https://www.youtube.com/watch?v=CR-a8upNjJ0)
### Further development
This project is not complete. I intend to later develop an interractive burger menu using JavaScript and to style the checkboxes to reflect the template design.