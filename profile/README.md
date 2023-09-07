# DALAI - Using artificial intelligence to improve the quality and usability of digital records

The included repositories contain code and model files for tools developed as part of the the [DALAI project](https://kansallisarkisto.fi/en/dalai-en) (September 2021 - August 2023). The project was funded by the European Regional Development Fund’s ”Sustainable growth and jobs 2012–2020” programme and the City of Mikkeli.  

The common aim of the different tools is to facilitate the automation of the digitisation and description of cultural heritage materials which are in the holdings of archives and other memory organisations.

<!-- [Annif_API](https://github.com/DALAI-project/Annif_API)|Subject Indexing|Instructions and configuration for using [Annif](https://annif.org/) software as an API for automatic subject indexing in Finnish, Swedish and English. -->
<!-- [Document-analysis_API](https://github.com/DALAI-project/Document-analysis_API)|Combination|Code for an API that combines optical character recognition using [Tesseract](https://tesseract-ocr.github.io/), language detection using [Apache Tika](https://tika.apache.org/) and automatic subject indexing and named entity recognition using the models listed above. -->

<details>
  
  <summary>Click here for more information on the included repositories</summary>

Repository|Domain|Content
-|-|-
[CornerAPI](https://github.com/DALAI-project/CornerAPI)|Image Classification|Code for an API that detects torn corners and edges from document images.
[EmptyAPI](https://github.com/DALAI-project/EmptyAPI)|Image Classification|Code for an API that detects empty pages from document images.
[PostitAPI](https://github.com/DALAI-project/PostitAPI)|Image Classification|Code for an API that detects post-it/sticky notes from document images.
[WritingtypeAPI](https://github.com/DALAI-project/WritingtypeAPI)|Image Classification|Code for an API that classifies document images based on the writing types(s) (handwritten, typewritten, combination) they contain.
[FaultyImageAPI](https://github.com/DALAI-project/FaultyImageAPI)|Image Classification|Code for an API that combines the classification models listed above.
[NER_API](https://github.com/DALAI-project/NER_API)|Named Entity Recognition|Code for an API that performs named entity recognition from text input in Finnish.
[Train_BERT_NER](https://github.com/DALAI-project/Train_BERT_NER)|Named Entity Recognition|Code for training Finnish named entity recognition (NER) model based on [BERT](https://huggingface.co/TurkuNLP/bert-base-finnish-cased-v1) language model.
[Empty_training](https://github.com/DALAI-project/Empty_training)|Image Classification|Code for training a neural network model to detect empty pages from document images.
[Train_document_classification](https://github.com/DALAI-project/Train_document_classification)|Image Classification|Code for training a neural network model to classify input documents into distinct classes based on the type/format of the document.
[Train_fault_detection](https://github.com/DALAI-project/Train_fault_detection)|Image Classification|Code for training a neural network model to detect faults like folded corners or sticky notes from document images.
[Train_writing_type](https://github.com/DALAI-project/Train_writing_type)|Image Classification|Code for training a neural network model to classify document images based on the writing types(s) (handwritten, typewritten, combination) they contain.
[Table_segmentation](https://github.com/DALAI-project/Table_segmentation)|Image Segmentation|Code for segmenting table structures and detecting text content in document images.

</details>

Some of the tools are also available via [Arkkiivi](http://www.arkkiivi.fi/) web user interface. 
