# FastTech-api

> CategoryID for e-cigarettes 3099

### Subcategories

> https://www.fasttech.net/support/ws/API.ashx?get=subcategories&CategoryID=3099

```JSON
{
   "d":{
      "Success":true,
      "Message":null,
      "ShortName":[
         "Atomizers",
         "Battery Cells",
         "Beauty Rings",
         "Cartomizers/Tanks",
         "Cartridges",
         "Cases/Bags",
         "Chargers/Adapters",
         "Clearomizers/Tanks",
         "Coil Heads",
         "Coil Jigs",
         "Disposables",
         "DIY Tools Kit",
         "Drip Tips - Aluminum",
         "Drip Tips - Brass",
         "Drip Tips - Ceramic",
         "Drip Tips - Copper",
         "Drip Tips - Glass",
         "Drip Tips - Hybrid",
         "Drip Tips - Others",
         "Drip Tips - PMMA",
         "Drip Tips - POM",
         "Drip Tips - SS",
         "E-Hookah \u0026 Supplies",
         "E-Liquid Bottles",
         "E-Liquids",
         "E-Solids",
         "Lanyards/Ring Clips",
         "Misc Accessories",
         "Mod Kits",
         "Mods - Hybrid",
         "Mods - Mechanical",
         "Mods - TC",
         "Mods - VV/VW",
         "Resistance Testers",
         "Stands/Holders",
         "Starter Kits",
         "Vaporizers",
         "Wax",
         "Wicks/Wires"
      ],
      "ExternalContentURLs":[null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null],
      "ID":[3028,3001,3002,3003,3008,3004,3005,3006,3007,3034,3012,3040,3013,3036,3014,3038,3015,3016,3017,3018,3037,3019,3035,3021,3009,3010,3022,3023,3024,3026,3027,3039,3032,3029,3030,3031,3020,3011,3033],
      "ParentID":null,
      "ProductCount":[8605,1845,52,144,71,2801,136,3657,1515,196,51,93,996,142,189,29,905,6158,2280,1460,883,1467,20,652,12190,29,200,8515,2734,147,3358,1151,2984,73,492,4026,330,0,2977]
   }
}
```

### Products (per page)
> https://www.fasttech.net/support/ws/API.ashx?get=products&CategoryID=(subcategorie)&API=1&SKU=0&PageIndex=(0..max)&SearchKeywords=&Filters=&SortOption=

```JSON
{
  "d":{
    "Success":true,
    "Message":null,
    "CategoryName":"Atomizers",
    "CategoryID":3028,
    "ResultsCount":8606,
    "PageSize":20,
    "CurrentPageIndex":0,
    "SearchKeywords":"",
    "Products":[],
    "Categories":null
  }
}
```

### Product

> https://www.fasttech.net/support/ws/API.ashx?get=products&CategoryID=-1&API=1&SKU=(SKU)&PageIndex=-1&SearchKeywords=&Filters=&SortOption=

```JSON
{  
  "d":{  
    "Success":true,
    "Message":null,
    "CategoryName":"6228800",
    "CategoryID":-1,
    "ResultsCount":1,
    "PageSize":20,
    "CurrentPageIndex":0,
    "SearchKeywords":"",
    "Products":[  
      {  
        "SKU":6228800,
        "ThumbnailURL":"//img.fasttechcdn.com/622/6228800/6228800-6-thumb.jpg",
        "Name":"SXK Hadaly Styled RDA Rebuildable Dripping Atomizer",
        "Tagline":"stainless steel / 22mm diameter",
        "OptionName":"22mm, SS, Silver (SXK)",
        "Price":14.9000,
        "IsSoldOut":false,
        "IsDiscontinued":false,
        "Descriptions":"\u003cul\u003e\n    \u003cli\u003eDelrin drip tip\u003c/li\u003e\n    \u003cli\u003eStainless Steel construction with PEEK insulation\u003c/li\u003e\n    \u003cli\u003ePrecision adjustable airflow with 4 points of contact for superior performance and flavor\u003c/li\u003e\n    \u003cli\u003eExtra deep well for more vaping and less dripping\u003c/li\u003e\n    \u003cli\u003eTwo-post style deck featuring innovative coil clamping system (CCS) for effortless coil installation and all vaping styles\u003c/li\u003e\n    \u003cli\u003e510 threading connection\u003c/li\u003e\n    \u003cli\u003e22mm overall diameter\u003c/li\u003e\n\u003c/ul\u003e",
        "Promotions":"The actual price is so fabulous we can\u0027t show it! \u003cbr /\u003e\nEnter coupon code MAP in the shopping cart page to see our unbeatable price.",
        "Warnings":null,
        "StockStatus":"Ships next day",
        "Specifications":"\u003cul\u003e\u003cli\u003e\u003cb\u003eProduct Type\u003c/b\u003e: RDA\u0027S \u003c/li\u003e\u003cli\u003e\u003cb\u003eCoil Rebuildable\u003c/b\u003e: Yes \u003c/li\u003e\u003cli\u003e\u003cb\u003eCoil Replaceable\u003c/b\u003e: No \u003c/li\u003e\u003cli\u003e\u003cb\u003eConnection Threading\u003c/b\u003e: 510 \u003c/li\u003e\u003cli\u003e\u003cb\u003eDrip Tip\u003c/b\u003e: Yes \u003c/li\u003e\u003cli\u003e\u003cb\u003eMaterial\u003c/b\u003e: Stainless Steel (minor parts may made by non-SS) \u003c/li\u003e\u003cli\u003e\u003cb\u003ePackage Contents\u003c/b\u003e: 1*RDA Atomizer, 3*Screws, 4*O-rings, 1*Slotted Screwdriver \u003c/li\u003e\u003cli\u003e\u003cb\u003eColor\u003c/b\u003e: Silver \u003c/li\u003e\u003cli\u003e\u003cb\u003ePackage Type\u003c/b\u003e: Plain \u003c/li\u003e\u003cli\u003e\u003cb\u003eProduct Weight\u003c/b\u003e: 24 g\u003c/li\u003e\u003cli\u003e\u003cb\u003eHeight\u003c/b\u003e: 31 mm\u003c/li\u003e\u003cli\u003e\u003cb\u003eWidth\u003c/b\u003e: 22 mm\u003c/li\u003e\u003cli\u003e\u003cb\u003eDepth\u003c/b\u003e: 22 mm\u003c/li\u003e\u003c/ul\u003e",
        "ProductRating":4.5274998,
        "ProductRatingSampleSize":80,
        "CategoryID":-1,
        "ThreadCount":18,
        "ThumbnailURLs":[  
          "//img.fasttechcdn.com/622/6228800/6228800-6-thumb.jpg",
          "//img.fasttechcdn.com/622/6228800/6228800-7-thumb.jpg",
          "//img.fasttechcdn.com/622/6228800/6228800-8-thumb.jpg",
          "//img.fasttechcdn.com/622/6228800/6228800-9-thumb.jpg",
          "//img.fasttechcdn.com/622/6228800/6228800-10-thumb.jpg"
        ],
        "ImageURLs":[  
          "//img.fasttechcdn.com/622/6228800/6228800-6.jpg",
          "//img.fasttechcdn.com/622/6228800/6228800-7.jpg",
          "//img.fasttechcdn.com/622/6228800/6228800-8.jpg",
          "//img.fasttechcdn.com/622/6228800/6228800-9.jpg",
          "//img.fasttechcdn.com/622/6228800/6228800-10.jpg"
        ],
        "OptionSKUs":null,
        "OptionNames":null,
        "RelatedProducts": []
      }
    ],
    "Categories":null
  }
}
```
