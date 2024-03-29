- [Manage Inventory](../MAIN_MD/3_SQUAREMIND_ManageInventory.md) > Edit Product

<img src="https://github.com/HarleyGotardo/square-mind/assets/106173250/9964a8ed-8342-4f60-a536-2beef49b70c7" alt="Add Product" width="300"/>

# Edit Product
> This is used for editing a selected product from the inventory.

## Input:
  ● The user shall select the product from the inventory that he or she desires to alter and change the product's information.

## Process:
  ● The user shall tap a particular product.
  ● The user shall tap on the “Edit” button.
  ● The user shall alter the information of that specific product.

## Output:
  ● The system shall update the product information according to the changes.

______
>
# Data Dictionary
| Element ID | Element Text| Element Type | Data Type | Required? | Rules |
|------------|------------|------------|------------|------------|------------|
| HeaderTitle | Inverntory Status | Header | Text |..| Centered Text Alignment |  
| InventoryTable |..| Table |..| yes |  |  
| ProdID | Product ID | Text Field | Text | Yes | Must coorespond to a valid product |  
| ProdQuantity | Product Quantity | Text Field | Text | Yes | Must be a positive numner |  
| PordExpDate | Expiration Date | Text Field | Text | No |..|  
| ProdBarcode | Barcode | Barcode | Character | No |  |  
| PodCost | Product Cost | Currency | Number | No | Cost of the production |  
| ProdName | Product Name | Text Field | Text | Yes |..|  
| RemoveButton | Remove | Button |..|..| Removes selected product/s from inventory |  
| EditButton | Edit | Button |..|..| Edit the selected product |  
| Add Button | Add | Button |..|..| Add a product to inventory |  
| SearchEntry | Search | Text Field | Text | Yes | Allow users to search a product |  
