# Fake-News-Detection Chrome Extension

This Chrome Extension helps users identify fake news and clickbait headlines. The extension, developed under the guidance of Professor Che Lin at National Taiwan University, uses Natural Language Processing (NLP) and machine learning to analyze headlines and articles for accuracy. 

## Demo image

<img width="498" alt="截圖 2023-03-07 下午10 18 10" src="https://user-images.githubusercontent.com/80436454/226223259-1f8c9e2d-b27c-4c4e-b49d-70ac292283f5.png">
<img width="467" alt="截圖 2023-03-07 下午10 17 56" src="https://user-images.githubusercontent.com/80436454/226223265-5188bcd3-5a93-472e-8f2c-399efbd03a01.png">

## Features

- **Cross-Language Translation:** Users input Chinese headlines, which are automatically translated into English to search for corresponding articles on international news and fact-checking websites, aiming to address misinformation due to loss in translation or malicious intent across languages.
  
- **Web Scraping:** The extension crawls relevant fact-check websites and credible news sources to gather articles for analysis. Each article's publication date, title, tags, and summary are retrieved for further evaluation.

- **Fake News Detection:** Our custom-trained machine learning model determines whether the news is fake and detects clickbait elements in the headline.

- **Summarization:** For each crawled article, the extension generates a concise summary, making it easier for users to understand the content at a glance.

## Machine Learning

The core of the project lies in our NLP models, which have been trained on diverse datasets. We use two main models:

- **Fake News Detection Model:** This model evaluates the veracity of articles by analyzing linguistic patterns and metadata from fact-checking websites. It determines whether a given news article is likely to be fake based on the content and structure.

- **Clickbait Detection Model:** In addition to fake news detection, we trained a model specifically to identify clickbait headlines. The model analyzes various features of the headline to determine whether it is designed to mislead or sensationalize content.

The main goal of this project is to bring these models into practical use. By integrating them into a Chrome Extension, we allow users to directly interact with the models in real time, providing them with valuable insights into the credibility and trustworthiness of the news they consume. The extension makes it easy for users to receive instant feedback on the articles they are reading, bridging the gap between machine learning theory and everyday application.

The training process for both models, available as an `.ipynb` notebook in this repository, outlines the steps taken to build and refine them, including data preprocessing, model selection, and evaluation metrics.

## Usage

- Enter a Chinese news headline in the extension popup.
- The extension will translate the headline and search for corresponding articles on international news websites.
- The model will analyze the articles and provide a fake news likelihood score along with a summary of the findings.

## Contributing

Feel free to submit issues and pull requests. We welcome contributions to improve the detection accuracy or expand functionality.


