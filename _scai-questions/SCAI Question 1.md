---
title: SCAI Question 1
permalink: /scai-question-1/
variant: markdown
description: ""
---
## Reliability & Trustworthiness

### How can we create a data collection and sharing ecosystem that produces high-quality data for AI, which can be shared and exploited within and across countries?

#### Context & Assumptions

High quality data leads to high quality AI. Training large models currently requires large amounts of high quality data. To have high quality data, one needs to consider what would be appropriate data governance, technologies, and infrastructures to manage the challenges of data collection, deal with data fragmentation, and support data integration. In addition, there is a need to address issues concerning legal real time continuous data (e.g., sensor data), fact editing, and challenges around model collapse and reproducibility. Data about the construction and performance of AI models themselves – for instance, on what data they were trained and evaluated on – is also an important asset.

Building good datasets has been problematic. In some domains, acquiring data can be a challenge. For example, in healthcare, developing good models requires diverse, high quality, accurate datasets from the local community, but this is difficult to achieve given the sensitivity and privacy of such data; these challenges persisted even during the COVID-19 pandemic, where data was essential to combatting its spread. Also, user generated content, a goldmine of potential insights, is often proprietary. Companies collecting this data are cautious about sharing, as it has competitive value and comes with privacy concerns and legal obligations.

Despite the challenges, some datasets and resources are maintained to high standards. This ranges from collaborative maintained resources such as Wikipedia to cultural heritage data, e.g., Europeana, the European digital cultural platform, which allows museums, galleries, libraries, archives across Europe to share and reuse digitised, standardised cultural heritage images such as 3D models of historical sites, and high quality scans of paintings. Additionally, biomedical data, such as genetic information, clinical trial results, and disease data, are typically well-catalogued and publicly available, fostering scientific collaboration and research.

#### Question

**How can we create a data collection and sharing ecosystem that produces high-quality data for AI, which can be shared and exploited within and across countries?**

A robust data collection and data sharing ecosystem will also allow us to address the following key issues:

* **Measuring data quality:** Principles guiding the measurement of data quality are essential for fostering reliable AI models. Adhering to the FAIR principles (Findable, Accessible, Interoperable, Re-usable) lays the foundation for robust datasets. Additionally, for factors such as diversity, representativeness, openness, trustworthiness and safety, the incorporation of mechanisms for both prevention and assistance in the unlearning processes of AI models are crucial. These principles collectively contribute to the integrity and efficacy of AI models and applications.
* **Data valuation:** Relatedly, the assignment of value to data is important in any effort to enable effective sharing. Data valuation can help to guide the selection, management, and the stewarding of data.
* **Scaling data:** Large language models require massive amounts of text data for training. Other frontier models require significant data in other modalities; image, video, audio etc. Acquiring and curating such large and diverse datasets can be logistically challenging and resource-intensive. Scaling data to accommodate large volumes necessitates a federated approach. Discovering and linking data across domains, maintaining standards to enable data sharing, maintaining a balanced representation across various demographics, and exploring the generation and use of synthetic data are potential approaches.
* **Data privacy:** Ensuring data privacy is paramount in a data-sharing ecosystem. Implementing robust privacy measures involves anonymization, encryption, and compliance with international privacy regulations. Striking a balance between data utility and privacy protection is essential for fostering trust among data contributors and users.
* **Data rights:** Establishing clear ownership frameworks ensures responsible data stewardship and facilitates ethical data sharing practices. Some of the primary challenges in managing data rights pertains to the constraint imposed by political boundaries—commonly known as data sovereignty. Additionally, navigating data copyrights requires understanding intellectual property laws and implementing mechanisms to protect creative elements within datasets.
* **Data reproducibility:** Data reproducibility is critical for the scientific community and AI practitioners. Implementing practices such as sharing code, documenting methodologies, and providing access to raw data enhances the reproducibility of AI research. Open and transparent practices will continue contributing to the credibility and reliability of AI models and findings.

#### Indicators of Progress

For data to be effectively used to build AI for good, we will need to consider a range of levers, including governance and technological approaches.

The governance approach, including setting up relevant regulations, incentives, subsidies, and data formatting and sharing agreements, can encourage the creation and flow of data. For example, one can mandate that datasets that are created through the support of federal funds should be publicly available in a standardised format. Furthermore, one can encourage the adoption of an agreed methodology to describe the origin, nature, and use of data. Data institutions such as the UK Biobank is one such example. Defining a taxonomy for data can also help classify data more effectively for appropriate privacy classification and data licensing.

In addition, there should be equivalent focus on novel technical approaches to achieve high-quality data for AI. Current examples include privacy enhancing/preserving technology and development of Trusted Research Environments (TRE). TREs allow for model development and deployment by leveraging data in a secure manner. New technologies to enable data provenance can also enable safer development of AI, especially large foundation models, so as to allow for appropriate model unlearning, licensing, watermarking etc. 

There should also be a focus on measuring the progress of enabling high-quality data sharing, which in itself is a non-trivial challenge. There will be cultural issues, liability concerns, political and jurisdictional boundaries that come into play that might impede creating and sharing data. There needs to be more recognition of the progress of such work, including the measurement of high quality data sharing and quantifying the friction of data flow, metrics of unlearning data, as well as data quality parameters such as data diversity and uniqueness, and accessibility.