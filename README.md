# SEEKER-encoding-and-decoding
Complete encoding and decoding process compatible with SEEKER for keyword search in DNA data storage


  This branch contains step-by-step procedures to implement the entire process from encoding text data to DNA sequences and decode sequencing reads to readable texts.
  The codes are written in Jupyter Notebook with a Python 3 kernel. Please directly download the zip file and execute it on Jupyter Notebook. The codes can be executed on both Windows and MacOS operating system. No command-line installation is needed. 
  Please follow the order of steps for a successful reproduction of the NCG encoding and decoding. The generation of DNA sequences and the conversion of sequencing reads to text data at a scale used in our study (~40 KB data) should be in seconds. 
  For the generation of reference and data DNA sequences (step 3 and 4), we built codes for the reproducibility of our results using existing text data to be encoded (provided in this branch). Users can also test with their own text data, but they should fill in their own file name in Line 7 of Step 1.
  In Step 5 and 6 for decoding, sequencing data (data pool #1-#4 and reference pool) is provided in fastq format for reproducibility. 
  In addition, we provided 

