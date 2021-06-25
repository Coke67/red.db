**[Nego.db]**

Verileri JSON Halinde Tutan Kullanışlı Database Mödülü

Kurulum
```
const nego = require("nego.db");
const db = new nego("./services/Database.json");

//Veriyi Ekleme

db.add("Value","Data");

//Veriyi Silme

db.delete("Value");



//Veriyi Çekmek

db.fetch("Value");

//ÇIKTI => "Veri"

//Tüm Veriyi Çekmek
db.fetchAll("Value");

//ÇIKTI => "DATA"

//Veriyi YEDEKLEME
db.backup("dosyaismi");

//veriyi pushlatma

db.push("array","data")

```

Discord : [TIKLA](https://discord.gg/aNnEfTbhve)

