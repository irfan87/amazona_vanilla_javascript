# AMAZONA

An Amazon-clone website with simple NodeJS and vanilla JS, no React.

1. Create Folder Structure
    
    * create root folder, such as AMAZON_VANILLA_JS (any name that you want)
    * add client (or frontend) and server (or backend)
    * create src folder in client folder
    * create index.html with heading AMAZONA in src
    * run npm init in client folder
    * `yarn add` (or `npm install`) -D live-server
    * add start command as `live-server src --verbose`
    * run `yarn start` (or `npm start`) 

2. Design Website
    
    * create style.css
    * link style.css to index.html
    * create div.grid-container
    * create header, main (body) and footer
    * style html, body
    * style grid-container, header, main and footer
    * make transitions for header's links 

3. Create Static Home Screen

    * create ui.products
    * create li
    * create div.product
    * add
        * .product-image
        * .product-name
        * .product-brand
        * .product-price
    * style ul.products and internal divs
    * duplicate 2 times to show 3 products

4. Render Dynamic Home Screen
    * create data.js
    * export an array of 6 products
    * create screens/HomeScreen.js
    * export HomeScreen as an object with render() method
    * implement render()
    * import data.js
    * return products mapped to li inside an ul
    * create app.js
    * link app.js to index.html as module
    * set main id to main_container
    * create router() function
    * set main_container innerHTML to HomeScreen.render()
    * set load event of window to router() function