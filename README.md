# Agile Web Development with Rails 6 
# Part II — Building an Ecommece Application 'depot'
https://github.com/ingafter60/rails-depot-ecommerce

## 6. Task A: Creating the Application

	6.1. Iteration A1: Creating the Product Maintenance Application
		6.1.1 Creating a Rails Application
		6.1.2 Creating the Database: MySQL DB
        	modified:   README.md
        6.1.3 Generating the Scaffold
			> rails generate scaffold Product title:string description:text image_url:string price:decimal
	        modified:   README.md
	        new file:   app/assets/stylesheets/products.scss
	        new file:   app/assets/stylesheets/scaffolds.scss
	        new file:   app/controllers/products_controller.rb
	        new file:   app/helpers/products_helper.rb
	        new file:   app/models/product.rb
	        new file:   app/views/products/_form.html.erb
	        new file:   app/views/products/_product.json.jbuilder
	        new file:   app/views/products/edit.html.erb
	        new file:   app/views/products/index.html.erb
	        new file:   app/views/products/index.json.jbuilder
	        new file:   app/views/products/new.html.erb
	        new file:   app/views/products/show.html.erb
	        new file:   app/views/products/show.json.jbuilder
	        modified:   config/routes.rb
	        new file:   db/migrate/20201025134858_create_products.rb
	        new file:   test/controllers/products_controller_test.rb
	        new file:   test/fixtures/products.yml
	        new file:   test/models/product_test.rb
	        new file:   test/system/products_test.rb
        
2. Iteration A2: Making Prettier Listings

7. Task B: Validation and Unit Testing

1. Iteration B1: Validating! 87
2. Iteration B2: Unit Testing of Models 91

8. Task C: Catalog Display

1. Iteration C1: Creating the Catalog Listing
2. Iteration C2: Adding a Page Layout
3. Iteration C3: Using a Helper to Format the Price
4. Iteration C4: Functional Testing of Controllers
5. Iteration C5: Caching of Partial Results

9. Task D: Cart Creation

1. Iteration D1: Finding a Cart
2. Iteration D2: Connecting Products to Carts
3. Iteration D3: Adding a Button

10. Task E: A Smarter Cart

1. Iteration E1: Creating a Smarter Cart
2. Iteration E2: Handling Errors
3. Iteration E3: Finishing the Cart

11. Task F: Add a Dash of Ajax

1. Iteration F1: Moving the Cart
2. Iteration F2: Creating an Ajax-Based Cart
3. Iteration F3: Highlighting Changes
4. Iteration F4: Hiding an Empty Cart with a Custom Helper
5. Iteration F5: Broadcasting Updates with Action Cable

12. Task G: Check Out!

1. Iteration G1: Capturing an Order
2. Iteration G2: Atom Feeds

13. Task H: Entering Additional Payment Details

1. Iteration H1: Adding Fields Dynamically to a Form 
2. Iteration H2: Testing Our JavaScript Functionality 

14. Task I: Sending Emails and Processing Payments

1. Efficiently
2. Iteration I1: Sending Confirmation Emails
3. Iteration I2: Connecting to a Slow Payment Processor
4. with Active Job

15. Task J: Logging In

1. Iteration J1: Adding Users
2. Iteration J2: Authenticating Users
3. Iteration J3: Limiting Access
4. Iteration J4: Adding a Sidebar, More Administration

16. Task K: Internationalization

1. Iteration K1: Selecting the Locale
2. Iteration K2: Translating the Storefront
3. Iteration K3: Translating Checkout
4. Iteration K4: Adding a Locale Switcher

17. Task L: Receive Emails and Respond with Rich Text

1. Iteration L1: Receiving Support Emails with Action Mailbox
2. Iteration L2: Storing Support Requests from Our Mailbox
3. Iteration L3: Responding with Rich Text

Part III — Rails in Depth

18. Finding Your Way Around Rails

1. Where Things Go
2. Naming Conventions

19. Active Record

1. Defining Your Data
2. Locating and Traversing Records
3. Creating, Reading, Updating, and Deleting (CRUD)
4. Participating in the Monitoring Process
5. Transactions

20. Action Dispatch and Action Controller

1. Dispatching Requests to Controllers
2. Processing of Requests
3. Objects and Operations That Span Requests

21. Action View

1. Using Templates
2. Generating Forms
3. Processing Forms
4. Uploading Files to Rails Applications
5. Using Helpers
6. Reducing Maintenance with Layouts and Partials

22. Migrations

1. Creating and Running Migrations
2. Anatomy of a Migration
3. Managing Tables
4. Advanced Migrations
5. When Migrations Go Bad
6. Schema Manipulation Outside Migrations

23. Customizing and Extending Rails

1. Testing with RSpec
2. Creating HTML Templates with Slim
3. Serving CSS via Webpack
4. Customizing Rails in Other Ways
5. Where to Go from Here