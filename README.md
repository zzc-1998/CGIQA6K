# CGIQA-6k: A Large-Scale Database for Computer Graphics Image Quality Assessment
Official repo for **'Subjective and Objective Quality Assessment for in-the-Wild Computer Graphics Images'**, accepted by **ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)**.

![](https://github.com/zzc-1998/CGIQA6K/blob/main/overview.jpg)

## Introduction

Computer Graphics Images (CGIs) are artificially generated visuals created using computer programs. They are prevalent across various platforms, from video games to streaming media. However, the quality of these CGIs often faces challenges such as poor rendering during production, compression artifacts during multimedia application transmission, and low aesthetic quality due to subpar composition and design.

## Problem Statement

Despite the widespread use of CGIs, there's a noticeable gap in the research dedicated to Computer Graphics Image Quality Assessment (CGIQA). Most Image Quality Assessment (IQA) metrics are tailored for Natural Scene Images (NSIs) and are validated on databases comprising NSIs with synthetic distortions. These metrics are not apt for evaluating in-the-wild CGIs.

## Our Solution

To bridge this gap, we introduce the **CGIQA-6k** database. It's a large-scale, in-the-wild CGIQA database consisting of 6,000 CGIs. We've conducted subjective experiments in a controlled laboratory environment to obtain accurate perceptual ratings for these CGIs.



## Features

- **Large-Scale Database**: With 6,000 CGIs, our database is one of the most extensive collections dedicated to CGIQA.
- **In-the-Wild**: Our database captures a wide variety of CGIs from real-world scenarios.
- **Accurate Perceptual Ratings**: Through rigorous subjective experiments, we ensure the ratings reflect genuine human perception.

## Usage

The onedrive download link is [here](https://1drv.ms/f/s!AjaDoj_-yWggge0HxeUlczDiEgpM0w?e=O5JWHC) 
The `database' folder contains 6,000 CGIs and the `mos.csv' file contains the subjective mean opinion scores.

## Citation

If you use the CGIQA-6k database or find our work useful, please cite our paper:

```bibtex
@article{zhang2023subjective,
  title={Subjective and Objective Quality Assessment for in-the-Wild Computer Graphics Images},
  author={Zhang, Zicheng and Sun, Wei and Zhou, Yingjie and Jia, Jun and Zhang, Zhichao and Liu, Jing and Min, Xiongkuo and Zhai, Guangtao},
  journal={Transactions on Multimedia Computing, Communications, and Applications (TOMM)},
  year={2023},
  publisher={ACM}
}
```

## Contact

For any queries or feedback, please reach out to [zzc1998@sjtu.edu.cn].






