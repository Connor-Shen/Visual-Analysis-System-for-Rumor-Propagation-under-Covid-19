# Visual-Analysis-System-for-Rumor-Propagation-under-Covid-19

## Topic Modeling of LDA & BERTopic
In this project I design a rumor visualization system for visualizing rumors in social networks during the epidemic. I conduct Topic Modeling of the rumor dataset and compare different method of LDA and BERTopic. LDA is a convenient and intuitive way for topic modeling while BERTopic has better word embedding and can understand the hidden semantics of the document. Topics like " 疫情、核酸、封控" and " 警方、平台、处罚“appear most frequently in our rumor dataset, which is reasonable in the period of epidemic.
### LDA result
html version can be found in the **figures** folder
![img](https://github.com/Connor-Shen/Visual-Analysis-System-for-Rumor-Propagation-under-Covid-19/blob/main/figures/1.png)
#### Topic modeling heatmap
![img](https://github.com/Connor-Shen/Visual-Analysis-System-for-Rumor-Propagation-under-Covid-19/blob/main/figures/heatmap.png)

### BERTopic result
![img](https://github.com/Connor-Shen/Visual-Analysis-System-for-Rumor-Propagation-under-Covid-19/blob/main/figures/newplot.png)
#### Dimensionality reduction clustering display
![img](https://github.com/Connor-Shen/Visual-Analysis-System-for-Rumor-Propagation-under-Covid-19/blob/main/figures/plot.png)

## Geographical Rumor Distribution
Using dynamic topic modeling (DTM), I explore the change of rumor topics over time and region. I divide the rumor topics into four time periods and give reasonable explanations of the changes in topics overtime, like Xi’an’s city closure and Zhejiang’s epidemic policy adjustment. Geographical Rumor Distribution is also conducted in this project. Zhejiang and Shanxi province occupy the largest proportion of rumor data. Meanwhile, I perform a geographic analysis based on different rumor topics like " 疫情", " 贷款" and visualize them in the form of China map.
![img](https://github.com/Connor-Shen/Visual-Analysis-System-for-Rumor-Propagation-under-Covid-19/blob/main/figures/epidemic.png)

## User Network & Community Detection
Based on the 18 users’ browse records, I build a user network and compute the degree centrality, betweenness centrality and rumor preference of each user. Community detection using the Louvain algorithm is also performed to demonstrate deeper user connections. Popular rumor data is specially listed according to the number of likes. Through topical modeling of popular rumor data and media analysis, we have a better understanding of the spread of 16 rumors and features of popular rumor.
![img](https://github.com/Connor-Shen/Visual-Analysis-System-for-Rumor-Propagation-under-Covid-19/blob/main/figures/user%20net.png)

