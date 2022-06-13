# SeinfeldScripts

Generate Seinfeld Script using RNNs (Deep Learning Nanodegree Udacity)

![alt text](p183875_b_h10_ab.jpeg "Seinfeld poster")

# Summary

For this project we have used a dataset of Seinfeld scripts from 9 seasons. First we have preprocessed the data by building a function `create_lookup_tables` that translates unique words to ids and vice versa. Then an additional function `token_lookup` tokenized the provided punctuation symbols.

Then our data is broken into sequences with the `batch_data` function. We have defined an RNN class that contains one LSTM and one fully connected layer. The training of the RNN model was perfored in GPU and the hyperparameters were selected after a series of trial and error. The model showed improvement after every epoch and the final loss was below the target of 3.5

# Generated Script

jerry:.

kramer: well, it's just a few months ago! i mean, it's a little irritating.

newman: well, i got the whole new new one.

jerry:(pointing at george) i don't think this is a good idea.

kramer:(quietly) i think you can.

jerry: i don't want that. i don't want to go to the hospital.

kramer:(looking for his coat) hey, jerry.

elaine: hey.

jerry: hi..(he opens door with the menu on a pad of george's hand) oh my god, this is my friend..

george: i can't believe i got to talk to him.(elaine looks at kramer, he stops and a smile)

jerry:(to elaine) hey! what did you say that for?

elaine: oh, i know, i know. he has to go...

kramer:(to george) i don't want to talk to her about it.

jerry: what, you think i don't think so, i think i'm getting to do this.

george: you know, it's like a couple of people are in.

jerry: i don't know, but i can't get the money.(to the phone) hello?

jerry: hello. oh, hi.

jerry:(to george) hey, i know you were going to the dentist, and i don't want to see this.

george: i know.

elaine: i think i could have been.

jerry: i don't know.

elaine: what?

jerry: i don't know.

george: you don't know.

kramer: i don't think you should be able to get it.

george: i don't want to hear it. i'm gonna get it. you want me to be a little nervous, i don't know how you are so much, but i don't know how you are, i'm sure you don't care for you and tell
