# Generating text with recurrent neural networks

In this repository you'll find a notebook and some data about my explorations with regards to generating text with RNNs.

## Example: Fakespeare

Shakespeare has a relatively large body of writing available, all of it in the public domain: thus, this makes his work an attractive source of data to train an RNN. Here is an example with 20 epochs of training:

```
ROMEO: Did use thee fair?

BENVOLIO:
Do count us grand it: but 'tis well:
In truth, sir; but the common rack with oath!
Tendering me to the garteous labour.

WARWICK:
I I last to-day, the vanity and double on
the human car above that gamps about,
And were her lips, how he not heard
The gamporr's maintily woo'd amazed: the unacowned silence
Upon their very house; thou hast
Wasted to thyself, but so defend thee.

CLIFFORD:
Come, couna with me well, and both be so long,
'Waving their fortune's to that Bolingbroke
Hath throw'd to harve thee as we do.

POMPEY:
Plentague, my lord; and weep you plain, I would know

KING RICHARD III:
Look on her! not a warning sense.

TRANIO:
Now is the Vincentio.

BAPTISTA:
And I could wish I do welcome for it.

JULIET:
Hath been God's knigns; we are comforter, no more;
Amen, amaz, to put Both obedient heir
A hope to give against yourself in thing,
And most cheer to the Tarquis rinisher.

GLOUCESTER:
At that may be!
Be as this own vassal hands, will you seek to
do.
```

Sentences often aren't grammatical and made-up words pop up frequently, but the RNN has learned the script structure of Shakespeare's writing well.

Please see the notebook for sources of data and inspiration, as well as to play with the models for yourself.
