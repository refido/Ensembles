# Ensemble

## Evaluasi

### Decision Tree

- sebelum hyperparameters
  - Kita dapat melihat bahwa akurasi pelatihan Decision Tree adalah 0.7460429124164615 (74%). Saat menyesuaikan model yang sama untuk menguji data, akurasi turun menjadi sekitar 0.38474159146841674 (38%). Model tersebut memiliki data pelatihan yang berlebihan, dan variansnya sangat tinggi, yang menunjukkan bahwa model berperilaku berbeda untuk sampel yang berbeda.  
- sesudah hyperparameters
  - Ketika menerapkan algoritma GridSearchCV ke model yang digunakan untuk memilih hyperparameter terbaik, terlihat bahwa akurasi pelatihan sekitar 0.6315511783327471 (63%) dan akurasi pengujian sekitar 0.6222313371616078 (62%). Sementara penyetelan hyperparameters mengurangi akurasi pelatihan, itu juga mengurangi overfitting di Decision Tree.

### Random Forest

- sebelum hyperparameters
  - Kita dapat melihat bahwa akurasi pelatihan Random Forest adalah 0.7460429124164615 (74%). Saat menyesuaikan model yang sama untuk menguji data, akurasi turun menjadi sekitar 0.38474159146841674 (38%). Model tersebut memiliki data pelatihan yang berlebihan, dan variansnya sangat tinggi, yang menunjukkan bahwa model berperilaku berbeda untuk sampel yang berbeda.  
- sesudah hyperparameters
  - Ketika menerapkan algoritma GridSearchCV ke model yang digunakan untuk memilih hyperparameter terbaik, terlihat bahwa akurasi pelatihan sekitar 0.6021807949349279 (60%) dan akurasi pengujian sekitar 0.5955701394585726 (59%). Sementara penyetelan hyperparameters mengurangi akurasi pelatihan, itu juga mengurangi overfitting di Random Forest.
