# 刘森华

> [https://github.com/liusenhua](https://github.com/liusenhua)  
> [senhua.liu@gmail.com](mailto:senhua.liu@gmail.com)  
> (086) 13764449535  

------
### Profile
* 11+ years of full-time software development.
  - Pingan Bank (5 month): Elasticsearch plugin development, cluster operation, performance optomization and ES technical review.
  - Wanda(1+ years): Private Cloud PAAS platform early and now working on Feeds Recommendation system.
  - Autodesk(10 years): Full Stack Development.
* Focus on Elasticsearch, solid skills and rich experience on ELK
* Solid skills with full stack web development & architecture. Various experiences on backend, frontend, deployment.
* The experience on specific domain vertical Search/Recommendation system
* DevOps related skills, such as Docker, Kubernetes. Familiar with AWS.

------
### Skills

* **Language**: Java, Scala, Python, Bash/Linux, JavaScript, Go, C++
* **Framework**: Spring Boot, Play, Swagger, AngularJs, Bootstrap
* **Database & middleware**: MySQL, Redis, Couchbase, Elasticseach, Kibna, Hbase, Zookeeper, Kafka
* **Web Infrastructure**: AWS, Apache/Tomcat, Varnish, HAProxy
* **CI/CD**: Docker, Kubenetes, Jenkins

------

### Experience
* **Pingan Bank / Retailer & Technology Group / Big Data platform** *Architect* __2018/2 to present__
    Focus on Elasticsearch:
    1. Elasticsearch SQL plugin development:
      + Support query ES using standard SQL syntax
      + Extend ES SQL functions to do variou via Plainess language
      + SQL validation, caching, and limit big concurrent query
  
    2. Elasticsearch cluser operation and performance optomization
      + The metrics for single ES cluster: 200 millions records increment with 1 TB size per day, 2+ billions records with 20 TB size total
      + Solve the unstable problems, such as: Crash, No response, Long GC, etc.
      + Theb ig query issue: Aggregation among 2+ billions records with big cardinal number fields, the latency should be less than 10 seconds
  
    3. Technical review about Elasticsearch:
      + The best practice & convention for ES development, operation and maintenance
      + Technical support

* **Wanda / Internet Technology Group / Feeds & Ads platform** *Senior Developer* __2017/5 to 2018/1__  
    [www.ffan.com](http://www.ffan.com/new/index.html)  
    A personalized feeds recommendation system, similar as Twiter or JinRiTouTiao in China. It recommend the premium articles about Fashion/Tourism/Foods based on user profile and article's NLP features, which are crawled from internet. 

    Focusing on architecture and technical solution definition:
    + As team leader, design and develop the distributed crawler system, which is based on Kafka(message broker)/Hbase(to save crawled articles)/Webmagic (the crawler library), with 50k+ premium articles increment per day and 20+ source websites(Toutiao, Weixin, UC, Sina, Xiaohongshu, etc).
    
    + As core developer, design and implement the feeds recommendation system.
      - The offline article process pipeline (article clean & filter, NLP extracting, tagging, de-duple, etc)
      - The inverted index & recall system
     
    + Design and setup web infrasture: the Elasticsearch cluster(to store online article), the Redis cluster(the inverted index for article), ELK, Elastic job(the distributed job scheduling)

  **Technical Stack**: Java/Python, Spring boot, HBase, Redis, ELK, Kafka, Thrift, Machine learning/NLP

* **Wanda / Internet Technology Group / Cloud platform** *Senior Developer* __2016/10 to 2017/5__  
    [www.ffan.com](http://www.ffan.com/new/index.html)  
    Build the cloud PASS platform Web Console based on Docker and Kubernetes, make the CI & CD as a PASS service.
    1. As core developer, led a team to build a set of backend API from scratch to support CI & CD based on Kubernetes and Docker SDK. Focusing on architecture and technical solution definition, coding practice and modularizing components etc.
      + Based on Fabric8 k8s SDK, a group of APIs about service life cycle and resource management etc.
      + Customize Docker base images for various of appliation
    
    2. Coordinate the project feature scope and milestones with PM, lead the team to develop and deliver APIs in time.
    
  **Technical Stack**: Java, Spring boot, Docker, Kubernetes, Jenkins, MySQL

* **Autodesk - Homestyler & EZHome Platform** *Senior Developer* __2015 to 2016/10__ 
    [www.shejijia.com](http://www.shejijia.com/)  
    Build the O2O home platform for EZHome (one of the largest home retailers in China) by leveraging Autodesk cloud design service.

  + Design and implement the search/index service for catalog/product based on Elasticsearch. Support features: query & filter by various of criteria, full-text search, ranking by customized weights(retailer, brands), etc.<br>
  **Technical Stack**: Java/Scala, Play Framework, Elasticsearch, AWS SQS.

  + Deign and setup web infrastructure with high criteria to improves the stability and the reliability of system. Actions are: Setup service cluster with AWS ELB, Couchbase cluster cetup, Elasticsearch cluster setup, AWS VPC setup.<br>
  **Technical Stack**: AWS ELB/EC2/SQS, HAPoxy, Couchbase, Elasticsearch.

  + Design and lead to build a set of backend API services(Micro-service oriented) from scratch. Focusing on architecture and technical solution definition, coding practice and modularizing components etc.<br>
  **Technical Stack**: Java, Spring boot, Jersey, Swagger, AWS, Couchbase, MySQL 
  
  + Design and lead a team to implemented AngularJs based back office website for administrators and various message driven services for distributed computing -- model process, index update.<br>
  **Technical Stack**: Java/Scala, Javascript, AngularJS, Bootstrap CSS, Html5, AWS S3

  + Work closely together with Ops to set up the build and deployment system for backend, writing scripts for migration or ad hoc requirements.<br>
  **Technical Stack**: Bamboo, Python, Bash, Linux

* **Autodesk**  __2007 to 2014__

  - __2013 to 2014__ Autodesk Tinkercad 
      [www.tinkercad.com](https://www.tinkercad.com/)  
      A simple, browser-based 3D design/modeling and 3D printing app for all.
    + Designed and implemented the core mesh processing algorithms: imprint image on mesh surface, emboss text on mesh surface, mesh slicing, etc.
    + Implement REST APIs based on feature's requirements
    + Responsible for Tinkercad deployment.
    
    **Technical Stack**: Go, Javascript/NodeJs, Bash/Linux, SVG, clipper.js, tess2.js.

  - __2011 to 2013__ Autodesk 123D Family app   
      [www.123dapp.com](http://www.123dapp.com/)  
      A family of free online apps to design and modeling.
    + Setup the Web Infrastructure, design and implement CI & CD system.
    + Design and implement various of features from UI to modeling.
    
    **Technical Stack**: Java, Javascript, Python, Bamboo, AWS

  - __2007 to 2010__  Autodesk Sketchbook
    [www.sketchbook.com](https://www.sketchbook.com/)  
      A desktop 2D sketch&paint tool.
    + Implement various of brush painting, image processing features.
    + UI 
    
    **Technical Stack**: C++, QT

------

### Education

* 2002 to 2006: Bachelor of Huazhong Agricultural University(Computer & science)
