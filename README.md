# Functional documentation

Instructions of how to create the documentation using writerside

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)



## Installation

Visit the writerside dowload page <a href="https://www.jetbrains.com/writerside/" target="_blank">here.</a>
</br>
Folow the instructions and open the app when installed.
</br> click on the top left on the following button and navigate to the git tab. Here you click on clone.
</br> It will ask for the link to the repository you fill in the clone link of this repository and it will clone it for you.
</br>
![burger menu](/Writerside/images/burgermenu.png)
</br>
![git hover](/Writerside/images/githover.png)


## Usage

Create a new branch, this can be done at the same place where you selected clone. Name the branch using the convention used with the playwright project (feature/BT-..)
</br> Create a new .md file using the name specified in your ticket, and start writing in MarkDown.
</br> Use at the top of the page "#(name of the covered feature)" and add the intertitles using ###.
</br></br>
To add a screenshot folow the folwong steps
 - Open the developer tools on the buildbase page, this way you can make the page smaller by setting the dimensions on responsive
 - take a screenshot of the screen you see
 - add it onto canva or any other photo editor
 - add a click cursor where you click to get onto the next screen

   Try to add multiple screens next to each other if you show the steps for a function, the dimensions used for this is 1900px x 800px
   </br> add the image in the images folder of the project and give it an explaining name
   </br> to add an image use `"![alt text](filename)"`

   </br></br> To host it on local host to see the preview of your changes follow the following steps
   - press at the top right on the button Writerside preview (see picture1)
   - This shows a preview in the app, this didn't refresh at my pc so I pressed "Open in browser" (see picture2) this runs it on localhost and refreshes automatically when you change something.
   - </br>
    ![Writeside preview](/Writerside/images/preview.png)
    ![Open in browser](/Writerside/images/browser.png)


## Contribution
You can push your branch using the same menu where you cloned and created your branch, than you can create a pull request at the repository.
