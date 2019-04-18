# Project: Can you unscramble a blurry image? 
![image](figs/example.png)

### [Full Project Description](doc/project3_desc.md)


+ Project summary: In this project, I created a classification engine to enhance the resolution of images. The baseline model is a GBM (Gradient Boosting Machine) model, and we used XGboost in order to enhance the images faster. In summary, for the baseline model, the time for training the model is around 53 minutes, and the time for super-resolution is around 13 minutes. For the XGboost model, the time for training the model is around 15 minutes and the time for super-resolution is around 4 minutes.

The source code of the baseline model is in [this folder](doc/main_baseline.Rmd) and the source code of the XGboost model is in [this folder](doc/main_xgb.Rmd)

This folder is orgarnized as follows.

```
proj/
├── lib/
    └──superResolution.R
    └──psnr.R
    └──test.R
    └──test_xgb.R
    └──train.R
    └──train_xgb.R
    └──feature.R
    └──cross_validation.R
├── data/
    └──SR-B
    └──SR-I
├── doc/
    └── main_baseline.Rmd
    └── main_xgb.Rmd
├── figs/
└── output/
```

Please see each subfolder for a README file.
