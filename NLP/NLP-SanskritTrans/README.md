# Sanskrit to English Translator
Natural language processing is a popular machine learning technique these days for translating texts from one language to another. Currently, tools are available to translate most common or popular languages such as German, Hindi, Punjabi, and Spanish. However, a translation tool does not exist for Sanskrit. Sanskrit is an ancient language that is one of the 22 official languages in the Eighth Schedule of the Indian Constitution. It is a very important language for the Hindu religion as it still is used in texts and chants to this day. Also, according to the 2001 census of India, Sanskrit has about five million speakers (as a first, second, or third language), so an effective, automated written translator of full sentences would be widely useful. Therefore, the aim of SanTran is to train an Sanskrit-English sentence translation model. Among the many different languages already translated, Sanskrit is one language that is still missing effective tools for full translation. There are numerous online dictionaries for Sanskrit-English word-by-word translation, but there is no full-fledged translator which takes the context and grammar of sentences into account. 

Machine Translation is an active but well-developed field of data science; there are already a host of techniques and models that have been tried and tested on numerous languages for full translation. Applying some of these to Sanskrit specifically would be challenging and interesting. Sanskrit has a non-Latin alphabet, but also an intermediate “Transliteration” language - called IAST - which is made up of Latin characters. This could be used to translate texts using existing models.

The model uses what is commonly known as Encoder-Decoder LSTM, where LSTM refers to Long-Short Term Memory. LSTM is a specialized version of a recurrent neural network. It works by understanding each word in a sentence based on your understanding of previous words. The context of the sentence helps aid the understanding of what each word within the sentence should be. Recurrent neural networks use loops to allow information to persist in future occurrences. LSTM allow for learning of long-term and short-term dependencies. The model also consists of an encoder-decoder, two submodels. The encoder is responsible for generalizing and summarizing the semantics between many languages. Whereas the decoder is responsible for predicting an output sequence within the given language, one character per iteration of the recurrent neural network.

### Prerequisites
Tensorflow
Jupyter-Notebook from anaconda distribution

## Authors

* **Shivani Kohli** 

* **Charlie Morley** 

* **Shivam Tharkar** 

* **Ben Wazlack** 

* **Brandon** 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Nemzy. Based on his original code





