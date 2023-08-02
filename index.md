
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
|:----------------------|:----------|:--------------|:---|
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


```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

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
