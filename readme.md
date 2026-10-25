# Parallel Fault Diagnosis Model Based on 2D-SWinTransformer + 1D-CNN-SENet

To meet the needs of high-level papers and graduation theses, we introduce an improved model based on the visual top conference paper SWinTransformer, along with experiments conducted on the CWRU West China University bearing dataset and Southeast University bearing dataset, as well as related comparative experiments and model ablation experiments. Experiments have proven that our model possesses exceptional classification and generalization capabilities! The innovation is high, the experiments are rich, and the workload is substantial, sufficient to support a high-level journal paper and graduation thesis!
● Datasets: CWRU West China University bearing dataset, Southeast University bearing dataset
● Environment framework: Python 3.9, PyTorch 1.8 or higher versions can run
● Accuracy: Test set 100% (CWRU), Test set 99% (Southeast University)
● Provided experiments: Comparative experiments, ablation experiments, generalization experiments
● Target users: Those requiring papers or graduation theses
● Code guarantee: Code comments are detailed and ready to run without modification.
\t\tNote: We also provide accompanying models explanations (for learning network structures) and parameter tuning explanations! For those who need a graduation design or a small paper, this is essential. The module is rich, the innovation is high, and the performance is excellent!!
A high-innovation model based on 2D-SWinTransformer + 1D-CNN-SENet
Innovation is high, the effect is evident! Innovation points:
1. Preprocessing part: Combining Fast Fourier Transform (FFT) and Variational Mode Decomposition (VMD) for signal time-frequency and domain feature extraction, which can mine multi-scale features in fault signals;
2. We creatively propose to perform 2D convolution learning on one-dimensional fault signals without converting them into two-dimensional images (which would complicate things), utilizing their window attention mechanism to extract local features from fault signals.
3. The multi-scale features are simultaneously processed through a 1DCNN convolutional pooling network optimized with channel attention mechanisms, enabling the model to automatically learn the importance of different channels and strengthen the learning of global signal features.
4. Subsequently, the local features and global spatial features extracted by both branches are fused through adaptive average pooling, enabling the model to better integrate feature representations at different levels, thereby enhancing model performance and generalization capabilities.
Preface
This paper preprocesses the data of bearings from Case Western Reserve University (CWRU) and Southeast University using Fast Fourier Transform (FFT) and Variational Mode Decomposition (VMD). Finally, it implements a feature fusion model based on 2D-SWinTransformer + 1D-CNN-SENet for fault classification.
1. Generalization Experiments - Western Reserve University Dataset
1.1 Set parameters and train the model
1.2 Model Evaluation
Accuracy, Precision, Recall, F1 Score
\tFault classification confusion matrix:
\tOther visualizations:
(1) Classification Label Visualization
(2) Original Data t-SNE Feature Visualization
\t  
(3) t-SNE feature visualization after model training:
\t  
(4) Visualization of the Model Training Process:
\t  
2. Generalization Experiments - Southeast University Bearing Dataset
2.1 Set parameters and train the model
2.2 Model Evaluation
Accuracy, Precision, Recall, F1 Score
\tFault 5 Classification Confusion Matrix:
\tOther visualizations:
(1) Classification Label Visualization
(2) Original Data t-SNE Feature Visualization
(3) t-SNE feature visualization after model training:
3. Model Comparison Experiment - Southeast University Bearing Dataset
Compare with conventional deep learning models.
The experimental results are shown in the table, and CNN-based convolutional networks performed better than LSTM and TCN models used for time series tasks on the Southeast University bearing dataset; Transformers showed good performance due to their structural advantages and attention mechanisms. Compared with common deep learning models, our innovative model achieved the best results!
Based on the window attention mechanism of SwinTransformer combined with channel attention optimization of 1DCNN network, it can better integrate feature representations at different levels, making the model focus more on important features and improve model performance and generalization ability.
Model ablation experiment - Southeast University bearing dataset
Model module ablation experiment
Not all models dare to conduct ablation experiments. Our innovative model has passed the test of ablation experiments, showing that different modules have a significant effect on improving the experimental results!
Summary:
We creatively propose a VMD-FFT preprocessing method, a parallel diagnostic model of 2D-SwinTransformer+1DCNN-SENet, which performs excellently on multiple datasets and has good generalization performance! Through extensive comparative verification work such as contrast experiments and ablation experiments, it can be demonstrated that our proposed model performs significantly on bearing fault diagnosis tasks with high innovation!
Previously interesting content:
Python-Kansas State University (CWRU) bearing data interpretation and classification processing
Python bearing fault diagnosis (Part I): Short-time Fourier Transform STFT
Python bearing fault diagnosis (Part II): Continuous Wavelet Transform CWT
Python bearing fault diagnosis (Part III): Empirical Mode Decomposition EMD
Pytorch-LSTM bearing fault one-dimensional signal classification (Part I)
Pytorch-CNN bearing fault one-dimensional signal classification (Part II)
Pytorch-Transformer bearing fault one-dimensional signal classification (Part III)
Python Bearing Fault Diagnosis (IV) - Fault Classification Based on EMD-CNN
Python Bearing Fault Diagnosis (V) - Fault Classification Based on EMD-LSTM
Python Bearing Fault Diagnosis (VI) - Fault Classification Based on EMD-Transformer
Python Bearing Fault Diagnosis (VII) - Fault Classification Based on EMD-CNN-LSTM
Python Bearing Fault Diagnosis (VIII) - Fault Classification Based on EMD-CNN-GRU Parallel Model
Fault Identification Model for Bearing Faults based on FFT + CNN - BiGRU-Attention, Time and Frequency Feature Attention Fusion
Fault Identification Model for Bearing Faults based on FFT + CNN - Transformer, Time and Frequency Feature Fusion
Python Bearing Fault Diagnosis (IX) - Fault Classification Based on VMD+CNN-BiLSTM
Python Bearing Fault Diagnosis (X) - Fault Classification Based on VMD+CNN-Transformer
Python Bearing Fault Diagnosis (XI) - Fault Classification Based on VMD+CNN-BiGRU-Attention
Cross Attention Fusion of Time and Frequency Features for Fault Identification Model based on FFT + CNN - BiLSTM-CrossAttention
Cross Attention Fusion of Time and Frequency Features for Fault Identification Model based on FFT + CNN-Transformer-CrossAttention
Introduction to Python Bearing Fault Diagnosis
Python Bearing Fault Diagnosis (XIII) - Super-strong Machine Learning Recognition Model Based on Fault Signal Feature Extraction
Python Bearing Fault Diagnosis (XIV) - Highly Innovative Fault Recognition Model
Python Bearing Fault Diagnosis (XV) - One-Dimensional Fault Signal Recognition Model Based on CNN-Transformer
Python Bearing Fault Diagnosis (16) High-Innovation Fault Identification Model (II)  
SCI 1 Zone High-Innovation Bearing Fault Diagnosis Model!
Python Bearing Fault Diagnosis (18) Innovative Diagnosis Model Based on CNN-TCN-Attention  
High-Innovation Bearing Fault Diagnosis Model Based on GADF+Swin-CNN-GAM  
Attention Magical Modification | Superior Bearing Fault Diagnosis Model!  
Bearing Fault—Cross Attention Innovative Model Full Set  
Python Bearing Fault Diagnosis (19) Innovative Diagnosis Model Based on Transformer-BiLSTM  
END  
\t2. Friends who like this can click to follow, give the article a "like", share in the circle of friends or discuss groups.

## Images

[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](01.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](02.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](03.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](04.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](05.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](06.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](07.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](08.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](09.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](10.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](11.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](12.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](13.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](14.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](15.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](16.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](17.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](18.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](19.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](20.png)
[ | Based on 2D-SWinTransformer + 1D-CNN-SENet Parallel Fault Diagnosis Model](21.png)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
