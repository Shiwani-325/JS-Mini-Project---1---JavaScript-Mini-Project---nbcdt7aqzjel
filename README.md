# html-css-js-project-boilerplate
First step in the website will be making a nav bar using flex. Inside the nav you will have a div with classname logo and a list for displaying the respective links as in the mock UI. Use flexbox in nav to display the logo and list of links on the opposite side of the screen and also use flexbox in the list inside the nav also, to evenly space the links.

Give nav a padding of 12px 16px. All the text on nav should have white for font color, so apply the property on nav itself.

You will be using the API functions in api.js file to fetch the relevant data. When page loads,make a request to get list of all image using fetch function.

This will return array of objects each having name and thumbnail URL. While you are fetching this data, we cannot show user a black screen, so instead we will show a loader element with id="loader", it could contain text "Loading..." or an animation, its up to you, but should have the id="loader".

After the data is finished loading, i.e request has finsihed, remove the loader from screen(dont hide it, remove it). Inside the main component, add  div inside it.

Inside that div we will be adding the individual movie components. Each individual movie component will be made up of an anchor tag on the outside with class Example of the basic strucutre is given below. Replace moviename by actual name of the rendered movie <a class="image-link" href="/imagename"> <div class="image" data-id="imagename"> <div class="image-img-wrapper"> </div> <h4>$moviename</h4> </div> </a> img-wrapper will have css, background image property set to the imgUrl of the movie and background size as cover.

index.html has markup defined for #booker class, which will hold elements related to seat booking. Upon clicking the imge-link, the app loads data from the fetchimageAvailability using imagename as parameter.

After data has been loaded h3 inside #booker should be visible by toggling the pre defined class v-none. Also two 4x3 grids should be displayed.Each box is numbered and equivalent of a seat.Seat will be numbered from 1-12 on left box and 13-24 on the right hand side box.


Clicking on "git" div adds a classname "selected-git" which should have these css styles "border:4px outset rgb(0, 0, 0)". You can select multiple seats.

