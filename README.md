# BnPC: A Gold Standard Corpus for Paraphrase Detection in Bangla, and its Evaluation

This is the official repository of the paper titled **"[BnPC: A Gold Standard Corpus for Paraphrase Detection in Bangla, and its Evaluation](https://aclanthology.org/2024.bucc-1.8/)"**, accepted in ***The 17th Workshop on Building and Using Comparable Corpora (BUCC 2024)*** co-located with ***LREC-COLING 2024***. It contains the codes and the dataset.

## Abstract

In this paper, we present a benchmark dataset for paraphrase detection in Bangla. Despite being the sixth most spoken language in the world, paraphrase identification in Bangla is barely explored. Our dataset contains 8,787 human-annotated sentence pairs collected from 23 newspaper outlets’ headlines in four categories. We explored several supervised modeling approaches to benchmark the dataset, including similarity metrics, linguistic features, and fine-tuned BERT models. We also conducted a zero-shot analysis to assess the performance of pre-trained BERT models, and we carried out both zero-shot and few-shot evaluations of the publicly accessible generative language model GPT 3.5 turbo. In the benchmark evaluations, when examining GPT-3.5 using a few-shot modeling approach, it becomes evident that the model can grasp paraphrases in a manner akin to fine-tuned mBERT language models with just a handful of example data points. Within the set of benchmarking trials, the fine-tuned BanglaBERT delivered the most remarkable performance, achieving a weighted-F1 score of 87.91. Noteworthy is that GPT-3.5 excelled in both zero-shot and few-shot experiments, attaining weighted-F1 scores of 51.51 and 80.53, in that order. We also performed a cross-dataset analysis and the outcomes suggest that the model trained in our dataset resembles both diversity and generalization when tested on the other dataset. Finally, we report a human evaluation experiment to obtain a better understanding of the paraphrasing task’s limitations.

## Dataset Overview

The dataset consists of the following columns:
- **sentence1**: First sentence.
- **sentence2**: Second sentence.
- **label**: 1 denotes paraphrase and 0 denotes non-paraphrase.

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
