# 20.A04-Cloning

## Papers
- MoClo system we will be using
    - [Joint universal modular plasmids (JUMP): a flexible vector platform for synthetic biology](https://academic.oup.com/synbio/article/6/1/ysab003/6126375)
- New parts
    - [Binding and sensing diverse small molecules using shape-complementary pseudocycles](https://pmc.ncbi.nlm.nih.gov/articles/PMC11542606)

## Software
- SnapGene (plasmid viewer and editor): https://ist.mit.edu/gsl/snapgene
- pLannotate (automatic annotation of plasmids): https://plannotate.barricklab.org/

## Plasmids
- pJUMP18-Uac (Universal part acceptor) (Addgene): https://www.addgene.org/126959/

## Creating a MoClo kit part

### JUMP overhangs

<table>
    <tr>
        <th>Part type</th>
        <th>5' overhang</th>
        <th>3' overhang</th>
    </tr>
    <tr>
        <td>A</td>
        <td>GGAG</td>
        <td>AATG</td>
    </tr>
    <tr>
        <td>B</td>
        <td>AATG</td>
        <td>AGCC</td>
    </tr>
    <tr>
        <td>C</td>
        <td>AGCC</td>
        <td>TTCG</td>
    </tr>
    <tr>
        <td>D</td>
        <td>TTCG</td>
        <td>CGCT</td>
    </tr>
</table>

### Example: IL11 as a Type "C" part

1. **Find a source of the IL11 gene**.
    - Luckily, there is an existing plasmid on Addgene that includes the IL11 gene.
    - If there wasn't, we'd need to look for the sequence itself, and have it synthesized.
        - NCBI Gene - IL11: https://www.ncbi.nlm.nih.gov/gene/3589
        - Consensus sequence: https://www.ncbi.nlm.nih.gov/CCDS/CcdsBrowse.cgi?REQUEST=CCDS&DATA=CCDS12923.1
2. Design the PCR reaction(s) to amplify your sequence of interest.

## References
- MoClo and Golden Gate, the original papers
    - [A One Pot, One Step, Precision Cloning Method with High Throughput Capability (Golden Gate)](https://pmc.ncbi.nlm.nih.gov/articles/PMC2574415/)
    - [A Modular Cloning System for Standardized Assembly of Multigene Constructs (MoClo)](https://pmc.ncbi.nlm.nih.gov/articles/PMC3041749/)

