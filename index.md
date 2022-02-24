Paper accepted at AAAI22

## Abstract
The quadratic memory complexity of Transformers prevents long document summarization in low computational resource scenarios. State-of-the-art models need to apply input truncation, thus discarding and ignoring potential summary-relevant contents, leading to a performance drop. Furthermore, such loss is generally destructive for semantic text analytics in the legal domain. In this paper, we propose a novel semantic self-segmentation (Se3) approach for long document summarization to address the critical problems of low-resource regimes, namely to process longer inputs than the GPU memory capacity and produce accurate summaries despite the availability of only a few dozens of training instances. Se3 segments a long input into semantically coherent chunks, allowing Transformers to summarize very long documents without truncation by summarizing each chunk and concatenating the results. Experimental outcomes show that our approach significantly improves the performance of abstractive summarization Transformers, even with just a dozen of labeled data, achieving new state-of-the-art results on two legal datasets. Finally, we perform ablation studies to assess how the different components of our method contribute to the performance gain.

## Presentation Slides and Poster
[Slides](https://liveunibo-my.sharepoint.com/personal/l_ragazzi_unibo_it/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fl%5Fragazzi%5Funibo%5Fit%2FDocuments%2Fmoro%5Fragazzi%5FAAAI22%2Epdf&parent=%2Fpersonal%2Fl%5Fragazzi%5Funibo%5Fit%2FDocuments)
[Poster](https://liveunibo-my.sharepoint.com/personal/l_ragazzi_unibo_it/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fl%5Fragazzi%5Funibo%5Fit%2FDocuments%2Fmoro%5Fragazzi%5FAAAI22%5Fposter%2Epdf&parent=%2Fpersonal%2Fl%5Fragazzi%5Funibo%5Fit%2FDocuments)

## Web Application

[Se3](http://137.204.107.42:37339)

_Note: the web app is still under development!_

## Team and Contacts

* Luca Ragazzi (Ph.D. Student) - l.ragazzi@unibo.it
* Gianluca Moro (Ph.D., Assistant Professor) - gianluca.moro@unibo.it

_Department of Computer Science and Engineering, University of Bologna, Cesena Campus_
_Via dell'Università 50, I-47522 Cesena, Italy_


<script src="http://code.jquery.com/jquery-1.4.2.min.js"></script> <script> var x = document.getElementsByClassName("site-footer-credits"); setTimeout(() => { x[0].remove(); }, 10); </script>
