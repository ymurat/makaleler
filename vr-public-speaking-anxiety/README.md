# Overcoming Public Speaking Anxiety of Software Engineers using Virtual Reality Exposure Therapy

**Authors:** Merve Denizci Nazligul, Murat Yilmaz, Ulas Gulec, Mert Ali Gozcu, Rory V. O'Connor, and Paul Clarke

**Venue:** EuroSPI 2017 - Systems, Software and Services Process Improvement

**Published in:** Communications in Computer and Information Science, vol 748, Springer, pp. 191-202 (2017)

**DOI:** [10.1007/978-3-319-64218-5_15](https://doi.org/10.1007/978-3-319-64218-5_15)

## Links

- **Project Page:** [https://ymurat.github.io/makaleler/vr-public-speaking-anxiety/docs/](https://ymurat.github.io/makaleler/vr-public-speaking-anxiety/docs/)
- **PDF:** [https://ymurat.github.io/makaleler/vr-public-speaking-anxiety/docs/paper.pdf](https://ymurat.github.io/makaleler/vr-public-speaking-anxiety/docs/paper.pdf)
- **LaTeX Source:** [latex/](latex/)

## Abstract

Public speaking anxiety is a type of social phobia, which might be commonly seen in novice software engineers. It is usually triggered by a fear of social performance especially when the performer is unfamiliar with the audience. Today, many software engineering activities (e.g. code inspection, peer review, daily meetings, etc.) require social gatherings where individuals need to present their work. However, novice software engineers may not be able to reduce their performance anxiety during their course of education. In this study, we propose a virtual reality approach to construct a practice environment for improving novice software engineers' pubic speaking experiences. Consequently, we examine the effects of virtual reality intervention on the public speaking experience of six novice software engineers from a computer engineering department. We designed a virtual auditorium to simulate the presentation delivery environment and findings suggest that using this infrastructre for training purposes can reduce presenter anxiety levels – which is consistent with related published studies. We believe that this virtual auditorium environment can deliver benefits for students and practitioners alike in terms of addressing the anxiety that is often associated with early stage career presenters.

**Keywords:** Virtual reality, public speaking anxiety, personal process improvement

## Building the LaTeX

To build the PDF from the LaTeX source:

```bash
cd latex/
pdflatex EuroSPI_2017.tex
bibtex EuroSPI_2017
pdflatex EuroSPI_2017.tex
pdflatex EuroSPI_2017.tex
```

**Note:** The source images (girisEkrani.png, kisiSayisi.png, secim.png, sunucu.png, fig5.png) referenced in the LaTeX are not included in this repository. The compiled PDF contains these figures, and they have been extracted for the project page.

## BibTeX

```bibtex
@inproceedings{nazligul2017overcoming,
  title     = {Overcoming Public Speaking Anxiety of Software Engineers Using Virtual Reality Exposure Therapy},
  author    = {Nazligul, Merve Denizci and Yilmaz, Murat and Gulec, Ulas and Gozcu, Mert Ali and O'Connor, Rory V. and Clarke, Paul},
  booktitle = {EuroSPI 2017: Systems, Software and Services Process Improvement},
  series    = {Communications in Computer and Information Science},
  volume    = {748},
  pages     = {191--202},
  year      = {2017},
  publisher = {Springer International Publishing},
  doi       = {10.1007/978-3-319-64218-5_15},
  url       = {https://doi.org/10.1007/978-3-319-64218-5_15}
}
```

## License

© 2017 Springer International Publishing. All rights reserved.
