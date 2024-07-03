APP PAGE
The application is a straightforward e-commerce app with two primary screens: HomeScreen and CartScreen. It boasts a sleek and modern design to ensure a user-friendly shopping experience.


HOMESCREEN PAGE
Header: Contains a logo and icons for the menu and search functionalities.
Product Grid: Shows products in a grid layout with an image, title, subtitle, price, and an "add to cart" button.
Condensed Space Above Product Section: Decreased padding and margins to display more products on the screen.
"View Cart" Button: Enables navigation to the CartScreen to review chosen items.


CARTSCREEN PAGE
Header: Features a logo, an optional search icon, and the title "CHECKOUT".
Cart Items: Shows items in the cart with an image, title, subtitle, price, and a remove button.
Total Calculation: Shows the estimated total cost of the items in the cart.
Checkout Button: Clearly displayed with a shopping bag icon to proceed with the purchase.


DATA STORAGE IMPLEMENTATION
AsyncStorage: Utilized for saving cart data locally on the device.
Add to Cart: Updates and stores the cart state in AsyncStorage whenever a new product is added.
Remove from Cart: Updates and stores the cart state in AsyncStorage when items are removed.
Load Cart on Startup: Retrieves cart data from AsyncStorage when the app initializes.

IMG-20240703-WA0147 

IMG-20240703-WA0148 

IMG-20240703-WA0149 

IMG-20240703-WA0145 

IMG-20240703-WA0144

IMG-20240703-WA0146

