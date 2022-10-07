## Basic Statistics

So there are around 19998 data points and no null values are present. We have two columns in the dataset one is input
and the other is labels . Let's see one by one the analysis for each column. We can get that the label column contains 2
unique values i.e 0 and 1 or we can say as the binary class . Talking about data biased or not? it is not biased, we
compared it with a graph as well as the number of values present in the label data. The most common words in the text
are:
- Will
- Want
- Today
- Think
- One
- English
- Time

The distribution for the length of characters and number of words in the input is slightly positive skewed. Though it is
close to the bell shaped curve Both (length of input and number of words) (CDF and PDF) the distributions almost follow
the same pattern. The part of speech being used the maximum number of times is Noun(NN) followed by
Preposition(IN). The overall numbers of parts of speech remains the same for input and output sentences but the
numbers vary in NNS(Noun, plural) and PRP(personal pronouns)

## Modeling
The pre-trained BERT representation can be fine-tuned through an additional output layer, thus making it suitable for the
construction of state-of-the-art models for a wide range of tasks, such as question-answering, text classification,
sentence generation etc. Loading data and tokenizer then tokenizing the sentences. Tokenizer splits the sentences into
words. using AdamW as the optimizer. With optimized parameters .

## Conclusion
With the validation score of 66.66% it should combine the current problems to improve constantly and propose a more
intelligent and accurate grammar detection model to make English teaching easier and more efficient.

#### References

https://www.kaggle.com/code/meuge672/tf-idf-and-knn-in-people-wikipedia-dataset , https://huggingface.co/docs/transformers/index,
https://towardsdatascience.com/checking-grammar-with-bert-and-ulmfit-1f59c718fe75
