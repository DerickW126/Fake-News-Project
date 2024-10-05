# Fake-News-Detection Chrome Extension

This Chrome Extension helps users identify fake news and clickbait headlines. The extension, developed under the guidance of Professor Che Lin at National Taiwan University, uses Natural Language Processing (NLP) and machine learning to analyze headlines and articles for accuracy. 

## Features

- **Cross-Language Translation:** Users input Chinese headlines, which are automatically translated into English to search for corresponding articles on international news and fact-checking websites.
  
- **Web Scraping:** The extension crawls relevant websites to gather articles for analysis. Each article's publication date, title, tags, and summary are retrieved for further evaluation.

- **Fake News Detection:** Our custom-trained machine learning model determines whether the news is fake and detects clickbait elements in the headline.

- **Summarization:** For each crawled article, the extension generates a concise summary, making it easier for users to understand the content at a glance.

## Machine Learning

The core of the project lies in our NLP model, which has been trained on a diverse dataset of fact-checked news and articles. This model evaluates the veracity of articles based on linguistic patterns and metadata from fact-checking websites.

The training process, available as an `.ipynb` notebook in this repository, provides insights into the steps taken to build and refine the model, including data preprocessing, model selection, and evaluation metrics.

## Demo image

<img width="498" alt="截圖 2023-03-07 下午10 18 10" src="https://user-images.githubusercontent.com/80436454/226223259-1f8c9e2d-b27c-4c4e-b49d-70ac292283f5.png">
<img width="467" alt="截圖 2023-03-07 下午10 17 56" src="https://user-images.githubusercontent.com/80436454/226223265-5188bcd3-5a93-472e-8f2c-399efbd03a01.png">

## Usage

- Enter a Chinese news headline in the extension popup.
- The extension will translate the headline and search for corresponding articles on international news websites.
- The model will analyze the articles and provide a fake news likelihood score along with a summary of the findings.

## Contributing

Feel free to submit issues and pull requests. We welcome contributions to improve the detection accuracy or expand functionality.


