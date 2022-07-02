# Project background

The compound of technologies we use to call 'AI' promises to revolutionize many sectors. However, there is a substantial gap between what firms say they do with AI and what they actually do with it. Several factors could account for such a gap: 
1.	the adoption of AI tools is costly since it tends to jeopardize an incumbent's operations  
2.	there is a shortage of human capital trained in the area of AI 
3.	developing AI applcations may require businesses to cope with ethical/societal implications 
4.	and regulatory issue

In the context of knowledge intensive industries, there is yet another obstacle to the diffusion of AI, namely, 'people.' While some professionals may be thrilled to integrate AI in their daily work, some others may just feel threatened. This project deals with the distribution of security traders’ opinions about the impact AI can make on 'trading floors.'

# Dataset

In order to get a better understanding of traders' attitudes toward AI, we have circulated a survey in a large trading floor. The resulting dataset [trading_floor.xml]( https://github.com/simoneSantoni/net-analysis-smm638/blob/9114bedfde4195f2e5ed4fa5c868e3d41b26f939/finalCourseProject/trading_floor.xml) contains 192 responses regarding:
•	the undirected network of knowledge exchange between traders (traders A and B are connected when A says he/she shares technical and industry knowledge with B and vice versa)
•	a trader's opinion about the contribution of AI to his/her productivity and effectiveness in evaluating securities (1 = not at all; 10 = to a great extent). In the datasets, this variable is reported as the node attribute ai.
Regarding the traders' location in the floor. 
There are six zones, each of which hosts 32 individuals (16 individuals on each side of the zone). In the dataset, the location of traders is reported as two node attributes, that is, x-pos and y-pos.

# Project context

This project aims to help an investment bank to sustain the diffusion of AI. Specifically, the bank would like to persuade traders to engage more with AI tools when it comes evaluating securities.

Here are the steps for the analysis:
1.	Map traders' opinions onto the knowledge exchange network
2.	Map traders' opinions map onto the physical layout of the trading floor
3.	Identifying network-related obstacles to the diffusion of positive opinions about AI in the trading floor
4.	Provide recommendation to promote the diffusion of positive opinions about AI in the trading floor.
