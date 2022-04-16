A store named ‘Viza’ needs a database for its products.

Business Rules:

1) The store sells three products: shoes, bags, and glasses.
2) Each product has a serial code, buying price, selling price, color, and quantity.
3) Bags and glasses are of different brands. (Shoes are of the same brand because they
are all Chinese)
4) Shoes are of different sizes.
5) More than one product can have the same serial code, and that’s because the store
deals with more than one merchant where each merchant has his own serial numbering,
and the store doesn’t have its unique serial numbering but uses that of the merchant.
6) Each merchant has a name, phone number, office address, and a company that he is
associated with.
7) Each shipment from a merchant has a date and a total price.
8) Each shipment consists of specific products with specific quantities.
9) The store pays each merchant in batches, where each batch has a date, paid amount,
and amount left for the merchant.

● Shipment’s total price will be a derived attribute (derived from the sum of the buying prices of the products in the shipment times their quantities)
● The batch’s left amount for the merchant will be a derived attribute (derived from the sum of the total prices of the merchant’s shipments minus the paid amounts for the merchant)
