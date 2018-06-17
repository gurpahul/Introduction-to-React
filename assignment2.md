## Assignment #2

This assignment accounts for 20% of your final grade

You should submit an archive (`.zip` file) for this assignment. This archive should contain all the necessary HTML, CSS and JS required to sucessfully run the app. Do not include the `node_modules` directory along with your assignment.

The `.zip` file should contain your first and last name.

Your `.zip` file containing your solution files should be uploaded to the [Assignment #2 Dropbox link](https://www.dropbox.com/request/xW5wWzh8bw602zzsO32h), no later than 8:45 AM, Wednesday, June 20th, 2018.

You can NOT submit more than zip 1 file. 

See [Assignment #2 rubric](https://github.com/jniziol/Introduction-to-React/blob/master/Assignment%20%232%20-%20Rubric.pdf) for the evaluation criteria.

## Picture Search

Using the Unsplash API and React, you will write an application that allows users to search the unsplash API for photos and display the results.

### Requirements

- To search photos from Unsplash, you'll need to use this [endpoint](https://unsplash.com/documentation#search-photos
)
- Users can type their search query into a input box
- Users can select from a drop-down, how many photos they would like displayed on the page (5,10 or 15)
- Users can select what type of orientation of photo they would like (landscape, portrait, and squarish or all [`all` is actually default, so consider this when your writing your app])
- Once a user hits search, the app will query the unsplash API and return photos that match the search criteria.
- When your app loads up, it will grab and display a random photo as a small avatar in the top left corner of your app. It should use this [endpoint](https://unsplash.com/documentation#get-a-random-photo)
- After searching, your app should display a message above the images - "Your search for `the users search query here` returned XX results."

