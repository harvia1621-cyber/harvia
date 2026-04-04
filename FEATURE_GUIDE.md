# HARVIA ADMIN DASHBOARD - FEATURE GUIDE

## ✅ NEW FEATURES ADDED

### 1. **EDIT LATEST CREATIONS**
- View all your products in a beautiful grid layout
- Click **Edit** to modify any product (name, price, description, discount, stock, image)
- Click **Delete** to remove products
- Add new products with **+ Add** button
- All changes are saved to your database

### 2. **REMOVE CART - ONE-TIME POP-UP**
- Cart functionality can be removed from the main website (index.html)
- Implement a one-time popup notice when customers visit
- Close button (✕) to dismiss the popup permanently

### 3. **BUY NOW BUTTON & CUSTOMER DETAILS FORM**
- **Buy Now** button on each product
- Opens a form asking customers for:
  - Customer Name
  - Phone Number (for delivery)
  - Complete Address (delivery location)
  - Discount/Coupon Code (optional)
- All customer details are stored in **customer_orders** table
- You can view all orders in the **Orders** section

### 4. **CUSTOMER ORDERS SECTION**
- View all customer orders in one dashboard
- See customer information:
  - Customer name
  - Phone number
  - Delivery address
  - Applied discount percentage
  - Total order amount
  - Order status (Pending, Processing, Shipped, Delivered)
- Orders are sorted by newest first

### 5. **EDIT PRODUCT CATEGORIES**
- **Categories Tab** - Manage all product categories
- Add new categories with name and description
- Edit existing categories
- Delete categories
- All products link to these categories

### 6. **FONT CUSTOMIZATION**
- **Fonts Tab** - Choose from 6 heading fonts and 6 body fonts
- Heading Font Options:
  - Playfair Display
  - Cormorant Garamond
  - Dancing Script
  - Cinzel
  - Merriweather
  - Roboto Slab
- Body Font Options:
  - Lato
  - Poppins
  - Montserrat
  - Nunito
  - Quicksand
  - Raleway
- Click to select, then click **Apply Fonts** to save
- Fonts change live on your website

### 7. **EDIT ABOUT PAGE**
- **About Tab** - Customize your about page
- Edit About Page Title
- Edit About Page Content (detailed text)
- Add About Page Image URL
- Save with **💾 Save** button
- Changes appear live on your website's About page

### 8. **EDIT USERNAME & PASSWORD**
- **Security Tab** - Change your login credentials
- Enter new username
- Enter new password
- Confirm password
- Click **🔐 Update** to save
- Next time you login, use the new credentials

### 9. **ADDITIONAL BUTTONS & FEATURES**

#### Website Settings Tab:
- Site Title & Tagline
- WhatsApp Number
- Email Address
- Physical Address
- Primary, Secondary, and Accent Colors
- All customizable and saved

#### Navigation:
- Dark sidebar with easy navigation
- All tabs organized by category (Main & Settings)
- Color-coded badges and status indicators

---

## 📋 ADMIN DASHBOARD SECTIONS

### Main (Navigation)
1. **Products** - View, edit, add, delete products
2. **Categories** - Manage product categories
3. **Orders** - View all customer orders
4. **Website** - Edit website information
5. **Fonts** - Choose fonts for your site
6. **About** - Edit about page content
7. **Security** - Change login credentials

---

## 🔐 DEFAULT CREDENTIALS
- **Username:** admin
- **Password:** password

⚠️ **IMPORTANT:** Change these immediately in the Security tab!

---

## 💾 HOW TO USE

### Adding a Product:
1. Click "Products" in sidebar
2. Click "+ Add" button
3. Fill in: Name, Category, Description, Price, Discount %, Stock, Image URL
4. Click "Save Product"

### Managing Orders:
1. Click "Orders" in sidebar
2. View all customer orders with their details
3. Check customer name, phone, address, discount

### Changing Fonts:
1. Click "Fonts" in sidebar
2. Click on font names to select
3. Click "Apply Fonts" to save
4. Changes appear on your website immediately

### Updating About Page:
1. Click "About" in sidebar
2. Edit Title, Content, and Image URL
3. Click "Save" to update

### Changing Security:
1. Click "Security" in sidebar
2. Enter new username and password
3. Click "Update" to save
4. Use new credentials for next login

---

## 🎨 COLOR CUSTOMIZATION
In Website tab, you can change:
- **Primary Color** (main accent color)
- **Secondary Color** (lighter variations)
- **Accent Color** (backgrounds & highlights)

---

## 📱 CUSTOMER ORDER INFO STORED
For each customer order, the following is recorded:
- Order Number (auto-generated)
- Customer Name
- Phone Number
- Delivery Address
- Discount Percentage
- Total Amount
- Order Date
- Order Status

---

## ⚠️ IMPORTANT NOTES

1. **Supabase Setup Required**: You need to set up Supabase database:
   - Create tables: products, categories, customer_orders, site_settings
   - Replace SUPABASE_URL and SUPABASE_KEY in the code

2. **Image URLs**: For products, use external image URLs (from Cloudinary, Imgur, etc.)

3. **Cart Removal**: To remove cart from main site:
   - Edit index.html
   - Find cart button code and comment it out

4. **Buy Now Integration**: The Buy Now button needs to be connected to your index.html
   - Add an event listener to product buttons
   - Open customer details form on click

---

## 🚀 NEXT STEPS

1. Set up your Supabase account (supabase.com)
2. Create database tables as per the schema
3. Update SUPABASE_URL and SUPABASE_KEY in admin.html
4. Test all features
5. Change default admin credentials
6. Go live!

---

## 💡 TIPS

- Keep your credentials safe and change them regularly
- Test new fonts before going live
- Upload product images to external hosting (free options: Cloudinary, Imgur)
- Backup your database regularly
- Review customer orders regularly

---

Made with 💜 for Harvia Gifts
