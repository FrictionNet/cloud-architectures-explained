# Cloud Architectures For Game Developers

> An introduction to modern cloud architectures for game developers

* Fundamentals
  * Domain Names
  * DNS & DNS Records
  * Transport Protocols
* What is Cloud Computing
  * Cloud Computing
  * Cloud Computing Architecture
  * Comparing Cloud Hosting & Traditional Hosting
    * Bare-metal Servers
    * Shared Hosting
    * Virtual Private Server (VPS)
    * Dedicated Servers
    * Cloud Hosting
    * On-Premises
    * https://www.upcloud.com/blog/cloud-server-vs-vps-vs-dedicated-server/
    * https://wp-rocket.me/blog/shared-vs-vps-vs-dedicated-vs-cloud-hosting/
    * https://www.rackspace.com/library/cloud-vs-dedicated
    * https://www.ibm.com/blogs/cloud-computing/2013/09/18/top-five-advantages-of-software-as-a-service-saas/
    * https://www.digitalocean.com/community/questions/vps-or-dedicated-server
  * Cloud Concepts Explained
    * Cloud Vendors
    * Pricing Calculators
    * Cloud Regions & Availability Zones
    * Images
    * Snapshots
    * HDD
    * SSD
    * https://cloud.google.com/compute/docs/regions-zones/global-regional-zonal-resources
    * https://docs.microsoft.com/en-us/azure/availability-zones/az-overview
    * https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html
    * https://cloud.google.com/compute/docs/regions-zones/
    * https://www.ibm.com/blogs/bluemix/2018/06/expansion-availability-zones-global-regions/
    * VM Platforms
    * Container build platforms
    * Container deployment platforms
    * Containers - https://jvns.ca/blog/2016/10/10/what-even-is-a-container/
    * Container Runtimes - https://www.ianlewis.org/en/container-runtimes-part-1-introduction-container-r
    * Microservices - http://microservices.io/
  * Comparing Service Architectures
    * On-premises
    * IaaS, Infrastructure as a Service
    * PaaS, Platform as a Service
    * SaaS, Software as a Service
    * CaaS, Containers as a Service
    * DBaaS, Database as a Service
    * FaaS, Functions as a Service / Serverless
    * MaaS, Monitoring as a Service
    * MBaaS, Mobile Backend as a Service
    * https://searchcloudcomputing.techtarget.com/definition/XaaS-anything-as-a-service
    * https://dzone.com/articles/iaas-vs-caas-vs-paas-vs-faas-choosing-the-right-platform
    * https://dzone.com/articles/an-introduction-to-the-types-of-cloud-computing?fromrel=true
    * https://dzone.com/articles/iaas-caas-paas-faas-how-do-you-choose?fromrel=true
    * https://dzone.com/articles/cloud-development-and-deployment-solutions-directo?fromrel=true
    * https://en.wikipedia.org/wiki/On-premises_software
  * Advantages of Cloud Computing - https://www.redpixie.com/blog/advantages-of-cloud-computing
  * SaaS, PaaS, IaaS & On-premises
  * Cloud Vendors
    * Public Cloud Services Comparison - http://comparecloud.in
    * Cloud Provider Directory - https://cloudharmony.com/directory
* Cloud Solutions
  * https://cloud.google.com/solutions/
  * https://azure.microsoft.com/en-us/solutions/
  * https://aws.amazon.com/solutions/
* Cloud Solutions for Gaming
  * https://cloud.google.com/solutions/gaming/
  * https://azure.microsoft.com/en-us/solutions/gaming/
  * https://aws.amazon.com/gaming/
* Cloud Marketplaces
  * https://aws.amazon.com/marketplace
  * https://azuremarketplace.microsoft.com/en-us/
  * https://cloud.google.com/launcher/
  * https://bitnami.com/stacks (downsides here: https://serverpilot.io/community/articles/bitnami-alternative.html)
* Cloud Deployment References
  * Heroku's 12-Factor App - https://12factor.net
  * Content Delivery Networks Best Practices - https://docs.microsoft.com/en-us/azure/architecture/best-practices/cdn
  * Architecture Styles - https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/index
  * Cloud Design Patterns - https://docs.microsoft.com/en-us/azure/architecture/patterns/
  * Pillars of Software Quality - https://docs.microsoft.com/en-us/azure/architecture/guide/pillars
  * Design Principles - https://docs.microsoft.com/en-us/azure/architecture/guide/design-principles/
  * Availability Checklist - https://docs.microsoft.com/en-us/azure/architecture/checklist/availability
  * Choose the right data store - https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-overview
  * Azure compute overview - https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-overview
* Cloud Reference Architectures, Explained
  * https://azure.microsoft.com/en-us/solutions/architecture/
  * https://aws.amazon.com/architecture/
  * https://gcp.solutions
  * https://medium.com/google-cloud/a-gcp-flowchart-a-day-2d57cc109401
  * https://medium.com/@grapesfrog/more-gcp-flowcharts-for-your-delectation-36b63ebb72ce
* Cloud Native Landscape
  * https://github.com/cncf/landscape
  * https://landscape.cncf.io/grouping=landscape
* Insightful Threads, Articles & Sites
  * https://news.ycombinator.com/item?id=8655435
  * https://news.ycombinator.com/item?id=8399767
  * https://www.reddit.com/r/gamedev/comments/1tvbe0/is_it_just_me_or_is_networking_really_hard/
  * Fast-paced Multiplayer - http://www.gabrielgambetta.com/client-server-game-architecture.html
  * Source Multiplayer Neetworking - https://developer.valvesoftware.com/wiki/Source_Multiplayer_Networking
  * Quake 3 Source Code Review - http://fabiensanglard.net/quake3/index.php
  * Unreal Networking Architecture - https://api.unrealengine.com/udk/Three/NetworkingOverview.html
  * Unreal Networking Model - http://thad.frogley.info/w/gfg08/gfg08.pdf
  * Short History of Game Networking Techniques - https://gafferongames.com/post/what_every_programmer_needs_to_know_about_game_networking/
  * The ups and downs of doing online multiplayer as an indie - https://www.gamasutra.com/view/feature/217434/the_ups_and_downs_of_doing_online_.php
  * Game Networking Techniques, Explained with Pong - http://drewblaisdell.com/writing/game-networking-techniques-explained-with-pong/
  * https://0fps.net/2014/02/10/replication-in-networked-games-overview-part-1/
  * https://0fps.net/2014/02/17/replication-in-networked-games-latency-part-2/
  * https://0fps.net/2014/02/26/replication-in-networked-games-spacetime-consistency-part-3/
  * https://0fps.net/2014/03/09/replication-in-network-games-bandwidth-part-4/
  * https://gafferongames.com/tags/networking/
  * https://eng.uber.com/trip-data-squeeze/
  * https://www.slideshare.net/AmazonWebServices/gam301migrating-the-league-of-legends-platform-into-aws-cloudpdf
  * https://www.compoundtheory.com/scaling-dedicated-game-servers-with-kubernetes-part-1-containerising-and-deploying/
  * https://rainbow6.ubisoft.com/siege/en-us/news/152-303559-16/dev-blog-ping-abuse-peekers-advantage-and-next-steps
  * https://cloudplatform.googleblog.com/2016/09/bringing-Pokemon-GO-to-life-on-Google-Cloud.html
  * https://forhonor.ubisoft.com/game/en-us/news-community/152-321584-16/input-delay-in-for-honor
  
#### References

* https://en.wikipedia.org/wiki/Cloud_computing_architecture
* http://www.opusinteractive.com/cloud-hosting-vs-traditional-hosting/
