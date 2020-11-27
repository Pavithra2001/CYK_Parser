# CYK_Parser
Parse the given text using CYK Algorithm

Parsing is one of the most notable problems of NLP. CYK (Cocke–Younger–Kasami) is a widely used parsig algorithm. A given text can be parsed with context-Free grammar using this algorithm.

In this project, first the given grammar is converted to CNF (Chomsky-Normal Form) as it needs to be in this format for the algorithm to accept the given text. Next a recognizer is built to check whether the given sentence is available in the given grammar text or not. if not, then the parser cannot be built.

Then the CYK Algorithm has been implemented to find the parse tree for the given sentence.

I have also implemented the probabilistic CYK Algorithm which outputs the most probable parse tree.
