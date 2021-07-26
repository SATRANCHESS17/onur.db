# Onur.db
 
 tr: Onur.db ile kaliteli bir veritabanı modülüne sahip olabilirsiniz. Bu keyfi yaşamak bir tık ötenizde. Hemen indirin!
 en: You can have a quality database module with Onur.db. Experiencing this pleasure is just a click away. Download now!

## Örnek Kod / Sample Code

```js
const data = require("onur.db");
const db = new data();

// Veri ayarlama
// Set data
db.set("data", "1");

// Veriyi çekme
// Get data
db.get("data"); // Input: 1

// Veriyi silme
// Delete data
db.delete("data");

db.get("data"); // Input: undefined because we deleted the data
db.control("data"); // Input: false because we deleted the data

db.set("age", 15);
db.add("age", 3); // => 18
db.subtract("age", 5); // => 13 

db.set("list", [ "pear" ]);
db.push("list", "strawberry"); // [ "pear", "strawberry" ]

// Bütün verileri silme
// Delete all data 
db.alldelete();
```
 
Yapımcı: Onur <3

