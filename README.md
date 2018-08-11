# Rudiments-of-Social-Network-Analysis
A brief overview of the key objectives and processes of Social Network Analysis along with examples of programs and code used to perform the analysis.

<h3>Introduction</h3>

To put it succinctly, <b>Social Network Analysis</b> (SNA) "can be described as a *study of human relations by means of graph theory*." 

<h4> Some Key Definitions</h4>

<b>Graph theory</b> is a branch of mathematics obviously devoted to the study of *graphs*," where a <b>graph</b> is defined "as a set of vertices, nodes or points connected by a set of edges, links or lines." While the terms are interchangeable, we will use the terms node and edge in this discussion. The term <b>network</b> is used to encompass a graph along with added data about the attributes of the nodes and edges (e.g. the *degree* of node or the strength or weight of the edge or connection).

<img src=https://github.com/daveking63/Rudiments-of-Social-Network-Analysis/blob/master/NetworkGraph.jpg  width="500" height="300">
 
Graph theory, graphs and networks have been used in a variety of application areas including physical, biological, social, and information systems. In the case of social systems and SNA, the <b>nodes</b> are typically social actors (individuals or collections of people sharing one or more characteristics) or the artifacts produced by the actors (e.g. emails or tweets, tags, articles or blogs, etc.).  In the same vein, the <b>edges</b> represent the relations or connections among the nodes. Like nodes, there is quite a bit of variety among the different *types of social connections*:

<ul>
  <li><i>Social Relations</i> - Kinship (mother of, sibling of...); Other Role (friend of, boss of, mentor of...);  Affective (likes, supports...); Cognitive (knows...)</li>
  <li><i>Interactions</i> - Talked to, Helped, Influenced, Cited, Mentioned, Retweeted, Linked to, etc.</li>
  <li><i>Flows</i> - Information, Beliefs, Personnel, Resources, etc.</li>
  <li><i>Similarities</i> - Location (same spatial and temporal space); Membership (same organization, same events, etc.); Attribute (same age, gender, occupation, organization, beliefs, memberships, etc. </li>
</ul>

In addition to the type of relations, distinctions are also made among edges in terms of their direction (denoted by an edge with or without an arrow) and strength or weight (denoted by either an accompanying numeric value or the width of the edge).

<img src=https://github.com/daveking63/Rudiments-of-Social-Network-Analysis/blob/master/NetworkGraphDirectionWeight.jpg  width="500" height="350">
 
SNA has it's genesis in the early days of the social sciences (like sociology) dating at least to the early 1900s. As a number of sources document, SNA was only of interest to small cadre of social scientists until the mid-1970s and didn't really come popular attention until the early 2000s with the rise of social media on the Web, as well as the the availability of social media APIs (e.g. Twitter) enabling the collection of large amounts of social network data. 

With this rise came an onslaught of books and research papers devoted to network analysis in general and SNA in particular.  Similarly, there has been a rise in the availability of specialized programs and languages devoted this form of analysis and various websites devoted to these programs and languages. For those who are interested in these general topics, see:

<ul>
<li><a href='https://github.com/daveking63/Rudiments-of-Social-Network-Analysis/blob/master/SNA-Resources.md'>SNA Resources</a> -- Bibliographic listing of key books, papers, presentations, and journals dealing with SNA and some of the major tools used to visualize and analyze social networks.</li> 
<li><a href='https://www.kdnuggets.com/software/social-network-analysis.html'>KDNuggets.com SNA</a></li> -- List of commercial software, sites for SNA, and free and open source SNA software.</li>
<li><a href='https://www.kdnuggets.com/2015/06/top-30-social-network-analysis-visualization-tools.html'>KDNuggets.com Top 30 SNA Visualization Tools</a></li> -- List of 30 frequently used commercial and free SNA software packages along with a short description of each and a link to the corresponding web site.</li>
<li><a href='https://www.rankred.com/free-social-network-analysis-tools/'>Free SNA Tools</a></li> -- List of 21 free SNA tools along with a brief description and image of each tool and a link to the associated web site.</li>
</ul>
