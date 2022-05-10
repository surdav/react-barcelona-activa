# react-it-academy
Curso d'autoformació de l'IT Academy: React

Sprint 1. Layout I
Web layout involves transforming the design of a website into a set of HTML and CSS files, so that web browsers can interpret and reproduce them correctly on different devices.
In this sprint you will learn the basics of HTML5 and CSS3 by visualizing practical examples of what a website is like. Also, you will discover those main mechanics most used by the layout designers themselves who are in charge of professionals designing a website in functional places.

Description
In this practice you will need to make a layout that should work on both desktop and mobile and tablet.


Please note the following considerations. These are common errors in deliveries:

In general, we never set the height of a layer, but let the layer fit its content (if the layer has no content, you can set a height).
The page should not have a horizontal scroll bar (if this happens to you, you should find out by inspecting the page that the blog is wider than the browser screen).
Within a div there are usually other divs. Divs have display: block by default. This causes them to be placed vertically. Therefore, it is often not necessary to specify the following styles for an item to be redundant:
.element {display: flex; flex direction: column}
On a div, the default width is for the entire wrapper layer, so you won't normally need to specify width: 100%

Delivered by GitHub

- Create a single GitHub repository for all three levels, you can separate them into folders.
For example: level-1, level-2 and level-3.

- In the first two sprints you will need to upload the code to GitHub so that your mentor can see it.
From sprint 3 you will have to deliver it by pull request, the way in which programmers deliver their work in companies.

- If you are not sure how to upload your project to git, at the end of this statement there is an "Appendix I: Upload your code to git" which contains the steps you need to follow.


Level 1
- Exercises 1
From the wireframe that we provide you in png format, you will have to make the layout in desktop format. The colors chosen are indifferent, but it is very important that you make the box structure that we indicate to you.

The maximum width of the layer that will contain all the layout will be 1200px (max-width: 1200px).

Screenshot of the wireframe desktop version

- Exercises 2
We will have to start preparing to adapt to different devices, so we need to be clear about the concept of Media Query. Note that there is a change in the layout and color of some items.

Continuing with the previous project, make the tablet version as shown in the following screenshot:

Screenshot of the tablet version wireframe

- Exercises 3
As in the previous case, you will now need to adapt to the Mobile version.



Level 2

Please note that before moving on to Level 2, check that you have understood all the exercises in Level 1 correctly.

Level 2 and 3 are optional, the important thing is to learn the concepts of each sprint, if you have copied it quickly from the internet it has no value, because if you pass all the sprints like this, you will have worked hard and learned little.

These cases are detected very quickly in a technical interview with a company or in the route level tests (after sprint 5 and 9). Do not delay your learning, it is better to do few exercises well than many fast ones.



Reference for exercises 4 and 5

Below is a sample of what the final layout of the page would look like.


- Exercises 4
In this part we want to work on the header and graphics. You will need to add icons and a logo as well as a background image. Replace the respective quadrants so that the new header looks like this tourism website in Japan:



It is important to consider the following:

Clickable options must have a roll-over effect.
Media queries created in the previous activity must be maintained.
The text "Enjoy ..." is semi-transparent.
The logo and the bottom of the header are attached to the activity. You will need to find the rest of the graphics and make them as similar as possible.
You can get the menu icons from font-awesome.

- Exercises 5
In this exercise you will have to add the section of the articles following this graphic:



Level 3
- Exercises 6
Congratulations! you have created a complete website, but as you can see, it is very static. To enhance the user experience, apply an animation using keyframes to the main elements of the web, title and logo.



- Exercises 7
Do you see yourself able to do the same job but with a grid layout? So the goal of this work is to use the grid layout properties to make the whole structure of the web and its different devices (always with Media Query).

If you want, you can consult the optional grid layout material on campus



