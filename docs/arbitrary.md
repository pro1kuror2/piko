Произвольный тип

https://yandex.ru/support/partnermarket/export/vendor-model.html


Название	 			| 			Ограничение						| Псевдоним	
----------------------- | 			------------- 					|------------
|**type**				|			=vendor.model ,аттрибут			| спрятан в конструкторе
|**model**				|						-					| в конструкторе
|**vendor**				|						-					| в конструкторе
|vendorCode				|						-					|
|typePrefix				|						-					|
|						|											|
|**id** 					| Цифры и буквы, до 20 символов, аттрибут	| в конструкторе
|cbid 					| 			int, аттрибут					|
|bid 					| 			int, аттрибут					|
|fee 					| 			int, аттрибут					|
|available				|			boolean, аттрибут				|
|`url`					|				 длина <= 512				| 
|**price**				| 	int >= 0, boolean для from 				| в конструкторе 
|oldprice 				| 					int >= 0				|
|vat 					|						-					|
|**currencyId**			|						-					| в конструкторе
|**categoryId**			| 		целое, >0, не длиннее 18 зн.		| в конструкторе
|`picture`				| 	максимум 10 шт. Длина url <= 512 		| `pic()`
|delivery				|			boolean							|
|delivery-options		| не больше 5 шт, int и тирэ, и т.д.		| `dlvOption()`
|pickup					|					boolean					|
|store					|					boolean					|
|description			| 		длина <= 3000, возможен CDATA		|
|sales_notes			| 				длина <= 50					|  `sale()`
|min-quantity 			| 					int >= 1				| `minq()`
|step-quantity			| 					int >= 1				| `stepq()`
|manufacturer_warranty	|					boolean					| `warranty()`
|country_of_origin		|						-					| `origin()`
|adult					|					boolean					|
|barcode				| 			целое, 8, 12 или 13 цифр		|
|cpa					| 			boolean, 0 или 1 на выходе		|
|`param`				|						-					| 
|expiry					|						-					| 
|weight					| 					float , кг				|
|dimensions				| 		3 раза float, сантиметры			|
|downloadable			|					boolean					|
|age					| если year, то 0,6,12,16 или 18 <br> если month, то от 0 до 12| 
|rec					|						-					| 