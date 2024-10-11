**GAMING STORE (E-COMMERCE WEBSITE)**

**Description**:

   This project is a simple eCommerce website for a gaming store, built using HTML, CSS, and Vanilla JavaScript. The site allows users to browse products, add items to their cart, and update the cart dynamically. This basic but functional site offers core eCommerce functionalities, such as a product catalog, shopping cart, and checkout pages, all while using local storage to save cart information.

**Features**:

  ◆ Product Catalog: Displays a list of gaming products with details.

  ◆ Add to Cart: Users can add products to the shopping cart.

  ◆ Cart Management:   Increase or decrease item quantity, Remove items from the cart, View total price and update dynamically.

  ◆ Local Storage: Cart items persist in local storage between page reloads.

  ◆ Responsive Design: Layout adjusts for different screen sizes.

  ◆ Technologies Used:

   HTML5: Structure and layout of the website.

   CSS3: Styling and responsiveness of the pages.

   JavaScript (ES6): Functionality such as adding products to the cart, updating cart values, and DOM manipulation.

   Vite: Development environment for faster builds and easier development workflow.

  ➤ **PROJECT STRUCTURE**:

    /api                     # Backend APIs or placeholders for API calls
    /public/Images            # Product images and other assets
    .gitignore                # Git ignore file for unnecessary files
    about.html                # About page
    addtocart.html            # Page for viewing products in the cart
    contact.html              # Contact page
    index.html                # Homepage displaying available products
    products.html             # Products page with detailed listings
    style.css                 # Main stylesheet for the site
    main.js                   # Main JavaScript file
    vite.config.js            # Configuration for Vite
    package.json              # Package file for project dependencies


  **Key Files and Components**:

   ◆ index.html: Displays the homepage with featured products.

   ◆ about.html: Provides information about the store.

   ◆ products.html: Contains the list of products available in the store.

   ◆ contact.html: Contact form for users to reach out.

   ◆ addtocart.html: Displays the shopping cart with options to modify the cart items.

JavaScript Files:

   ◆ homeProductsCard.js: Dynamically renders products on the homepage.

   ◆ getCartProducts.js: Fetches products stored in the cart using local storage.

   ◆ incrementDecrement.js: Handles updating product quantities in the cart.

   ◆ updateCartValue.js: Updates total price based on cart contents.

   ◆ showToast.js: Displays notifications (like item added to cart).

CSS (style.css): Main CSS file for styling, ensuring responsive design.  


➤ **Installation**:
    
  Prerequisites
    
  Make sure you have Node.js installed. Clone this repository and navigate to the project directory.

    git clone https://github.com/yourusername/gaming-store.git
    cd gaming-store
    npm install

 ➤ **Run the Project**

   Start the development server using Vite.

     npm run dev

➤ **Build for Production**

   To create a production build, run:

     npm run build

**Usage**:

   ◆ Browse the products on the homepage.

   ◆ Click on a product to view more details.

   ◆ Add the product to the cart and navigate to the cart page to view selected items.

   ◆ Adjust the quantity or remove items from the cart.
   
   ◆ Cart items and totals are stored in local storage, so the information persists even after refreshing the page.
   
