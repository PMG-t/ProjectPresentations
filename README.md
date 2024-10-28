# Data Science Projects
All, or almost all, of the projects carried out during the university course of Data Science at Milano-Bicocca University.

## Contents list:
- [Audio classification and image classification and matching](#audio-classification-and-image-classification-and-matching)
- [Collecting user annotations for training neural network-based object detectors](#collecting-user-annotations-for-training-neural-network-based-object-detectors)
- [Content relations between google news and twitter posts](#content-relations-between-google-news-and-twitter-posts)
- [Do Cov-19 mobility restrictions affect your music and movie choices?](#do-cov-19-mobility-restrictions-affect-your-music-and-movie-choices)
- [Europe air quality exploration](#europe-air-quality-exploration)
- [Exploration of drugs' reviews](#exploration-of-drugs-reviews)
- [Football teams performance indicators clustering](#football-teams-performance-indicators-clustering)
- [Fruit classification and segmentation with transfer-learning neural network approach](#fruit-classification-and-segmentation-with-transfer-learning-neural-network-approach)
- [Fundus image classification and processing for diabetic retinopathy](#fundus-image-classification-and-processing-for-diabetic-retinopathy)
- [Hourly energy consumption time series prediction](#hourly-energy-consumption-time-series-prediction)
- [Survey on job and contractual opportunities for graduates using ISTAT data](#survey-on-job-and-contractual-opportunities-for-graduates-using-istat-data)
- [Multi-domain claim detection: a coreset and an external feature based approach for automated fact-checking](#multi-domain-claim-detection-a-coreset-and-an-external-feature-based-approach-for-automated-fact-checking)
- [Turntable 3D modelling](#turntable-3d-modelling)
- [Understanding semantic perception of cities in society](#understanding-semantic-perception-of-cities-in-society)
- [Unimib energy consumption descriptive and predictive analysis](#unimib-energy-consumption-descriptive-and-predictive-analysis)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Audio classification and image classification and matching

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Audio_classification_and_image_classification_and_matching.png?raw=true)

- **Course:** *Digital signal and image preprocessing*
- **Tools and techniques:** *Python, Tensorflow, convolutional neural network, image features descriptors*
- **Worked on:** *Whole project, especially in image matching and retrieval task*
- **Description:** This project explores different image matching and retrieval techniques to identify correspondences between historical photographs of Amsterdam dating back to 1900 and modern images of the same places. Images are analysed using a range of representation techniques, including SIFT descriptors, VLADs and convolutional neural networks (CNNs), with a focus on the use of siamese architectures for visual similarity-based training. The comparison of the methods highlights the advantages and limitations of each approach, providing useful insights for historical reconstruction and visual heritage conservation applications.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Audio%20classification%20and%20image%20classification%20and%20matching.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Collecting user annotations for training neural network-based object detectors

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Collecting_user_annotations_for_training_neural_network-based_object_detectors.png?raw=true)

- **Course:** *Bachelor's degree in Computer Science (Milano-Bicocca University)*
- **Tools and techniques:** *Python, Matlab, Flask, MongoDB, Android Studio*
- **Description:** The following report describes the creation of a client-server system for requesting the detection of objects on images provided by the user. The primary goal was to create a system capable of improving or creating new detectors after the use of users, whose results must then be collected and stored. The technology of the YOLO neural network, used for object recognition, and its implementation will be analyzed. Project structure and development components will be described in the course of the report in parallel with the different problems each of them faces. Finally, the realization of an interface intended for the user, of which are described the different features that together lead to the achievement of the initial intent. Lastly, the results achieved are presented, in terms of time and computational resources, and also of accuracy degree and potential offered.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Collecting%20user%20annotations%20for%20training%20neural%20network-based%20object%20detectors.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Content relations between google news and twitter posts

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Content_relations_between_google_news_and_twitter_posts.png?raw=true)

- **Course:** *Master's degree stage*
- **Tools and techniques:** *Python, Tensorflow, web scraping, text representation techniques (TF-IDF, LLMs, Word2Vec), PlotLy*
- **Description:** This study presents a descriptive analysis aimed at identifying semantic relationships between contents published on Google News and trending topics on Twitter. Data were collected through scraping from the two platforms and three different text representation approaches were used: TF-IDF, Word2Vec and BERT. Relationships are extracted by calculating cosine similarity, both between individual texts and by exploiting the aggregation provided by the platforms. The visualization of the links was achieved through a Sankey diagram, which is effective for highlighting the connections between contents. Finally, the work discusses the results obtained for the different experiments, describing the limitations of the approaches used and suggesting possible improvements. This study represents an attempt to describe the relationships between traditional media and social media and offers a possible starting point for subsequent analyses of information flows between different platforms.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Content%20relations%20between%20google%20news%20and%20twitter%20posts.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Do Cov-19 mobility restrictions affect your music and movie choices?

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Do_Cov-19_mobility_restrictions_affect_your_music_and_movie_choices.png?raw=true)

- **Course:** *Data management and visualization*
- **Tools and techniques:** *Python, web scraping, Spotify API, IMDB API, Apache Kafka, MongoDB, Tableau*
- **Worked on:** *Retrieval, processing, db management and integration + final visualization for Netflix data*
- **Description:** This study analyzes the impact of mobility restrictions, introduced during the COVID-19 lockdown, on emotional and sentimental preferences of content searched on platforms such as Spotify and Netflix. The data, collected from different sources and integrated into a MongoDB database in deferred streaming, are processed to extract statistical indicators that highlight any correlations between the intensity of restrictions and the choice of content. The resulting information is displayed in interactive dashboards, which allow to monitor and analyze the phenomena by country, offering a detailed view of the aggregated emotional responses.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Do%20Cov-19%20mobility%20restrictions%20affect%20your%20music%20and%20movie%20choices.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Europe air quality exploration

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Europe_air_quality_exploration.png?raw=true)

- **Course:** *Big data in geographic information systems*
- **Tools and techniques:** *Python, Geo-Pandas, Self-Organizing-Map*
- **Description:** This project examines the levels of air pollutants (PM-10, NO, CO, SO₂) in Europe, using data collected from monitoring stations from 1998 to date. The analysis includes an assessment of overall trends and seasonal and weekly variations for each pollutant, providing a detailed view of temporal concentration patterns. To identify geographical areas with similar trends, a clustering technique based on Self Organizing Maps (SOM) is applied, which groups locations with common concentration trajectories of the substances under consideration. This approach allows to identify similarities based on environmental exposure dynamics and shared seasonal behaviors, highlighting regions with comparable risk profiles and pollution characteristics.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Europe%20air%20quality%20exploration.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Exploration of drugs' reviews

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Exploration_of_drugs_reviews.png?raw=true)

- **Course:** *Text mining and search*
- **Tools and techniques:** *Python, Word2Vec, text classification and text clustering, strong text preprocesing techniques*
- **Worked on:** *Text processing, cluster analysis*
- **Description:** In this study, clustering techniques are applied to a dataset of textual reviews to group drugs based on the meaning of terms present in user comments. The clustering process uses semantic analysis to identify similarities in feedback, allowing to aggregate drugs that share similarly perceived characteristics. Once the clusters are formed, the peculiarities of each group are examined, with a particular focus on the most representative terms and adjectives, which emerge as key indicators of users' experiences and opinions. This approach allows a structured view of common perceptions about drugs, offering relevant insights for qualitative analysis.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Exploration%20of%20drugs%E2%80%99s%20reviews.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Football teams performance indicators clustering

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Football_teams_performance_indicators_clustering.png?raw=true)

- **Course:** *Machine learning*
- **Tools and techniques:** *Python, KNIME, KPIs construction, cluster analysis*
- **Worked on:** *KPIs construction, cluster analysis*
- **Description:** Using a dataset that details the performance of each player in each match, this project develops a set of indicators based on the success of specific actions in different areas of the pitch. These indicators are used in a clustering analysis to identify distinct levels of skill and tactical contribution for each role, allowing players to be segmented based on their relative effectiveness. The clustering results are visualized through interactive dashboards that facilitate the analysis of the potential strengths and weaknesses of opposing teams, supporting strategic decisions based on the strengths and vulnerabilities of the various positions on the pitch.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Football%20teams%20performance%20indicators%20clustering.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Fruit classification and segmentation with transfer-learning neural-network approach

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Fruit_classification_and_segmentation_with_transfer-learning_nn_approach.png?raw=true)

- **Course:** *Advanced machine learning*
- **Tools and techniques:** *Python, Tensorflow, image preprocessing, convolutional neural network*
- **Worked on:** *Whole project*
- **Description:** The project focuses on the automatic classification of a large set of images of different types of fruit, using advanced transfer learning techniques applied to convolutional neural networks (CNN). To improve the accuracy and generalization of the model, data augmentation techniques are adopted, which increase the variety and robustness of the training data. To complete the classification, image segmentation techniques are implemented, to accurately identify and distinguish fruits in realistic and complex contexts.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Fruit%20classification%20and%20segmentation%20with%20transfer-learning%20nn%20approach.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Fundus image classification and processing for diabetic retinopathy

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Fundus_image_classification_and_processing_for_diabetic_retinopathy.png?raw=true)

- **Course:** *Data science lab in biosciences*
- **Tools and techniques:** *Python, Tensorflow, text processing and information retrieval, convolutional neural networks, strong image elaboration techniques*
- **Description:** The project explores methods for the identification of diabetic retinopathy using a dataset of fundus images. Two main approaches are compared: the first is based on standard convolutional neural networks (CNNs), while the second integrates a specific image preprocessing, aimed at emphasizing the retinal areas where the symptoms of the pathology are more common. This preprocessing has been designed based on information extracted from a textual analysis of specific scientific articles, obtained from PubMed, describing the main features of diabetic retinopathy. The targeted approach aims to improve diagnostic accuracy and to focus the model attention on the most relevant regions for the early identification of symptoms.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Fundus%20image%20classification%20and%20processing%20for%20diabetic%20retinopathy.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Hourly energy consumption time series prediction

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Hourly_energy_consumption_time_series_prediction.png?raw=true)

- **Course:** *Time series analysis*
- **Tools and techniques:** *Python, Statsmodel, time series decomposition analysis and SARIMAX-based model prediction*
- **Description:** This project focuses on the analysis of a time series of hourly energy consumption, using decomposition techniques to isolate the different seasonal components and understand the periodic behavior of energy consumption. The decomposition allows to break down the series into different levels of seasonality and trend, providing an in-depth description of the consumption patterns. Based on the autocorrelation plots, a SARIMAX model is developed, integrating multi-level seasonal components and a regression on the overall trend, to obtain accurate forecasts of future energy consumption levels.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Hourly%20energy%20consumption%20time%20series%20prediction.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Survey on job and contractual opportunities for graduates using ISTAT data

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/ISTAT_opportunità_lavorative_e_contrattuali_laureati.png?raw=true)

- **Course:** *Statistics*
- **Tools and techniques:** *R Studio*
- **Description:** This study uses ISTAT data to examine Italian students' choices of educational paths and their subsequent occupations. The analysis focuses on differences in university choices and job opportunities, exploring variations across different Italian regions and research fields. Through comparisons based on statistical tests, the project aims to identify trends in educational preferences and subsequent careers, providing insight into local dynamics and regional influences on students' career paths.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/ISTAT%20opportunit%C3%A0%20lavorative%20e%20contrattuali%20laureati.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Multi-domain claim detection: a coreset and an external feature based approach for automated fact-checking

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Multi-domain_claim_detection_-_a_coreset_and_an_external_feature_based_approach_for_automated_fact-checking.png?raw=true)

- **Course:** *Master thesis work*
- **Tools and techniques:** *Python, Tensorflow, Large Language Models (LLMs), strong text preprocessing techniques for feature extraction*
- **Description:** This study focuses on the initial phase of automated fact-checking, the claim detection task, with the aim of developing a model capable of effectively generalizing across different linguistic styles and thematic domains while maintaining a sustainable computational complexity. By exploiting the CheckThat! competition datasets published in the last five years, we propose a coreset-based approach to reduce the size of the datasets without compromising their representativeness. This approach allows combining information from different domains, creating a smaller but equally representative training dataset. The use of coresets then allows the adoption of more complex models, integrating not only the representations generated by Large Language Models (LLM), but also external features, such as key concept definitions and syntactic structures. The results demonstrate the effectiveness of coresets in maintaining the representativeness of the original data, reducing noise and allowing an average performance equivalent (or even better) than the one obtained with the full datasets. Furthermore, an increase in the average performance on different datasets is observed when the model incorporates external features, improving the claim detection capabilities compared to the exclusive use of LLM representations.
- [Open PDF (Slides)](https://github.com/PMG-t/ProjectPresentations/blob/master/Multi-domain%20claim%20detection%20-%20a%20coreset%20and%20an%20external%20feature%20based%20approach%20for%20automated%20fact-checking%20(Thesis%20slides).pdf)
- [Open PDF (Thesis)](https://github.com/PMG-t/ProjectPresentations/blob/master/Multi-domain%20claim%20detection%20-%20a%20coreset%20and%20an%20external%20feature%20based%20approach%20for%20automated%20fact-checking%20(Thesis%20report).pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Turntable 3D modelling

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Turntable_3D_modelling.png?raw=true)

- **Course:** *Computer graphics*
- **Tools and techniques:** *Blender*
- **Description:** This project aims to create a detailed 3D model of a turntable and a sound system using Blender software. The modeling involves creating shapes and aggregating various 3D objects into a single cohesive scene. Advanced shaders are used to develop specific textures for each component, contributing to a visually realistic representation. Additionally, the project includes the creation of animations that will simulate the movements of the turntable and the sound system.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Turntable%203D%20modelling.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Understanding semantic perception of cities in society

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Understanding_semantic_perception_of_cities_in_society.png?raw=true)

- **Course:** *Data semantics*
- **Tools and techniques:** *Python, Word2Vec, strong text preprocessing techniques, Bokeh interactive visualization*
- **Worked on:** *Unsupervised apporaches for key-phrases extraction and graph visualization development*
- **Description:** This project uses a large corpus of texts from different sources to analyze and represent the perception of various cities around the world, focusing on the extraction of thematic keywords. Both supervised and unsupervised approaches are employed, using textual representations based on Word2Vec for the extraction of keyphrases. The city representations are linked based on the similarity of the terms and the context in which they are used, allowing for an in-depth comparison between the different perceptions. Finally, an interactive interface is developed to visualize the results, highlighting the most common meanings associated with each city, their number and their similarity to the perceptions of other cities. This approach offers a new way to explore urban narratives and global cultural interconnections.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Understanding%20semantic%20perception%20of%20cities%20in%20society.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->

## Unimib energy consumption descriptive and predictive analysis

![alt text](https://github.com/PMG-t/ProjectPresentations/blob/master/Images/Unimib_energy_consumption_descriptive_and_predictive_analysis.png?raw=true)

- **Course:** *Data science lab*
- **Tools and techniques:** *R Studio, time series forcasting models, Self-Organizing-Maps*
- **Worked on:** *Self-Organizing-Map to indetify different consumption behaviour patterns*
- **Description:** This study analyzes a time series related to the energy consumption of a building at the University of Bicocca, applying an autoregressive model for the forecasting of future consumption. To understand consumption variations, a Self-Organizing Map (SOM) is used to observe the differences in consumption trends based on variables such as percentage consumption and the increasing or decreasing intensity of hourly consumption. The analysis also integrates external meteorological data, such as temperature and humidity, to evaluate their impact on energy consumption. This approach allows to distinguish different periods of the year in which consumption levels present similar or divergent patterns, highlighting critical moments and offering ideas for energy efficiency and sustainable management interventions.
- [Open PDF](https://github.com/PMG-t/ProjectPresentations/blob/master/Unimib%20energy%20consumption%20descriptive%20and%20predictive%20analysis.pdf)

<br> <!-- ------------------------------------------------------------------------------------------------------------ -->























