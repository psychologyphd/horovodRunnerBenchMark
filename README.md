# horovodRunnerBenchMark
Authors: Jing Pan, Ph.D and Wendao Liu, doctoral student. 

This is the code for AAAI 2020 workshop 8 DLGMA paper titled "Benchmark Tests of Convolutional Neural Network and Graph Convolu-tional Network on HorovodRunner Enabled Spark Clusters". The files are exported as html format databricks notebook. To use them, please import them to databricks console.   

It has the MNIST task, Caltech 101 tasks with vgg and inception, and GCN task. We show lift in scaling efficiency other than the GCN task. For Caltech 101 task, we have an additional file to implement rectified adam optimizer with HorovodRunner. We didn't report results of rectified adam in the main paper. 

If you use any part of the code, please cite as: 

Jing Pan, Wendao Liu, Jing Zhou. 2020. Benchmark Tests of Convolutional Neural Network and Graph Convolu-tional Network on HorovodRunner Enabled Spark Clusters. In Proceedings of AAAI (AAAI Workshop Deep Learning on Graphs: Methodologies and Applications). AAAI, New York, New York, USA, 5 pages.

Paper URL on arXiv and workshop site will be updated later. 
