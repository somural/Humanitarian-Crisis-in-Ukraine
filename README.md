Summary
To support humanitarian actions in Ukraine, I:
1) map the conflict to identify areas most in need of assistance,
2) classify war-damaged infrastructure to target humanitarian response.
Problem Statement
The conflict in Ukraine has resulted in a humanitarian crisis with millions of people in dire need of essential supplies. Real-time data analysis can provide crucial information about the needs of vulnerable populations and enable us to make better decisions on how to allocate our limited resources for an effective response. Mapping the conflict can help identify the areas that require immediate assistance. Moreover, determining the type of damaged infrastructure is critical to identifying locations and populations in need, and to guide the appropriate allocation of resources.
Project
I developed a model that uses machine learning and natural language processing techniques to analyze thousands of reports and extract the most relevant information. I use ACLED, an open-source database that tracks and reports on conflict and violence around the world.
First, a rule-based model is utilized to categorize damaged infrastructure into nine distinct types, namely industrial, logistics, power, telecom, agriculture, health, education, shelter, and businesses. This model operates by comparing relevant keywords associated with each infrastructure type to the information contained in the reports. The resulting classification is then represented on a data visualization, which illustrates the geographic distribution of infrastructure damage by type.
Next, to gain a deeper understanding of the damaged infrastructure, NLP topic modeling is employed. The process involves preprocessing the data and extracting features, followed by the application of two models: k-means clustering and Latent Dirichlet allocation (LDA). The outcomes of these models are then visualized for enhanced comprehension. 
