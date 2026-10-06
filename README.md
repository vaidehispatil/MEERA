# MEERA
# Meera – Online Jewellery E-Commerce Platform

## About the Project

Meera is a modern online jewellery e-commerce platform developed to provide customers with a smooth, elegant, and user-friendly online shopping experience.

The platform is designed to allow users to browse jewellery products, explore different collections, view product information, manage their shopping cart, provide customer and delivery details, apply discounts, select payment methods, review their order, and complete the checkout process.

The project focuses on creating a responsive and structured e-commerce interface while providing a complete checkout experience from customer information to final order placement.

## Live Website

[Visit Meera Website](YOUR_DEPLOYMENT_LINK)

## Project Objectives

The main objectives of the Meera project are:

- To develop a responsive online jewellery shopping platform.
- To provide an easy-to-use product browsing experience.
- To implement a structured shopping cart and checkout process.
- To collect and validate customer information.
- To provide billing and shipping address management.
- To calculate order totals including discounts, taxes, and shipping charges.
- To provide multiple payment options.
- To create a responsive interface suitable for different screen sizes.
- To provide a clear order review and order placement process.

## Key Features

### Product Browsing

Users can explore jewellery products and different product collections through a structured and user-friendly interface.

### Shopping Cart

The shopping cart allows users to manage selected products and review product quantities before proceeding to checkout.

### Customer Information

The checkout process includes customer contact information required for order processing.

### Billing and Shipping Address

Users can enter and manage their billing and shipping information during the checkout process.

### Delivery Method

Users can select the available delivery method for their order.

### Order Summary

The order summary provides a detailed breakdown of the purchase, including:

- Product details
- Product quantities
- Subtotal
- Discounts
- Taxes
- Shipping charges
- Final payable amount

### Coupon and Discount

The checkout process supports coupon and discount functionality, allowing applicable discounts to be reflected in the order total.

### Payment Methods

Users can select an available payment method before placing their order.

### Validation and Error Handling

Form validation and error handling are implemented to ensure that required information is provided correctly before proceeding with the order.

### Order Review

Users can review their customer information, delivery details, products, pricing, discounts, and payment information before placing the order.

### Place Order

After reviewing all required information, users can proceed with the Place Order functionality to complete the checkout process.

### Responsive Design

The interface is designed to work across different screen sizes, providing a consistent user experience on desktop, tablet, and mobile devices.

## Checkout Flow

The checkout process follows a structured flow:

1. Customer Information
2. Billing and Shipping Address
3. Delivery Method
4. Product and Quantity Details
5. Coupon and Discount
6. Order Summary
7. Payment Method
8. Order Review
9. Validation
10. Place Order

## Technologies Used

- React
- TypeScript
- Tailwind CSS

## Development

The project was developed using a component-based approach with React and TypeScript. Tailwind CSS was used to create a responsive and consistent user interface.

The checkout page was developed with separate sections for customer information, addresses, delivery options, order details, pricing, payment methods, validation, and order placement.

## Project Structure

The project is organized into reusable components to make the application easier to develop, maintain, and extend.

```text
Meera
├── Components
│   ├── Customer Information
│   ├── Billing and Shipping
│   ├── Delivery Method
│   ├── Product Details
│   ├── Order Summary
│   ├── Coupon and Discount
│   ├── Payment Methods
│   └── Order Review
│
├── Pages
│   ├── Home
│   ├── Products
│   ├── Cart
│   └── Checkout
│
└── Styling
    └── Tailwind CSS
