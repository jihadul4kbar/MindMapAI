# Peta Penelitian (Artificial Intelligence - AI )

## 1. **Machine Learning (ML)**: 
Cabang AI yang fokus pada pengembangan teknik yang memungkinkan komputer untuk belajar dari data dan meningkatkan kinerjanya dalam tugas-tugas tertentu tanpa perlu diprogram ulang.
### 1. **Supervised Learning**: 
Jenis pembelajaran di mana model belajar dari data yang telah dilabeli, dengan tujuan untuk memprediksi label untuk data baru.
- Classification
  - Logistic Regression
  - Support Vector Machine (SVM)
  - k-Nearest Neighbors (k-NN)
  - Decision Trees
  - Random Forest
  - Naive Bayes
  - Neural Networks
- Regression
  - Linear Regression
  - Polynomial Regression
  - Support Vector Regression (SVR)
  - Decision Trees
  - Random Forest
  - Ridge Regression
  - Lasso Regression
- Ensemble Methods
  - Bagging
    - Random Forest
    - Bootstrap Aggregating
  - Boosting
    - AdaBoost
    - Gradient Boosting Machines (GBM)
    - XGBoost
    - LightGBM
    - CatBoost





### 2. **Unsupervised Learning**: 
Jenis pembelajaran di mana model belajar dari data yang tidak dilabeli dan mencoba untuk menemukan pola atau struktur yang berguna dalam data tersebut.

- Clustering
  - K-Means Clustering
  - Hierarchical Clustering
  - DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
- Dimensionality Reduction
  - Principal Component Analysis (PCA)
  - Singular Value Decomposition (SVD)
  - t-Distributed Stochastic Neighbor Embedding (t-SNE)
- Association
  - Apriori Algorithm
  - FP-Growth Algorithm

### 3. **Semi-Supervised Learning**: 
Kombinasi antara supervised learning dan unsupervised learning, di mana model menggunakan sebagian data yang dilabeli dan sebagian lagi yang tidak dilabeli untuk melakukan pembelajaran.

### 4. **Reinforcement Learning**: 
Pendekatan pembelajaran di mana agen belajar untuk melakukan tindakan tertentu dalam lingkungan dengan tujuan untuk memaksimalkan hadiah atau meminimalkan hukuman.

### 5. **Deep Learning**: 
Sub-bidang dari machine learning yang menggunakan neural networks dengan banyak lapisan (deep neural networks) untuk mengatasi tugas-tugas kompleks seperti pengenalan wajah, pengenalan suara, dan penerjemahan bahasa.

### 6. **Transfer Learning**: 
Pendekatan di mana model yang telah dilatih pada satu tugas digunakan sebagai awal yang baik untuk tugas yang berbeda, mempercepat pembelajaran pada tugas baru dengan dataset terbatas.

### 7. **Online Learning**: 
Metode pembelajaran di mana model diperbarui secara berkelanjutan saat data baru tersedia, memungkinkan model untuk beradaptasi dengan perubahan dalam data atau lingkungan.

### 8. **Ensemble Learning**: 
Teknik di mana beberapa model (ensambel) digabungkan bersama untuk meningkatkan kinerja prediksi dibandingkan dengan menggunakan model tunggal.

### 9. **Probabilistic Graphical Models**: 
Representasi grafis dari distribusi probabilitas yang menggambarkan hubungan probabilistik antara berbagai variabel, sering digunakan untuk pemodelan data yang kompleks.


## 2. **Deep Learning**: 
Sub-bidang dari machine learning yang menggunakan neural networks dengan banyak lapisan (deep neural networks) untuk mengatasi tugas-tugas kompleks seperti pengenalan wajah, pengenalan suara, dan penerjemahan bahasa.
### 1. **Convolutional Neural Networks (CNNs)**: 
Jenis neural network yang khusus dirancang untuk memproses data grid, seperti gambar dan video. CNNs efektif dalam ekstraksi fitur spasial dari data visual.

### 2. **Recurrent Neural Networks (RNNs)**: 
Jenis neural network di mana hubungan antar elemen dalam data sequential diperhitungkan. RNNs sering digunakan dalam pemrosesan bahasa alami dan tugas-tugas sequential lainnya.

### 3. **Long Short-Term Memory (LSTM)**: 
Sebuah jenis unit dalam jaringan saraf rekuren yang dapat "mengingat" informasi dalam jangka waktu yang lama. LSTM sering digunakan dalam RNNs untuk menangani masalah vanishing gradient.

### 4. **Generative Adversarial Networks (GANs)**: 
Sebuah model pembelajaran yang terdiri dari dua jaringan neural, generator dan discriminator, yang berkompetisi satu sama lain. GANs digunakan untuk menghasilkan data baru yang menyerupai data pelatihan.

### 5. **Autoencoders**: 
Sebuah jenis jaringan neural yang bertujuan untuk merekonstruksi inputannya sendiri. Autoencoders sering digunakan untuk reduksi dimensi dan pembelajaran fitur yang tidak terawasi.

### 6. **Deep Belief Networks (DBNs)**: 
Sebuah arsitektur jaringan neural yang terdiri dari beberapa lapisan neuron yang setiap lapisannya saling terhubung secara penuh. DBNs dapat digunakan untuk pembelajaran yang tidak terawasi.

### 7. **Attention Mechanism**: 
Sebuah mekanisme yang memungkinkan jaringan neural untuk fokus pada bagian-bagian tertentu dari input, berguna dalam pemrosesan bahasa alami dan tugas-tugas lain yang memerlukan pemahaman konteks.

### 8. **Transformers**: 
Sebuah arsitektur jaringan neural yang menggunakan attention mechanism untuk memproses data sequential, seperti teks atau audio, dengan cara yang paralel dan efisien.

### 9. **Capsule Networks**: 
Sebuah pendekatan baru dalam deep learning yang menggantikan neuron tunggal dengan kapsul sebagai unit pengenalan fitur, yang dapat memperbaiki masalah dalam pemahaman representasi gambar.


## 3. **Computer Vision**: 
Memungkinkan komputer untuk melihat, menginterpretasi, dan memproses visual informasi pada gambar atau video. Contohnya termasuk deteksi objek, pengenalan wajah, dan segmentasi gambar.
### 1. **Image Classification**: 
Tugas dalam computer vision yang melibatkan pengelompokan gambar ke dalam kelas-kelas yang telah ditentukan. Contohnya adalah mengklasifikasikan gambar sebagai kucing atau anjing.

### 2. **Object Detection**: 
Mengidentifikasi dan menggambar kotak pembatas (bounding box) di sekitar objek-objek tertentu dalam gambar. Hal ini sering digunakan dalam aplikasi pengawasan dan deteksi objek pada video.

### 3. **Semantic Segmentation**: 
Mengklasifikasikan setiap piksel dalam gambar ke dalam kelas-kelas yang berbeda tanpa memperhatikan objeknya. Misalnya, memisahkan setiap piksel dalam gambar menjadi kelas "jalan", "trotoar", atau "mobil".

### 4. **Instance Segmentation**: 
Mirip dengan semantic segmentation, tetapi dengan membedakan setiap objek individu dalam gambar. Misalnya, memisahkan setiap orang dalam gambar ke dalam objek yang berbeda.

### 5. **Object Tracking**: 
Mengikuti pergerakan objek dari frame ke frame dalam sebuah video. Hal ini penting dalam aplikasi seperti pengawasan video dan kendaraan otonom.

### 6. **Pose Estimation**: 
Mengidentifikasi posisi dan orientasi objek dalam gambar, khususnya manusia. Ini berguna dalam aplikasi augmented reality dan analisis gerakan.

### 7. **Image Generation**: 
Menghasilkan gambar baru dari data latih, sering kali menggunakan model generatif seperti Generative Adversarial Networks (GANs).

### 8. **Image Restoration**: 
Memulihkan gambar yang rusak atau kabur menggunakan teknik seperti super-resolution dan denoising.

### 9. **Visual Question Answering (VQA)**: 
Menjawab pertanyaan berdasarkan konten gambar, memerlukan pemahaman yang mendalam tentang gambar dan bahasa natural.


## 4. **Natural Language Processing (NLP)**: 
Bidang AI yang berfokus pada interaksi antara komputer dan manusia menggunakan bahasa alami. Ini mencakup pemahaman bahasa, pembangkitan bahasa, dan penerjemahan bahasa.

### 1. **Tokenization**: 
Memecah teks menjadi bagian-bagian yang lebih kecil, seperti kata-kata atau frasa.

### 2. **Stemming and Lemmatization**: 
Mengubah kata-kata ke bentuk dasarnya (stemming) atau ke bentuk kata baku (lemmatization).

### 3. **Part-of-Speech (POS) Tagging**: 
Mengidentifikasi jenis kata dalam sebuah kalimat (misalnya, verba, nomina, atau adjektiva).

### 4. **Named Entity Recognition (NER)**: 
Mengidentifikasi dan mengklasifikasikan entitas bernama dalam teks, seperti nama orang, tempat, atau organisasi.

### 5. **Sentiment Analysis**: 
Menentukan sentimen atau opini yang terkandung dalam sebuah teks, apakah positif, negatif, atau netral.

### 6. **Text Classification**: 
Mengklasifikasikan teks ke dalam kategori atau label tertentu berdasarkan isinya.

### 7. **Machine Translation**: 
Menerjemahkan teks dari satu bahasa ke bahasa lain menggunakan mesin.

### 8. **Speech Recognition**: 
Merubah ucapan menjadi teks secara otomatis.

### 9. **Question Answering**: 
Menjawab pertanyaan berdasarkan informasi yang terdapat dalam sebuah teks.

### 10. **Language Modeling**: 
Memprediksi kata-kata berikutnya dalam sebuah urutan berdasarkan konteks yang diberikan.


## 5. **Robotics**: 
Menggabungkan AI, sensorika, dan teknologi lain untuk menciptakan robot yang dapat melakukan tugas-tugas fisik di lingkungan manusia, seperti pabrik, rumah sakit, atau ruang bencana.
### 1. **Robot Perception**: 
Menggunakan sensor untuk mengumpulkan informasi tentang lingkungan sekitar robot, termasuk pengolahan citra, pemrosesan sinyal, dan pemetaan lingkungan.

### 2. **Robot Control**: 
Menerjemahkan informasi yang diterima oleh robot menjadi gerakan fisik, termasuk perencanaan gerakan, pengendalian gerakan, dan kontrol yang adaptif.

### 3. **Robot Learning**: 
Mengembangkan metode untuk robot belajar dari pengalaman, termasuk reinforcement learning, imitation learning, dan learning from demonstration.

### 4. **Human-Robot Interaction (HRI)**: 
Mempelajari cara agar manusia dan robot dapat berinteraksi secara efektif dan intuitif, termasuk pengenalan emosi, komunikasi verbal dan non-verbal, dan keamanan dalam interaksi.

### 5. **Robot Kinematics and Dynamics**: 
Studi tentang gerakan dan gaya pada robot, termasuk perencanaan gerakan, analisis kestabilan, dan pengoptimalan gerakan.

### 6. **Robot Mechanisms**: 
Desain dan analisis struktur mekanik pada robot, termasuk manipulator robotik, sensorika, dan aktuator.

### 7. **Multi-Robot Systems**: 
Studi tentang koordinasi dan kontrol antara beberapa robot untuk mencapai tujuan bersama, termasuk pemetaan tugas, alokasi sumber daya, dan komunikasi antar robot.

### 8. **Robot Ethics and Societal Impact**: 
Menyelidiki implikasi etis dari penggunaan robot dalam masyarakat, termasuk keamanan, privasi, dan dampak sosial.

### 9. **Field Robotics**: 
Pengembangan dan penggunaan robot dalam lingkungan yang tidak terstruktur atau berbahaya, seperti pertanian, eksplorasi bawah air, atau eksplorasi luar angkasa.


## 6. **Reinforcement Learning**: 
Pendekatan dalam machine learning di mana agen belajar bagaimana mengambil tindakan dalam lingkungan untuk mencapai tujuan tertentu. Agennya diberi umpan balik positif atau negatif berdasarkan tindakan-tindakannya.
### 1. **Agent**: 
Entitas yang belajar dan berinteraksi dengan lingkungannya. Misalnya, dalam permainan, agen bisa menjadi pemain atau robot.

### 2. **Environment**: 
Dunia di mana agen beroperasi dan belajar. Lingkungan memberikan masukan kepada agen dan menerima tindakan dari agen.

### 3. **State**: 
Representasi dari kondisi lingkungan pada titik waktu tertentu. Ini bisa mencakup informasi visual atau fitur-fitur yang relevan untuk pengambilan keputusan.

### 4. **Action**: 
Tindakan yang dapat diambil oleh agen dalam lingkungan tertentu. Misalnya, dalam permainan catur, tindakan bisa berupa langkah yang mungkin diambil oleh seorang pemain.

### 5. **Reward**: 
Sinyal umpan balik yang diberikan kepada agen setelah agen melakukan tindakan tertentu. Reward menunjukkan seberapa baik atau buruk tindakan tersebut dalam mencapai tujuan.

### 6. **Policy**: 
Strategi atau aturan yang digunakan oleh agen untuk memilih tindakan berdasarkan keadaan tertentu. Tujuan utama dari reinforcement learning adalah untuk mengembangkan kebijakan yang optimal.

### 7. **Value Function**: 
Fungsi yang memperkirakan seberapa baik suatu keadaan atau tindakan dalam jangka panjang. Value function membantu agen memilih tindakan yang akan menghasilkan reward maksimum.

### 8. **Exploration vs. Exploitation**: 
Dilema dalam reinforcement learning di mana agen harus memutuskan antara mencoba tindakan baru untuk mengeksplorasi lingkungan atau memilih tindakan yang sudah diketahui untuk mengeksploitasi pengetahuan yang ada.

### 9. **Q-Learning**: 
Metode dalam reinforcement learning di mana agen belajar untuk memperkirakan reward masa depan dengan memperbarui nilai-nilai Q (yang mewakili nilai tindakan dalam keadaan tertentu) berdasarkan reward yang diterima.

### 10. **Deep Q-Networks (DQN)**: 
Pendekatan dalam reinforcement learning yang menggunakan neural networks untuk memperkirakan nilai-nilai Q, memungkinkan penanganan ruang keadaan yang lebih kompleks.


## 7. **Expert Systems**: 
Sistem komputer yang merancang pengetahuan ahli dalam bidang tertentu untuk memecahkan masalah yang biasanya memerlukan kecerdasan manusia. Expert systems menggunakan aturan-aturan untuk membuat keputusan atau memberikan solusi.

### 1. **Knowledge Base**: 
Tempat penyimpanan informasi pengetahuan yang dimiliki oleh sistem pakar, termasuk fakta, aturan, dan heuristik.

### 2. **Inference Engine**: 
Komponen yang bertanggung jawab untuk mengeksekusi aturan-aturan yang ada dalam knowledge base untuk mencapai kesimpulan atau solusi.

### 3. **User Interface**: 
Antarmuka yang memungkinkan pengguna berinteraksi dengan sistem pakar, memasukkan informasi, dan menerima jawaban atau solusi.

### 4. **Explanation System**: 
Komponen yang dapat menjelaskan kepada pengguna mengapa sistem mencapai kesimpulan atau solusi tertentu.

### 5. **Knowledge Acquisition System**: 
Proses untuk mengumpulkan, memvalidasi, dan memasukkan pengetahuan ke dalam knowledge base, sering melalui interaksi dengan ahli domain.

### 6. **Rule-Based Systems**: 
Sistem pakar yang menggunakan aturan-aturan berbasis logika untuk membuat keputusan atau memberikan solusi.

### 7. **Case-Based Reasoning (CBR)**: 
Pendekatan di mana sistem pakar menggunakan kasus-kasus yang telah dipecahkan sebelumnya untuk menyelesaikan masalah baru yang mirip.

### 8. **Fuzzy Systems**: 
Sistem yang menggunakan logika fuzzy untuk mengatasi ketidakpastian dalam pengetahuan, memungkinkan representasi yang lebih dekat dengan cara manusia berpikir.

### 9. **Neural Networks**: 
Pendekatan dalam sistem pakar yang menggunakan jaringan saraf tiruan untuk memodelkan dan mengekstraksi pola kompleks dalam data.

### 10. **Genetic Algorithms**: 
Metode optimisasi yang terinspirasi dari evolusi biologis untuk menemukan solusi yang baik dalam ruang pencarian yang kompleks.

## 8. **Knowledge Representation and Reasoning**: 
Mengembangkan representasi pengetahuan yang memungkinkan sistem AI untuk menyimpan informasi dan menggunakan pengetahuan ini untuk merencanakan tindakan dan memecahkan masalah.

### 1. **Logical Representation**: 
Representasi pengetahuan menggunakan logika matematika, seperti proposisional atau predikat, untuk menggambarkan hubungan antar entitas dalam domain pengetahuan.

### 2. **Semantic Networks**: 
Representasi pengetahuan menggunakan graf yang menggambarkan entitas sebagai node dan hubungan antara entitas sebagai edge.

### 3. **Frames**: 
Representasi pengetahuan yang mengorganisir pengetahuan dalam struktur hierarkis yang mirip dengan struktur dalam bahasa pemrograman.

### 4. **Ontologies**: 
Representasi pengetahuan yang menyusun pengetahuan dalam domain tertentu berdasarkan hubungan semantik antara konsep-konsep dalam domain tersebut.

### 5. **Rule-based Representation**: 
Representasi pengetahuan menggunakan aturan-aturan logika yang menyatakan hubungan antar entitas atau kondisi-kondisi tertentu dalam domain pengetahuan.

### 6. **Probabilistic Representation**: 
Representasi pengetahuan yang memperhitungkan ketidakpastian dalam informasi, menggunakan model probabilitas untuk menggambarkan keyakinan terhadap fakta-fakta atau hubungan-hubungan dalam domain.

### 7. **Temporal Representation**: 
Representasi pengetahuan yang memperhitungkan aspek temporal, seperti perubahan dalam keadaan atau hubungan antar entitas dari waktu ke waktu.

### 8. **Qualitative Representation**: 
Representasi pengetahuan yang menggambarkan hubungan-hubungan kualitatif antar entitas, seperti lebih besar dari atau mirip dengan.

### 9. **Spatial Representation**: 
Representasi pengetahuan yang memperhitungkan hubungan-hubungan spasial antar entitas, seperti dekat dengan atau di dalam.

### 10. **Inference Mechanisms**: 
Teknik-teknik untuk melakukan penalaran atau kesimpulan berdasarkan representasi pengetahuan yang ada, seperti penalaran logis, penalaran berbasis aturan, atau penalaran berbasis kasus.

