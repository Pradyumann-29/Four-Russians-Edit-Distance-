# Four-Russians-Edit-Distance

## Overview

This repository contains Python implemntation of edit distance of calculation between 2 strings. There is still some optimsation needed to be done but it features how the algorithm works.

## Getting Started

### Packages Needed

1. concurrent.features
2. time
3. Numpy

### Usage

1. This notebook includes the conventional Dynamic Programming Edit distance, Four-Russians Optimized Edit Distance and a Parallel computing function that enables concurrency. By running all the cells in the notebook, you'll get the output for the DP Edit distance, Four-Russians Edit distance with t=3,4 and varying string lengths. To change the block size, set different values for t. Make sure the string length is a multiple of t so that there are no errors in computation.

## Contributors
- Pradyumann Singhal
- Gopinath Balaji

## Referrences 
[1] E. S. Ristad and P. N. Yianilos, "Learning string-edit distance," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 20, no. 5, pp. 522-532, May 1998, doi: 10.1109/34.682181.  
[2] Dan Gusfield, “Algorithms on strings, trees and sequences: computer science and computational biology,” Cambridge University Press, 1997.  
[3]  Brian Brubach and Jay Ghurye ”A Succinct Four Russians Speedup for Edit Distance Computation and One-against-many Banded Alignment,” May 2018, doi: 10.4230/LIPIcs.CPM.2018.13  
[4] Carl Kingsford, “Four Russians’ Speedup,” https://www.cs.cmu.edu/~ckingsf/bioinfo-lectures/4russians.pdf  
[5] Kundeti, V., & Rajasekaran, S. (2008). Extending the four Russian algorithm to compute the edit script in Linear Space. Computational Science – ICCS 2008, 893–902. https://doi.org/10.1007/978-3-540-69384-0_94  
[6] Cristina Teodoropol, “Applying the Four Russians Technique to Banded Extension and X-Drop Sequence Alignment,” December 2020.  
[7] Rani, S., Singh, J. (2018). Enhancing Levenshtein’s Edit Distance Algorithm for Evaluating Document Similarity. In: Sharma, R., Mantri, A., Dua, S. (eds) Computing, Analytics and Networks. ICAN 2017. Communications in Computer and Information Science, vol 805. Springer, Singapore. https://doi.org/10.1007/978-981-13-0755-3_6  
[8] Frid, Y., Gusfield, D. An improved Four-Russians method and sparsified Four-Russians algorithm for RNA folding. Algorithms Mol Biol 11, 22 (2016). https://doi.org/10.1186/s13015-016-0081-9  

