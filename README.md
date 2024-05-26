# BnPC: A Gold Standard Corpus for Paraphrase Detection in Bangla, and its Evaluation

This is the official repository of the paper titled **"[BnPC: A Gold Standard Corpus for Paraphrase Detection in Bangla, and its Evaluation](https://aclanthology.org/2024.bucc-1.8/)"**, accepted in ***The 17th Workshop on Building and Using Comparable Corpora (BUCC 2024)*** co-located with ***LREC-COLING 2024***. It contains the codes and the dataset.

## Dataset Overview

This dataset contains three columns. sentence1 and sentence2 are the sentence pairs. 

label: 1 denotes paraphrase and 0 denotes non-paraphrase.

## Sample Data

| sentence1       | sentence2 | label  |
|------------|-----|----------|
| করোনাভাইরাস থেকে মুক্তি ‘সহসাই নয়’   | দীর্ঘকাল ধরে করোনা মোকাবিলার প্রস্তুতি রাখতে হবে'  | 1      |
| করোনাভাইরাস থেকে মুক্তি ‘সহসাই নয়’ | করোনা ভাইরাস থেকে সহসাই মুক্তি পাওয়া যাচ্ছে না  | 1       |
| দীর্ঘকাল ধরে করোনা মোকাবিলার প্রস্তুতি রাখতে হবে'  | 	করোনা ভাইরাস থেকে সহসাই মুক্তি পাওয়া যাচ্ছে না  | 1   |
| সেনাবাহিনীকে উপেক্ষা করে মিয়ানমারের রাস্তায় বিক্ষোভ অব্যাহত   | মিয়ানমার সেনাবাহিনীর বিরুদ্ধে অবস্থান নিল জাতিসংঘের মানবাধিকার কাউন্সিল  | 0 |

## License
Contents of this repository are restricted to only non-commercial research purposes under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). Copyright of the dataset contents belongs to the original copyright holders.

## Citation
```
@inproceedings{saha-etal-2024-bnpc,
    title = "{B}n{PC}: A Gold Standard Corpus for Paraphrase Detection in {B}angla, and its Evaluation",
    author = "Saha, Sourav  and
      Nobin, Zeshan Ahmed  and
      Chowdhury, Mufassir Ahmad  and
      Mobin, Md. Shakirul Hasan Khan  and
      Amin, Mohammad Ruhul  and
      Kar, Sudipta",
    editor = "Zweigenbaum, Pierre  and
      Rapp, Reinhard  and
      Sharoff, Serge",
    booktitle = "Proceedings of the 17th Workshop on Building and Using Comparable Corpora (BUCC) @ LREC-COLING 2024",
    month = may,
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.bucc-1.8",
    pages = "69--84",
}
```
