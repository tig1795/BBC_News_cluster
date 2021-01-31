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
         kmeans_tsne_categorymarker_content.png
         kmeans_tsne_categorymarker_stemming_5_Cluster.png
         kmeans_tsne_categorymarker_text_10_Cluster.png
         kmeans_tsne_categorymarker_text_5_Cluster.png
         kmeans_tsne_davor_categorymarker_content_5_Cluster.png
       SVM
         SVM_Classification_Report_text.PNG
       Topic Modeling 
         TM_Gensim_Word2Vec_Ergebnis.PNG
         lda_text_alles.html
         topic_modelling_verteilung.png
         wordcloud_Entertainment.png
         wordcloud_Technology.png
         wordcloud_Topic7.png 

Datensaetze:

         bbc-news-data.csv
         bbcNews_stemm_types_tokens.csv
         news_POS_POS_tags.csv
         news_POS_POS_tags_nouns_adjectives_verb.csv (aktueller Datensatz)
         news_sample_25percent.csv
         word_frequencies_by_category_and_pos.csv
         word_frequencies_by_category_strict.csv 
         
Notebooks

       0_Preprocessing
         25_Percent_Dataset.ipynb
         30 MFWs.ipynb
         Dataexploration.ipynb
         Preprocessing.ipynb 
       1_KMeans
         KMeans.ipynb
         KMeans_with_Stopwords.ipynb
         KMeans_with_miniBatch.ipynb 
       2_SVM
         SVM_BBC.ipynb
       3_Hierarchisches Clustering
         HC_PCA.ipynb
         HC_TSNE.ipynb
         HC_UMAP.ipynb 
       4_Gaussian Mixture Models
         GMM_different_combinations.ipynb
         Gaussian mixture models.ipynb 
       5_DBScan
         DB_Scan.ipynb 
       6_Topic Modeling
         Topic_Mod.ipynb
         Topic_Modeling2.ipynb
         articles-model-nmf-k10.pkl
         articles-raw.pkl
         articles-tfidf.pkl
         stopwords.txt
         text.txt
         w2v-model.bin
         w2v-model.bin.trainables.syn1neg.npy
         w2v-model.bin.wv.vectors.npy 
       7_Auto Encoder
         Auto Encoder.ipynb
         Auto_Encoder_einzelne_Kategorien(Colab).ipynb
         Auto_Encoder_ganzer_Datensatz(Colab).ipynb
         autoencoder_embeddings.npy 
       
-README.md

