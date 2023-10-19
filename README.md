# SEEKER-encoding-and-decoding
The code aims to provides a complete encoding and decoding process compatible with SEEKER for keyword search in DNA data storage.


  This branch contains step-by-step procedures to implement the entire process from encoding text data to DNA sequences and decode sequencing reads to readable texts.
  
  The codes are written in Jupyter Notebook with a Python 3 kernel. Please directly download the zip file and execute it on Jupyter Notebook. The codes can be executed on both Windows and MacOS operating system. No command-line installation is needed. 
  
  Please follow the order of steps for a successful reproduction of the NCG encoding and decoding. The generation of DNA sequences and the conversion of sequencing reads to text data at a scale used in our study (~40 KB data) should take less than 1 min. 

  For keyword searching, the query sequences can be obtained through "Keyeword Sequence Determination" based on established "Groups" from Step 2. This sequence can be directly inputted for crRNA ordering through IDT website.

  Notes to users:
  
  1). The primer library is randomly generated in Step 0. When encoding text data other than the data provided, users should use a newly generated primer library. However, to reproduce the results in this study, users should execute "Step 0.1-Primer library used in this study" which produces and stores primer sets mattching the raw sequencing reads. 
  
  2). For the generation of reference and data DNA sequences (step 3 and 4), we built codes for the reproducibility of our results using existing text data to be encoded (provided in this branch). Users can also test with their own text data, but they should fill in their own file name in Line 7 of Step 1.
  
  3). In Step 5 and 6 for decoding, sequencing data (data pool #1-#4 and reference pool) in "Raw reads" folder is provided in fastq format for reproducibility. Step 5 offers the algorithms for both before and after the "remedial process" so users can compare the difference. 

Required Python packages to be installed and the commands to install them:
1. primer3.                       pip install primer3-py
2. reedsolo.                      pip install reedsolo

We also provided requirements.txt in this repository so all dependencies can be installed by running the following command:

pip install -r requirements.txt


  
