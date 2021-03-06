# Restaurant iOS App

# Description 
An iOS app which would allow users to place (& pay) order in a restaurant just by scanning a QR code. Integrates with Cloud Firestore to store user information and orders. Special focus on C.R.A.P principles for better UI.
 
# Build and Runtime Requirements

- Xcode 10.3 or later
- Swift 5
- iOS 8.0 or later

# Design Principles (C.R.A.P)

![43378304-059d4f7e-9394-11e8-85b8-7aefb9896e65](https://user-images.githubusercontent.com/49186141/103502969-06788a00-4ea7-11eb-9acd-23108f9e7da5.gif)

- Contrast: IInvolves making two different elements stand out, and it is usually used to draw a user’s attention to a specific element on that page. In the case of my app, a pop shows up when a button is clicked which blurs the background and draws the user's attention to the actions provided by the pop up

- Repetition: Involves using consistency across different screens for text, such that the user may become familiar with the interface and use less mental energy. Throughout the app I have carried a unified color scheme as well as font. This is to allow the user to get use to the app as well as providing some familiarity when using it.

- Alignment: Involves organizing information in a way that is ordered, structured and leads to a cohesive design. On the Menu detailpage, all the items and their types are left alligned which ensures a smoother and more intuitive user experience.


- Proximity: Involves elements that are related to each other, being placed closely together. This is a visual cue to the user if information is related to each other or not. In my application, all the relevant information regarding the resturant is clustered together closely at the top of the page, while menu items are placed on the bottom of the screen. 


# Features Completed
- Login and Sign Up View
- Integrating cloud firestore and storing user information there
- Giving access controls to users
- Allowing users with user type "resturant" to add items and saving them to the database
- Generating qr codes for each resturant and mailing them through a button click
- Allowing user to scan qr codes and displaying the menu


# Features In Progress
- Add to Cart
- Allowing the user to make an order and a payment
- A subscription fee
- Improving UI
- Correcting the constraints




