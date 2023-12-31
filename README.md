The primary objective of this exercise is to evaluate the performance of Retinal-VesselNet, a neural network with U-net architecture, on two widely used retinal image datasets - Digital Retinal Images for Vessel Extraction (DRIVE) and STructured Analysis of the Retina (STARE). These datasets have been recognized as significant benchmarks for evaluating retinal image analysis techniques. 
Furthermore, it explores two separate morphological preprocessing methods to improve vessel detection in retinal images. The first method involves applying a top-hat transformation to enhance the contrast between the vessels and the background. The second method is based on bottom-hat transformation. 
- Find the details in [```MV4-Tabatabei.pdf```](https://github.com/TahaTabatabaei/Retina-VesselNet/blob/master/MV4-Tabatabaei.pdf).
- The `/mytrain/` directory consists of scripts for training and test with DRIVE and `/stare/` is for STARE. 
- To train your own model, you can use `Training.ipynb` notebook. The pre-trained model will be added.
- Test results are in the `TestAndEvaluation.ipynb`.
- You can download DRIVE from [```here```](https://drive.grand-challenge.org/) and STARE from [```here```](https://cecas.clemson.edu/~ahoover/stare/)

