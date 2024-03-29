# Data Engineering Monday
The following is a list of articles/blog posts/videos/podcast that we think are really important for data engineering practice. We have posted them each Monday for elevent weeks on [our linkedin page](https://www.linkedin.com/company/813697) with the hashtag #dataEngineeringMonday. What do you think? We have missed something important? Please suggest it in a PR! ;)


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

# 06 - DATA PIPELINE TEST
Pipeline debt is a species of technical debt that infests backend data systems. It drags down productivity and puts analytic integrity at risk. The best way to beat pipeline debt is a new twist on automated testing: pipeline tests, which are applied to data (instead of code) and at batch time (instead of compile or deploy time). This post describes the pipeline testing problem and introduces [Great Expectations](https://docs.greatexpectations.io/en/latest/), an open-source tool that make easy to perform and automate these kind of tests.


## Links
- [Down with Pipeline debt / Introducing Great Expectations (blog post)](https://medium.com/@expectgreatdata/down-with-pipeline-debt-introducing-great-expectations-862ddc46782a)
- [Pipeline testing with Great Expectations (video)](https://learning.oreilly.com/videos/strata-data-conference/9781492025955/9781492025955-video319102)

# 07 - DATA APPLICATIONS
A model based on the clear separation between pure tasks that produce and consume data assets in a deterministic and idempotent way and orchestration logic is increasingly becoming established in the development of ETL processes and ML pipeline. 

In this model builders can use the tool of their choice — e.g. Spark for data engineers, SQL for analysts, Python for data scientists — all while collaborating on the same logical data application. They do not have to abandon all their existing code or investments in those tools. 

In this blog post **Nick Schrock** describes [Dagster](https://dagster.readthedocs.io/en/0.6.4/),  an open-source library focused on  the orchestration of the graph of heterogeneous  transformation tasks that compose this new class of data applications. In particular he dive into the genesis of and inspiration for this project, the unique challenges of building data applications and the project’s roadmap.

## Links
- [Introducing Dagster - A open-source Python library for building data applications (blog post)](https://medium.com/dagster-io/introducing-dagster-dbd28442b2b7)
- [Dagster: A New Programming Model for Data Processing (video)](https://www.youtube.com/watch?v=D_1VJapCscc)
- [Build Maintainable And Testable Data Applications With Dagster (podcast)](https://www.dataengineeringpodcast.com/dagster-data-applications-episode-104/)


# 08 - DATA ENGINEERING TRENDS
The way data platforms are built and managed is changing fast. In this post **Chris Riccomini** describes four areas in particular where there will most likely be shifts over the next few years in the practice: Timeliness, Connectivity, Centralization and Automation.

## Links
- [The Future of Data Engineering](https://riccomini.name/future-data-engineering)

## 09 - DATA GRAVITY
In this post **Dave McCrory** introduce for the first time the idea that data has a mass and when begins to accumulate it generates a gravity field. accumulates, it begins to have gravity. This Data Gravity pulls services and applications closer to the data.  This attraction (gravitational force) is caused by the need for services and applications to have higher bandwidth and/or lower latency access to the data. The larger the mass the greater the attraction and consequently the concentration and complexity of the system.

## Links
- [Data Gravity – in the Clouds (blog post)](https://datagravitas.com/2010/12/07/data-gravity-in-the-clouds/)
- [Data Gravity and Complex Systems (video)](https://www.youtube.com/watch?v=nMo5V5JcdAU)

# 10 - DATA CENTRICITY
Legacy systems because of data gravity continue to get more and more entrenched while at the same time silos are becoming more numerous. The problem, at its core, is that we have allowed applications exclusive control over the data they manipulate. The remedy is to flip this on its head. Data is the center of the universe; applications are ephemeral. In this post **Nick Lazzaro** describe this paradigm shift towards Data-Centricity that is occurring in data management.

## Links
- [A Generational Shift Is Occurring In Data Management](https://www.forbes.com/sites/forbestechcouncil/2019/10/16/a-generational-shift-is-occurring-in-data-management/)
- [The data centric manifesto](http://datacentricmanifesto.org/)

# 11 - REAL TIME ETL
With the advent of the new data centric paradigm it becomes necessary to build data platforms that make data available to any application that needs to use them in a way that is flexible, scalable and maintainable in the long term. And with today’s technology, we can do so in real time, at scale. In this article, **Robin Moffatt** shows how to do this  in real time and at scale using a powerful design pattern based around event-driven architectures and an event streaming platform.

## Links
- [The Changing Face of ETL (blog post)](https://www.confluent.io/blog/changing-face-etl)
- [The Changing Face of ETL: Event-Driven Architectures for Data Engineers (video)](https://videos.confluent.io/watch/JPAnk3i2enPodLh5UhZ2Xf?)
