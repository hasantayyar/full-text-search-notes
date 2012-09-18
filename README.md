Full-Text Search Engines Quick Look
======================
![cc](http://i.creativecommons.org/l/by-nc/3.0/88x31.png) 

[@htayyar](http://twitter.com/htayyar)


 - ELASTICSEARCH
 - SOLR & LUCENE
 - SPHINX
 - XAPIAN
 - SEARCHBLOX
 - WHOOSH


ELASTICSEARCH
============

**Languages Written In :** 
Java

**Meta Description :**
Elasticsearch aims to solve all these problems and more. It is an Open Source (Apache 2), Distributed, RESTful, Search Engine built on top of Apache Lucene.

**Website :**
http://www.elasticsearch.org/

**Installation :** http://www.elasticsearch.org/tutorials/2010/07/02/setting-up-elasticsearch-on-debian.html 
Macport veya apt-get ile kolay kurulum paketleri mevcuttur.

**Documentation & Community Links :**  
http://www.elasticsearch.org/tutorials/
http://www.elasticsearch.org/guide/ 
https://groups.google.com/forum/?fromgroups#!forum/elasticsearch 

**Notes :** ElasticSearch Solr ile cok benzer bir yapidadir ancak kullanim yontemlerine gore Solr’dan basarili oldugu iddia edilen yonleri vardir#. Tum islemleri HTTP Api’si uzerinden Json datalar ile gerceklestirmektedir. Datalar document based olarak saklanmaktadir. Search sonucu  id’ler degil dokumanlar verir.
Sphinx forumarinda yer alan su baslik oldukca ilgi cekici : ) http://sphinxsearch.com/forum/view.html?id=5118 



SOLR & LUCENE
============

**Language Written In :** 
Java

**Meta Description :** 
Solr is a standalone enterprise search server with a REST-like API. You put documents in it (called "indexing") via XML, JSON or binary over HTTP. You query it via HTTP GET and receive XML, JSON, or binary results.
**Website :** 

**Installation :** 
Documentation & Community Links :   



SPHINX 
============

**Language Written In :* 
C++

**Meta Description : **
Sphinx is an open source full text search server, designed from the ground up with performance, relevance (aka search quality), and integration simplicity in mind. It's written in C++ and works on Linux (RedHat, Ubuntu, etc), Windows, MacOS, Solaris, FreeBSD, and a few other systems.

**Website :**
 http://sphinxsearch.com/ 

**Installation :** 
Download and build binaries http://sphinxsearch.com/docs/2.0.4/installing.html 
Documentation & Community Links : 
http://sphinxsearch.com/community/ 
http://sphinxsearch.com/docs/ 

- Ozellikle ElasticSearch ve Solr’a gore indexer kullanimi rahat degil. Kendi icerinden ayrica index araclari geliyor ve dikkatlice hazirlanmasi gereken bir indexer ayar dosyasi vardir. Bu dosyada db sorgular, indexlenecek alanlar ve ozellikleri ile ilgili ayarlar yapiliyor. Indexing asamasindaki kendine has yapisi disinda indexleme hizi oldukca yuksektir. Sphinx arama sonucu olarak sadece id getirmektedir. ElasticSearch ve Solr’da (ve benzeri diger sistemlerde) arma sonucu olarak dokumanlar gelmektedir. Mysql ile kullanimi cok yaygindir ancak PostgreSQL ile de kullanilabiliyor. Stemmer eklenebiliyor http://sphinxsearch.com/docs/manual-0.9.8.html#conf-morphology 



XAPIAN
============

**Language Written In :** 
C++

**Meta Description :** Xapian is a highly adaptable toolkit which allows developers to easily add advanced indexing and search facilities to their own applications. It supports the Probabilistic Information Retrieval model and also supports a rich set of boolean query operators.

**Website :** 

**Installation :** 
Downoad binaries from http://xapian.org/download
Documentation & Community Links :  

- Testlerimde# indexleme hizi bahsedilen diger alternatiflerine gore fark edilir derecede yavasti. Ancak bu durum ozellikleri arasinda siralanan “hizli indexleme” maddesine uymuyor. Duzgun bir test ortaminda mutlaka tekrar denenmeli. 
Indexleme icin herhangi bir dil kolaylikla kullanilabiliyor.



SEARCHBLOX
============

**Language Written In :** Java

**Website :** 

**Installation :** 

**Documentation & Community Links :**



WHOOSH
============

**Language Written In :**
Python

**Meta Description :**
Whoosh is a fast, featureful full-text indexing and searching library implemented in pure Python. Programmers can use it to easily add search functionality to their applications and websites. Every part of how Whoosh works can be extended or replaced to meet your needs exactly. 

**Website :** 
https://bitbucket.org/mchaput/whoosh/wiki/Home

**Installation :**
 easy_install Whoosh
 
**Documentation & Community Links :**  
http://packages.python.org/Whoosh/

