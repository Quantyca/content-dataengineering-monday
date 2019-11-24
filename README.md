# Data Engineering Monday
TODO

Have something to add? suggest it in a PR! ;)

# 01 - DATA ENGINEER
Let's start this series with two great posts by  **Maxime Beauchemin**.

In  the first one Maxime  attempts to define data engineering and described how this new role relates to historical and modern roles in the data space. 

In the second one, reported in the comments, Maxime concentrates instead on the challenges and risks that cripple data engineers and enumerates the forces that work against this discipline as it goes through its adolescence.

## Links
- [Data engineering: A quick and simple definition](https://www.oreilly.com/ideas/data-engineering-a-quick-and-simple-definition)
- [The Rise of the Data Engineer](https://www.freecodecamp.org/news/the-rise-of-the-data-engineer-91be18f1e603/)
- [The Downfall of the Data Engineer](https://medium.com/@maximebeauchemin/the-downfall-of-the-data-engineer-5bfb701e5d6b)


# 02 - DATA ENGINEER vs DATA SCIENTIST
The two positions are not interchangeable—and misperceptions of their roles can hurt teams and compromise productivity. In this post **Jesse Anderson** describes the two different skill sets required by data engineers and data scientists.

## Links
- [Data engineers vs. data scientists](https://www.oreilly.com/ideas/data-engineers-vs-data-scientists)
- [Why a data scientist is not a data engineer](https://www.oreilly.com/ideas/why-a-data-scientist-is-not-a-data-engineer)
- [Data science is different now](https://www.snowflake.com/blog/snowflake-launches-kafka-connector/)

# 03 - DATA DICHOTOMY
Managing data inside services is very different from managing data outside of them. In the first case we want to hide data as much as possible in the second case we want to expose it as much as possible. These two opposite forces well described in this post by **Ben Stopford** causes a data dichotomy! 

Data-on-the-outside that is the natural working domain of data engineers has been managed so far in a tactical way when an integration or analytical problem arise. It's now time to make data-on-the outside a first class citizen of our IT Architectures if we want to really treat  data as an organizational asset and make it fungible! 

## Links
- [The Data Dichotomy: Rethinking the Way We Treat Data and Services (blog post)](https://www.confluent.io/blog/data-dichotomy-rethinking-the-way-we-treat-data-and-services/)
- [The Data Dichotomy: Rethinking the Way We Treat Data and Services (video)](https://www.youtube.com/watch?v=2Vo-aMOyqbw)


# 04 - DATA MESH
We introduced the concept of data dichotomy last week and stressed the importance of dealing with external data in a strategic way. OK, but how?

Surely data engineering practices have improved in recent years but not at the same speed as software engineering and software reliability engineering practices. Data integration is still one of the biggest pains in all organizations today. In this interesting post **Zhamak Dehghani** describes a new enterprise data architecture called data mesh that tries to solve some problems of current data platforms by adopting and applying the learnings of the past decade in building distributed architectures at scale to the domain of data.

## Links
- [How to Move Beyond a Monolithic Data Lake to a Distributed Data Mesh (blog post)](https://martinfowler.com/articles/data-monolith-to-mesh.html)
- [How to Move Beyond a Monolithic Data Lake to a Distributed Data Mesh (video)](https://fast.wistia.net/embed/iframe/vys2juvzc3?videoFoam)
- [Straining Your Data Lake Through A Data Mesh (podcast)](https://www.dataengineeringpodcast.com/zhamak-dehghani-data-mesh-episode-90/)

# 05 - FUNCTIONAL DATA ENGINEERING
All data engineers know how much  challenging is batch data processing. In this post **Maxime Beauchemin** explains how applying the functional programming paradigm to ETL can bring a lot of clarity to the process.  

This new functional approach to ETL better leverage modern distributed computation and storage systems respect to traditional data-warehousing literature, empowering larger teams to push the boundaries of what’s possible further by using reproducible and scalable practices.

## Links
- [Functional Data Engineering — a modern paradigm for batch data processing (blog post)](https://medium.com/@maximebeauchemin/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a)
- [Functional Data Engineering — a set of best practices (video)](https://www.youtube.com/watch?v=4Spo2QRTz1k)


