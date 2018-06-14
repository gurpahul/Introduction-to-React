## Assignment #1

This assignment accounts for 20% of your final grade

You should submit an archive (`.zip` file) for this assignment. This archive should contain all the necessary HTML, CSS and JS required to sucessfully run the app.

The `.zip` file should contain your first and last name.

Your `.zip` file containing your solution files should be uploaded to the [Assignment #1 Dropbox link](https://www.dropbox.com/request/wVyMJoEPGdXYiGgVXGfi), no later than 10:15 AM, Friday, June 15th, 2018.

You can NOT submit more than zip 1 file. 

See [Assignment #1 rubric](https://github.com/jniziol/Introduction-to-React/blob/master/Assignment%20%231%20-%20Rubric.pdf) for the evaluation criteria.

## Shopping Cart

### Items

- Your app should have a variety of items (at least 4) that a user can add to their shopping cart.

- Each item should have a price, a description, a name and an image.

- Each item should have a button or link that allows a user to add it to their shopping cart.

### Shopping Cart

- When users add items to the cart, the cart should display the amount of items in the cart.

- On your main page, you should have a list of available items that you can add to your cart, AND you should also have a small, clickable cart icon-like thingy(image, link, text) that displays the *TOTAL* amount of items in your shopping cart, beside it.

- Your cart should be clickable. On clicking the cart, it will drive users to `/cart` page that will display all info and items related to your cart. You should use React Router to accomplish this.

- Your cart should display a subtotal that displays the total cost of all the items in your cart.

- Users should be able to remove items from the cart.

- If the cart has no items in it, the cart page should display a message that your cart is empty.

- You should implement a back button on the shopping cart page that allows users to go back to the main page where they can add more items.

- Everything should be done using react componenents. Your HTML should only contain a `root` element.

### TIP

- You should NEVER modify the state of a component. This means using the `push` method to add a new item to your cart probably won't work. You should consider using a function like `concat` instead.
