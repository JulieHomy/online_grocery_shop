# online_grocery_shop
Online shop built using Node.js, Express, and MongoDB/Mongoose. The user can create an account, reset their password, add and remove cart items, upload and delete products, update data for products they added, checkout their cart, place orders, and view past orders.

It follows the MVC design pattern, and renders views on the server using the EJS templating engine. The SendGrid API is used to send emails (confirmation of account creation and password reset instructions) and payments are handled using the Stripe API. Other features include pagination, error handling, validation of user input, sessions, authentication, and file storage.
