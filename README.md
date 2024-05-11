#  **Jewelry Sales System At The Store** {#jewelry-sales-system-at-the-store .unnumbered}

Software Requirement Specification

# **1.Team Member:** {#team-member .unnumbered}

## Nguyễn Ngọc Quy SE171134

## Phan Phạm Hòa SE171730

## Huỳnh Thái Tài SE171320

## Trần Trọng Nhân SE171973

# **2.Requirement:** {#requirement .unnumbered}

## **2.1 Name of The System:** {#name-of-the-system .unnumbered}

### **Jewelry Sales System At The Store** {#jewelry-sales-system-at-the-store-1 .unnumbered}

### (Phần mềm bán hàng trang sức tại cửa hàng) {#phần-mềm-bán-hàng-trang-sức-tại-cửa-hàng .unnumbered}

## **2.2 Purpose of The System:** {#purpose-of-the-system .unnumbered}

### Creating a platform to support the staff to interact with customers easier.

## **2.3 Actor** {#actor .unnumbered}

  --------------------------------------------------------------------------
  **No.**   **Actor**      **Description**
  --------- -------------- -------------------------------------------------
  1         Admin          User who take responsible for managing managers

  2         Manager        User who take responsible for managing staffs

  3         Staff          User who interacting with customers
  --------------------------------------------------------------------------

## **2.4 List of Feature:** {#list-of-feature .unnumbered}

### **Admin** {#admin .unnumbered}

  ----------------------------------------------------------------------------
  **No.**   **Use case**         **Description**
  --------- -------------------- ---------------------------------------------
  1\.       Add Manager          Create a new account for manager role

  2\.       Update Manager Info  Edit manager information, enable/disable
                                 manager account

  3\.       Login                Log in into the system as an administrative
                                 role

  4\.       View Dashboard       View dashboard statistics in an interval of
                                 time
  ----------------------------------------------------------------------------

### **Manager** {#manager .unnumbered}

  ----------------------------------------------------------------------------
  **No.**   **Use case**         **Description**
  --------- -------------------- ---------------------------------------------
  1\.       Add Staff            Create a new account for manager role

  2\.       Update Staff Info    Edit staff information, enable/disable staff
                                 account

  3\.       Login                Log in into the system as a manager role

  4\.       Add Accessory        Add new accessory into product list

  5\.       Delete Accessory     Delete accessory in product list

  6\.       Update Accessory     Edit accessory info in product list

  7\.       View Product List    View list of product (name, price, stock)
                                 available in store

  8\.       View Product Info    View product's specified info such as name,
                                 price, stock, weight,\...

  9\.       View Counter Info    View the revenue and staff info of the
                                 counter under the management of the manager

  10\.      Display Accessory    Display accessory info on external screen
  ----------------------------------------------------------------------------

### **Staff** {#staff .unnumbered}

+----+-------------------+--------------------------------------------+
| *  | **Use case**      | **Description**                            |
| *N |                   |                                            |
| o. |                   |                                            |
| ** |                   |                                            |
+====+===================+============================================+
| 1  | Add Item          | Add a new item in the cart by scanning     |
| \. |                   | barcode or by inputting product code       |
|    |                   | directly                                   |
+----+-------------------+--------------------------------------------+
| 2  | Delete Item       | Remove item from the card                  |
| \. |                   |                                            |
+----+-------------------+--------------------------------------------+
| 3  | Update Cart       | Update item's quantity in the card         |
| \. |                   |                                            |
+----+-------------------+--------------------------------------------+
| 4  | Login             | Log in into the system as a staff role     |
| \. |                   |                                            |
+----+-------------------+--------------------------------------------+
| 5  | View Cart         | View the product in the cart and total     |
| \. |                   | price.                                     |
|    |                   |                                            |
|    |                   | -   ***Price of product*** = historical    |
|    |                   |     > cost \* gold price ratio.            |
|    |                   |                                            |
|    |                   | -   ***Historical cost*** = (Gold price at |
|    |                   |     > current time \* product weight) +    |
|    |                   |     > manufacture price + stone price.     |
+----+-------------------+--------------------------------------------+
| 6  | Print Receipt     | Print receipt for customer after payment   |
| \. |                   |                                            |
+----+-------------------+--------------------------------------------+
| 7  | Print Warranty    | Print warranty for each accessory that     |
| \. |                   | customers has purchased                    |
+----+-------------------+--------------------------------------------+
| 8  | Check out         | Confirm the payment and change the stock   |
| \. |                   |                                            |
+----+-------------------+--------------------------------------------+
| 9  | Refund            | Reclaim the product that customer had      |
| \. |                   | bought from the store before.              |
+----+-------------------+--------------------------------------------+
| 10 | View Product Info | View product information such as name,     |
| \. |                   | price, stock, weight,\...                  |
+----+-------------------+--------------------------------------------+
| 11 | View Order List   | View list of order                         |
| \. |                   |                                            |
+----+-------------------+--------------------------------------------+
| 12 | View Order Info   | View order's properties                    |
| \. |                   |                                            |
+----+-------------------+--------------------------------------------+
| 13 | Search Order      | Search order based on customer's phone     |
| \. |                   | number and order ID.                       |
+----+-------------------+--------------------------------------------+
| 14 | Update Order      | Edit order info (status, delivery date).   |
| \. |                   |                                            |
+----+-------------------+--------------------------------------------+

## **2.5 Statistics** {#statistics .unnumbered}

### **Dashboard Statistics**

#### Total Revenue.

### **Accessory Statistic**

#### Product Name.

-   Price.

-   Stock.

-   Weight.

-   Main Stone.

-   Sub Stone.

-   Number of Main Stone.

-   Number of Sub Stone.

-   Brand.

-   Cut.

-   Gender.

### **Staff/Manager Info**

-   Full Name.

-   Address.

-   Role.

-   Phone Number.

-   Email.

-   Date of Birth.

### **Order Info:**

-   Order ID.

-   Customer Name.

-   Phone Number.

-   Gender.

-   Delivery Address.

-   Payment Method.

-   Payment Status.(Paid/Unpaid)

-   Order Date Time.

-   Delivery Date Time.

-   Delivery Status.

-   List of purchased products.

```{=html}
<!-- -->
```
-   Name.

-   Quantity.

-   Price. (Individual Price \* Quantity)

```{=html}
<!-- -->
```
-   Delivery Cost. (Based on delivery policy)

-   Sale Promotion. (optional)

-   Total Cost. (Sum of Product's Price)

## **2.6 Order Management** {#order-management .unnumbered}

### **Order Process:**

#### **Create order at store:**

-   Step 1: Input Customer Information.

```{=html}
<!-- -->
```
-   Name.(Required)

-   Phone Number.(Required)

-   Gender.

```{=html}
<!-- -->
```
-   Step 2: Check out

```{=html}
<!-- -->
```
-   Choose payment method: cash, momo.

-   Issue company invoice.(optional)

-   Perform payment.

```{=html}
<!-- -->
```
-   Step 3 (Optional): Customers want to deliver to a specific address.

```{=html}
<!-- -->
```
-   Input delivery address.

#### **Create order through phone:**

-   Step 1: Check product stock.

```{=html}
<!-- -->
```
-   Step 2: Input Customer Information.

    -   Name.(Required)

    -   Phone Number.(Required)

    -   Gender.

```{=html}
<!-- -->
```
-   Step 3: Choose the receive method.

```{=html}
<!-- -->
```
-   Delivery.

-   At the store. (Choose branch address)

```{=html}
<!-- -->
```
-   Step 4: Delivery Method.

```{=html}
<!-- -->
```
-   Input delivery address

-   Note.(optional)

-   Issue company invoice.(optional)

```{=html}
<!-- -->
```
-   Step 4.5: At the store Method.

```{=html}
<!-- -->
```
-   Choose a city/province and district based on the given list.

-   Choose a branch.

-   If not any branch available on the location then show the statement
    > "No stores are available on this location."

-   Note.(optional)

-   Issue company invoice.(optional)

```{=html}
<!-- -->
```
-   Step 5: Check out. (Only delivery method)

```{=html}
<!-- -->
```
-   COD. (cash on delivery)

### **Note:**

-   Staff can only update Delivery Date and Order Status.

-   When Order Status changes to Finished Delivery, payment method must
    > update to Paid.

## **2.7 Delivery Management** {#delivery-management .unnumbered}

### **There are 5 stages of product delivery process:**

-   Stage 1: Contact Delivery Unit.

-   Stage 2: Prepare Product.

-   Stage 3: Transfer Product To Delivery Unit.

-   Stage 4: Deliver Product.

-   Stage 5: Finished Delivery.

-   Stage 5.5: Delivered Failed.

```{=html}
<!-- -->
```
-   If stage 4 fails, the product will be restocked and the order will
    > be changed to "Delivered Failed" status.

## **2.8. Staff Management** {#staff-management .unnumbered}

-   1 manager manages 3 counters.

# **3.Policy:** {#policy .unnumbered}

## **3.1 Points Policy** {#points-policy .unnumbered}

-   The payment will be turned into points, with every 10 million vnd =
    > 1 point.

-   Points can be used in various activities such as discounts.

-   The point will be printed within the receipt in a form of code.
    > (User will input the code into their account gift code feature or
    > in web gift code page)

## **3.2 Discount Policy** {#discount-policy .unnumbered}

-   1 point = 100.000 vnd discount

### **Discount = Discount during promotion (optional) + Discount policy (optional)**

**Note:** For customers who can be affected by discount policy need
approval of the manager before applying the discount into invoice.

## **3.2 Purchasing Policy** {#purchasing-policy .unnumbered}

-   For women's accessory + normal stone, Shop will only buy the real
    > gold part.

-   Reclaim the jewels which customers had bought with 70% sold price.

-   The gold price will be based on a real-time price chart.

## **3.3 Warranty Policy** {#warranty-policy .unnumbered}

-   Every accessory can be returned to the shop within 7 days under
    > these condition:

```{=html}
<!-- -->
```
-   The accessory must remain intact and not have any sign of being
    > used.

```{=html}
<!-- -->
```
-   Return procedure:

```{=html}
<!-- -->
```
-   Step 1: Contact the staff to request returning product. (To
    > facilitate the process, customer should provide warranty of the
    > returning product)

-   Step 2: We will check the product's warranty and product's integrity
    > then respond to the customer.

-   Step 3: We will perform a refund/replace procedure. (100% sold
    > price)

## **3.4 Delivery Policy** {#delivery-policy .unnumbered}

+----------------+--------------------------+-------------------------+
| **Distance**   | **Expected Delivery      | **Delivery Charge**     |
|                | Time**                   |                         |
+================+==========================+=========================+
| Below 20 km in | Same day or next day     | First 2 km: 18.000 VND  |
| HCM            |                          |                         |
|                |                          | Above 2 km: 5.000 VND/  |
|                |                          | km                      |
+----------------+--------------------------+-------------------------+
| Below 20 km in | From 1-3 days            | First 2 km: 20.000 VND  |
| other          |                          |                         |
| locations      |                          | Above 2 km: 5.000 VND/  |
|                |                          | km                      |
+----------------+--------------------------+-------------------------+
| Above 20 km    | From 2-7 days            | 5.000 VND/km            |
+----------------+--------------------------+-------------------------+

-   The distance calculated from the nearest store branch where the
    > product is available.

-   Time may vary depending on the location.

-   In case the order costs above 20 million VND, delivery charge will
    > be free but customers need to pay in deposit.

  ---------------------------------------------------
  **Order Cost**                    **Deposit Rule**
  --------------------------------- -----------------
  Between 20 million VND - 50       30%
  million VND                       

  From 50 million VND - 100 million 50%
  VND                               

  Above 100 million VND             70%
  ---------------------------------------------------

-   If customers have any complaints in any processes, please call the
    > number 1800 XX XX XX in time between 08:00 to 21:00 (holiday
    > included).

-   Time solving the complaints will be from 2-7 working days.
