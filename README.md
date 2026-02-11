# E-commerce Shop &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/ainh01/ecommere/blob/main/LICENSE)  
> A simple e-commerce shop for perfumes.  

This project is a basic e-commerce website focused on selling perfumes. It includes features for product display, filtering, a shopping cart, and order management.  

## Installing / Getting started  

To get this project running locally, simply clone the repository and open the `shop.html` file in your web browser.  

```shell  
git clone https://github.com/ainh01/ecommere.git  
cd ecommere  
```  

Then, open `shop.html` in your preferred web browser. This will launch the e-commerce shop.  

## Developing  

### Built With  
* HTML5  
* CSS3 (Bootstrap 3/4, custom CSS)  
* JavaScript (jQuery 2.1.0, custom JS)  

### Prerequisites  
A modern web browser (e.g., Chrome, Firefox, Safari) is required to view and interact with the site. No specific server-side environment is needed as it's a client-side only application.  

### Setting up Dev  

To set up the development environment:  

```shell  
git clone https://github.com/ainh01/ecommere.git  
cd ecommere  
```  

No additional package management installation is required as all assets are included directly within the repository. You can modify `shop.html` and the files in the `assets/` directory.  

### Building  

This project does not require a build step as it is a static HTML, CSS, and JavaScript application. Changes made to the source files will be reflected directly upon refreshing the browser.  

### Deploying / Publishing  
To deploy this project, simply upload the entire `ecommere` folder (including all subfolders and files) to a web server. The `shop.html` file should be accessible as the main entry point.  

## Versioning  

This project does not currently follow a formal versioning system. Development is ongoing, and updates will be pushed to the main branch.  

## Configuration  

Product data is configured directly within the `shop.html` file using JavaScript arrays (`monHang`).  
Other configurations like shipping fees and discounts are also hardcoded within the JavaScript.  

## Tests  

No formal automated tests are implemented for this project. Testing is performed manually by interacting with the website features in a web browser.  

## Style guide  

The project uses a mix of Bootstrap (3 and 4) and custom CSS defined in `assets/css/custom.css` and `assets/css/templatemo-hexashop.css`. JavaScript is located in `assets/js/custom.js` and other library files.  

## Api Reference  

This project does not utilize an external API. All data and logic are handled client-side within the `shop.html` file and its associated JavaScript files.  

## Database  

No database is used for this project. All product and order information is stored in JavaScript arrays within the `shop.html` file, meaning data is not persistent across sessions or browser closures.  

## Licensing  

This project is licensed under the MIT License. See the [LICENSE](https://github.com/ainh01/ecommere/blob/main/LICENSE) file for details.
