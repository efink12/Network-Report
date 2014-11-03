Network-Report
==============

  Social networking is re-defining the nature of relationships and how people interact with each other. The analysis of these social networks helps to understand these relationships and how being connected to others impacts the user. While analyzing my social networking graph, I’ve found distinct relationships and patterns between my friends on Facebook.  
  When I initially imported the .gdp file I obtained through the program Netvizz on my Facebook page, the graph was a solid cluster of nodes and edges. There was no way to analyze my data because it wasn’t legible at all. After narrowing down my number of nodes using the degree range filter, I started to manipulate my graph to better analyze its data.  First, I went into the layout section, and chose ForceLayout2. This separated my nodes and brought them into more obvious clusters. I turned my labels on, so I knew which nodes represented which friends. Next, I went into the partition tab and chose modularity class; this is what color-coded the clusters in my graph. In order to see which nodes have more influence, I went in the network overview drop down menu and selected average degree. This changed the size of the nodes depending on the influence that node carries. At this point my graph was legible and color coordinated, I just needed to manually move a few nodes to make sure that all edges and vertices were clearly shown, and that each label could be clearly read. 
Each node represents a person within the social network. Each edge represents the relationship between two people. For example, in this graph, Scott Huddle and Mike Cieslak are two people within the social network (nodes) and the line connecting them (edge) represents their relationship. The size of the nodes are relative to the influence that node has. Influence is quantified by how many edges the node has coming in and going out. Larger nodes can make a greater impression on the network, because they have more access to other nodes through these edges. 
  Bonding occurs when edges create networks in a homogenous group, also called clusters. In my social network, you can define clusters by their color. There is a green cluster, and a pink cluster, telling the analyst that these groups of people are separated in some way. An example of bonding would be Erin Edson is connected to Josh Greco, and Josh Greco is connected to Meghan Thoin, who shares an edge with Stephanie Boundy. 
Bridging occurs when connections are made between heterogeneous groups. The connection between Amanda Jane connects Stephanie Boundy from the pink cluster, to Elizabeth Meindl from the green cluster, which bridges the clusters together.
A network’s degree shows how many tiers of relationships are involved in the network. A 1-degree network would include connections between two people. A 1.5-degree network includes a connection between two people and then the connection to their friend. A 2-degree connection would include one connection, connections to friends, then connections to friend of friends. My graph is an example of a 2-degree network, as Amanda Jane is connected to Zachary Cicero through Elizabeth Meindl.
Betweenness is the number of times a node acts as a bridge on the shortest path between two other nodes. Mike Tarantula is a bridge between Melissa Bilinski and Courtney Lynne, as well at Melissa Bilinslki and Kayla Lyn Ellis, which adds to his betweenness centrality. Closeness refers to the distance of the edges from one node to another.  Mike Cieslak has a higher closeness with Scott Huddle than Josh Greco does with Jeff Aonso. Eigen-vector centrality is the measure of influence a node has in a network. How many nodes a node is connected to, combined with how influential those nodes are, gives each node a score on their level of influence. For example, Melissa Bilinski has a higher Eigen-vector because the people she is connected to are more influential.
  This lab exercise was very informative on how to read social networking graphs, and how to analyze the information that you’ve collected. I can begin to see how impactful these studies could be, and the importance of this type of analysis.
