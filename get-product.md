**Get Product**
----

* **Root Url**
  https://api.styletribute.com
  
* **URL**

  - /product/path/:urlpath => Get product by Path
  - /product/sku/:sku => Get produt by Sku

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   - `urlpath=[string]` => by Path
   - `sku=[string]` => by Sku

* **Data Params**

  None

* **Success Response:**

  **Code:** 200 <br />
  **Content:** <br />
  ```
  {
	"id": "21190",
	"sku": "SVSGCL18202",
	"name": "Floral Petal Dress",
	"type": "VIP",
	"mageUrl": "https://styletribute.com/floral-petal-dress.html",
	"urlpath": "floral-petal-dress.html",
	"price": 145,
	"oldPrice": 610,
	"normalPrice": 145,
	"saleDiscount": 0,
	"condition": "EXCELLENT",
	"size": "US2",
	"sizing": "size",
	"styles": [
		"Spring-Summer"
	],
	"color": 1677,
	"manufacturer": 0,
	"colorValue": "Black Print",
	"status": 1,
	"designer": "DIANE VON FURSTENBERG",
	"description": ".",
	"shortDescription": "MATERIAL: 100% Silk<br />\r\nSIZE: US2<br />\r\nCONDITION: EXCELLENT",
	"largeImage": "catalog/product/5/e/edt-5e1c0b165e435e5efb48691854ba6b864f5c8ad9.JPG",
	"similar": [

	],
	"stylesort": 19021824,
	"allowOffers": true,
	"images": [
		"catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/5/e/edt-5e1c0b165e435e5efb48691854ba6b864f5c8ad9.JPG",
		"catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/2/e/edt-2e9ffed5e08ca1e050996d891fc22e321ff9f144.JPG",
		"catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/b/e/edt-be2f34d97597b3557eefb257c893fb35f8107fe6.JPG",
		"catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/e/8/edt-e832c619daaaffaa35548e7a83ca5db2ffc8a463.JPG",
		"catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/4/b/edt-4b2d8d51d5f4fa3129c6ff974da143165324673d.JPG",
		"catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/b/8/edt-b80aa60a9376643dde729ed571bd92fabda556bf.JPG"
	],
	"largeImages": [
		"catalog/product/cache/1/image/1800x1800/9df78eab33525d08d6e5fb8d27136e95/5/e/edt-5e1c0b165e435e5efb48691854ba6b864f5c8ad9.JPG",
		"catalog/product/cache/1/image/1800x1800/9df78eab33525d08d6e5fb8d27136e95/2/e/edt-2e9ffed5e08ca1e050996d891fc22e321ff9f144.JPG",
		"catalog/product/cache/1/image/1800x1800/9df78eab33525d08d6e5fb8d27136e95/b/e/edt-be2f34d97597b3557eefb257c893fb35f8107fe6.JPG",
		"catalog/product/cache/1/image/1800x1800/9df78eab33525d08d6e5fb8d27136e95/e/8/edt-e832c619daaaffaa35548e7a83ca5db2ffc8a463.JPG",
		"catalog/product/cache/1/image/1800x1800/9df78eab33525d08d6e5fb8d27136e95/4/b/edt-4b2d8d51d5f4fa3129c6ff974da143165324673d.JPG",
		"catalog/product/cache/1/image/1800x1800/9df78eab33525d08d6e5fb8d27136e95/b/8/edt-b80aa60a9376643dde729ed571bd92fabda556bf.JPG"
	],
	"imageData": [{
			"label": "Delete Mannequin",
			"path": "catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/5/e/edt-5e1c0b165e435e5efb48691854ba6b864f5c8ad9.JPG"
		},
		{
			"label": "front",
			"path": "catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/2/e/edt-2e9ffed5e08ca1e050996d891fc22e321ff9f144.JPG"
		},
		{
			"label": "back",
			"path": "catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/b/e/edt-be2f34d97597b3557eefb257c893fb35f8107fe6.JPG"
		},
		{
			"label": "side",
			"path": "catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/e/8/edt-e832c619daaaffaa35548e7a83ca5db2ffc8a463.JPG"
		},
		{
			"label": "Detail",
			"path": "catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/4/b/edt-4b2d8d51d5f4fa3129c6ff974da143165324673d.JPG"
		},
		{
			"label": "ruler 175",
			"path": "catalog/product/cache/1/image/620x/9df78eab33525d08d6e5fb8d27136e95/b/8/edt-b80aa60a9376643dde729ed571bd92fabda556bf.JPG"
		}
	],
	"products": [

	],
	"models": [

	]
}```

* **Success Response Description:**<br />
  **NOTE: Please only used attributes that is shown in below description**

<pre>
  <b>sku</b> => SKU of the product
  <b>name</b> => Product Name
  <b>urlpath</b> => Url Path of the product
  <b>price</b> => Price of the product
  <b>oldPrice</b> => MSRP (manufacturer's suggested retail price) price
  <b>saleDiscount</b> => Current sale of this product in our website
  <b>condition</b> => Our condition guideline which are
  <br/>
  - BRAND NEW (10 out of 10)	The item has never been worn or used and is as good as brand new.
  - EXCELLENT (8-9 out of 10)	The item has barely been used or worn and has minimal signs of usage.
  - VERY GOOD (7 out of 10)	The item has been used or worn and has some signs of wear but it still looks great.
  - GOOD (6 out of 10)	The item has been used or worn and shows moderate signs of wear but it still looks great.
  - GENTLY LOVED (5 out of 10)	The item has obvious signs of wear (hard scratches, stains). However, we have chosen to list the item       due to its special character.   
  <br/>
  <b>size</b> => Product size
  <b>sizing</b> => Product sizing can be either shoesize for shoe size or size for cloth size
  <b>styles</b> => Product styles
  <b>colorValue</b> => Product color
  <b>status</b> => Product status, either 1 for available or 0 for not available 
  <b>designer</b> => Product designer
  <b>description</b> => Product description
  <b>shortDescription</b> => Product summarized description
  <b>largeImages</b> => Product large images array, sorted respectively in reference as imageData below
  <b>imageData</b> => List of product images in the form of object below
  [
    {
      "label" => Product image label
      "path" => Product image url
    }
  ]
  <b>models</b> => Product models list
</pre>

* **Error Response:**

  **Code:** 400 BAD REQUEST <br />
  Happen when the urlpath given was invalid or sku was invalid

* **Getting Url Path:** <br />
  
  - Urlpath can be get from styletribute website, 
    - When we go to any product detail page as shown in image below
    ![alt text](https://raw.githubusercontent.com/StyleTributeIT/api-documentation/master/1.jpg)
    - The path shall normally looks like - https://styletribute.com/product/floral-petal-dress.html
    - Text after the "/product/" will be the urlpath, in this case is floral-petal-dress.html
  
  - Sku can be get from styletribute website as shown in image below
  ![alt text](https://raw.githubusercontent.com/StyleTributeIT/api-documentation/master/2.jpg)
  
* **Sample Call:** <br />
  **By path**
  ```javascript
    $.ajax({
      url: "https://api.styletribute.com/product/path/floral-petal-dress.html",
      dataType: "json",
      type : "GET",
      success : function(r) {
        console.log(r);
      }
    });
  ```
  
  **By sku**
  ```javascript
    $.ajax({
      url: "https://api.styletribute.com/product/sku/SVSGCL18202",
      dataType: "json",
      type : "GET",
      success : function(r) {
        console.log(r);
      }
    });
  ```
