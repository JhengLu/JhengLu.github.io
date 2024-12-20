---
title: "Automatic Information Extraction for Financial Events by Integrating BiGRU and Attention Mechanism"
excerpt: "<strong>Jiaheng Lu</strong> and Weirong Liu. 
<br><em><strong>Journal of Physics: Conference Series, International Conference on Computer, Big Data and Artificial Intelligence</strong></em>, 2022
<br>[<a href='https://iopscience.iop.org/article/10.1088/1742-6596/2171/1/012001'>Paper</a>], [<a href='https://github.com/JhengLu/Cause-Effect-Relation-Extraction-from-Text-of-Financial-Events'>Code</a>]"
collection: publications
---

[//]: # (**Jiaheng Lu** and Weirong Liu.)

[//]: # (<br>*Journal of Physics: Conference Series, International Conference on Computer, Big Data and Artificial Intelligence*, 2022)

[//]: # (<br>[[Paper]&#40;https://iopscience.iop.org/article/10.1088/1742-6596/2171/1/012001&#41;], [[Code]&#40;https://github.com/JhengLu/Cause-Effect-Relation-Extraction-from-Text-of-Financial-Events&#41;])


<h2>Abstract</h2>
In this paper, an information extraction method for financial events written in Chinese is proposed. The core entities of the causes and results, as well as the verbs and
conditions are extracted from the financial events reported by websites. The method takes the original words and the part-of-speech of words as two inputs. BERT encoder is utilized to
transform the original sentences to word-embedding vectors, which then are send to BiGRU to extract the sematic features. And a full-connected network is overlapped on BiGRU to reduce
the impact of “covariate shift”. For the second input, the original sentences are cut by Chinese cut-word tool ‘jieba’ to get the part-of-speech of words, which are then transformed by
self-attention mechanism to get global dependencies. The two outputs for word-embedding vectors and part-of-speech of words are combined and then decoded by CRF. Finally, the
Viterbi algorithm is utilized to get the best sequences. The experiment results validate the effectiveness of the proposed method.

<br>
<img src='/images/NLP-arch-new.jpg'>

<p><center><b>Architecture</b></center></p>

**Materials**
<ul>
<li><a href="https://iopscience.iop.org/article/10.1088/1742-6596/2171/1/012001">Paper</a></li>
<li><a href="https://github.com/JhengLu/Cause-Effect-Relation-Extraction-from-Text-of-Financial-Events">Code</a></li>
</ul>
