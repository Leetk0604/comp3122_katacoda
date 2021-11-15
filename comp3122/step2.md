#open browser in katacoda and try below comment 
#port 15000 /15001 /15002 /16000

Login
/login/<customer_id>/<password>

customers: /login/00001/1111
admin: /login/admin/admin
shops: /login/001/001


Customer view:
GET:
/customers 
/customers/<customer_id>

Create customer:
POST:
/customers

Edit customer:
PATCH:
/customers/<customer_id>

Delete customer:
DELETE:
/customers/<customer_id>/delete

Cart view
GET
/cart 
/cart/<customer_id>

Create cart:
POST:
/cart

Edit cart:
PATCH:
/cart/<customer_id>

Delete cart:
DELETE:
/cart/<customer_id>/delete

Shop view:
GET:
/shops
/shops/<shop_id>

Create shop:
POST:
/shop

Edit shop:
PATCH:
/shops/<shop_id>

Delete shop:
DELETE:
/shops/<shop_id>/delete

Menu view
GET
/menu 
/menu/<shop_id>

Create menu:
POST:
/menu

Edit menu:
PATCH:
/menu/<shop_id>

Delete menu:
DELETE:
/menu/<shop_id>/delete

Generate order:
GET:
/cart/<customer_id>/order

Get order:
GET:
/orders
/orders/<customer_id>

Delete order:
DELETE:
/orders/<customer_id>/delete

Finish order:
PATCH:
/finish_order/<customer_id>

Receipt view:
GET:
/receipts

