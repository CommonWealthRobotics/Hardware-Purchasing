#Hardware-Purchasing
Hardware Purchasing usable in mechanical design.

##Function
Purchasing Data are stored in  JSON files generated BowlerStudio. 


```JSON
{
"filename" : [
    { 
    "M3": {//Vitamin Size ID to reference to CAD
    "M3-Socket-Cap-Screw-5mm": { //vitamin specific variant ID (Internal Reference in Odoo)
      "variantParameters": {
        "Bolt Length": 5
      },
      "pricsUSD": {
        "1": 0.02
      },
      "urlAPI": "http://localhost:8069/",
      "db": "testdatabse",
      "serverType": "odoo",
      "cartURL": "http://localhost:8069/shop/product/m3-socket-cap-screw-73"
    }
    ]
}   
```
##License
MIT. See LICENSE.txt for details.
