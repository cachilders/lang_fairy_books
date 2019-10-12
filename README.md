## Lang's Fairy Books, a corpus for the training of machines to write fairy tales
I put this corpus together some time back to explore recurrent neural nets using [torch-rnn](https://github.com/jcjohnson/torch-rnn). It is now the foundation of a larger literary project I'm developing called Billy as an extension of the folktale podcast I coproduce, [Old Wives](https://www.patreon.com/user?u=25265677).

The work of training and sampling models is left to you, but the minimum groundwork of preprocessing is represented in this repo.

### Regarding the text

This material is pulled from [Project Gutenberg](http://www.gutenberg.org/files/30580/30580-h/30580-h.htm), and has only been scrubbed of extraneous white space and extratextual matter.

It's worth noting that [these folktale collections](https://en.wikipedia.org/wiki/Lang%27s_Fairy_Books) were collated around the turn of the Twentieth Century, and as a result may consist of elements insensitive to cultural progress. As with all machine learning projects, care should be used in generating automatic content.

#### Please contribute

If you find text missing (it's possible a volume or two were missed, though I don't think so) or that does not belong (less likely), feel free to open a PR. Likewise, I'd like to see any work produced via this repo, and would welcome an index of projects and recipes should any arise.