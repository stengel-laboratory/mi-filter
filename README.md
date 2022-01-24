# mi-filter

Cross-Linking Mass Spectrometry (XL-MS) has become an indispensable tool for the emerging field of systems structural biology over the recent years. However, the confidence in individual protein-protein interactions (PPIs) depends on correct assessment of false discovery rates for individual inter protein cross-links. This can be challenging, in particularly in samples where relatively few PPIs are detected, as is often the case in complex samples containing low abundant proteins or in in-vivo settings. In this manuscript we are describing a novel mono- and intralink filter (mi-filter) that is applicable to any kind of crosslinking data and workflow. It stipulates that only proteins for which at least one monolink or intra-protein crosslink has been identified within a given dataset are considered for an inter-protein cross-link and therefore participate in a PPI. We show that this simple and intuitive filter has a dramatic effect on all types of crosslinking-data ranging from single protein complexes, over medium-complexity affinity enrichments to proteome-wide settings and significantly improves false-discovery rates for inter-protein links in all types of XL-MS data. 

This package introduces an pipeline of mi-filter which is used for data analysis in the system of crosslinking mass spectrometry(XL-MS). This is a completely new filter that could combine with all XL-MS software. The 26S proteosome is used for the template of mi-filter analysis. The csv files are triplicates of wild type 26S proteasome crosslinking data from XQuest. 

The following steps are required in order to run mi-filter: 

1. Download the whole folder including the template data. 
2. Run the script using python software such as jupyter notebook or pycharm. 
3. In the mi-filter folder you would get mi-filter data for triplicates separately. "mi-filter_sum.csv" is all mi-filter results from three csv templates. 
