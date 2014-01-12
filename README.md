geoJSON
=======
##このデータについて
このデータはOpenStreetMapのデータをカテゴリ別に抽出し、GeoJSON形式にしたものです。

##データの構造
※name要素があるものはproperties内に入っています。
    {
     "type": "FeatureCollection",
    "features": [
        {
            "type": "Feature",
            "properties": {},
            "geometry": {
                "type": "Point",
                "coordinates": [
                    139.631757,
                    35.8926583
                ]
            }
        },
        {
            "type": "Feature",
            "properties": {
                "name": "千葉駅前交番"
            },
            "geometry": {
                "type": "Point",
                "coordinates": [
                    140.1157961,
                    35.612906
                ]
            }
        }...中略...
        ]
        }
        
```
function test() {
  console.log("notice the blank line before this function?");
}
```

##ライセンス
Open Database License 1.0


