# **[Red.db]** - Database Modülü

# Verileri JSON Halinde Tutan Kullanışlı Database Mödülü

 Kurulum:
```
const red = require("nego.db");
const db = new red("./red/Database.json");

//Veriyi Ekleme

`db.add("Value","Data");`

//Veriyi Silme

`db.delete("Value");`



//Veriyi Çekmek

`db.fetch("Value");`

//ÇIKTI => "Veri"

//Tüm Veriyi Çekmek
`db.fetchAll("Value");`

//ÇIKTI => "DATA"

//Veriyi YEDEKLEME
`db.backup("dosyaismi");`

//veriyi pushlatma

`db.push("array","data")`

```

Discord : [TIKLA](https://discord.gg/eQpQthhhPd)

