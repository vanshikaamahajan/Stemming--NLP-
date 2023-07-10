# Stemming--NLP-
Stemming involve reduction of a word to its word stem and is vital to various tasks of NLP, NLU.

General rule of thumb

Reduce the suffix to following

1.SSES - SS<br>
2.S - NULL
3.IES - I
4.SS - SS
5.LY - LI

Porter Algorithm is the most common algorithm deployed in NLP/NLU tasks for Stemming.
Lancaster Stemming which stems based on the last letter of the words also exists, But is often computationally expensive.
Lovins Stemmer on the other hand is a single pass, context sensitive stemmer which removes ending based on the longest match principle.
Snowball Stemmer is mostly deployed for stemming.
