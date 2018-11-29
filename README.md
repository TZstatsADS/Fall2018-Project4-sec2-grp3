# Project: OCR (Optical Character Recognition) 

![image](figs/intro.png)

### [Full Project Description](doc/project4_desc.md)

Term: Fall 2018

+ Team # 3
+ Team members
	+ Samuel Kolins (sk3651)
	+ Sheng Wang (sw3224)
	+ Jiaxi Wu (jw3588)
	+ Yan Wang (yw3177)
	+ Wanyi Zheng (wz2409)
+ Paper: C1 + D3

+ Project summary: In this project, we created an OCR post-processing procedure to enhance Tesseract OCR output. The fisrt step is detecting garbage out from the OCR output by extracting features, also building and training SVM models to predict the garbage label for all tokens. For the error correction part, among those errors that detectable, the set of binary digrams can be used to attempt correction.  
	
**Contribution statement**: 
+ Error detection: Wanyi Zheng(main), Samuel Kolins and Yan Wang
+ Error correction: Jiaxi Wu
+ Evaluation: Wanyi Zheng(main), Jiaxi Wu(main), Sheng Wang and Samuel Kolins
+ Presentation: Samuel Kolins

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
