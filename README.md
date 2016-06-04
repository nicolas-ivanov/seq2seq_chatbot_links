## NN-chatbot links

Links to the implementations of neural conversational models for different frameworks.
Contributions are welcomed.

___
**Keras**

##### [farizrahman4u/seq2seq](https://github.com/farizrahman4u/seq2seq)
The most popular implementation of Seq2seq archintecture on GitHub. 
However there is still no evidence of getting good results with this repo.

##### [nicolas-ivanov/debug_seq2seq](https://github.com/nicolas-ivanov/debug_seq2seq)
A wrapper for [farizrahman4u/seq2seq](https://github.com/farizrahman4u/seq2seq) used for running experiments. No good results were achieved so far.

##### [codekansas/keras-language-modeling](https://github.com/codekansas/keras-language-modeling)
Need to check this up.

___
**Lasagne**

##### [nicolas-ivanov/lasagne_seq2seq](https://github.com/nicolas-ivanov/lasagne_seq2seq)
The model manages to learn language on syntactical level:

    what do you think about bill gates ?         →  you ' re not a little man , baby . .
    what happens if machines can think ?         →  i ' m going to be a lot of your wife
    what is the greatest novel every written ?   →  what are you doing ?
    have you hurt anyone ?                       →  i can ' t believe it .

___
**Torch**
##### [macournoyer/neuralconvo](https://github.com/macournoyer/neuralconvo)
Probably the best results currently achieved with an open-sourced Seq2seq implementation:

    Hello?					→ Hi.
    How are you?			→ I'm fine.
    What's your name?		→ It's hard to describe.
    How so?					→ I'm not sure.
    What color is the sky?	→ It's blue.
    What is your job?		→ It's not that i'm a fucking werewolf!

___
**Tensorflow**

##### [nicolas-ivanov/tf_seq2seq_chatbot](https://github.com/nicolas-ivanov/tf_seq2seq_chatbot)
Modified code of [machine translation model](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/models/rnn/translate).
No answering randomisation is implemented in this code, so the models answers with the same phrase way each time:

    hello baby					→ hello
    how old are you ?			→ twenty .
    i am lonely					→ i am not
    nice						→ you ' re not going to be okay .
    so rude						→ i ' m sorry .
    are you a robot or human?	→ no .
    are you better than siri?	→ yes .

##### [inikdom/neural-chatbot](https://github.com/inikdom/neural-chatbot)
No good results so far.

##### [skflow/neural_translation_word.py](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/skflow/neural_translation_word.py)
Give it a try.


## Corpora
##### [AlJohri/OpenSubtitles](https://github.com/AlJohri/OpenSubtitles)
Get a lot of raw movie subtitles (~1.2Gb)


## Papers

* [\[1\] Sequence to Sequence Learning with Neural Networks][1]
* [\[2\] A Neural Conversational Model][2]

[1]: http://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf
[2]: http://arxiv.org/pdf/1506.05869v1.pdf
