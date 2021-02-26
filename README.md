# CS-360 Final Project

This application is a tool to manage inventory for a store or warehouse that runs on Android. The requirements of this project were to build an Android application with the following features:

1. User login
2. Adding and removing products from inventory
3. Increasing and decreasing the number of each product in stock
4. Ability to enable SMS notifications when the stock of a certain product goes below a certain threshold

There are 3 screens: a login/register form, main product display grid, and settings menu. More screens would be a nice-to-have but only three were needed for the MVP. 

The process of building the app started with implementing the login screen, followed by the database and CRUD operations on the single resource, product, then connecting those operations to user actions, and finally, the settings and permissions.

Ideally there would have been unit tests for this app to ensure proper functionality, but due to time constraints, unit tests were not included. Testing of the app was done manually on a physical Android device. Physical testing should be done on multiple devices, especially ones with different screen sizes and pixel densities in order to make sure the layout appears correct on each device.

A fair bit of innovation was required in order to get the product grid to display items from the database properly, as there wasn't a single straightforward way to accomplish that.

I was most successful with implementing CRUD operations on products in the database, and displaying them on a grid dynamically, without having to repeat any code. Many other parts of the app were a significant challenge and thus were not fully implemented.
