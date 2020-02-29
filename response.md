# ZERO-1 Tasks

## Tasks relating to [divine trash](https://pwa.divinetrash.co.uk/)

### List which local storage Keys begin with 'shop/'.

* shop/attributes/attribute_code$$price
* shop/claims/cookiesAccepted
* shop/carts/current-cart
* shop/attributes/attribute_id$$93
* shop/carts/current-cart-token
* shop/carts/current-cart-hash
* shop/recently-viewed/recently-viewed
* shop/attributes/attribute_code$$color
* shop/attributes/attribute_code$$size
* shop/attributes/attribute_id$$143
* shop/attributes/attribute_id$$77 
---

### Where do you find and inspect your Cookies?

>*From the developer console, go to the Applications tab, and then expand the Cookies dropdown under the Storage section. Under Cookies, you can see the domains from which the cookies are being used on the website.*

**Source:** [CookieYes](https://www.cookieyes.com/how-to-check-cookies-on-your-website-manually/ "How to check you cookies manually")

---


### What manifest.json is and what it does.

```A file that defines how a browser should display the web application. Including a manifest is required in order for a user to install a PWA to their device’s home screen.```

__This file can include:__

* The application name and a __short_name__ (to be displayed in the address bar on smaller screens).

* The source, size and image type of any icons used by the PWA.

* A __start_url__ that defines the page which the browser will open when the application is launched, rather than whatever page the user was viewing when they added the app to their home screen.

* __background_color__ sets the colour of the splash screen when the app launches

* __display__ defines the preferred display mode for the website, __"standalone"__ grants the appearance of a standalone application by excluding browser UI elements

**Source:** [web.dev/add-manifest](https://web.dev/add-manifest/ "Add a web app manifest")

---

### After the initial application load, when navigating the site what 2 main asset types would you expect to see loading (in your network tab) when loading categories?

* jpg for the product thumbnails

* text/html for product names and prices

---

### What is lighthouse?
> _Lighthouse can audit a web page or app, checking performance and measuring against developer best practices. Can give feedback and tips for improving performance._

**Source:** [freecodecamp.org](https://www.freecodecamp.org/news/introduction-to-chrome-lighthouse/ "Introduction to chrome lighthouse")

---

## Other tasks

### Can you write a Ghost Inspector Test which creates a user account on [Divine Trash](https://pwa.divinetrash.co.uk/ "Divine Trash") and attempts to add 3 items to the cart them logs out?

```A bit messy, but it works. I spent about 30 mins reading documentation, about 1 hour and 15 minutes trying to write the test. Got bogged down trying to implement email response functionality that actually wasn’t required to register an account. I learned about using ghost inspector's built in **timestamp** functions to create unique emails and passwords for each test run. I also learned how to respond to sent emails in order to verify an account, though this was actually not required.```

---

### Provide an explanation on what Composer is and how Magento use it.

__Composer__ is a package manager for php, similar to __NPM__ for __node.js__. We used NPM to install __cordova__ during the **_Open University_** module __Web, mobile and cloud technologies__ [TM352](http://www.open.ac.uk/courses/modules/tm352 "Web, mobile and cloud technologies").

Composer is used to manage **Magento** components and their dependencies. 

Using Composer to get the **Magento** software *metapackage* provides the following advantages: 

* Reuse third-party libraries without bundling them with source code

* Reduce extension conflicts and compatibility issues by using a component-based 
architecture with robust dependency management

* Adhere to PHP-Framework Interoperability Group (FIG) standards

* Repackage Magento Open Source with other components

* Use the Magento software in a production environment

---

### Create an AWS account, create a free-tier EC2 instance and see how far you can get with installing Magento Community using SSH and Composer

``` Spent around an hour signing up and completing the tutorial for opening an EC2 instance. Installed composer successfully, got tangled installing Ubuntu prerequisites whilst preparing to install Magento. Spent around an hour reading various documentation.```
