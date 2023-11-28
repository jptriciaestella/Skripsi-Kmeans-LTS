# Skripsi Kmeans LTS
 Semoga masuk Q1

1. Kmeans + preprocessing boxplot
2. Kmeans LTS: Cluster awal -> cari residual (jarak antara centroid dan titik tsb) -> buang (bisa berdasarkan persentase LTS, atau cari ideal persentase dengan membandingkan silhouette score terbaik) -> cluster lagi
3. Trimmed k-means

Untuk evaluasi:
- purity score
- visualisasi data (bisa diPCA menjadi 2 dimensi), kasih liat outliernya yang dideteksi oleh kmeans LTS sama trimmed kmeans gimana