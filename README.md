# local_alignment
Local alignment using the Smith-Waterman algorithm.
  NOTE: this implementation prioritizes matches/mismatches over creating a gap
  NOTE: when a gap is to be created, this implementation prioritizes deletions over insertions
 
Usage:    python hw1.py -i <input file> -s <score file>
Example:    python hw1.py -i input.txt -s blosum62.txt
Output: a text file containing the sequences, the score matrix, highest alignment score, and the alignment
  
NOTE: line 1 in input is assumed to be the query sequence. Line 2 is assumed to be the reference sequence
