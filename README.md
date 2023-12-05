# VulnSense

This repository presents our GPT-experiments and dataset statistics.


## GPT-Experiments

We present 18 images illustrating the classification of various vulnerability instances using the advanced GPT(The version of GPT used in our experiments is GPT-4, accessed on 8th August 2023.). These instances are categorized into two classes based on the time of their discovery: the "Seen Class" and the "Unseen Class."

### Seen Classes:
We randomly selected two instances from each of three randomly selected vulnerability types discovered before 2021, which are presumed to be part of seen classes, as GPT had been trained on extensive data up to that period. Notably, images with serial numbers 1 to 6 represent the results of experiments involving instances of the seen classes.

### Unseen Classes:
We further sampled two instances from each of three vulnerability types discovered after 2021, constituting the unseen classes. Images with serial numbers 7 to 18 represent the results of experiments involving instances from the unseen class. In images with serial numbers 7 to 12, vulnerability descriptions were not provided to GPT, while in images with serial numbers 13 to 18, vulnerability descriptions were provided to GPT.

Image Naming Convention:
Each image is labeled with a consistent naming convention: "Serial Number . Label # - GPT-4.0 Predicted Label."


## Dataset Statistics

We provide readers with detailed statistics of the dataset utilized in our experiments, including the number of instances for each class. The IDs of the classes designated as 'unseen' are highlighted in bold.

| CWE-ID | instance numbers | CWE-ID | instance numbers |
|-------|------------------|-------|------------------|
| **CWE-78**  | 455            | CWE-369 | 484            |
| **CWE-90**  | 496            | CWE-400 | 515            |
| CWE-114 | 495            | **CWE-401** | 506            |
| CWE-121 | 502            | CWE-404 | 448            |
| **CWE-122** | 470            | CWE-415 | 336            |
| CWE-123 | 168            | CWE-426 | 224            |
| CWE-124 | 502            | **CWE-427** | 560            |
| CWE-126 | 510            | CWE-457 | 496            |
| **CWE-127** | 496            | CWE-476 | 372            |
| **CWE-134** | 434            | **CWE-563** | 366            |
| CWE-190 | 489            | CWE-590 | 470            |
| CWE-191 | 469            | **CWE-606** | 501            |
| **CWE-194** | 532            | CWE-617 | 354            |
| CWE-195 | 467            | CWE-675 | 224            |
| CWE-197 | 494            | **CWE-680** | 336            |
| **CWE-252** | 479            | CWE-690 | 488            |
| **CWE-253** | 477            | CWE-758 | 365            |
| CWE-272 | 252            | CWE-761 | 511            |
| CWE-284 | 216            | CWE-773 | 168            |
| **CWE-319** | 224            | **CWE-789** | 500            |
