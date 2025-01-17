# Marketplace Technical Foundation  

## Marketplace Name: E-Commerce  

 Workflow  

 Visual Diagram:  
```plaintext
Home Page --> View Products --> View Product Detail  
          \                    --> Add to Cart --> Proceed to Checkout --> Complete Profile/Payment Details  
           \-----------------------------------------------> Order Confirmed --> Track Shipment --> Delivery at Home
Flow Explanation:
User Sign-Up/Login: When a user visits the website, they must first sign up or log in.
Browse Home Page: Users can view the homepage featuring all products.
View Products and Details: Users can view product listings and individual product details.
Add to Cart: To purchase, users can add products to their cart.
Checkout Process: Proceed to checkout and fill in required payment and profile details.
Order Confirmation: Once payment is successful, the order is confirmed.
Track Shipment: Users can track their order using a shipment tracking ID.
Receive Delivery: The product is delivered to the user’s home.

API Endpoints
Endpoint	Method	Description
/products	GET	Fetch all products
/products/{id}	GET	Fetch a specific product
/order	POST	Create an order
/order/{id}	GET	Fetch a specific order
/shipment/{trackingId}	GET	Track shipment status

Technical Analysis
Frontend
Next.js: A modern framework for building dynamic and user-friendly UIs.
Tailwind CSS: Ensures a responsive and visually appealing design.
ShadCN UI: Utilized for creating reusable components.
Backend
Sanity CMS: A headless CMS used to meet frontend content requirements.
API
ShipEngine: API used for shipment tracking and delivery.
Tools
GitHub: For version control and collaborative development.
Vercel: For deploying the Next.js application.
System Architecture Diagram in pdf file.
