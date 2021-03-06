# Smart Communities Rising Up with Digital Twin: Transforming the interconnection between travelers, open data and city planners

The recently emerging trend of digital twin technology and high-performance
computing is creating a revolutionary paradigm shift in the coming years. For
smart city and community mobility applications, the pairing of the virtual and
physical world allows analysis of data and monitoring of systems, evaluating
different improvement strategies, and planning the future by using simulations.
A long-term goal of Smart Community Digital Twin (SCDT) is to create sustainable
urban systems that benefit the citizens and societies at large.

Our long-term goal of ASU Trans+AI lab aims to bring together experts from
academia, industry, municipalities, and nonprofit organizations from large and
small metropolitan areas to develop an Open data hub and Open-source simulation
framework for transportation-focused Open-SCDT applications. We hope to deliver
rapid prototyping of SCDT and enabling smarter multimodal policy decisions for
transforming the livability, sustainability, and resilience of community. A
successful SCDT in our project will enable both: (1) integration of a variety of
emerging technologies and practitioner expertise from community stakeholders;
and (2) integration of large-scale agent-based simulators of urban landscapes at
the city and regional scales. Designers and engineers can make use of our
integrated models for quick, inexpensive prototyping of new ideas, which further
provides potential for creating new forms of citizen engagement by communities,
and new approaches to city operations and management by city planners.

Please join us at smartcityplanning.slack.com to volunteer, or provide comments
to our ASU Trans+AI [team members](mailto:xzhou74@asu.edu).

# Web portal and open datasets for state-by-state multimodal transportation infrastructure data from OSM

>   To facilitate a better understanding of **multimodal transportation
>   infrastructure** in the U.S., our ASU team provides a web-based interface to
>   visualize multimodal transportation networks, state by state, for both rail
>   and highway modes. <https://asu-trans-ai-lab.github.io/web/index.html#/> You
>   can select either Bing or OSM as the base map. We also provide **open data
>   set of rail and highway networks** from
>   [\#OpenStreetMap](https://www.linkedin.com/feed/hashtag/?keywords=openstreetmap&highlightedUpdateUrns=urn%3Ali%3Aactivity%3A6783468501521756161),
>   in
>   [\#GMNS](https://www.linkedin.com/feed/hashtag/?keywords=gmns&highlightedUpdateUrns=urn%3Ali%3Aactivity%3A6783468501521756161)
>   format, at
>   <https://github.com/asu-trans-ai-lab/Integrated_modeling_GMNS/tree/main/examples/United_States_network>
>   . For system-level planning, detailed information, such as company ownership
>   capacity and commodity demand, is still needed for rail networks along this
>   line.

# Web portal for visualizing open standard GMNS files

By simply uploading node.csv and link.csv at
<https://asu-trans-ai-lab.github.io/index.html#/>, you can easily **create
custom** [online maps](https://en.wikipedia.org/wiki/Online_maps) **for any GMNS
network files**. You can also visualize POI.csv, agent.csv and demand.csv from
the grid2demand package.

![](media/b68219e7074c4f3c1d02c075072ef8d7.png)

Sample node and link files for the above Arizona State University campus can be
found at
[here](https://github.com/asu-trans-ai-lab/integrated_modeling_GMNS/tree/main/examples/university_campus/Arizona_State_University).
You can contribute your data set for other beautiful [university
campuses](https://github.com/asu-trans-ai-lab/integrated_modeling_GMNS/tree/main/examples/university_campus/Arizona_State_University).
If you are interested in large-scale network modeling, please fetch the
[state-by-state transportation network
data](https://github.com/asu-trans-ai-lab/integrated_modeling_GMNS/tree/main/examples/United_States_network/motorway/states)
in the United States, in four different layers (motorway, trunk, primary and
secondary roads). The network data are converted from Openstreet map to GMNS
format using the [OSM2GMNS](https://pypi.org/project/osm2gmns/) python package
our team develop.

![](media/114a123c1ced45c426e9a0464b553cd8.png)

Categories of OpenStreetMap road network: Source:
https://wiki.openstreetmap.org/wiki/Map_features

| Motorway  | A restricted access major divided highway, normally with 2 or more running lanes plus emergency hard shoulder. Equivalent to the Freeway, Autobahn, etc. |
|-----------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Trunk     | The most important roads in a country's system that aren't motorways. (Need not necessarily be a divided highway.)                                       |
| Primary   | The next most important roads in a country's system. (Often link larger towns.)                                                                          |
| Secondary | The next most important roads in a country's system. (Often link towns.)                                                                                 |

Our team is devoted to developing enterprise grade open-source tools for
transportation modeling, in a broader context of computational transportation
science. Please visit our website for integrated Analysis, Modeling and
Simulation ([AMS](https://github.com/asu-trans-ai-lab/integrated_modeling_GMNS))
and related [FHWA AMS data hub
effort](https://www.fhwa.dot.gov/publications/research/operations/13036/004.cfm).

![](media/e6c1394fc509f786c6342ca4849e6f25.png)

Using [ASU research computing
facility](https://cores.research.asu.edu/research-computing/about), we also
create an entire U.S. driving network from OpenStreetMap with 20 million nodes.
The multi-modal network of ASU Tempe Campus can be found
[here](https://github.com/asu-trans-ai-lab/GTFS2GMNS/tree/main/walk_and_bike/Tempe-bike)
([Walk](https://github.com/asu-trans-ai-lab/GTFS2GMNS/tree/main/walk_and_bike/Tempe-walk):
red;
[Bike](https://github.com/asu-trans-ai-lab/GTFS2GMNS/tree/main/walk_and_bike/Tempe-bike):
green)

![](media/5cdd93054fc2d27451b1bae8504ed49c.png)
