# ML_token_prices
This project applys machine learning models to predict crypto token prices and trends using different machine learning models to asses their perfomance.

# ML_token Application: new application 

This is a fintech tool that helps in predicting possible crypto prices using historical data.
This tool can be used by potential investors or crypto enthusiats in predicting market trends for Bitcoin (BTC), Etherium (ETH)and Solana (SOL)
 

The current project is the inital design and development of the application to get MVP that can be tested on the current market cycle.

A copy of our slide deck can be found at this link here:
[Slide Deck]((https://colab.research.google.com/github/tylergusmyers/ML_token_prices/blob/main/BTC_Pricing_Model.ipynb)  

---

## Technologies


*[Jupyter](https://jupyter.org/documentation) - For documentation
*[Logistic Regression](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression) - Documentation
*[SVM](https://scikit-learn.org/stable/modules/svm.html)
*[LSTM](https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM) - Documentation


---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install yahoofinancials  
  pip install -U scikit-learn
  conda install -c conda-forge imbalanced-learn
  conda install -c conda-forge pydotplus
  pip install --upgrade tensorflow  
    
```

---

## Usage
Please click on the url link below to run the application from Google colab

[GC_BTC_Pricing_Model](https://colab.research.google.com/github/tylergusmyers/ML_token_prices/blob/main/BTC_Pricing_Model.ipynb) 

[GC_SOL_Pricing_Model](https://colab.research.google.com/github/tylergusmyers/ML_token_prices/blob/main/SOL_Pricing_Model.ipynb)

[ETH LR_Pricing_Model](https://colab.research.google.com/drive/1nTJ-AWbKg1uWteWnP9S3coDfUAg5fVh2?usp=sharing) 

[ETH LTSM_Pricing_Model](https://colab.research.google.com/drive/1tdBSfIZxPdXqIr_aHgjkFGddWquN7o7p?usp=sharing)

[ETH SVM_Pricing_Model](https://colab.research.google.com/drive/1YorlqEyumXc2Dusp9MD-WOMAmpZJdJas?usp=sharing) 


with the:

```jupyter
from command line type

jupyter lab
```

---

## Contributors

Brought to you by:
  odhissm@gmail.com, 
  tylergusmyers@gmail.com, 
  aheesh@gmail.com, 
  

---

## License

MIT
