---
layout: about
title: about
permalink: /
nav_order: 1

profile:
  align: right
  image: headshot.jpg
  image_circular: false # crops the image to make it circular

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a computer science researcher with an interest in making it easier for domain specialists to construct performant programs and take advantage of parallel and distributed systems. My approach to this problem has been the construction of domain specific languages, middleware, libraries, and tooling that abstract away the complexity of the underlying systems. The focus of this is not to chase the absolute peek of performance, but to make accessible the large performance improvements that exist beyond environments such as Python notebooks without requiring the user to tackle the associated complexity.

Most recently as part of Oracle Labs I initiated and lead the [Sandwood project](http://sandwood.org), developing a user-friendly probabilistic programming language, Sandwood that allows the construction of Bayesian models in a Java-like language. These models are then compiled to Java classes that can be integrated into products as discrete components. This project combined the user-friendliness of languages like Infer.net and PyMC, with robust and user friendly type checking of Java, and the performance of models that are compiled and optimised ahead of time. These models were used in projects ranging from anomaly detection in large systems, to predicting resource requirements for hospitals, and detecting organised crime in financial transactions.

Before the Sandwood project, I lead the Pandia project to predict program performance for NUMA systems. This formed part of Tim Harris's wider work on rack scale scheduling Technology from Pandia was included in the Smart Collections project allowing data structures to automatically change their underlying representations to suit the workload and system characteristics that they were being applied to.

Prior to joining Oracle I was part of the TeraFlux project at the University of Manchester, looking at programming models to make it easier for experts and non-experts alike to make use of the increasing parallelism in modern CPUs and GPUs. The Teraflux project aimed to combine course grained dataflow and transactional Memory. This allowed uses to write familiar single threaded code within each dataflow task, and use either read only state, or shared mutable state protected by transactions to communicate between tasks. This greatly simplified tracking of race conditions. I developed Nesoi, a tool providing type checking to track the require properties of memory, and ensure that all shared mutable state is accessed via transactions, and transactions are only used where shared mutable is used. In addition to Nesoi, I also developed Manchester University Transactions for Scala (MUTS) and a Scala based dataflow library, DFScala as parts of this project.

As a Research Associate and Junior Research Fellow at the Oxford e-Research Centre, Oxford University, and Pembroke College, Oxford University respectively. I was an early adopter of GPGPU compute investigating tooling and programming models for high performance computing on both single CPU/GPU systems and clusters of CPUs and GPUs. I developed memory visualisation tools to allow easier debugging of the more complex memory interactions in GPUs. In all cases this work was based on making high performance computing more accessible to application scientists in areas ranging from searching for pulsars in radio telescope data in real time, to medical imagery, to simulating the visual cortex.

I graduated from Oxford University in 2003 and was awarded the Hoare Prize for the highest 1st in Computer Science that year. I then started a doctorate working with ClimatePrediction.net looking at techniques for the analysis of large quantities of distributed data in a Grid environment. This resulted in the development of the Martlet workflow language. Building on ideas from dataflow and functional programming, Martlet abstracts from the user the distribution and partitioning of large data sets, allowing them to construct functions that would automatically adjust to the changing environment without the user having to be aware of the underlying topology. This work was well received with best student paper at UK e-Science AHM 2006 a nomination for best student paper at WWW2007 and the awarding of my doctorate in 2007.

Outside of work I am a keen scuba diver and an instructor. I take great pleasure in introducing people to diving and watching them grow into the sport. I have dived across the world, but my favourites are the spectacular underwater environments around the UK with the Farne Islands being a particular favourite.

My other interests include volunteering with heritage railway lines where I qualified as a fireman at the Llangollen Railway in North Wales, and flying gliders, something that has been harder to do since moving away from Oxfordshire, but I have maintained a keen interest in aviation. I also enjoy restoring old machinery, particularly early stationary engines. A particular draw to this type of equipment is all the innovative approaches that were taken by early engine designers to resolve problems before a best solution was settled on.
