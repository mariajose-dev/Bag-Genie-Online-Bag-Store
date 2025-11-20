<h1 align="center">👜 Bag Genie – Online Bag Store</h1>
<p align="center">A complete e-commerce platform for browsing, purchasing, and delivering stylish and durable bags.</p>

---

<h2>📌 Overview</h2>
<p>
Bag Genie is a fully functional online bag store designed to provide a smooth shopping experience for customers and efficient backend management for business owners. 
The platform supports browsing products by categories and subcategories, secure purchasing, courier assignment, and real-time delivery tracking. 
It includes dedicated modules for staff, customers, vendors, and couriers to ensure a streamlined operational workflow.
</p>

---

<h2>🎯 Key Features</h2>

<ul>
  <li><b>Structured Product Browsing</b> – Categories, subcategories, item listings, and search filters.</li>
  <li><b>Role-Based Access</b> – Administrator, Staff, Customer, and Courier dashboards.</li>
  <li><b>Secure Transactions</b> – Integrated payment handling.</li>
  <li><b>Courier Assignment</b> – Automatic courier allocation for completed orders.</li>
  <li><b>Inventory & Purchase Tracking</b> – Manage vendor purchases and stock updates.</li>
  <li><b>Order Management</b> – Cart, checkout, order processing, and delivery updates.</li>
</ul>

---

<h2>👥 User Roles</h2>

<h3>1️⃣ Administrator</h3>
<ul>
  <li>Full access to all system modules.</li>
  <li>Manage staff, customers, products, vendors, and couriers.</li>
  <li>Record and monitor vendor purchases.</li>
</ul>

<h3>2️⃣ Staff</h3>
<ul>
  <li>Add, edit, and view categories, subcategories, products, and vendor details.</li>
  <li>Assist admin with purchase management.</li>
</ul>

<h3>3️⃣ Customer</h3>
<ul>
  <li>Browse products and filter by category/subcategory.</li>
  <li>Registered users can add items to cart and purchase.</li>
  <li>Track orders and receive courier updates.</li>
  <li>Unregistered users can only view products.</li>
</ul>

<h3>4️⃣ Courier</h3>
<ul>
  <li>View assigned orders and update delivery status.</li>
  <li>Mark orders as <i>Out for Delivery</i> or <i>Delivered</i>.</li>
</ul>

---

<h2>📦 System Modules</h2>

<ol>
  <li><b>Staff Management</b> – Add/Edit staff profiles and manage roles.</li>
  <li><b>Customer Registration</b> – Account creation and profile handling.</li>
  <li><b>Vendor Management</b> – Add/Edit vendor details and track suppliers.</li>
  <li><b>Courier Management</b> – Manage courier details and delivery operations.</li>
  <li>
    <b>Product Management</b>
    <ul>
      <li>Category Management</li>
      <li>Sub Category Management</li>
      <li>Item Management</li>
    </ul>
  </li>
  <li><b>Purchase Management</b> – Record and track bulk purchases from vendors.</li>
  <li><b>Cart Management</b> – Add, update, and remove items before checkout.</li>
  <li>
    <b>Sales Management</b>
    <ul>
      <li>Payment Management</li>
      <li>Courier Assignment</li>
      <li>Delivery Management</li>
    </ul>
  </li>
</ol>

---

<h2>🚀 Highlights</h2>
<ul>
  <li>Clean UI for easy browsing and checkout.</li>
  <li>Backend designed to minimize maintenance and support smooth operations.</li>
  <li>Random courier assignment to ensure fair and efficient delivery allocation.</li>
</ul>

---

<h2>📁 Project Structure</h2>
<pre>
bag_genie/
├── app.py
├── loginpage.py
├── reports.py
├── invoice_generator.py
│
├── category_management.py
├── subcategory_management.py
├── item_management.py
├── customer_management.py
├── staff_management.py
├── courier_management.py
├── vendor_management.py
├── purchase_management.py
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── base.html
│   ├── home.html
│   ├── products.html
│   ├── loginpage.html
│   ├── checkout.html
│   ├── dashboards/
│   ├── management_pages/
│   └── partials/
</pre>


<h2>Tech Stack</h2>
<ul>
  <li>HTML, CSS, JavaScript</li>
  <li>Flask (Python Framework)</li>
  <li>MySQL Database</li>
  <li><strong>XAMPP:</strong> Required to run MySQL. 
      Make sure the Apache and MySQL services in XAMPP are active before running the project.</li>
</ul>

<h2>Installation</h2>
<ol>
  <li>Clone the repository:</li>
  <pre><code>git clone  https://github.com/mariajose-dev/Bag-Genie-Online-Bag-Store.git</code></pre>
  <li>Run the application:</li>
  <pre><code>run flask</code></pre>
</ol>



---

<h2>📬 Contact</h2>
<p>
For queries or contributions, feel free to reach out via GitHub or the project maintainer.
</p>

---

<h3 align="center">⭐ If you find this project helpful, consider giving it a star!</h3>


