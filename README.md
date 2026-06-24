# Light

This repository provides the source code used for the experiments in our IEEE Access manuscript.
The code is organized according to the experimental workflow, including data preprocessing, stacking-based models, Transformer, LSTM, baseline comparison, testing, and ablation experiments.

## Repository Structure

```text
Light/
├── 00_common/
├── 01 数据处理/
├── 02 Stacking/
├── 03 Transformer/
├── 04 LSTM/
├── 05 基线对比/
├── 06 test/
└── 07 3×3/Ca_轻量 vs 全特征的 ablation/
```

## Data Availability

Due to the file size limitation of GitHub, the complete dataset is not directly included in this repository.
The data required for running the experiments can be downloaded from Baidu Netdisk:

```text
链接: https://pan.baidu.com/s/197bFCF2kZbrlhc8MOkempw?pwd=a5px
提取码: a5px
```

After downloading the data, please place it in the corresponding project directory according to the original folder structure.
## Execution Order
The code can be executed according to the following order:
1. `00_common/`
   Common functions, utility scripts, and shared configurations.
2. `01 数据处理/`
   Data preprocessing and feature organization.
3. `02 Stacking/`
   Stacking-based model training and evaluation.
4. `03 Transformer/`
   Transformer-based model training and evaluation.
5. `04 LSTM/`
   LSTM-based model training and evaluation.
6. `05 基线对比/`
   Baseline model comparison experiments.
7. `06 test/`
   Testing scripts and result checking.
8. `07 3×3/Ca_轻量 vs 全特征的 ablation/`
   Ablation experiments comparing lightweight feature settings with full-feature settings.

## Notes

Please run the scripts in the above order to reproduce the main experimental results.
Some intermediate files generated during data preprocessing are required by the subsequent model training and evaluation scripts.

Large data files are stored externally because GitHub does not allow uploading individual files larger than 100 MB.

## Citation

If this repository is helpful for your research, please cite our related paper after publication.
