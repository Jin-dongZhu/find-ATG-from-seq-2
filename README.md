# find-ATG-from-seq-2
python-2
seq = "ATGCTGATCGGGGAAGGCCTACCCTTCTCAGGCATGCCTTCCCTAGAAGTGAGAA"
import re
seqsite=[m.start() for m in re.finditer('ATG',seq)]
print (seqsite)
