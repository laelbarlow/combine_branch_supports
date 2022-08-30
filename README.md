
This script adds bootstrap support values from a bootstrap pseudoreplicate tree
file (newick format) to a MrBayes tree (MrBayes nexus format) with posterior
probabilities, and outputs the tree with combined support values in newick
format. 

Instructions:
    - Install the dependencies listed in the YAML file using conda (these
      include ETE3 and RAxML).
    - Ensure that your input trees have the same set of taxon names, and that
      the taxon names are simple alphanumeric strings (otherwise there may be
      errors in parsing).
    - Use the script as follows:
        ```
        python3 boots_on_mb.py <MrBayes consensus tree file NEXUS> <Bootstrap tree file NEWICK> <Output tree file NEWICK>
        ```
    - Visualize output using FigTree.

