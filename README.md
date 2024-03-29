# comment-filter

![](https://img.shields.io/github/license/animesh-chouhan/comment-filter.svg)
![](https://img.shields.io/pypi/pyversions/Django.svg)
![](https://img.shields.io/badge/platforms-linux--64-lightgrey.svg)

> Python script to filter and flag user comments
> Dictionary based filter to flag profanity, spamming and offensive content

## Setup

Linux:

```sh
#clone the repo
git clone https://github.com/animesh-chouhan/comment-filter.git
cd /comment-filter.git

#install python3, jupyter-notebook
sudo apt-get install python3 python3-pip
sudo pip3 install jupyter

#install dependencies
pip3 install -r requirements.txt

#running the notebook
jupyter-notebook comment-filter.ipynb

```


## Built With

* [profanity-check](https://github.com/vzhou842/profanity-check) - Python library to check for profanity or offensive language
* [VADER-Sentiment-Analysis](https://github.com/cjhutto/vaderSentiment) - Lexicon and rule-based sentiment analysis tool

## Dataset Used

* [YouTube Spam Collection v. 1](http://www.dt.fee.unicamp.br/~tiago//youtubespamcollection/)
* [LDNOOBW](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words)

## Contributing

1. Fork the repo (<https://github.com/animesh-chouhan/comment-filter/>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[wiki]: https://github.com/animesh-chouhan/yt-comment-scraper//wiki

## License
MIT License
copyright (c) 2019 [Animesh Singh Chouhan](https://github.com/animesh-chouhan). Please have a look at the [license](LICENSE) for more details.

