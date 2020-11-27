# BBC_News_cluster

Gegenstand dieses Repositorys soll es sein, 2225 Dokumente von der BBC-Nachrichten-Website, im Zeitraum von 2004-2005, nach den 5 Themengebieten (Wirtschaft, Unterhaltung, Politik, Sport, Technik) über die jeweiligen Texte zu clustern.

# TO-DOs:

- HC (Hierarchical Clustering Dendrogram herausfinden, was das genau aussagt.)
- GMM

# Potenzielle Fragen:

- Wieso erkennt HC nicht nur 2 Cluster sondern drei bei Vergleich von zwei Kategorien?
- Wie kann ich mir die verwendeten Wörter der SVM anzeigen lassen?
- Grafiken KMeans und HC, sind die gut/schlecht?

# Ergebnisse:
KMeans: Dimensionsreduktions danach besser als davor, TSNE am besten, Am besten zu Cluster Sport.
HC: PCA am besten, TSNE zeigt nur eine Kategorie an, Tech klappt am besten mit einer anderen Kategory.
    Mit Entertainment schwierig, da alle Kategorien, außer tech, auch im Entertainment auftreten (TV!).
    
