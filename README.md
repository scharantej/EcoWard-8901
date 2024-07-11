## Design for Python Flask Application

**HTML Files**

- `index.html`: Home page with hero section, featured products, and a brief about us.
- `shop.html`: Online shop page with product categories and filtering options.
- `about.html`: About Us page detailing the brand's mission and sustainable practices.
- `contact.html`: Contact Us page with a form and company information.
- `blog.html`: Blog section with 3-4 sample posts about sustainable fashion.

**Routes**

- `@app.route("/")`: Home page
- `@app.route("/shop")`: Online shop page
- `@app.route("/about")`: About Us page
- `@app.route("/contact")`: Contact Us page
- `@app.route("/blog")`: Blog page
- `@app.route("/product/<product_id>")`: Product detail page
- `@app.route("/cart")`: Shopping cart page
- `@app.route("/checkout")`: Checkout page