
# Target Websites

| Web app type          | Web name                      | URL                        |
|:----------------------|:------------------------------|:---------------------------|
|Accommodation	        |Agoda	                        |agoda.cn                    |
|Advertising	          |Doubleclick	                  |marketingplatform.google.com|
|Airlines	              |Ryanair	                      |ryanair.com                 |
|Banking	              |Chase	                        |chase.com                   |
|Beauty	                |Sephora	                      |sephora.com                 |
|Computer software	    |Openai	                        |openai.com                  |
|Distance learning	    |Stackoverflow	                |stackoverflow.com           |
|E-commerce	            |Onliner	                      |online.by                   |
|Eduction	              |Youtube	                      |youtube.com                 |
|Entertainment	        |Archive of our own	            |archiveofourown.org         |
|Fashion	              |Shein	                        |shein.com                   |
|Finance	              |Paypal	                        |paypal.com                  |
|Food and Beverages	    |All recipes	                  |allrecipes.com              |
|Games	                |Steam store	                  |store.steampowered.com      |
|Health	                |National Institutes of Health	|nih.gov                     |
|Information technology	|Wordpress	                    |wordpress.com               |
|Insurance	            |Robobank	                      |rabobank.nl                 |
|Investment	            |upstox	                        |upstox.com                  |
|Jobs	                  |ADP	                          |adp.com                     |
|Market research	      |Qualtrics	                    |qualtrics.com               |
|Music	                |Genius	                        |genius.com                  |
|News and Media	        |Wikipedia	                    |wikipedia.com               |
|Online services	      |Google	                        |cloud.google.com            |
|Real estate	          |redfin	                        |redfin.com                  |
|Restaurants	          |Uber eats	                    |ubereats.com                |
|Science	              |Sciencedirect	                |sciencedirect.com           |
|Sports	                |Marca                        	|marca.com                   |
|Telecom	              |Samsung                      	|samsung.com                 |
|Transportation	        |Usps	                          |usps.com                    |
|Travel and Tourism	    |Bahn	                          |bahn.de                     |
|Vehicles	              |Av.by	                        |cars.av.by                  |
|Wellness	              |Mayoclinic	                    |mayoclinic.org              |


The sample test scripts we use are put on [./SampleTests](./SampleTests)


## Offline Sequencer Results
| Web app type          |Offline generated sequences number| sampling sequence number|leagl sequence number|
|:---------------------:|-----------|---------------|----|
|Accommodation          |   74,030  |   382         | 0  |
|  Advertising          |   35,420  |   380         | 0  |    
|  Airlines             |  2,826,252|   384         | 0  |   
|  Banking              |   168,480 |   384         | 0  |  
|  Beauty               |   55,680  |   381         | 0  |  
|  Computer software    |   58,562  |   381         | 2  |   
|  Distance learning    |   23,440  |   377         | 1  |   
|  E-commerce           | 3,386,812 |   384         | 0  | 
|  Eduction             | 1,695,200 |   384         | 0  |   
|  Entertainment        |   162,150 |   383         | 0  |   
|  Fashion              |  1,617,000|   384         | 0  |  
|  Finance              |   37,352  |   380         | 1  |  
|  Food and Beverages   |   74,700  |   382         | 0  |   
|  Games                | 603,720   |   383         | 0  |  
|  Health               |   90,896  |   382         | 0  |  
| Information technology|   617,760 |   383         | 0  |   
|  Insurance            |   169,664 |   383         | 0  |  
|  Investment           |   304,128 |   383         | 0  |   
|  Jobs                 |   44,649  |   380         | 0  |   
|  Market research      |   26,895  |   378         | 1  |  
|  Music                |   41,040  |   380         | 0  |   
|  News and Media       |   509,184 |   383         | 0  |   
|  Online services      |   31,140  |   379         | 1  |   
|  Real estate          |   58,590  |   381         | 0  |   
|  Restaurants          |   110,700 |   382         | 1  |   
|  Science              |   536,130 |   383         | 0  |   
|  Sports               |   55,440  |   381         | 0  |   
|  Telecom              |   57,456  |   381         | 0  |   
|  Transportation       |   32,480  |   379         | 1  |  
|  Travel and Tourism   |   54,272  |   381         | 0  |   
|  Vehicles             |   78,064  |   382         | 0  |   
|  Wellness             |   25,984  |   378         | 0  |   



### Generated Sequences for 2 Online Sequencer

|web app type	|random deduplication<br>sequence number 	|random redundancy<br>sequence number	|coloring deduplication<br>sequence number|
|:----------------------|:----------|:--------------|:---|
|Accommodation	|66	|7	|63|
|Advertising	|296	|113	|372|
|Airlines	|92	|36	|109|
|Banking	|81	|53	|102|
|Beauty	|135	|14	|138|
|Computer software	|269	|34	|289|
|Distance learning	|65	|57	|93|
|E-commerce	|62	|29	|89|
|Education	|106	|77	|162|
|Entertainment	|274	|27	|341|
|Fashion	|194	|14	|197|
|Finance	|203	|23	|213|
|Food and Beverages	|224	|84	|289|
|Games	|50	|6 |52|
|Health	|36	|45	|74|
|Information technology	|13	|8	|20|
|Insurance	|269	|42	|292|
|Investment	|50	|8	|55|
|Jobs	|94	|24	|119|
|Market research	|152	|15	|161|
|Music	|68	|13	|81|
|News and Media	|234	|38	|236|
|Online services	|67	|19	|84|
|Real estate	|117	|15	|123|
|Restaurants	|89	|37	|125|
|Science	|31	|20	|42|
|Sports	|107	|17	|96|
|Telecom	|51	|12	|59|
|Transportation	|100	|14	|105|
|Travel and Tourism	|96	|39	|121|
|Vehicles	|71	|16	|85|
|Wellness	|38	|27	|52|




#### Generated sequences number of each experiment

|     web app  type      | strategy type | medium number | s1   | s2   | s3   | s4   | s5   |
| :--------------------: | ------------- | ------------- | ---- | ---- | ---- | ---- | ---- |
|     Accommodation      | random        | 66            | 48   | 66   | 70   | 65   | 78   |
|                        | coloring      | 63            | 57   | 74   | 63   | 62   | 75   |
|      Advertising       | random        | 296           | 296  | 332  | 276  | 324  | 262  |
|                        | coloring      | 372           | 359  | 378  | 273  | 374  | 372  |
|        Airlines        | random        | 92            | 47   | 97   | 92   | 95   | 64   |
|                        | coloring      | 109           | 48   | 116  | 109  | 113  | 86   |
|        Banking         | random        | 81            | 124  | 80   | 86   | 81   | 79   |
|                        | coloring      | 102           | 145  | 81   | 108  | 102  | 82   |
|         Beauty         | random        | 135           | 117  | 153  | 145  | 112  | 135  |
|                        | coloring      | 124           | 156  | 133  | 120  | 111  | 124  |
|   Computer software    | random        | 269           | 250  | 269  | 347  | 291  | 225  |
|                        | coloring      | 289           | 283  | 289  | 371  | 327  | 233  |
|   Distance learning    | random        | 65            | 138  | 44   | 68   | 62   | 65   |
|                        | coloring      | 93            | 173  | 75   | 107  | 70   | 93   |
|       E-commerce       | random        | 62            | 35   | 85   | 62   | 54   | 92   |
|                        | coloring      | 89            | 42   | 123  | 89   | 78   | 118  |
|        Eduction        | random        | 106           | 86   | 144  | 104  | 106  | 141  |
|                        | coloring      | 162           | 141  | 176  | 153  | 162  | 165  |
|     Entertainment      | random        | 274           | 38   | 274  | 308  | 368  | 243  |
|                        | coloring      | 341           | 45   | 343  | 341  | 383  | 316  |
|        Fashion         | random        | 194           | 402  | 194  | 116  | 137  | 228  |
|                        | coloring      | 197           | 484  | 197  | 119  | 142  | 238  |
|        Finance         | random        | 203           | 226  | 182  | 203  | 217  | 197  |
|                        | coloring      | 213           | 230  | 213  | 210  | 224  | 212  |
|   Food and Beverages   | random        | 224           | 108  | 224  | 248  | 218  | 267  |
|                        | coloring      | 289           | 115  | 289  | 301  | 287  | 335  |
|         Games          | random        | 57            | 50   | 57   | 58   | 43   | 57   |
|                        | coloring      | 52            | 52   | 62   | 52   | 48   | 53   |
|         Health         | random        | 36            | 47   | 36   | 35   | 36   | 37   |
|                        | coloring      | 74            | 83   | 74   | 74   | 74   | 74   |
| Information technology | random        | 13            | 14   | 13   | 10   | 13   | 16   |
|                        | coloring      | 20            | 20   | 20   | 21   | 20   | 24   |
|       Insurance        | random        | 269           | 467  | 216  | 269  | 187  | 284  |
|                        | coloring      | 292           | 551  | 279  | 292  | 229  | 317  |
|       Investment       | random        | 50            | 51   | 50   | 46   | 50   | 48   |
|                        | coloring      | 55            | 64   | 56   | 54   | 54   | 55   |
|          Jobs          | random        | 94            | 145  | 72   | 74   | 94   | 132  |
|                        | coloring      | 119           | 155  | 97   | 84   | 119  | 152  |
|    Market research     | random        | 133           | 214  | 152  | 178  | 107  | 133  |
|                        | coloring      | 161           | 348  | 121  | 211  | 126  | 161  |
|         Music          | random        | 68            | 68   | 77   | 67   | 76   | 67   |
|                        | coloring      | 81            | 83   | 81   | 73   | 87   | 72   |
|     News and Media     | random        | 234           | 234  | 213  | 223  | 261  | 264  |
|                        | coloring      | 236           | 236  | 218  | 224  | 266  | 269  |
|    Online services     | random        | 67            | 62   | 69   | 58   | 79   | 67   |
|                        | coloring      | 84            | 87   | 82   | 77   | 86   | 84   |
|      Real estate       | random        | 117           | 52   | 117  | 138  | 114  | 172  |
|                        | coloring      | 130           | 103  | 123  | 130  | 168  | 164  |
|      Restaurants       | random        | 87.5          | 89   | 70   | 97   | 86   | 93   |
|                        | coloring      | 114           | 125  | 82   | 134  | 114  | 107  |
|        Science         | random        | 31            | 95   | 25   | 31   | 27   | 33   |
|                        | coloring      | 42            | 114  | 41   | 42   | 41   | 54   |
|         Sports         | random        | 96            | 95   | 134  | 96   | 86   | 117  |
|                        | coloring      | 107           | 94   | 131  | 107  | 101  | 136  |
|        Telecom         | random        | 51            | 51   | 72   | 42   | 62   | 47   |
|                        | coloring      | 59            | 59   | 75   | 43   | 73   | 45   |
|     Transportation     | random        | 100           | 100  | 98   | 192  | 168  | 84   |
|                        | coloring      | 105           | 105  | 104  | 175  | 152  | 92   |
|   Travel and Tourism   | random        | 96            | 53   | 96   | 105  | 83   | 98   |
|                        | coloring      | 117           | 121  | 128  | 132  | 113  | 117  |
|        Vehicles        | random        | 71            | 71   | 95   | 62   | 70   | 97   |
|                        | coloring      | 85            | 77   | 90   | 85   | 81   | 95   |
|        Wellness        | random        | 38            | 27   | 38   | 46   | 41   | 37   |
|                        | coloring      | 52            | 25   | 52   | 52   | 52   | 52   |



##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
