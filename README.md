This repo contains a computational pipeline for evaluating how CRISPRi-specific and Chromatin-Aware prediction scores perform across 32,275 gRNAs from the Katsano tiling dataset (Srikanth et al. 2026). The objective is to determine how particular biological features influence CRISPRi off-target activity. It is important to note that the original pipeline was designed in Google Colab, meaning that certain file paths and setup was are specific to a Google Drive–mounted Colab session. If running locally, then the paths and environment setup steps may need to be adjusted. This work was done for my Spring 2026 Independent Work at Princeton University. 

The off-target enumeration files are hosted on Google Drive due to size:
[Download here](https://drive.google.com/drive/folders/1zbbPzJJR8rKzkV5qjtkrciwP6t7mX4jw?usp=drive_link)

The external data/files were downloaded via:
- ATAC-seq peaks: ENCODE accessions [ENCFF808YMI](https://www.encodeproject.org/files/ENCFF808YMI/) (A549) and [ENCFF068PVP](https://www.encodeproject.org/files/ENCFF068PVP/) (HCT116)
- CFD matrices: [crisporWebsite](https://github.com/maximilianh/crisporWebsite/tree/master/CFD_Scoring)
- hg38 index: [GCF_000001405.39](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000001405.39/)
