# SearchEngineTamil
I am going to build a text corpus of metaphors in popular Tamil Songs from 2000 to 2020 of particular music directors. 
I have chosen Illayaraja , YuvanShankar raja and AR Rahman songs only. 
After creating my text corpus, I'm going to implement a search engine for those metaphors in the corpus.

Text corpus 

At Least 100 unique songs will be used to create the corpus. Each of the songs will be selected considering the presence of at least 1 metaphor. Attributes that are planned to be included (some more attributes will be added considering the path of the project):

Name         	:	Name of the tamil song 

Lyrics          	:	Tamil lyrics

Lyricist        	:	LYricist of the song

Album 	       	:	Movie name in which the song is featured. 

Year  	       	:	Movie released year

Metaphor    	:	Metaphors used in that song. At Least 1 metaphor for each

In addition to this a few attributes will be added  for each metaphor. Currently I am planning to include source domain, target domain, interpretation and type of metaphor. And the necessary data for the corpus will be scraped from the internet. Currently I am planning to use several web pages from the internet to obtain the data and build the corpus. Preprocessing will be done in appropriate places.


Scope and Usecase of the Search Engine

	Main scope of the project is to give the users an opportunity to understand more about the usage of the metaphors. Since metaphors are complex syntaxes of a language, users can understand the patterns from this system easily.They can discover more about the metaphors for the specified subject.  They can use our  search engine for finding  metaphors in Tamil songs by searching with the subject.They can use it to conduct searches based on the metaphor's source domain or target domain also.For now, I have selected  Apache Solr Framework  in the project which is designed to drive powerful document retrieval applications .
