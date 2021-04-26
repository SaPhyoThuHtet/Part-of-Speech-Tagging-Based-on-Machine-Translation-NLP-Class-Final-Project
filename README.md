# Part-of-Speech-Tagging-Based-on-Machine-Translation--NLP-Class-Final-Project
This compares the performances achieved by Phrase-Based Statistical Machine Translation system (PBSMT), Neural Machine Translation based on sequence model of LSTM (Long Short Term Memory), and Attention-Based Neural Machine Translation systems when translating Part-Of-Speech tagging (POS tagging) in Myanmar Language.  Part-Of-Speech tagging is essential in natural language processing: most NLP tasks such as building lemmatizers, text classification, spelling checkers, and others require POS Tagging as a foundation step. The three approaches use parallel data Myanmar-POS tagging corpus with word segmented 10k text. Through the research, PBSMT outperforms NMT. PBSMT also has a much higher evaluation score in comparison. The evaluation process of this research uses metrics RIBES score, BLEU score, and ChrF++. The result shows the Statistical approach outperforms Neural Machine Translation based on the data used in this research.


Introduction
Part of speech is a category to which a word is assigned by its syntactic functions and so the POS tagging is the activity of marking up a word in a text (corpus) as corresponding to a particular part of speech. Part of Speech tagging (also known as Grammatical tagging) is one of the most important NLP research processes. POS also is an important port in Linguistics. As it has a relationship with adjacent and related words in a phrase, sentence, or paragraph, Part-Of-Speech Tagging stands as a fundamental role in NLP research processes. Myanmar is one of the most spoken languages in Myanmar by the people in plain and also a sub-language for most people of the hills and belongs to the subfamily of Sino-Tibetan languages.
Myanmar is one of the under-resourced languages and there is no exact rule for word boundaries. Myanmar Language also needs to be POS tagged(Grammatical tagging). Like other translations (E.g. English to Spanish), Myanmar and POS tags can use the machine translation approach. Myanmar sentence is input as source language and POS would be the target language. For example,
ဦးသန့် အား ၎င်း မွေးဖွား ရာ ပန်းတနော် မြို့ ကို ရည်စူး ၍ ပန်းတနော် ဦးသန့် ဟု အမည်တွင် ခဲ့ သည် ။
n ppm pron v part n n ppm v conj n n part v part ppm punc
