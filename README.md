# pretrained-clinical-embeddings
Resourses of pre-trained language models on clinical texts.


## Pre-trained models

As of <u>July 8, 2019</u>, the following models have been made available:

* **ELMo**

  * **[`ELMo at 20K steps`](https://drive.google.com/a/uth.edu/file/d/1gOuS2rPCU8Dw72ghXvnboicZIJ3aSsgO/view?usp=sharing)**
  * **[`ELMo at 100K steps`](https://drive.google.com/a/uth.edu/file/d/1YIeREZKmYPL2GMNrJqAmTNZ98GWwrn0i/view?usp=sharing)**
  * **[`ELMo at 200K steps`](https://drive.google.com/a/uth.edu/file/d/1k6mAJ9UijFrs_hbTD4Nyb-Ymg1NVMZKf/view?usp=sharing)**
  * **[`ELMo at 300K steps`](https://drive.google.com/a/uth.edu/file/d/1vC7ZdT7V3hPMynVQKV7ftLjikWVaaXY3/view?usp=sharing)**

  Each `.tar.gz` file contains two items: a `.json` file of pre-training architecture and a `.hdf5` file of pre-trained weights.
  
* **BERT**

  * Large Cased Models
    * **[`at 20K steps`](https://drive.google.com/a/uth.edu/file/d/1WWT6j_rqrqGJWBgKbsGk_UUzrYtZZTnR/view?usp=sharing)**
    * **[`at 100K steps`](https://drive.google.com/a/uth.edu/file/d/1T5WLdX1B6OsNoORRLYoiG-qt2WdyqPvQ/view?usp=sharing)**
    * **[`at 200K steps`](https://drive.google.com/a/uth.edu/file/d/1WklJPDIvG901uRQTmubBmuM5S6hGq_cD/view?usp=sharing)**
    * **[`at 300K steps`](https://drive.google.com/a/uth.edu/file/d/1SU33tTZrvdbMcTV5krNuYK2I66fIx_DV/view?usp=sharing)**
    
  * Base Cased Models
    * **[`at 20K steps`](https://drive.google.com/a/uth.edu/file/d/14U59c_gYy-RFNSgJhIrQVKPUfNIujAAe/view?usp=sharing)**
    * **[`at 100K steps`](https://drive.google.com/a/uth.edu/file/d/137Bv07YOMMrALuuHIVGrgNj0LYFxryM7/view?usp=sharing)**
    * **[`at 200K steps`](https://drive.google.com/a/uth.edu/file/d/1jxZzXWALdXTijJ_BlNA5ILpPfG1o4xfV/view?usp=sharing)**
    * **[`at 300K steps`](https://drive.google.com/a/uth.edu/file/d/1v3Al8TwhEgAHc0oE-sHyUwdcQp9F5R7O/view?usp=sharing)**
    
  Each `.tar.gz` file contains a TensorFlow checkpoint (`model.ckpt.*`) including the pre-trained weights (which is actually 3 files).  We followed the authors' detailed instructions to set up the pre-training parameters therefore the pre-training architecture files `bert_config.json` are the same with released BERT models respectively.
  
  The vocabulary list (`vocab.txt`) released by Google Team consisting of 28,996 word-pieced tokens is also adopted.


## Acknowledgments

We are grateful to the authors of BERT and ELMo to make the pre-training codes and instructions publicly available. We are also thankful to the MIMIC-III team for providing valuable resources about clinical text. Please follow the [`intructions`](https://mimic.physionet.org/gettingstarted/access/) to get the access of MIMIC-III data before downloading the above pre-trained models. 


## Citation

If you use models available in this repository, we would be grateful if you would cite the paper as follows:

* Si, Yuqi, Jingqi Wang, Hua Xu, and Kirk Roberts. "Enhancing Clinical Concept Extraction with Contextual Embedding." arXiv preprint arXiv:1902.08691 (2019).

```
@article{si2019enhancing,
  title={Enhancing Clinical Concept Extraction with Contextual Embedding},
  author={Si, Yuqi and Wang, Jingqi and Xu, Hua and Roberts, Kirk},
  journal={arXiv preprint arXiv:1902.08691},
  year={2019}
}
```

