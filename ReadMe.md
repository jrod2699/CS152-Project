# Automatic Text Summarization - A Project Proposal for CS152

## Title: Automatic Text Summarization 
![image](https://github.com/jrod2699/CS152-Project/blob/gh-pages/Text-Summarization.jpg?raw=true)

## Project Description 

I will focus on building an automatic text summarizer -- a project based in the intersection between Natural Language Processing and Neural Networks. Automatic text summarization is the task of producing a concise and fluent summary while preserving key information, content, and overall meaning. In order to do this, I will be implementing an abtractive summarization approach wherein the summarizer generates new sentences from the original text -- meaning that the sentences generated might not be present in the original text. 

Text summarization can be viewed through sequence-to-sequence (Seq2Seq) modeling -- given that it involves sequencial information. The objective will be to construct a text summarizer where the input will be a long sequence of words, and the output is a concise summary of the original text (both are sequences of words). According to my research, there are major components of a Seq2Seq model: 
* Encoder
* Decoder

In the training phase, the encoder and decoder will be set up and trained to 1. read the entire input sentence sequence wherein the text is processed in order to capture the contextual infromation present in the input sentence, and 2. predict the next word in the sequence given the previous word. 

In constructing this summarizer, the hope is to gain a deeper understanding of how neural networks can help in NLP applications as well as circumvent shortcomings of the architectures used to develop the summarizer -- and hopefully remedy those shortcomings.

## Project Goals
1. Implement encoder-decoder architecture in construction of automatic text summarizer.
2. Explore other models to improve the performance of the text summarizer. 
3. Evaluate performance through an appropriate metric(TBD).
