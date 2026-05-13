# API PLAN

## POST /api/orders/create

Create print order.

Request:

* file
* copies
* print_type
* page_size

Response:

* token
* status

---

## GET /api/orders

Get all orders.

---

## PATCH /api/orders/{id}

Update status.
