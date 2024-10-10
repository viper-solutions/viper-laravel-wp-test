<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="200" alt="Laravel Logo">
  </a>
  <a href="https://wordpress.org/download/" target="_blank">
    <img src="https://i.ibb.co/jZYWyR3/logo-wordpress-49488.png" width="100" alt="WordPress Logo">
  </a>
</p>

## About This Test

This test will asses you knowledge on doing a Laravel project with some WordPress knowledge. The test will cover two phases.
1. Laravel MVC Test
2. Wordpress Theme Creation

## Prerequisite

1. Fork this repository
2. [Docker](https://www.docker.com/)
   
   We are using `Docker` for this test to avoid version reset on your local machine. When using docker, there is no need to upgrade or downgrade your tech stack version. Docker containers will handle it for you.

3. Docker Compose
   1. [Docker Compose](https://docs.docker.com/compose/install/linux/) for Ubuntu
   2. [Docker Desktop](https://www.docker.com/products/docker-desktop/) for Windows
   
  > If you are not familiar with `Docker`, that is totally fine. You'll need to create your own public repository and share it after the test.

## Phase 1: Laravel

We want to see how familiar are you when it comes to the plain MVC version of Laravel. No need to do headless technology and other JS frameworks for now.

> Make sure that the sample data goes to `model`, the endpoints are calling `controllers`, and the layouts are handled by `*.blade.php`

1. Create a navigation bar with the following menus:
   1. Homepage
   
      Nothing more, nothing less. Just a homepage that has a text saying "My Homepage". Make sure it is vertically and horizontally centered.

   2. Products

      Show a page for product catalogs, this can be on a list, cards, or what best that presents a collection of products. A good design is a plus but not required. Please see products catalog below:

      | Category       | Product Name             | Description                                                                 | Price  | Sizes / Materials  | Colors                          | SKU     |
      |----------------|--------------------------|-----------------------------------------------------------------------------|--------|---------------------|---------------------------------|---------|
      | Women’s Fashion | Classic Denim Jacket     | Timeless and versatile denim jacket made from 100% cotton with a relaxed fit.| $49.99 | XS, S, M, L, XL     | Light Blue, Dark Wash           | WDJ001  |
      | Women’s Fashion | Maxi Floral Dress        | Flowy maxi dress with floral print, adjustable straps, and a sweetheart neckline. | $69.99 | XS, S, M, L, XL     | Red Floral, Blue Floral, Green Floral | WFD010  |
      | Women’s Fashion | Cozy Knit Sweater        | Soft knit sweater with a relaxed fit and ribbed cuffs.                      | $39.99 | XS, S, M, L, XL     | Cream, Mustard, Burgundy        | WKS002  |
      | Women’s Fashion | High-Waisted Jeans       | Comfortable high-waisted jeans with a slim fit, made from stretch denim.    | $59.99 | 24, 26, 28, 30, 32  | Light Wash, Black               | WHJ006  |
      | Women’s Fashion | Faux Leather Skirt       | Chic faux leather skirt with a high waist and A-line silhouette.            | $34.99 | XS, S, M, L         | Black, Brown                    | WLS004  |
      | Men’s Fashion  | Slim Fit Chinos           | Comfortable and stylish slim-fit chinos made from breathable cotton.        | $39.99 | 30, 32, 34, 36, 38  | Khaki, Navy, Black              | MCH003  |
      | Men’s Fashion  | Graphic T-Shirt           | Soft cotton t-shirt featuring a bold, trendy graphic print.                 | $19.99 | S, M, L, XL, XXL    | Black, White, Gray              | MGT009  |
      | Men’s Fashion  | Casual Hoodie             | Warm, soft hoodie with front pocket and adjustable hood.                    | $29.99 | S, M, L, XL, XXL    | Heather Gray, Navy, Olive       | MCH008  |
      | Men’s Fashion  | Button-Down Shirt         | Classic button-down shirt with a slim fit and chest pocket.                 | $34.99 | S, M, L, XL, XXL    | White, Light Blue, Pink         | MBS015  |
      | Men’s Fashion  | Cargo Shorts              | Durable cargo shorts with multiple pockets, perfect for outdoor adventures. | $24.99 | 30, 32, 34, 36, 38  | Olive, Beige, Charcoal          | MCS007  |
      | Accessories    | Leather Tote Bag          | Spacious leather tote bag with inner pockets for easy organization.         | $89.99 | Genuine Leather     | Black, Brown, Tan               | ATB012  |
      | Accessories    | Sunglasses with UV Protection | Stylish sunglasses with UV protection. Comes with a protective case.       | $29.99 | Plastic             | Black, Tortoise, Gold           | ASG018  |
      | Accessories    | Gold Hoop Earrings        | Classic gold hoop earrings, lightweight and hypoallergenic.                 | $14.99 | Gold-Plated Alloy   | Gold                            | AHE003  |
      | Accessories    | Knit Beanie               | Warm knit beanie with a soft, stretchy fit, perfect for chilly weather.     | $12.99 | Acrylic             | Black, Gray, Red                | AKB009  |
      | Accessories    | Leather Wallet            | Compact leather wallet with card slots and a coin pocket.                   | $24.99 | Genuine Leather     | Black, Brown, Navy              | ALW006  |
      | Home Decor     | Ceramic Vase Set          | Set of three ceramic vases in different shapes and sizes.                   | $45.99 | Ceramic             | White, Pastel Blue, Pastel Pink | HCV005  |
      | Home Decor     | Woven Throw Blanket       | Cozy woven throw blanket with fringe edges.                                 | $34.99 | Cotton Blend        | Cream, Olive Green, Charcoal    | HTB002  |
      | Home Decor     | Scented Soy Candle        | Hand-poured soy candle with a soothing lavender scent.                      | $19.99 | Soy Wax             | White                           | HSC004  |
      | Home Decor     | Wall Art Print Set        | Set of three abstract wall art prints, perfect for any living space.        | $29.99 | Paper               | Blue, Beige, Gray               | HWA011  |
      | Home Decor     | Decorative Pillows        | Set of two decorative pillows with a textured design and zipper closure.    | $24.99 | Cotton Blend        | Mustard, Teal, Neutral          | HDP008  |


   3. Product Details

      Plain and simple, a page where it will display the product details from the selected item on the list.

   4. Each pages must be available on the navigation bar. Again good design is a plus but not required. 

## Phase 2: WordPress

We are also considering if you have a background in `WordPress`. While this is very nice to have, for the initial phase of the project. `Laravel` will be the main tech used here.

1. Login on this [WordPress Admin](http://viper-test.nadescrib.com/wp-login.php)
   
   username: applicant

   password: Password123!

2. Create a WordPress theme, no need to apply. We can view it from our end.
3. Make sure that you are the actual author of the theme. We can verify if it was a template made by another.

## Submission

You can email or message your contact person for this interview and our technical will get back if the above requirements are met. Looking forward to hearing from you.

Please don't hesistate to message us for questions. We are happy to answer valid questions.



