# IPVQA
Agriculture is fundamental to the global economy and food security, yet insect pests significantly threaten agricultural productivity by causing direct crop damage, spreading plant pathogens, and increasing production costs due to pest control measures. Overuse of pesticides not only leads to environmental and ecological issues but also fosters pesticide resistance in pests. Advanced technologies like Visual Question Answering (VQA) offer promising solutions by combining image processing with natural language understanding, enabling efficient pest detection, crop health monitoring, and classification through natural language interaction. Existing datasets such as IP102 have advanced pest recognition but lack the question-answer pairs necessary for VQA tasks in agriculture.

To bridge this gap, this paper introduces the Insect Pest Visual Question Answering (IPVQA) dataset, specifically designed for agricultural applications. The IPVQA dataset comprises a diverse collection of high-quality images annotated with detailed question-answer pairs covering various aspects of crop health, pest identification, and agricultural practices. Our meticulous data collection and annotation process ensures the reliability and relevance of the dataset. In addition, this paper employs the latest multimodal large-language models to establish the benchmark for this dataset.

The primary contribution of the IPVQA dataset is its comprehensive coverage and innovative integration of VQA in agricultural contexts. By providing a rich source of both visual and textual information, the dataset connects advanced VQA techniques with practical agricultural needs. This not only supports current research efforts but also opens new avenues for future studies in smart farming and precision agriculture. Potential applications of the IPVQA dataset include automated pest detection systems and intelligent crop monitoring tools. In addition, the extensibility of the dataset allows it to adapt to evolving research requirements and incorporate new agricultural insights.


The original paper is: IP-VQA Dataset: Empowering Precision Agriculture with Autonomous Insect Pest Management through Visual Question Answering
Users can access the dataset by this Github file or using Google Drive link:
https://drive.google.com/drive/folders/1ZW3hrLp-ByK1zTy9Uv31m11moXOQ5i-M?usp=drive_link

# Usage
## Dataset Structure
To generate and evaluate the dataset, structure the dataset as follows:

--Dataset

|--VQA

    |---JPEGImages

    |---Polygon

    |---system_message*.txt

    |---*.ipynb


---

## Generation and Evaluation Instructions

### Generating the Dataset

Run the `caption_generation.ipynb` Notebook:

1. Open the `caption_generation.ipynb` notebook.
2. Execute each cell step by step.
3. Ensure that the file paths within the notebook are set to the correct directories on your system.

### Evaluating the Dataset

Run the `evaluation.ipynb` Notebook:

1. Open the `evaluation.ipynb` notebook.
2. Execute each cell step by step.

The evaluation process includes:

- **Distribution of Question Types**: Analyze the variety and frequency of different question types within the dataset.
- **VQA Evaluation**: Assess the performance of VQA models on the dataset.
- **Overall Evaluation**: Provide a comprehensive evaluation of the dataset's effectiveness and reliability.

---

## Requirements

- **OpenAI API Key**: Readers need to set their own OpenAI API key to run every GPT-related part of the notebooks.


# Contribution
Please raise an issue if you need help, any contributions are welcomed.

# Citation
If you use this dataset for your research or paper, please cite our paper

@inproceedings{10.1145/3701716.3718386,
author = {Jin, Kairui and Zi, Xing and Thiyagarajan, Karthick and Braytee, Ali and Prasad, Mukesh},
title = {IP-VQA Dataset: Empowering Precision Agriculture with Autonomous Insect Pest Management through Visual Question Answering},
year = {2025},
isbn = {9798400713316},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3701716.3718386},
doi = {10.1145/3701716.3718386},
abstract = {Precision agriculture is essential for social good, global economy and food security, yet insect pests threaten productivity through crop damage, pathogen spread, and rising pest control costs. The overuse of pesticides leads to environmental issues and pesticide resistance. Advanced technologies like Visual Question Answering (VQA) provide solutions by integrating image processing with natural language understanding, facilitating efficient pest detection and crop health monitoring. While datasets like IP102 have enhanced pest recognition, they lack necessary question-answer pairs for VQA tasks in agriculture. To address this gap, we introduce the Insect Pest Visual Question Answering (IP-VQA) dataset, designed specifically for precision agricultural applications. This dataset includes a diverse collection of high-quality images annotated with detailed question-answer pairs related to crop health, pest identification, and agricultural practices. Our thorough data collection ensures reliability and relevance. We also utilize advanced multimodal large language models to set a benchmark for the dataset. The primary contribution of the IP-VQA dataset lies in its comprehensive coverage and VQA integration within agricultural contexts. By providing rich visual and textual information, it connects VQA techniques to practical agricultural needs, supporting ongoing research and paving the way for future studies in precision agriculture.},
booktitle = {Companion Proceedings of the ACM on Web Conference 2025},
pages = {2000–2007},
numpages = {8},
keywords = {autonomous system., inspect pest management, ip-vqa dataset, precision agriculture, visual question answering},
location = {Sydney NSW, Australia},
series = {WWW '25}
}
