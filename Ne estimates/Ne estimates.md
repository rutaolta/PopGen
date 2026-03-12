
##### $N_e$ estimates per compartment (autosomes, X, Y, mtDNA) based on the coalescence theory:
$N_{e}^{AUT}=\frac{4N_{M}N_{F}}{N_{M}+N_{F}}$

$N_{e}^{X}=\frac{9N_{M}N_{F}}{4N_{M}+2N_{F}}$

$N_{e}^{MT}=N_{F}$

$N_{e}^{Y}=N_{M}$

> [!Theory box 1]
> Where the equation for autosomes is derived from the probability to coalesce in the preceding generation as:
>
> $p=\frac{1}{4}(\frac{1}{2N_M})+\frac{1}{4}(\frac{1}{2N_F})$,
>
> and the probability of 2 alleles to have the same parental allele in proceeding generation (identical by descend) in N diploid individuals is:
>
> $p=\frac{1}{2N_e}$
>
> $\frac{1}{2N_e}=\frac{1}{4}(\frac{1}{2N_M})+\frac{1}{4}(\frac{1}{2N_F})$
>
> $\frac{1}{N_e}=\frac{1}{4}(\frac{1}{N_M}+\frac{1}{N_F})$
>
> $\frac{1}{N_e}=\frac{N_F+N_M}{4N_FN_M}$
>
> $N_e=\frac{4N_FN_M}{N_F+N_M}$

> [!Theory box 2]
> ##### $N_e$ estimates based on nucleotide diversity
> Diploids: $\theta=4N\mu$, $N=\frac{\theta}{4\mu}$
>
> Haploids: $\theta=2N\mu$, $N=\frac{\theta}{2\mu}$

---
##### Sex-bias ratio estimates
$r=\frac{N_{M}}{N_{F}}=\frac{N_{e}^{Y}}{N_{e}^{MT}}=\frac{\theta_{Y}/\mu_{Y}}{\theta_{MT}/\mu_{MT}}$

$\frac{N_{e}^{AUT}}{N_{e}^{X}}=\frac{4N_{M}N_{F}}{N_{M}+N_{F}}=\frac{4N_{M}N_{F}(4N_{M}+2N_{F})}{(N_{M}+N_{F})9N_{M}N_{F}}=\frac{8(2r+1)}{9(r+1)}$

$\frac{N_{e}^{Y}}{N_{e}^{MT}}=\frac{N_{M}}{N_{F}}=r$

$\frac{N_{e}^{Y}}{N_{e}^{X}}=\frac{N_{M}(4N_{M}+2N_{F})}{9N_{M}N_{F}}=\frac{4r+2}{9}$

$\frac{N_{e}^{Y}}{N_{e}^{AUT}}=\frac{N_{M}(N_{M}+N_{F})}{4N_{M}N_{F}}=\frac{r+1}{4}$

$\frac{N_{e}^{X}}{N_{e}^{MT}}=\frac{9N_{M}N_{F}}{(4N_{M}+2N_{F})N_{F}}=\frac{9r}{4r+2}$

$\frac{N_{e}^{AUT}}{N_{e}^{MT}}=\frac{4N_{M}N_{F}}{(N_{M}+N_{F})N_{F}}=\frac{4r}{r+1}$

---
##### $N_e$ estimates per compartment
1. **MT & Y**
Let's calculate $N_{e}^{MT}$ and $N_{e}^{Y}$ based on mutation rates and nucleotide diversity as
$N_e^{MT}=N_F=\frac{\theta_{MT}}{2\mu_{MT}}$, and

$N_e^{Y}=N_M=\frac{\theta_{Y}}{2\mu_{Y}}$

then we can derive $N_e$ for the rest compartments as
$N_e^{AUT}=\frac{4N_FN_M}{N_F+N_M}$, and

$N_e^{X}=\frac{9N_FN_M}{2N_F+4N_M}$

2. **MT & AUT**
Now let's calculate $N_{e}^{MT}$ and $N_{e}^{AUT}$ based on mutation rates and nucleotide diversity as
$N_e^{MT}=N_F=\frac{\theta_{MT}}{2\mu_{MT}}$, and

$N_e^{AUT}=\frac{\theta_{AUT}}{4\mu_{AUT}}$

then we can derive $N_e$ for the rest compartments using formulas above the [Theory box 1] as
$N_e^{Y}=N_M=\frac{N_e^{MT}N_e^{AUT}}{4N_e^{MT}-N_e^{AUT}}$, and

$N_e^{X}=\frac{9N_FN_M}{2N_F+4N_M}$

3.  **MT & X**
$N_e^{MT}=N_F=\frac{\theta_{MT}}{2\mu_{MT}}$

$N_e^{X}=\frac{\theta_{X}}{4\mu_{X}}$

$N_e^{Y}=N_M=\frac{2N_e^{MT}N_e^{X}}{9N_e^{MT}-4N_e^{X}}$

$N_e^{AUT}=\frac{4N_FN_M}{N_F+N_M}$

4. **AUT & X**
$N_e^{AUT}=\frac{\theta_{AUT}}{4\mu_{AUT}}$

$N_e^{X}=\frac{\theta_{X}}{4\mu_{X}}$

$N_e^{Y}=N_M=\frac{2N_e^{AUT}N_e^{X}}{16N_e^{X}-9N_e^{AUT}}$

$N_e^{MT}=N_F=\frac{2N_e^{AUT}N_e^{X}}{9N_e^{AUT}-8N_e^{X}}$

---
- [Population differentiation and migration: Coalescence times in a two-sex island model for autosomal and X-linked loci](https://doi.org/10.1016/j.tpb.2008.08.003), Ramachandran, 2008
- [The Idiot's Guide to Effective Population Size](https://doi.org/10.1111/mec.17670), Waples, 2025
- [Effective population size and patterns of molecular evolution and variation]( https://doi.org/10.1038/nrg2526), Charlesworth, 2009
- [Estimation of Levels of Gene Flow From DNA Sequence Data](https://www.ccg.unam.mx/~vinuesa/tlem/pdfs/Hudson_gene_flow_Genetics92.pdf), Hudson, 1992
