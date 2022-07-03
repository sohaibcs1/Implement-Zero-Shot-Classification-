# Implement-Zero-Shot-Classification

Zero-shot classification is a technique that allows us to associate an appropriate label with a piece of text. A zero-shot model allows us to classify data that has not been previously used to build the model.
it uses a model built by other people, against your data!<br>
I test the model on santance and find that The model has successfully performed a multi-class classification. It has classified the sentence to be of the category of dancing (98%), and entertainment (87%) as well.

We use the facebook/bert-large-nli model from the Zero Shot text Classification. Noticed that the this model perform better.<br>

for example we want to classify the santance "Dance is a performing art form consisting of sequences of movement, either improvised or purposefully selected. This movement has aesthetic and often symbolic value.[nb 1] Dance can be categorized and described by its choreography, by its repertoire of movements, or by its historical period or place of origin."
