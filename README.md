# The Football World as a Social Network

<a href="https://github.com/0wenH/The-Football-World-as-a-Social-Network/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=0wenH/The-Football-World-as-a-Social-Network" />
</a>

Made with [contrib.rocks](https://contrib.rocks).


This is the GitHub for Matthew Jarrams and Owen Hunter's research paper on the football world. In this paper we collect all footballers playing in Europe's top 5 leagues since 2010 and create a social network by using their playing histories from their entire career, pairing any players they have played with over their career. From this resulting network, we attempt to find relationships and metrics using social network techniques such as community detection, information and influence spread through the network, and machine learning algorithms to predict nationality and teams based on certain edge (teammate) and node (player) attributes.

## Notebook Overview

1. Scraping.ipynb - Scraping data from *[FBref.com](https://fbref.com/en/)*.
2. NetworkConstruction.ipynb - Creating nodes and edges lists from scaped data
3. BasicStatistics.ipynb - Overview of basic statistics about the network and comparison to Null Models
4. Classifying.ipynb - 2 Classifying Models on Nodes and Edges
5. Leagues.ipynb - Analyzing community sub-graphs and league sub-graphs
6. Spreading.ipynb - Information cascade and Influence spreading analysis
7. GenerateNetwork.ipynb - Recreating the network from scratch using an algorithm
8. RawNotebooks - Includes raw unedited notebooks where most of the exploratory analysis took place
9. csvFiles -A collection of .csv files used in the project
