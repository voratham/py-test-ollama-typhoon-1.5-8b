# Learn Tutorial LLM local python connect ollama + scbx typhoon-1.5:8b model


## In case i used macos
```sh
brew install ollama
b
ollama serve # for start service
ollama pull kahnwong/typhoon-1.5:8b # pull model

python -m venv . # in case using virutal env
source ./bin/activate
pip install notebook
pip install -r requirements.txt 
```

## Preview result
```txt
product_name :: Koala Diary Koala Town Doll House - Furniture & Accessories : Room&Shop  🟢 category :: Furniture
product_name :: BE@RBRICK Karimoku Modern Furniture 400% 🟢 category :: Furniture
product_name :: Barbie Estate Outdoor Furniture Accessories เฟอร์นิเจอร์กลางแจ้งของตุ๊กตาบาร์บี้  🟢 category :: Outdoor
product_name :: Barbie Estate Outdoor Furniture Accessories เฟอร์นิเจอร์กลางแจ้งของตุ๊กตาบาร์บี้  🟢 category :: Outdoor
product_name :: BE@RBRICK Antique Furniture Model 1000％ 🟢 category :: Animal Furniture
product_name :: 2BF 2BF 30 Instruments and Furniture Stamps Brushes Set |PROCREAT BRUSHED| 🟢 category :: Other
product_name :: Green Dollhouse with Furniture 🟢 category :: Animal Furniture
product_name :: Barbie Furniture & Accessories เฟอร์นิเจอร์และอุปกรณ์เสริมสำหรับตุ๊กตาบาร์บี้  🟢 category :: Furniture
product_name :: 2018年7月21日発売予定 BE@RBRICK カリモク 400％ Modern Furniture 🟢 category :: Animal Furniture
product_name :: เคาน์เตอร์ แบรนด์ Mdec Furniture. 🟢 category :: Kitchen
product_name :: Furniture Cleaning Spray QMAX / น้ำยาเช็ดเครื่องใช้เฟอร์นิเจอร์ 🟢 category :: Furniture
product_name :: โซฟา 2 ที่นั่ง สีแดง Koncept​ Furniture​ 🟢 category :: Furniture
product_name :: Panton Wire - Chrome Cube by Montana Furniture 🟢 category :: Furniture
product_name :: ECF Furniture เก้าอี้ไม้วีเนียร์ รุ่น LAZIO 🟢 category :: Furniture
product_name :: pre-order • Modular furniture 🟢 category :: Furniture
product_name :: Wooden Furniture  Set G 🟢 category :: Furniture
product_name :: ECF FURNITURE เก้าอี้กินข้าว ผ้ากำมะหยี่  รุ่น Jolie 🟢 category :: Furniture
product_name :: ECF FURNITURE เก้าอี้กินข้าว ผ้ากำมะหยี่ รุ่น Victoria 🟢 category :: Furniture
product_name :: Full set Kids Wooden furniture Playroom Furniture ชุดเฟอร์นิเจอร์ไม้เด็ก 🟢 category :: Furniture
product_name :: BEEBS BREAKFAST FURNITURE POSTER 🟢 category :: Furniture
product_name :: Masking tape 'Furniture Party' 🟢 category :: Animal Furniture
product_name :: 🌈Premium Quality : ชุดโฮมเธียร์เตอร์ ALL&CO FURNITURE 🟢 category :: Furniture
product_name :: โต๊ะกลาง JACKSON แบรนด์ KONCEPT FURNITURE. 🟢 category :: Furniture
product_name :: ตู้ข้างเตียง W40xD35xH50cm.🌈มี5สี [สินค้ามีพร้อมส่ง] BROWN FURNITURE 🟢 category :: Furniture
product_name :: หนังสือปลอม L5-007 Furniture 🟢 category :: Furniture
product_name :: RECLINER 3 ที่นั่งไฟฟ้า แบรนด์SB Furniture. 🟢 category :: Furniture
product_name :: CUSTOMIZE PRODUCT FOR 50SHADES OF FURNITURE  🟢 category :: Furniture
product_name :: ชุดห้องนอน 6 ฟุต รุ่น Kuma (คูม่า) สีเทา | Livinghome Furniture Mall. 🟢 category :: Bedding
product_name :: เก้าอี้นั่งเล่นสไตล์มินิมอล รุ่น AB508 สีธรรมชาติ | Livinghome Furniture Mall. 🟢 category :: Furniture
product_name :: ชั้นเอนกประสงค์ ขนาด 85x40x190 ซม. สีวอลนัท | Livinghome Furniture Mall. 🟢 category :: Furniture
product_name :: น้ำยาเช็ดเบาะหนังรถยนต์ / เฟอร์หนัง งานไม้ (Furniture Cleaner) ทรีพลัส 🟢 category :: Furniture
product_name :: DELILAH cloud sofa 🟢 category :: Furniture
product_name :: โซฟาเบดผ้า Loder สีน้ำตาล 🟢 category :: Furniture
product_name :: ROMEO lazy sofa 🟢 category :: Furniture
product_name :: Egg Sofa Chair  🟢 category :: Furniture
product_name :: PETNITURE Yusu style pet bed - เพ็ทนิเจอร์ ที่นอนสัตว์เลี้ยง งานพรีเมี่ยม  🟢 category :: Animal Furniture
product_name :: Teander leaf - Foxtail Villa  (Furnitures included) 🟢 category :: Furniture
product_name :: Teander leaf - Cottontail Cottage(Furnitures included) 🟢 category :: Animal Furniture
product_name :: zeze Minimal Cat Furniture คอนโดแมว สไตล์มินิมอล ลายไม้ธรรมชาติ งาน handmade  🟢 category :: Animal Furniture
product_name :: CT101D043 ZEITAKUMS ชั้นวางรองเท้า ชั้นวางรองเท้าสีทอง Furniture Modern  🟢 category :: Furniture
product_name :: PETNITURE Yume pet bed - เพ็ทนิเจอร์ ที่นอนสัตว์เลี้ยงสไตล์ใหม่ งานพรีเมี่ยม  🟢 category :: Animal Furniture
product_name :: Mat PDM POLAR 🟢 category :: Furniture
```


- tutorial connect with model
https://medium.com/@mattanapol.k/%E0%B9%83%E0%B8%8A%E0%B9%89-ai-%E0%B8%8A%E0%B9%88%E0%B8%A7%E0%B8%A2%E0%B8%87%E0%B8%B2%E0%B8%99-ep3-%E0%B9%83%E0%B8%8A%E0%B9%89-langchain-x-ollama-%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-app-%E0%B8%8A%E0%B9%88%E0%B8%A7%E0%B8%A2%E0%B9%81%E0%B8%A2%E0%B8%81-category-%E0%B8%82%E0%B8%AD%E0%B8%87%E0%B8%AA%E0%B8%B4%E0%B8%99%E0%B8%84%E0%B9%89%E0%B8%B2-%E0%B8%88%E0%B8%B2%E0%B8%81%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%AA%E0%B8%B4%E0%B8%99%E0%B8%84%E0%B9%89%E0%B8%B2-ac07b583f07f

- tuorial setup python and llm
- - https://medium.com/@mattanapol.k/%E0%B9%83%E0%B8%8A%E0%B9%89-ai-%E0%B8%8A%E0%B9%88%E0%B8%A7%E0%B8%A2%E0%B8%87%E0%B8%B2%E0%B8%99-ep1-%E0%B9%80%E0%B8%A3%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B9%84%E0%B8%87%E0%B8%94%E0%B8%B5%E0%B8%AB%E0%B8%A5%E0%B8%B0-python-0cd4f5567d81
- - https://medium.com/@mattanapol.k/%E0%B9%83%E0%B8%8A%E0%B9%89-ai-%E0%B8%8A%E0%B9%88%E0%B8%A7%E0%B8%A2%E0%B8%87%E0%B8%B2%E0%B8%99-ep2-setup-local-llm-%EF%B8%8F-3d78e6a7aa00

- venv
https://stackpython.co/tutorial/python-virtual-enviroment-pipenv
