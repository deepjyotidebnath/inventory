Inventory Manager (standalone project)

FILES
  index.html    the app - open this in a browser
  style.css     styling
  script.js     all the logic
  products.js   sample products used for the first start (optional to edit)
  images/       product pictures (optional)

FEATURES
  - Stock per location (Main Store, Godown; add more) and move stock between them
  - Low-stock and out-of-stock alerts, with a one-click purchase order for low items
  - Add, edit and delete products with SKU, barcode (EAN-13), MRP, price, cost, reorder level
  - Barcode labels you can print; scan a barcode or type a SKU to open a product
  - Suppliers and purchase orders (send on WhatsApp, mark Received to add stock)
  - Stock movement history, stock value, CSV export
  - Reset data: load sample medicines or start with an empty inventory

DATA
  Saved in the browser you use (localStorage). Use "Export stock (CSV)" for backups.
  Different browsers or computers do not share data.

PRODUCT PICTURES
  Put a photo in images/ named after the product (lowercase letters and digits only, e.g.
  images/paracetamol650.jpg). The app tries .jpg, .png, .webp then .svg.
  The sample products already have pictures. Products without a picture show no image.
