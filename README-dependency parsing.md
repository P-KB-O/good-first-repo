### dependency parsing


#### Stanford CoreNLP

https://web.stanford.edu/~jurafsky/slp3/14.pdf

https://blog.csdn.net/haoronge9921/article/details/105795834

enable CoreNLP server:
``` shell
java -mx4g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer \
-preload tokenize,ssplit,pos,lemma,ner,parse,depparse \
-status_port 9000 -port 9000 -timeout 15000 &
```
and input **http://localhost:9000/** on you web browser, then you can paser some sentences.
<img width="1455" alt="image" src="https://user-images.githubusercontent.com/85916131/181723515-17f0b168-da0b-4fea-9462-e04a80127464.png">

if you wanna process data in a batch way, you can refer to this [code](https://github.com/P-KB-O/bio-misc/blob/main/DependencyParser/stanfordParser.py)
