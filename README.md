# Fake News Project

There are numerous sources of information on the net. They can be more or less biaised or reliable and it is sometimes difficult to know where the truth is.

The GDELT project follows news fom thousands of news sites in real time, all over the world. It records the URL, the topic, the publication time, the site and several additional metadata describing each article. Every 15 min the site is updated to release the latest activity in the world of medias.

This rich dataset provides interesting information about the behavior and interaction between news sites. We have started several data science projects to extract valuable information about news from this data. From these first analyses, many questions arise.

This GitHub repository gathers a work on it, especially :
- Extraction of data and creation of DataFrame and graphs
- Geographical Label Propagation
- Type Label Propagation according to neighbors
- A work on the republication
- A study of event time line 

The folders of this repository containes :
- archives	: The old notebooks, showing some results showed in the report, but not always clean.
- notebooks	: The "clean" notebooks containing a clean code and understandable.
- reference_data : The reference data used in the notebooks (GDELT reference for country attribution, our country attribution CSV reference and the reference data for confidence and controversial websites)

Remark : Unfortunatly the all_data, graph and the various array saved files can not be upload on git because of their size. They are all reproductible from the notebooks provided. 
