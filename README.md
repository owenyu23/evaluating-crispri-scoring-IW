This repo contains a computational pipeline for evaluating how CRISPRi-specific and Chromatin-Aware prediction scores perform across 32,275 gRNAs from the Katsano tiling dataset (Srikanth et al. 2026). The objective is to determine how biological features of the gRNA influence CRISPRi off-target activity.

The off-target enumeration files are hosted on Google Drive due to size:
[Download here](https://drive.google.com/drive/folders/1zbbPzJJR8rKzkV5qjtkrciwP6t7mX4jw?usp=drive_link)

The external data/files were downloaded via:
- ATAC-seq peaks: ENCODE accessions [ENCFF808YMI](https://www.encodeproject.org/files/ENCFF808YMI/) (A549) and [ENCFF068PVP](https://www.encodeproject.org/files/ENCFF068PVP/) (HCT116)
- CFD matrices: [crisporWebsite](https://github.com/maximilianh/crisporWebsite/tree/master/CFD_Scoring)
- hg38 index: [GCF_000001405.39](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000001405.39/)
