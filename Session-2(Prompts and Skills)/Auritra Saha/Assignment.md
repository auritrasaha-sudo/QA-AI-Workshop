QA Manual Test Cases:-
Member :-Auritra Saha
Query/Test cases:- Demo Web Shop  (Write test cases based on your given
website)
Human Thinking Test Cases

TestCases_001:- User Registration with Invalid last name and Valid Data
Open Demo Web Shop website
Click on Register
Select Gender
Enter First Name
Leave Last Name blank
Enter Email Address
Enter Password
Enter Confirm Password
Click Register
Verify validation message for Last Name
Enter Last Name
Click Register
Verify registration success message

TestCases_002:- User Registration with Invalid password and Valid Data
Open Demo Web Shop website
Click on Register
Select Gender
Enter First Name
Enter Last Name 
Enter Email Address
Enter Password
Enter different Confirm Password
Click Register
Verify validation message for confirm password
Enter right passwordin confirm password
Click Register
Verify registration success message

TestCases_003:- User Registration with Invalid confirm password and Valid Data
Open Demo Web Shop website
Click on Register
Select Gender
Enter First Name
Enter Last Name 
Enter Email Address
keep Password blank
Enter Confirm Password
Click Register
Verify validation message for password
Enter password in password
Click Register
Verify registration success message

TestCases_004:- User Registration with Invalid email and Valid Data
Open Demo Web Shop website
Click on Register
Select Gender
Enter First Name
Enter Last Name 
Enter invalid Email Address
Enter Password 
Enter Confirm Password
Click Register
Verify validation message for email
Enter valid email 
Click Register
Verify registration success message

TestCases_005:- Login with Invalid Password then Successful Login
Open Demo Web Shop website
Click on Log in
Enter registered Email ID
Enter incorrect Password
Click Log in
Verify error message
Enter correct Password
Click Log in
Verify user is logged in successfully

TestCases_006:- Search Product and Add to Cart
Login to application
Enter "Laptop" in search box
Click Search
Verify search results are displayed
Open a product from results
Click Add to Cart
Open Shopping Cart
Verify selected product is present in cart

TestCases_007:- Add Multiple Products and Update Quantity
Login to application
Open Electronics category
Click on first category
Add first product to cart
Navigate to Books category
Add second product to cart
Open Shopping Cart
Change quantity of first product from 1 to 3
Click Update Cart
Verify cart total is recalculated correctly

TestCases_008:- Checkout with Empty Mandatory Fields
Login to application
Add a product to cart
Open Shopping Cart
Accept Terms of Service
Click Checkout
Leave Billing Address fields blank
Click Continue
Verify validation messages are displayed
Enter required details
Continue checkout process


AI Manual Test Cases:-
Member :-Auritra Saha

TestCases_001 – New Customer Completes First Purchase Successfully
Open the application home page.
Click Register.
Enter valid registration details including email and password.
Submit the registration form.
Verify registration success message is displayed.
Verify user is automatically logged in.
Browse multiple product categories.
Open a product detail page.
Verify product information, price, and availability are visible.
Add the product to cart.
Verify success notification is displayed.
Open shopping cart.
Verify correct product, quantity, and price are displayed.
Proceed to checkout.
Enter billing information.
Select shipping method.
Select payment method.
Review order summary.
Verify total amount is calculated correctly.
Confirm order.
Verify order confirmation page is displayed.
Verify order number is generated.
Navigate to Order History.
Verify newly placed order appears in order history.

TestCases_002 – Registration with Existing Email Address
Open the application.
Navigate to Register page.
Enter a previously registered email address.
Enter valid personal details.
Enter password and confirm password.
Submit registration form.
Verify registration request is processed.
Verify duplicate email validation message is displayed.
Verify account is not created.
Navigate to Login page.
Login using the existing account.
Verify login succeeds.
Verify only one account exists for that email.

TestCases_003 – Login with Invalid Credentials
Open Login page.
Enter valid email and incorrect password.
Click Login.
Verify authentication fails.
Verify error message is displayed.
Verify user remains on Login page.
Retry with another invalid password.
Verify system behavior remains consistent.
Refresh page.
Verify no user session is created.
Enter correct password.
Verify login succeeds.
Verify user account information is displayed.

TestCases_004 – Search, Compare, and Purchase Multiple Products
Login with valid account.
Search for a product using keyword.
Verify relevant search results appear.
Open first product.
Add product to comparison list.
Return to search results.
Open second product.
Add second product to comparison list.
Navigate to comparison page.
Verify both products are displayed.
Compare pricing and specifications.
Add both products to cart.
Open cart.
Verify both items are present.
Update quantity of one item.
Verify cart total recalculates correctly.
Proceed to checkout.
Complete checkout process.
Verify order confirmation is displayed.
Verify all purchased items appear in order details.

TestCases_005 – Customer Changes Mind During Checkout
Login to application.
Browse products.
Add multiple products to cart.
Open cart.
Verify products are listed correctly.
Proceed to checkout.
Complete billing details.
Reach order review page.
Return to cart.
Remove one product.
Verify cart updates correctly.
Verify order total is recalculated.
Increase quantity of remaining product.
Verify quantity update succeeds.
Resume checkout.
Review updated order summary.
Confirm order.
Verify order confirmation reflects modified cart.

TestCases_006 – Wishlist to Purchase Journey
Login to application.
Browse a category.
Open a product page.
Add product to wishlist.
Verify wishlist success notification appears.
Navigate to wishlist.
Verify product exists in wishlist.
Continue browsing.
Add another product to wishlist.
Verify both products appear in wishlist.
Move first product to cart.
Verify product is added to cart.
Verify wishlist updates correctly.
Move second product to cart.
Proceed to checkout.
Complete order placement.
Verify order confirmation page is displayed.
Verify wishlist no longer contains purchased items.

TestCases_007 – Invalid Checkout Data Validation
Login with valid account.
Add a product to cart.
Proceed to checkout.
Leave mandatory billing fields blank.
Attempt to continue.
Verify validation messages appear.
Enter invalid email format.
Verify email validation message appears.
Enter alphabetic values in numeric fields where applicable.
Verify validation prevents progression.
Correct some fields.
Leave one mandatory field empty.
Attempt checkout again.
Verify system identifies remaining invalid field.
Enter all valid information.
Continue checkout.
Verify checkout proceeds successfully.

TestCases_008 – Boundary Testing for Registration Fields
Open registration page.
Enter minimum valid values in all fields.
Submit form.
Verify registration succeeds.
Logout.
Register another account using maximum acceptable field lengths.
Submit form.
Verify registration succeeds.
Attempt registration with one character beyond maximum limit.
Submit form.
Verify validation message appears.
Verify account is not created.
Verify field length restrictions are enforced consistently.

TestCases_009 – Security Validation for Session Management
Login successfully.
Navigate through multiple account pages.
Logout.
Verify logout confirmation.
Use browser back button.
Verify account pages are inaccessible.
Copy account URL before logout.
Paste URL after logout.
Verify redirection to login page.
Login again.
Open account page in second tab.
Logout from first tab.
Refresh second tab.
Verify session is terminated.
Verify sensitive data is not exposed.

TestCases_010 – Order History and Account Management
Login using existing customer account.
Navigate to My Account.
Verify profile details are displayed correctly.
Update customer information.
Save changes.
Verify success message appears.
Navigate to Order History.
Open a previous order.
Verify order details match original purchase.
Verify product quantities are accurate.
Verify pricing information is correct.
Return to account page.
Change password.
Logout.
Attempt login using old password.
Verify login fails.
Login using new password.
Verify login succeeds.

TestCases_011 – Exploratory Shopping Journey
Login to application.
Browse categories randomly.
Open products in multiple tabs.
Add products from different categories to wishlist.
Compare selected products.
Add products to cart from comparison page.
Continue browsing before checkout.
Remove one item from cart.
Add a different item.
Apply any available discount or gift options if present.
Verify cart updates correctly.
Proceed through checkout.
Refresh browser during checkout.
Verify data persistence behavior.
Complete purchase.
Verify final order accuracy.

TestCases_012 – Usability and Data Consistency Journey
Open home page.
Verify navigation menus are understandable.
Search for a product using partial keyword.
Verify search results are relevant.
Open product page.
Verify product images load correctly.
Add product to wishlist.
Navigate using header links.
Verify wishlist count updates immediately.
Add product to cart.
Verify cart count updates correctly.
Open cart.
Verify totals match product prices.
Proceed to checkout.
Verify field labels are understandable.
Complete checkout.
Verify confirmation page clearly displays order information.
Verify order appears in order history.
Verify data remains consistent across all pages.

Your thoughts:-
What I felt Suitable
Human Test Cases
Easy to understand.
Good validation coverage for Registration.
Follow a realistic user workflow.
Clear expected verification points.
AI Test Cases
Better end-to-end business coverage.
Includes Wishlist, Order History, Security, Boundary Testing, and Usability.
Covers complete customer journeys.
More suitable for regression testing.

What I felt Not Suitable
Human Test Cases
Repetitive steps.
Not structured for automation.
Limited coverage of edge cases.
AI Test Cases
Some cases are too large and should be split.
A few exploratory/usability scenarios are difficult to automate.

Final Automation-Ready Test Cases
TC_001 – User Registration Validation
Precondition
User is not registered.
Steps
Open Registration page.
Leave Last Name blank.
Enter valid data in remaining fields.
Click Register.
Verify Last Name validation message.
Enter valid Last Name.
Click Register.
Expected Result
Validation appears for blank Last Name.
User registration succeeds after correction.

TC_002 – Password Confirmation Validation
Precondition
User is on Registration page.
Steps
Enter valid registration details.
Enter Password.
Enter different Confirm Password.
Click Register.
Verify mismatch validation.
Correct Confirm Password.
Click Register.
Expected Result
Validation message displayed.
Registration succeeds after correction.

TC_003 – Login Authentication
Precondition
Registered user exists.
Steps
Navigate to Login page.
Enter valid email.
Enter invalid password.
Click Login.
Verify error message.
Enter valid password.
Login again.
Expected Result
Login fails with invalid credentials.
Login succeeds with valid credentials.

TC_004 – Product Search and Cart
Precondition
User logged in.
Steps
Search product using keyword.
Verify search results.
Open product details.
Add product to cart.
Open cart.
Expected Result
Relevant products displayed.
Product successfully added to cart.

TC_005 – Wishlist to Purchase Flow
Precondition
User logged in.
Steps
Open product page.
Add product to wishlist.
Open wishlist.
Move product to cart.
Proceed to checkout.
Complete order.
Expected Result
Product moves from wishlist to cart.
Order placed successfully.

TC_006 – Cart Quantity Update
Precondition
Cart contains products.
Steps
Open cart.
Change quantity.
Click Update Cart.
Expected Result
Cart quantity updated.
Total recalculated correctly.

TC_007 – Checkout Validation
Precondition
Product available in cart.
Steps
Start checkout.
Leave mandatory fields blank.
Continue.
Verify validation messages.
Enter valid details.
Complete checkout.
Expected Result
Mandatory field validations displayed.
Checkout succeeds after correction.

TC_008 – Complete Purchase Journey
Precondition
New customer.
Steps
Register account.
Login.
Browse products.
Add item to cart.
Checkout.
Confirm order.
Expected Result
Order number generated.
Order visible in Order History.

TC_009 – Registration Boundary Testing
Steps
Enter minimum field lengths.
Register.
Enter maximum field lengths.
Register.
Enter values exceeding limits.
Expected Result
Min/max values accepted.
Exceeding values rejected.

TC_010 – Session Security Validation
Steps
Login.
Logout.
Use browser Back button.
Access saved account URL.
Expected Result
Protected pages inaccessible after logout.
User redirected to Login page.

TC_011 – Account Management
Steps
Login.
Update profile.
Save changes.
Change password.
Logout.
Login with old password.
Login with new password.
Expected Result
Profile updated successfully.
Old password invalid.
New password works.

TC_012 – End-to-End Regression Flow
Steps
Register user.
Login.
Search product.
Compare products.
Add to cart.
Update quantity.
Checkout.
Verify order history.
Expected Result
Entire purchase flow works without errors.
These 12 test cases are structured in a way that can be directly converted into Selenium + TestNG/Cucumber automation scripts with clear Preconditions, Steps, and Expected Results.


