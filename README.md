# これまでに作成されてきたデータ、オントロジー

## 主語, 動詞, 目的語の3つ組データ（まだらの紐）: 東京都市大学 勝島修平さん作成
* http://challenge.knowledge-graph.jp/submissions/2019/katsushima/knowledge_graph_data.xlsx

```
Holmes,come,coach	
Holmes,come,garden_of_Roylott	
Julia,come,bedroom_of_Helen	
```

## Wikidata を用いたオントロジー
* https://github.com/takanori-ugai/KGRCOntology
```
<http://kgc.knowledge-graph.jp/data/SpeckledBand/fear> a fjs:basic_emotion .
fjs:basic_emotion  rdfs:label "basic emotion"@en .
fjs:basic_emotion  a rdfs:Class .
fjs:basic_emotion  rdfs:seeAlso <http://www.wikidata.org/entity/Q16748867> .
fjs:basic_emotion rdfs:subClassOf fjs:emotion .
fjs:emotion a rdfs:Class .
fjs:emotion rdfs:label "emotion"@en .
```
```
<http://kgc.knowledge-graph.jp/data/SpeckledBand/bed>  rdfs:subClassOf fjs:furniture .
fjs:furniture a rdfs:Class .
fjs:furniture rdfs:label "furniture"@en .
<http://kgc.knowledge-graph.jp/data/SpeckledBand/bed>  rdfs:subClassOf fjs:sleeping_place .
fjs:sleeping_place a rdfs:Class .
fjs:sleeping_place rdfs:label "sleeping place"@en .
```
