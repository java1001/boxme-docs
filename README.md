##############################################
API Boxme SDK 
##############################################

I. API Tạo Sản phẩm(Product):
=============================

API tạo thông tin sản phẩm: Tên sản phẩm, Category, Model, Giá, Hình ảnh sản phẩm, ....

1. Tạo sản phẩm:
----------------
**URL** ``http://dev.boxme.vn/api/product-sdk``

**Method** ``POST``

**Input Params**
 ``secret_key: Mã key bảo mật Boxme``
 
**Input Body**

```javascript
{
  "ExternalUrl": "",               //Link bài viết về sản phẩm			
  "BrandName": "",                 //Tên thương hiệu			
  "Description": "May hut mui",    //Mô tả về sản phẩm			
  "QuantityUnit": "1",             //Đơn vị tính 1 sản phẩm ( 1 : cái, 2 : hộp)			
  "BasePrice": 766000,             //Giá gốc của sản phẩm			
  "ManufactureBarcode": "",        //Mã barcode của nhà sản xuất			
  "Weight": 250,                   //Trọng lượng của sản phẩm			
  "WeightUnit": 1,                 //Đơn vị tính trọng lượng sản phẩm ( 1 : Gram 2 : Kg, 3 : Tạ, 4 : Tấn)			
  "Volume": "10x10x10",            //Thể tích sản phẩm (dài x rộng x cao)			
  "Name": "Haatz DSA-90S",         //Tên sản phẩm			
  "CategoryId": "332",             //ID danh mục sản phẩm			
  "CategoryName": "Máy hút mùi",   //Tên danh mục sản phẩm			
  "SupplierId": "29338",           //ID hãng sản xuất			
  "SupplierName": "Haatz",         //Tên hãng sản xuất			
  "ModelId": "432617",             //ID model sản phẩm			
  "ModelName": "Haatz DSA-90S",    //Tên model sản phẩm			
  "SellerSKU": "332432617",        //Mã sản phẩm			
  "Quantity": 2,                   //Số lượng sản phẩm			
  "SalePrice": 799000,             //Giá bán của sản phẩm			
  "InventoryId": 21,               //ID của kho hàng			
  "ProductTags": "haatz,rewq",     //Tag (nhãn sản phẩm) tag1,tag2,…			
  "ProductImages": ""              //Link hình sản phẩm	
}
 


	


