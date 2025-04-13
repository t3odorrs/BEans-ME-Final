# BEans - Delivery Cafea Iași

## Overview

BEans is a simple web page for a coffee delivery service based in Iași, Romania. It allows users to browse available coffee and pastry products, add items to a virtual cart, and view a summary of their selected items. The cart menu appears with a modern design, including product emojis, and automatically hides after 5 seconds of inactivity. Users can also manually toggle the cart and remove items from it.

## Features

* **Product Catalog:** Displays a variety of coffee and pastry items with their names, prices, and brief descriptions.
* **Add to Cart Functionality:** Enables users to add desired products to their virtual shopping cart with a click of a button.
* **Dynamic Cart Menu:**
    * Appears when an item is added to the cart or when the "Coș" button is clicked.
    * Displays a list of items in the cart with their quantities and total price.
    * Includes relevant emojis for each product for a visually appealing and modern look.
    * Provides a "×" button next to each item in the cart to remove it.
* **Automatic Cart Hide:** The cart menu automatically disappears after 5 seconds of inactivity (when the mouse is not hovering over it).
* **Manual Cart Toggle:** Users can manually show or hide the cart menu by clicking the "Coș" button in the header.
* **Delivery Modal:** A basic modal for initiating the delivery process (currently only displays a form field for the address).
* **Modern and Fresh Design:** Utilizes rounded corners, subtle shadows, and a clean layout for a contemporary user experience.

## Technologies Used

* **HTML:** Provides the structure and content of the web page.
* **CSS:** Styles the HTML elements to create the visual design and layout, including the modern cart appearance.
* **JavaScript:** Implements the interactive features, such as adding and removing items from the cart, dynamically updating the cart menu, and handling the auto-hide functionality.

## How to Use

1.  **Open `index.html` (or the name of your HTML file) in a web browser.**
2.  **Browse the "Produse Disponibile" section.**
3.  **Click the "Adaugă în coș" button** next to any product you wish to add to your cart.
4.  **The cart menu will appear** on the right side of the screen, displaying the added items.
5.  **To remove an item from the cart, click the "×" button** next to that item in the cart menu.
6.  **The cart menu will automatically hide** after 5 seconds if you don't interact with it.
7.  **You can manually toggle the cart** by clicking the "Coș" button in the header.
8.  **Click the "Livrare" button** to open a basic delivery information modal.

## File Structure
├── index.html      (The main HTML file)
└── style.css       (The CSS stylesheet)
└── README.md       (This README file)

## Potential Future Enhancements

* More robust cart functionality (quantity updates, persistent storage).
* Actual form submission for delivery details and integration with a backend.
* User authentication and order history.
* Dynamic product loading from a database or API.
* Payment gateway integration.
* Improved UI/UX and responsiveness for different screen sizes.
* Location services for delivery address.

## Author

[t3odorrs/BEans-ME]

## License

