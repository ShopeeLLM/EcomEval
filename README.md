# EcomEval
EcomEval is comprehensive multilingual and multimodal benchmark for evaluating LLMs in e-commerce. EcomEval covers six categories and 37 tasks. It spans seven languages (English, Chinese, Indonesian, Vietnamese, Thai, Malay, Portuguese), addressing low-resource settings and reflecting the global breadth of online e-commerce.
Our paper is [here](https://arxiv.org/abs/2510.20632).

# Task Categories
EcomEval benchmark, encompass six primary categories—Ecom Question Answering, Shopping Concepts, User Understanding, Shopping Reasoning, Ecom Generation,
and Ecom Multimodal—covering both user and merchant-oriented tasks.

# Dataset Construction Pipeline
The process consists of four stages:
(1) collecting API call logs and website queries from LLM usage; <br>
(2) clustering API data via
prefix grouping and classifying website data with a fine-tuned model to form 37 representative task
categories; <br>
(3) verifying that sampled questions are e-commerce–relevant, coherent, and unambiguous;<br>
(4) generating and fact-checking answers with LLMs, external sources, and human expert review
across multiple languages. 


## Citation
If you find the dataset in our project is useful, please consider citing our work as follows:   
```
@article{EcomEval,
      title={EcomEval: Towards Reliable Evaluation of Large Language Models for Multilingual and Multimodal E-Commerce Applications}, 
      author={Shuyi Xie and Ziqin Liew and Hailing Zhang and Haibo Zhang and Ling Hu and Zhiqiang Zhou and Shuman Liu and AnXiang Zeng},
      journal={arXiv preprint arXiv},
      url={https://arxiv.org/abs/2510.20632},
      year={2025}
}
```
