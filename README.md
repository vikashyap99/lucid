

# Inventory Management Web App Documentation

### Deploy Link: [https://lucid-vikash.netlify.app/](url)

## Overview
  The Inventory Management Web App is a simple application that allows users to view a list of products and manage the inventory. The app has two views: Admin and User. Admins can     edit, delete, and disable products, while users can only view the products without any editing capabilities. The application leverages a RESTful API to fetch the inventory data and updates the UI dynamically.

## Technology Stack

### Frontend: ` Framework: React with JavaScript`
### Styling: ` CSS, and design library like Material UI`

## Features

### Admin View:
Edit product details (price and quantity)
Delete products from the inventory
Disable products, which prevents them from being edited or deleted

### User View:
View products without any editing capabilities

## Widgets:
Display total number of products
Calculate and display total store value
Display number of out-of-stock products
Display number of product categories

## Guidelines
Make an API call to fetch the inventory data.
Calculate and display key metrics in widgets.
Update the product list and widgets dynamically based on user actions.
Handle all updates locally as there's no API for updating inventory.

###API
Endpoint: https://dev-0tf0hinghgjl39z.api.raw-labs.com/inventory
Method: GET
