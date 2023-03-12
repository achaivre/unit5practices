# Purpose

You will be creating a order management system for an e-commerce site. It should allow you to create a customer, a product, and to create an order that attaches them.

Create three models that are connected to one another.

`Customer` should have the following fields:

- [ ] first_name
- [ ] last_name
- [ ] email
- [ ] and it should be connected to the Order class in some way with a relational field. (either here or with Order)

`Product` should have the following fields:

- [ ] name
- [ ] price
- [ ] type of product
- [ ] description

`Order` should have the following fields:

- [ ] date_field that auto adds current date.
- [ ] status (should allow the user to pick from a few different choices: RECEIVED, PENDING, and SHIPPED, it should default to RECEIVED)
- [ ] it should connect product class in some way with a relational field
- [ ] it should connect to customer class in some way with a relational field (either here or with Customer)

## Functions

- [ ] Create Customer function that is thoroughly tested.
- [ ] Create Product function that is thoroughly tested.
- [ ] Create Order function that is thoroughly tested.
- [ ] Search for Orders by Customer, which allows you to search for any order that is attached to specific customer. It should return a queryset/list of orders by that customer.
- [ ] Amount sold, should return an integer of the total amount of a given product sold given the product.
- [ ] Filter orders by status, this should allow the user to filter all orders by one of the three statuses given and return a list/queryset of all of the orders.
- [ ] Add a product to an order, this should allow the user to add another product to their order.
- [ ] Total Cost of an Order, should return the total amount due for a given order based on the product. It should take in an order.
