---
permalink: /projects/
title: "Projects" 
author_profile: true
---

* **Custom Sentiment Analysis with DistilBERT and DistilBertTokenizerFast**  
[\[Link\]](https://github.com/ShubhranshuPattnaik/Custom-Sentiment-Analysis-with-DistilBERT/blob/main/CUSTOM_SENTIMENT_ANALYSIS_WITH_DISTILBERT_and_DistilBertTokenizerFast.ipynb) 

    The Custom Sentiment Analysis with DistilBERT and DistilBertTokenizerFast project utilizes Pandas for data preprocessing, TensorFlow for model training, and Hugging Face's Transformers for leveraging the DistilBERT model. The aim is to classify SMS messages as either "Spam" or "Not Spam" using state-of-the-art NLP techniques.

    The model, TFDistilBertForSequenceClassification, achieved an evaluation loss of 0.0192. The confusion matrix reveals that the model effectively minimizes misclassifications, confirming its high performance and reliability in distinguishing between spam and non-spam messages. Gradio is employed to create an interactive web interface for user testing, enhancing the model's accessibility.
<style>
  .image-container {
    text-align: center;
  }

  .image-container img {
    display: inline-block;
    margin: 0;
    border: none;
    max-width: 50%;
  }

  .image-container img.large {
    height: 250px; /* Adjust height as needed */
    max-width: 100%;
  }

  .vertical-stack {
    display: block;
    margin: 0 auto;
  }
  
  .horizontal-stack {
    display: inline-block;
    vertical-align: top; /* Align images at the top */
  }
</style>

<div class="image-container">
  <!-- Horizontal stack of images -->
  <div class="horizontal-stack">
    <img src="images/p14.png" height="300" alt="Image 14">
    <img src="images/p13.png" width="350" height="300" alt="Image 13">
  </div>

  <!-- Vertical stack of images -->
  <div class="vertical-stack">
    <img src="images/p1.png" class="large"   alt="Image 1">
    <img src="images/p12.png" class="large" alt="Image 12">
  </div>
</div>


<br>

- **LLM-POWERED SUMMARIZATION APP WITH T5-SMALL**  
    [\[Link\]](https://github.com/ShubhranshuPattnaik/summarization-t5-small/blob/main/summarization_t5_small.ipynb) 

    Leveraged natural language processing to fine-tune the T5-small model using over 200,000 samples from the XSum dataset, enhancing summarization capabilities and processing more than 500,000 tokens with AutoTokenizer.
    
    Achieved notable performance metrics with ROUGE scores: ROUGE-1: 28.30, ROUGE-2: 7.72, ROUGE-L: 22.24, and ROUGE-Lsum: 22.25, indicating effective summary coherence and relevance. The training involved optimizing model performance across multiple epochs, achieving a training loss of 2.7211 and a validation loss of 2.4793 in the first epoch, with a runtime of approximately 4909 seconds and processing efficiency of 2.60 samples per second
<p align="center">
<img style="float: center;" src="/images/text.png" max-width="100%">
</p>



