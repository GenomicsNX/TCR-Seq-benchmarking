# TCR.Seq.Compare
Comparison of captured immune repertoire between IMREP, MIXCR, and TRUST4 using TCR seq data as a gold standard.  


Step 1: 

Generate extracted features for full samples and subsamples for each tool:

git clone https://github.com/Mangul-Lab-USC/TCR.Seq.Compare.git

<pre>
  cd TCR.Seq.Compare 
  scripts/./master.extract_cdr3_TCR.sh 
  scripts/./master.extract_cdr3_MIXCR.sh 
  scripts/./master.extract_cdr3_IMREP.sh 
  scripts/./master.extract_cdr3_TRUST4.sh 
  scripts/./master.extract_cdr3_IMREP2.sh 
</pre>

STEP 2: 

Process/merge data into one summary data csv


Step3:

Run Jupyter Notebook for figure generation from summary data.
