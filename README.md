# gnews

Follow these steps on terminal:

``
git clone https://github.com/Ar9av/gnews.git
``
``
cd gnews
``
``
pip install -r requirements.txt
``


In Python IDE:

``
from gnewsclient import gnewsclient
``
``
your_search_text = "Apple" 
``
``
g = gnewsclient(query = your_search_text)
``
``
news = g.get_news()
``

``
print(news)
``