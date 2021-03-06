### Phase 3 Team Assignment
In this assignment, each team member will produce one assignment with the following parameters. 
1. Take phase 2 assignment, and apply a CSS3 grid, so that several columns and rows of images now appear. Apply a color to the background
and font to each grid box. 
2. In each box, add two buttons via JQuery or createElement(). One button will read 'make favorite' and the other will read 'unfavorite.'
3. If the 'make favorite' button in any box is clicked, in the grid page, save the image's url or filename to a cookie. Next time the page loads, the 'make favorite' button will disappear for that grid box. A small picture icon will appear in its place, signifying that the image is the favorite. This may require creating divs for each button, and adding/removing the button if the favorite was selected. 
3.5. Sets of icons are available for free with sites like this: https://maxbuttons.com/free-icon-set/
4. When the box with a 'favorite' is clicked, navigate to a detail page. On that page, an icon or small picture will be present, letting the user know that the image is a 'favorite.' 
5. When 'unfavorite' button is clicked, the cookie favorite is deleted, or set to "". 
6. Create a navigation bar at the top of every page, linking to each team mate's production. 
7. Host publicly on Amazon S3. Apply a responsive CSS to each image, per phase 2, when they appear inside of each grid box. 

#### Production notes
1. for your buttons created during the for-loop, use addEventListener, in this example, to add the button to each box, with a prescribed function. In the parameters of the function, you should send in the id of the button (i, in the loop), specifying the name of the image (also [i].jpg). Here is that example: https://www.w3schools.com/jsref/met_element_addeventlistener.asp
2. code the function to receive the name of the image, then save it as a cookie. 
