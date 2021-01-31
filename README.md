# BBC_News_cluster

Gegenstand dieses Repositorys soll es sein, 2225 Dokumente von der BBC-Nachrichten-Website, im Zeitraum von 2004-2005, nach den 5 Themengebieten (Wirtschaft, Unterhaltung, Politik, Sport, Technik) über die jeweiligen Texte zu clustern.

Datensatz: https://www.kaggle.com/hgultekin/bbcnewsarchive

Der Datensatz und die verschiedenen Clustering-Verfahren sind in Ordner unterteilt und wie folgt strukturiert:

Bilder

    Datenexploration
        Anzahl_Laenge_Kategorie
             Anzahl_der_Newsartikel_pro_Kategorie.png
             Artikellängen_pro_Kategorie.png
             Verteilung_der_Artikellängen.png 
        MFW30_categroy
             freq_30mfw_korrekt.png
        Wordclouds 
             wordcloud_Business.png
             wordcloud_Entertainment.png
             wordcloud_Politics.png
             wordcloud_Sport.png
             wordcloud_Technology.png 
        Gaussian Mixture Models
             GMM_AIC.png
             GMM_BIC.png
             GMM_Sport_Politics_TSNE.png
             GMM_Sport_Politics_Tech_TSNE.png
             GMM_Sport_Tech_TSNE.png
             GMM_alle_Kategorien_TSNE.png 
        HC
         HC_PCA_2.5_percent_all_categorys.png
         HC_PCA_Business_Tech_5_percent.png
         HC_PCA_Sport_Tech_5_percent.png
         HC_Sport_Entertainment.png
         HC_Sport_Entertainment_5_percent_filenames.png 
       KMeans
         Ellenbogen_Methode_und_Silhouetten_Koeffizient
              EM.png
              SK.png
         Content_Cluster.png
         UMAP_kmeans_POS.png
         UMAP_kmeans_POS_5_Cluster.png
         UMAP_kmeans_content.png
         kmeans_pca_POS.png
         kmeans_pca_POS_5_Cluster.png
         kmeans_pca_content.png
         kmeans_tsne_categorymarker_POS.png
         kmeans_tsne_categorymarker_POS_5_Cluster.png
Dataexploration + KMeans Modification
4 months ago
kmeans_tsne_categorymarker_content.png
Dataexploration + KMeans Modification
4 months ago
kmeans_tsne_categorymarker_stemming_5_Cluster.png
Dataexploration + KMeans Modification
4 months ago
kmeans_tsne_categorymarker_text_10_Cluster.png
Modification KMeans + SVM
3 months ago
kmeans_tsne_categorymarker_text_5_Cluster.png
Modification KMeans + SVM
3 months ago
kmeans_tsne_davor_categorymarker_content_5_Cluster.png

             
       
Literatur

    HC: hier werden die Beziehungen zwischen den Genres und Künstlern beschrieben, 
        die für die Erklärung der Ausreißer benötigt wurden
    Visualization_in_Stylometry
    Topic-modelling-with-scikitlearn

datasets

This folder contains the old and the new record.

    Currently_dataset
        song_decades_long.csv
    Old_datasets
        Datenexploration_1
            pop_genre1_2.csv
            rock_genre1_2.csv
            sample_25percent.csv
            songs_longtexts.csv
            songtexte_bereinigt_gekuerzt.csv
        Datenexploration_2
            songs_100.csv
            songs_25.xlsx
        Discogs
            discogs_dates.xlsx
            discogs_id.xlsx
        Spotify
            songdata.csv
            songdata.xlsx
            songs_decades.csv
            songs_plus_dates.csv
    datasets_info



Notebooks

    .ipynb_checkpoints
    0_preprocessing
    1_KMeans
        Dimensionsreduktion
            umap
        Implementierung_K-Means
        K_Means
    2_SVM
        SVM_KM
    3_HC
    4_GMM
    5_DBScan
    6_TopicModeling
        mallet_text
    7_AutoEncoder
        Final AutoEncoder
    8_Delta
        zscores
    Clustering_Verfahren .ipynb - Pipeline for all procedures

-.gitattributes

-README.md

