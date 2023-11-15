# CMPS 2200 Recitation 6
## Answers

**Name:**__Ali Sulehria


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt       |          1340       |        826     |    0.617
alice29.txt  |       1039367       |     676374     |    0.651
asyoulik.txt |        876253       |     606448     |    0.692
grammar.lsp  |         26047       |      17356     |    0.666
fields.c     |         78050       |      58206     |    0.746




- **e.**

The cost for a huffman encoding is the sum of the length for an encoding times the frequency of the encoded character for all encoded characters. The Huffman tree for an alphabet where every character's frequency is identical is a balanced binary tree, where each level has a code length equal to its depth, the cost is as follows:

x is the length of the alphabet
freq is the frequency of each character

cost = sigma (n from 1 to log2(x))(n * freq * 2^(log2(n)-1)
