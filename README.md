# Propaganda_detection
The first column contains a label from a set of 9 possibilities which are 
1. flag waving
2. appeal to fear prejudice
3. causal simplification
4. doubt
5. exaggeration,minimisation
6. loaded language
7. name calling,labeling
8. repetition
9. not propaganda

   
The first 8 labels are all propaganda techniques and are a subset of those identified in the Propaganda Techniques Corpus (Da San Martino et al., 2020). The final label not propaganda indicates that no propaganda has been identified in the text. The second column contains a sentence or chunk of text where the propaganda technique has been identified (or no propaganda has been identified in the case of not propaganda). Note the use of additional tokens <BOS> and <EOS> which indicate the beginning and end of the span of text (within the sentence) which is actually annotated with the given propaganda technique. In the first example above, the span of text “our soldiers” has been identified as an example of flag waving in the context of the sentence “I want to get our soldiers out.”

Giovanni Da San Martino, Alberto Barr ́on-Ceden ̃o, Henning Wachsmuth, Rostislav Petrov, and Preslav Nakov. 2020. SemEval-2020 task 11: Detection of propaganda techniques in news articles.
