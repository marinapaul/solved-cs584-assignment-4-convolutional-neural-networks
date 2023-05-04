Download Link: https://assignmentchef.com/product/solved-cs584-assignment-4-convolutional-neural-networks
<br>
Homework assignments will be done individually: each student must hand in their own answers. Use of partial or entire solutions obtained from others or online is strictly prohibited. Electronic submission on Canvas is mandatory.

<ol>

 <li><strong>Document Classification </strong>(50 points) Implement a Convolutional Neural Network with word embeddings to classify paragraphs into three categories. Use the data in the first assignment.

  <ul>

   <li>Preprocess the train and validation data, build the vocabulary, tokenize, etc.</li>

   <li>Initialize parameters for the model</li>

   <li>Implement the forward pass for the model. Use an embeddings layer as the first layer of your network (i.e. nn.embedding lookup). Set zero paddings to the input matrix.</li>

   <li>Calculate the loss of the model (cross-entropy loss is suggested).</li>

   <li>Set up the training step: use a learning rate of 1<em>e</em>− 3 and an adam optimizer.</li>

   <li>Train you model and report the classification error on validation/test data.</li>

  </ul></li>

 <li><strong>Sentiment Analysis </strong>(50 points)</li>

</ol>

This is a standard Rotten Tomatoes dataset with sentiment annotations, deriving from the paper (which you’ll need to cite, if you use the dataset): <em>Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank, Socher et al., Conference on Empirical Methods in Natural Language Processing (EMNLP, 2013).</em>

Use the train, validation, test data split defined in the data. Report your root mean square error on the sentiment label prediction.