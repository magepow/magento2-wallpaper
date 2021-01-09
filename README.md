# Magento2 Wallpaper Change the product price as desired 

## Details

- The module adds the option of price, product quality as desired

## Description

- Receive feedback, reviews from customers about products or receive information and requests about products from customers via email.

- Change the price of the product according to the length, the width can be the height. 

- Change the price of the product by unit of measure such as inch, cm, meters, foot, ... can add or change to pound, kg, gram ...

- Sample order can be ordered


# I : Download Magento 2 Wallpaper Extension
   ### ✓ Install Magepow Wallpaper via composer (recommend)

Run the following command in Magento 2 root folder:
    
    composer require magepow/wallpaper
    php bin/magento setup:upgrade
    php bin/magento setup:static-content:deploy -f
    php bin/magento c:f

# II : Results In Frontend

website demo : https://wp2cart.com/colornew

demo product view : https://wp2cart.com/colornew/kids-hot-air-balloon-with-cartoon-animals-wallpape.html

 #### I *: Catalog Product View
    
    If you want to buy a sample product, please click on "Buy Sample", 
    the price will be customized according to the administrator's settings
    in the admin guide below.
    
    If you want to buy products of different quality and size as desired 
    please click on but the options are in "Select Material" and "Enter Your Dimensions" 
    the price will be changed according to the prices listed in the settings. are guided below
    
    Anything you need help with making product changes or comments on certain products 
    can be sent via the comment box by clicking "Get Quote & Preview" and entering the 
    required information.
    
![price-frontend.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/price-frontend.png)

![resultfrontend.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/resultfrontend.png)


 #### II *: Shopping cart show

![show-price-cart.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/show-price-cart.png)

# III : User guide ConFig Admin 
## step 1: Add new image 

 ### Step 1.1 : Magepow=>List Wallpaper => add new Image , Enter the required information and then click on Save Image.

![add-new-image-1.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/add-new-image-1.png)

![add-new-image-2.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/add-new-image-2.png)



## Step 2 . Catalog Product :  where to add necessary option attributes and enable or disable custom functions

  ### Step 2.1 Catalog=>Product=>Edit  Or  Add Product => Wallpaper Product => yes or no

![config-product-1.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/config-product-1.png)

 ### Step 2.2 click Customizable Options=> Add options

![config-product-2.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/config-product-2.png)
 
  ### step 2.3  Enter option attribute information

    Option Title :
    Width   => And Click Required
    Height => And  Click Required
    Sample => And Click Required
    Material => And Click Required

	Option type: Click Text =>Field

![config-product-3.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/config-product-3.png)


## Step 3 : How To Enable/Disable The Extension


   ### Step 3.1 : Configuration Wallpaper : Where to enable or disable the module and modify the sample price and units of measure for the product
   ##### STORES => Configuration => Magepow => Wallpaper

    STORES => Configuration => Magepow => Wallpaper => General => Enable : Yes Or No   . Then, select Yes to Enable module/No to Disable the module

	STORES => Configuration => Magepow => Wallpaper => General => Unit Wallpaper  Select the unit of measure to be used outside the frontend

	STORES => Configuration => Magepow => Wallpaper => General => Sample Product  .  Price for the product to buy sample

![store-config.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/store-config.png)

## Step 4 : On Of Attributes Show Page : Conditions are necessary and sufficient to display attributes product information

 ### Step 4.1 : STORES => Attributes =>Product => Search (wallpaperproduct)=>click wallpaperproduct

![store-config-attribute-1.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/store-config-attribute-1.png)

![store-config-attribute-2.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/store-config-attribute-2.png)

  ### Step 4.2 Click => Storefront  Properties => Visible on Catalog Pages on Storefront : pick Yes and Save Attribute

![store-config-attribute-3.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/store-config-attribute-3.png)

![store-config-attribute-4.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/store-config-attribute-4.png)



## Step 5 Config Send mail 

 ### Step 5.1 STORES => Configuration => GENERAL => Contacts
    
    * Contact Us => Enable Contact Us => Yes
    * Email Options = > Send Emails To (Enter the email you want to send and receive 
    related information from the customer when it is received outside the frontend)
    Example (magepow@gmail.com)
    
    * Email Options = > Email Sender => General Contact
    
    * Email Options = > Email Template => Contact Form (Default)
    

![config-contacts-sendmail.png](https://github.com/magepow/magento2-wallpaper/blob/master/media/config-contacts-sendmail.png)

# IV : - CUSTOM SUPPORT

### 1 - Support
- Ticket Support: http://alothemes.com/ticket. If you have found any bugs or have some other problems with this extension. If the problem is not covered there, you can contact us via support center. We will respond as soon as possible (within 24 – 48 hours, usually much faster)

### 2 - Contact

- Support Email support@alothemes.com

- Contact Sales: contact@alothemes.com
