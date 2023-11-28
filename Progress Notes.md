## Non-Competitive Part
What we need to do, an implementation level analysis
1. Implement CNN to encode image to context vector, all specifications are given
2. Create an LSTM layer. Involved step: create vocubulary from given formulae, create embedding layer. [might help](https://www.youtube.com/watch?v=e6kcs9Uj_ps)
3. Training using Teacher forcing [might help](https://www.youtube.com/watch?v=RRP0czWtOeM).
4. Test and calculate BLEU score.
Note: A piece of work on img-2-latex. What a clarity..[blogpost](https://guillaumegenthial.github.io/sequence-to-sequence.html)

## Changes yet in comp.ipynb
1. Remove UNK labels. Currently 30-40% of the formulas
## Competitive Part Ideas
1. Bi Directional LSTM
2. Use RNN for decoder, seqToseq (image column wise) - generates a sequence which is the context
3. 
