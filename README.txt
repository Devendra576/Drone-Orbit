DRONE ORBIT — EASY PRODUCT MANAGEMENT
=====================================

FILES
-----
index.html       Website layout and styling
products.js      Product catalogue (names, prices, categories, image paths)
images/          Local product images
README.txt       These instructions

CHANGE A PRODUCT
----------------
1. Open products.js in VS Code.
2. Edit a product's name, category, price, and image filename.
3. Save the file.
4. Keep the image path relative to this folder, for example images/my-new-drone.jpg.
5. Add the new image file to the images folder.
6. Redeploy the complete project to Vercel.

CHANGE AN IMAGE
---------------
1. Add your photo to the images folder (JPG, PNG, WebP or SVG).
2. In products.js, update the image field to the exact path, e.g.
   image: "images/new-drone.jpg"
3. Make sure the filename and capitalization match exactly. Vercel hosting is case-sensitive.
4. Redeploy the entire folder, including products.js and images/.

ADD A PRODUCT
-------------
Copy one object in products.js, paste it inside the array, and change its id, name,
category, price, image and description. Each object must be separated by a comma.
Supported categories are Drones, Cameras and Accessories (other categories can also
appear in the All products view, but create a matching filter if you want a separate tab).

WHATSAPP
--------
Product image, product name and Order on WhatsApp button open WhatsApp chat to
+91 9151293189 with product name, category, and listed price prefilled.
To change the destination, update WHATSAPP_NUMBER in index.html.

IMPORTANT
---------
This is a static catalogue/enquiry website, not online checkout. No online payment is taken.
After changes, redeploy to Vercel for the live site to update. Keep all files and folders
together in the project root.

Drone Orbit website update
