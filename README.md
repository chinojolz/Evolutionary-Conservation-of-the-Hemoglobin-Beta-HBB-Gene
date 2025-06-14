# Evolutionary-Conservation-of-the-Hemoglobin-Beta-HBB-Gene
## Project Overview

This project investigates the evolutionary conservation of the Hemoglobin Beta (HBB) gene across different species, specifically *Homo sapiens* (humans), *Mus musculus* (mice), *Danio rerio* (zebrafish), *Rattus norvegicus* (brown rat), *Lagothrix lagotricha* (woolly monkey), and *Bos taurus* (cow). The HBB gene encodes a vital component of hemoglobin, which is essential for oxygen transport in the bloodstream.

## Objectives

The primary objectives of this project are to:

1. Perform sequence retrieval using BLAST
2. Conduct pairwise and multiple sequence alignments
3. Generate sequence logos to visualize conservation
4. Construct phylogenetic trees to infer evolutionary relationships
5. Practice documenting and presenting scientific findings

## Methods

The following bioinformatics tools and resources were utilized:

- **NCBI:** For sequence retrieval.
- **EMBOSS Needle:** For pairwise sequence alignment.
- **ClustalW:** For multiple sequence alignment.
- **Skylign:** For generating sequence logos.
- **MEGA X:** For constructing phylogenetic trees.

## Results

### 1. Pairwise Sequence Alignment

![Screenshot 2025-06-12 234443](https://github.com/user-attachments/assets/8062862d-0a3c-4043-b1e3-6c0f840b5355)

![Screenshot 2025-06-14 203807](https://github.com/user-attachments/assets/0d8849f0-18d1-47ad-a17e-4f31af76a6eb)

![Screenshot 2025-06-14 204126](https://github.com/user-attachments/assets/85fb8b42-9f9c-4b80-bb43-4ed645f79e31)





**Explanation:** The pairwise sequence alignment was performed using EMBOSS Needle. The output shows matched nucleotides represented by vertical lines, indicating conserved regions between the sequences of interest. It also shows the gap penalties, which are scores assigned when inserting gaps; the similarity score, which indicates how well the sequences align overall; and the match/mismatch, which identifies identical or different nucleotides at each position in the alignment. This alignment helps identify essential functional areas of the HBB gene.

### 2. Multiple Sequence Alignment (MSA)

![Screenshot 2025-06-14 205125](https://github.com/user-attachments/assets/ae8c20d2-5014-4c1b-9ed9-b2d2462408a7)

![Screenshot 2025-06-14 205146](https://github.com/user-attachments/assets/d3269169-dc13-4525-9c2e-34ef08c898d4)

![Screenshot 2025-06-14 205203](https://github.com/user-attachments/assets/0200f7bb-88ec-4cc5-8f3e-f61597daccea)

![Screenshot 2025-06-14 205215](https://github.com/user-attachments/assets/31ac1b9d-9655-4256-99d5-ccecf8c6a2f6)





**Explanation:** The MSA was conducted using ClustalW. The alignment output highlights conserved regions across multiple sequences, with asterisks indicating highly conserved residues. This analysis underscores the evolutionary significance of these regions. *Homo sapiens* and *Mus musculus* show a high degree of similarity, which is expected due to their closer evolutionary relationship. In contrast, *Danio rerio* and *Lagothrix lagotricha* display more differences, reflecting their more distant evolutionary paths.

### 3. Sequence Logo Generation

![Screenshot 2025-06-14 205412](https://github.com/user-attachments/assets/f5023bce-d699-4a8c-9e7c-5786280c36db)



**Explanation:** The sequence logo generated using Skylign visually represents nucleotide conservation across the aligned sequences. The different colors represent the four nucleotides (A, T, C, G), with the most abundant nucleotides at specific positions being emphasized. Red typically indicates adenine (A) or thymine (T), while green and blue represent cytosine (C) and guanine (G), respectively. Specific positions with very high information content suggest critical functional sites in the HBB gene, which are likely essential for its biological role in oxygen transport. Lower columns indicate positions that show greater variability among the species, suggesting less evolutionary pressure to conserve those nucleotides.

### 4. Phylogenetic Tree Construction

![Screenshot 2025-06-14 210224](https://github.com/user-attachments/assets/a35313c3-ace7-46cc-a480-56fca8691c12)



**Explanation:** The phylogenetic tree constructed using MEGA X illustrates the evolutionary relationships among the species studied. The numbers along the branches represent genetic distances between the species. Longer branches indicate greater genetic divergence. *Homo sapiens* (humans) and *Danio rerio* (zebra fish) appear to be more distantly related, as indicated by the longer branch length (0.645). In contrast, *Mus musculus* (mouse) is more closely related to *Rattus norvegicus* (brown rat) and *Lagothrix lagotricha* (woolly monkey), as their branch lengths are shorter (0.042 and 0.051, respectively). The tree suggests that while humans and zebrafish share a common ancestor, their evolutionary paths diverged significantly. The close relationships among rodents (mouse and rat) indicate a more recent common ancestor, which supports their use in biomedical studies.
 The tree effectively illustrates expected evolutionary relationships based on common ancestry and divergence times among these species. The close relationship between *Mus musculus* (mouse) and *Rattus norvegicus* (brown rat) is expected due to their shared lineage as rodents. Also, the more distant relationship between *Homo sapiens* (humans) and *Danio rerio* (zebra fish) reflects the significant evolutionary divergence between mammals and fish, consistent with their distinct evolutionary paths. The placement of *Lagothrix lagotricha* (woolly monkey) further supports the idea of evolutionary divergence among primates, showing its relation to other species within the primate lineage.
