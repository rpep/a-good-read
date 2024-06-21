# A Good Read

The BBC has an excellent radio programme called '[A Good Read](https://www.bbc.co.uk/programmes/b006v8jn)'. It goes back nearly 30 years and there have been hundreds of episodes, each of which has several celebrities and authors recommending a book each along with the host. I often like to listen to it, but couldn't find anywhere that the books had been recommended were listed online. Because it's been around a long time, the format of the descriptions isn't consistent and at different points in time, there have been more and fewer guests. I decided to have a try and using Llama locally on my Macbook Pro M2 to try and extract the information.

## Prerequisites

* Python 3.x
* Download and install `ollama`
* From the command line install the Llama 3 model with `ollama pull llama3:8b-instruct-q4_0`. The download is roughly 4GB so this may take some time.
* `virtualenv env && source env/bin/activate && pip install -r requirements.txt`
* `jupyter notebook`
