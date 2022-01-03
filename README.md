## H0TensionRealm

** This code produces the whisker plot used as explanatory data analysis in the associated paper:
> E. Di Valentino et al. (2021), "In the Realm of the Hubble tension − a Review of Solutions", Class. Quant. Grav. 38 15, 153001 (2021); ArXiv:2103.01183

Data are contained in the file "./data/dataset.csv" which is organised as follows:

Column 1: Indirect / Direct measurement of H0, as defined in 2103.01183
Column 2: Type of measurement
Column 3: First author of the publication
Column 4: et al. or not
Column 5: Year of the publication
Column 6: Central value of H0 obtained, in km/s/Mpc
Column 7: Lower value (at 1sigma), in km/s/Mpc
Column 8: Upper value (at 1sigma), in km/s/Mpc
Column 9: ArXiv reference (if present)

The Python code "./code/WhiskerPlot.py" collects data from the file "dataset.csv" and organises them into a whisker plot. The code allows for additional data to be added and reshuffled, as long as the structure for the .csv file described above is kept.

The first thing to modify is the command [data_path = "../data/"] so that the directory variables point to the right place where "dataset.csv" is found.

A sample plot has been included in "./plot/H0whisker.pdf"

### Citation

If you use this code, please cite the associated paper:
> E. Di Valentino et al., "*In the Realm of the Hubble tension − a Review of Solutions*", [Class.Quant.Grav.38 (2021) 15, 153001](https://iopscience.iop.org/article/10.1088/1361-6382/ac086d) [arXiv:2103.01183](https://arxiv.org/abs/2103.01183)

### Bibtex entry

    @article{DiValentino:2021izs,
    author = "Di Valentino, Eleonora and Mena, Olga and Pan, Supriya and Visinelli, Luca and Yang, Weiqiang and Melchiorri, Alessandro and Mota, David F. and Riess, Adam G. and Silk, Joseph",
    title = "{In the realm of the Hubble tension\textemdash{}a review of solutions}",
    eprint = "2103.01183",
    archivePrefix = "arXiv",
    primaryClass = "astro-ph.CO",
    doi = "10.1088/1361-6382/ac086d",
    journal = "Class. Quant. Grav.",
    volume = "38",
    number = "15",
    pages = "153001",
    year = "2021"}

### Latex (EU) entry

     \bibitem{DiValentino:2021izs}
     E.~Di Valentino, O.~Mena, S.~Pan, L.~Visinelli, W.~Yang, A.~Melchiorri, D.~F.~Mota,  A.~G.~Riess, J.~Silk,
     Class. Quant. Grav. {\bf 38} 15, 153001 (2021), arXiv:2103.01183 [astro-ph.CO].

### Authors & Contact

This repository contains code which is being actively used for research, so in places it may not be 100% clear. If you have any questions whatsoever, or if the code behaves in an unexpected way, please do not hesitate to contact the authors: [Weiqiang Yang](mailto:d11102004@163.com) and [Luca Visinelli](mailto:luca.visinelli@gmail.com) 
