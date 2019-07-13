# comment-filter

![license][https://img.shields.io/github/license/animesh-chouhan/comment-filter.svg]
![](https://img.shields.io/pypi/pyversions/Django.svg)
![](https://img.shields.io/badge/platforms-linux--64-lightgrey.svg)

>Description

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


## Usage example

Sample resonse of api hosted on localhost:

<p align="center">
  <img src="https://github.com/animesh-chouhan/yt-comment-scraper/blob/master/images/sample-response-alt.png" width="700" align="center"/>
</p>

Sample comments scraped:

<p align="center">
  <img src="https://github.com/animesh-chouhan/yt-comment-scraper/blob/master/images/sample-csv.png"  width="700" align="center"/>
</p>


_For more examples and usage, please refer to the [Wiki][wiki]._


## Built With

* [profanity-check](https://github.com/vzhou842/profanity-check) - Python library to check for profanity or offensive language
* [VADER-Sentiment-Analysis](https://github.com/cjhutto/vaderSentiment) - lexicon and rule-based sentiment analysis tool

## Dataset Used

*[YouTube Spam Collection v. 1](http://www.dt.fee.unicamp.br/~tiago//youtubespamcollection/)


## Contributing

1. Fork the repo (<https://github.com/animesh-chouhan/yt-comment-scraper/>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[wiki]: https://github.com/animesh-chouhan/yt-comment-scraper//wiki

## License
MIT License
copyright (c) 2019 [Animesh Singh Chouhan](https://github.com/animesh-chouhan). Please have a look at the [license](LICENSE) for more details.

