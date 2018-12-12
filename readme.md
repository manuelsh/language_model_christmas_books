# A Christmas books title generator

Based on the Christmsas books dataset, a language model is trained to generate new book titles. The model will learn, character by character. It will start with some baby-talk like:

* `koormcas yor rrtstere`
* `vey caroms`
* `dig whel cald the carding a bocket ard leever's fit lternifor christmas necrimen`

After a few seconds of “learning”, it starts to write something with a bit of sense:

* `in the trevouut of christmas ques on lonemorney`
* `how to my christmas treee innmanceed and story ; twats a seut`
* `reait palgoit, a christmas gift`

And after a 5 minutes, it is able to produce some original  titles, like these ones:

* `christmas storm damage on the human heart`
* `snap-dragons : a tale of christmas eve, and other poems`
* `deterioration of christmas holly in transit and song`


The language model is based on an embedding layer and a Recurrent Neural Network (LSTM) which, based on the previous set of characters, will generate a new character until it predicts the <END> special character, which represents that a title ends there.

The model has 3.7 million parameters.
