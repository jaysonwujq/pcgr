About
-----

What is the Personal Cancer Genome Reporter (PCGR)?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The Personal Cancer Genome Reporter (PCGR) is a stand-alone software
package for functional annotation and translation of individual cancer
genomes for precision oncology. It interprets both somatic SNVs/InDels
and copy number aberrations. The software extends basic gene and variant
annotations from the `Ensembl’s Variant Effect Predictor
(VEP) <http://www.ensembl.org/info/docs/tools/vep/index.html>`__ with
oncology-relevant, up-to-date annotations retrieved flexibly through
`vcfanno <https://github.com/brentp/vcfanno>`__, and produces
interactive HTML reports intended for clinical interpretation.

|image0|

The Personal Cancer Genome Reporter has been developed by scientists
affiliated with the `Norwegian Cancer Genomics
Consortium <http://cancergenomics.no>`__, at the `Institute for Cancer
Research/Oslo University Hospital <http://radium.no>`__.

Example reports
~~~~~~~~~~~~~~~

-  `Report for a breast tumor sample
   (TCGA) <http://folk.uio.no/sigven/tumor_sample.BRCA.pcgr_acmg.grch37.v0.8.2.html>`__
-  `Report for a colon adenocarcinoma sample
   (TCGA) <http://folk.uio.no/sigven/tumor_sample.COAD.pcgr_acmg.grch37.v0.8.2.html>`__

Why use PCGR?
~~~~~~~~~~~~~

The great complexity of acquired mutations in individual tumor genomes
poses a severe challenge for clinical interpretation. There is a general
scarcity of tools that can *i)* systematically interrogate cancer
genomes in the context of diagnostic, prognostic, and therapeutic
biomarkers, *ii)* prioritize and highlight the most important findings,
and *iii)* present the results in a format accessible to clinical
experts. PCGR integrates a comprehensive set of knowledge resources
related to tumor biology and therapeutic biomarkers, both at the gene
and variant level. The application generates a tiered report that will
aid the interpretation of individual cancer genomes in a clinical
setting.

If you use PCGR, please cite our recent publication:

Sigve Nakken, Ghislain Fournous, Daniel Vodák, Lars Birger Aaasheim, Ola
Myklebost, and Eivind Hovig. **Personal Cancer Genome Reporter: variant
interpretation report for precision oncology** (2017). *Bioinformatics*.
34(10):1778–1780.
doi:\ `10.1093/bioinformatics/btx817 <https://doi.org/10.1093/bioinformatics/btx817>`__

Docker-based technology
~~~~~~~~~~~~~~~~~~~~~~~

The PCGR workflow is developed using the `Docker
technology <https://www.docker.com/what-docker>`__. The software is thus
packaged into isolated containers, in which the installation of all
software libraries/tools and required dependencies have been taken care
of. In addition to the bundled software, in the form of a Docker image,
the workflow only needs to be attached with an `annotation data bundle
for precision oncology <annotation_resources.html>`__.

|image1|

Contact
~~~~~~~

sigven@ifi.uio.no

.. |image0| image:: PCGR_workflow.png
.. |image1| image:: docker-logo50.png

