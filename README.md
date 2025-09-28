#  Edge-Guided Multi-Scale Frequency Attention Network for Revealing the Spatial Distribution of Immune Cells in Tumor Microenvironment


##  Requirements

* torch
* torchvision 
* tqdm
* opencv
* scipy
* skimage
* PIL
* numpy

##  Usage

####  1. Training

```bash
python train.py  --root /path-to-project  --mode train
--train_data_dir /path-to-train_data   --valid_data_dir  /path-to-valid_data
```



####  2. Inference

```bash
python test.py  --root /path-to-project  --mode test  --load_ckpt checkpoint  
--test_data_dir  /path-to-test_data
```

#### 3. datasets
We evaluated the performance of EGMFA-Net on several publicly available benchmark datasets, including SEED, ClinicDB, ColonDB, ETIS, Kvasir, BKAI, CVC-300, and Synapse. The datasets originate from the following sources: SEED (\href{https://www.jseedata.com/}{SEED datasets}), ClinicDB (\href{https://polyp.grand-challenge.org/CVCClinicDB/}{ClinicDB Datasets}), ColonDB (\href{https://github.com/DengPingFan/PraNet?tab=readme-ov-file}{GitHub repository}), ETIS (\href{https://service.tib.eu/ldmservice/dataset/etis-larib-polyp-db}{ETIS datasets}), Kvasir (\href{https://datasets.simula.no/kvasir-seg/}{Kvasir Datasets}), BKAI (\href{https://www.kaggle.com/c/bkai-igh-neopolyp/data}{Kaggle competition}), CVC-300 (\href{https://drive.google.com/file/d/1Y2z7FD5p5y31vkZwQQomXFRB0HutHyao/view}{CVC-300 Datasets}) and Synapse (\href{https://www.synapse.org/#!Synapse:syn3193805/wiki/217789}{Synapse Datasets}). Further inquiries can be directed to the corresponding author.





