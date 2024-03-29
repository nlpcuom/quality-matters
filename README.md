# Quality Does Matter: A Detailed Look at the Quality and Utility of Web-Mined Parallel Corpora
This repository contains code for the paper **Quality Does Matter: A Detailed Look at the Quality and Utility of Web-Mined Parallel Corpora(2024)**. If you have any questions, please feel free to create a Github issue .

## Models
We used fairseq library to train our vanilla transformer models. 
|Model Name|  English -> Sinhala | English -> Tamil |
|--|--|--|
| NLLB cleaned translators top_25K | [link](https://drive.google.com/drive/folders/1ea3QO0LXvL6oevSXitlfKKsmzODlsWpI?usp=sharing)|[link](https://drive.google.com/drive/folders/12S2KwFgafD_yORd2tty6yh80-S15X5Aq?usp=sharing)
| NLLB cleaned translators complete|[link](https://drive.google.com/drive/folders/1ea3QO0LXvL6oevSXitlfKKsmzODlsWpI?usp=sharing) |[link](https://drive.google.com/drive/folders/12S2KwFgafD_yORd2tty6yh80-S15X5Aq?usp=sharing)

## Data
The translator cleaned data is now released,
|Dataset Name| Language direction |Link
|--|--|--|
| NLLB Cleaned | English -> Sinhala |[link](https://huggingface.co/datasets/NLPC-UOM/nllb-top25k-ensi-cleaned)
| NLLB Cleaned | English -> Tamil |[link](https://huggingface.co/datasets/NLPC-UOM/nllb-top25k-enta-cleaned)

## Todo

 1. ~~Upload links to data sets~~
 2. ~~Update links to models~~
 3. Release code for filtering data using LASER3
 4. Release notes on how to train data in fairseq library

## Citation

```
@misc{ranathunga2024quality,
      title={Quality Does Matter: A Detailed Look at the Quality and Utility of Web-Mined Parallel Corpora}, 
      author={Surangika Ranathunga and Nisansa de Silva and Menan Velayuthan and Aloka Fernando and Charitha Rathnayake},
      year={2024},
      eprint={2402.07446},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
