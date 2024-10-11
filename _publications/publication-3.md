---
title: "Automatic Information Extraction for Financial Events by Integrating BiGRU and Attention Mechanism"
excerpt: "**Jiaheng Lu** and Weirong Liu. <br>*Journal of Physics: Conference Series, International Conference on Computer, Big Data and Artificial Intelligence*, 2022"
collection: publications
---

<h2>Abstract</h2>
In this paper, an information extraction method for financial events written in Chinese is proposed. The core entities of the causes and results, as well as the verbs and
conditions are extracted from the financial events reported by websites. The method takes the original words and the part-of-speech of words as two inputs. BERT encoder is utilized to
transform the original sentences to word-embedding vectors, which then are send to BiGRU to extract the sematic features. And a full-connected network is overlapped on BiGRU to reduce
the impact of “covariate shift”. For the second input, the original sentences are cut by Chinese cut-word tool ‘jieba’ to get the part-of-speech of words, which are then transformed by
self-attention mechanism to get global dependencies. The two outputs for word-embedding vectors and part-of-speech of words are combined and then decoded by CRF. Finally, the
Viterbi algorithm is utilized to get the best sequences. The experiment results validate the effectiveness of the proposed method.
      
<br>
**Materials**
<ul>
<li><a href="http://JhengLu.github.io/files/paper2.pdf">PDF</a></li>
<li><a href="https://github.com/JhengLu/Cause-Effect-Relation-Extraction-from-Text-of-Financial-Events">Code</a></li>
</ul>
