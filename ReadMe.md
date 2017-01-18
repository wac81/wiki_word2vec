#We create word2vec model use wiki Text like this https://dumps.wikimedia.org/zhwiki/20161001/zhwiki-20161001-pages-articles-multistream.xml.bz2

##

##parameter:
=================================
    feature_size = 500
    content_window = 5
    freq_min_count = 3
    # threads_num = 4
    negative = 3   #best采样使用hierarchical softmax方法(负采样，对常见词有利)，不使用negative sampling方法(对罕见词有利)。
    iter = 20

##process.py deal with wiki*.xml

##word2vec_wiki.py : create model and load model

##and you can download trained moedel from http://pan.baidu.com/s/1bpbzt6n    password:62i2

thank you and enjoy it!
