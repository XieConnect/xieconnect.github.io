---
layout: page
permalink: /publication/
title: Publications

preprints:
  - title:      "PrivLogit: Efficient Privacy-preserving Logistic Regression by Tailoring Numerical Optimizers"
    author:     "**W Xie**, Y Wang, SM Boker, DE Brown"
    journal:    "arXiv preprint"
    year:       "2016"
    url:        "https://arxiv.org/abs/1611.01170"
    anchor:     "privlogit16"
    tldr:       "We pointed out a surprising performance lag in privacy-preserving logistic regression methods, and propose to tailor numerical optimizers to better suit cryptography. Our new protocol provides several times speedup over state-of-the-art cryptographic protocols."
    media:
      - name: "PDF"
        url:  "https://arxiv.org/pdf/1611.01170v1.pdf"
      - name: "Preprint"
        url:  "https://arxiv.org/abs/1611.01170"

pubs:

    - title:   "A machine learning-based framework to identify type 2 diabetes through electronic health records"
      author:  "T Zheng, **W Xie**, L Xu, X He, Y Zhang, M You, G Yang, Y Chen"
      journal: "International Journal of Medical Informatics (IJMI)"
      #note:    "(presented at Oz)"
      year:    "2017"
      url:     "http://www.sciencedirect.com/science/article/pii/S1386505616302155"
      anchor:  "mlEHR17"
      #doi:     "http://dx.doi.org"
      #image:   "http://ars.els-cdn.com/content/image/1-s2.0-S1386505616X00111-cov150h.gif"
      tldr:     "Manually phenotyping patient cohorts from medical records (EHR) using expert rules is still dominating genome- and phenome-wide association studies (GWAS, PheWAS). Our work instead proposes machine learning-based phenotyping approach, and comprehensively evaluates top classifiers against expert rules and yields superior performance. We validated our methods and findings using hundres of ground-truth labels reviewed by expert clinicians from a large EHR network in China."
      media:
        - name: "PDF"
          url:  "/files/mlEHR-phenotyping-main.pdf"
        - name: "Supplement"
          url:  "/files/mlEHR-phenotyping-SUPPLEMENT.pdf"
        - name: "Preprint"
          url: "http://biorxiv.org/content/early/2016/09/30/078634"

    - title:   "Supporting Regularized Logistic Regression Privately and Efficiently"
      author:  "W Li, H Liu, P Yang, **W Xie** \\* (*Corresponding author*)"
      journal: "PloS ONE"
      year:    "2016"
      url:     "http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0156479"
      anchor:  "secureRegRression16"
      #doi:     "http://dx.doi.org"
      #image:   "http://journals.plos.org/plosone/resource/img/logo.png"
      tldr:    "We presented an efficient and secure method for privacy-preserving regularized logistic regression, building on secret sharing and distributed Newton method. Previous works did not protect model inference sufficiently or at all, and did not report any computational performance evaluations using real cryptographic implementation. Our work thus fills the gap."
      media:
        - name: "PDF"
          url:  "/files/secureRegRegression16.pdf"
        - name: "Preprint"
          url:  "https://arxiv.org/abs/1510.00095"


    - title:   "SecureMA: protecting participant privacy in genetic association meta-analysis"
      author:  "**W Xie**, M Kantarcioglu, WS Bush, D Crawford, JC Denny, R Heatherly, BA Malin"
      journal: "Bioinformatics"
      #note:    "(presented at Oz)"
      year:    "2014"
      url:     "http://bioinformatics.oxfordjournals.org/content/30/23/3334"
      anchor:  "secureMA14"
      tldr:    "We presented a privacy-preserving method and framework to perform genome-wide association studies (GWAS) for multi-center consortia, following the widely-used meta-analysis formulation. This approach conforms with common practice in human genetics research and seems more natural and computationally efficient/scalable than privacy-preserving distributed regression alternatives."
      media:
        - name: "PDF"
          url:  "/files/secureMA14-bioinformatics.pdf"
        - name: "Supplementary"
          url: "/files/secureMA14-bioinformatics-SUPPLEMENT.pdf"
        - name: "SecureMA code"
          url:  "http://github.com/XieConnect/SecureMA"
        - name: "CircuitService"
          url:  "http://github.com/XieConnect/CircuitService"

    - title:   "Inferring Clinical Workflow Efficiency via Electronic Medical Record Utilization"
      author:  "Y Chen, **W Xie**, CA Gunter, D Liebovitz, S Mehrotra, H Zhang, B Malin"
      journal: "American Medical Informatics Association (AMIA) Annual Symposium Proceedings"
      #note:    "(presented at Oz)"
      year:    "2015"
      url:     "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4765602"
      anchor:  "workflowEHR15"
      tldr:    "We proposed a topic modeling (latent dirichlet allocation, or LDA) based method to model clinical workflow and care teams. This framework points out potential opportunities for workflow optimization and better resource allocation."
      #image:   "https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fimages.moviepostershop.com%2Fthe-matrix-movie-poster-1999-1020518087.jpg&f=1"
      media:
        - name: "PDF"
          url:  "/files/workflowEHR15.pdf"
        - name: "Slides"
          url:  "http://hiplab.mc.vanderbilt.edu/~ychen/AMIA_2015.pdf"

    - title:    "A novel transfer learning method based on common space mapping and weighted domain matching"
      author:   "RZ Liang, **W Xie**, W Li, H Wang, JJY Wang, L Taylor"
      journal:  "Proceedings IEEE 28th International Conference on Tools with Artificial Intelligence (ICTAI)"
      year:    "2016"
      anchor:  "transferMapping16"
      tldr:    "We proposed a new method for transfer learning -- useful for limited labeled data regime."
      media:
        - name: "PDF"
          url:  "https://arxiv.org/pdf/1608.04581v1.pdf"
        - name: "Preprint"
          url:  "https://arxiv.org/abs/1608.04581"


presentations:
  - title:    "PrivLogit: Fast Privacy-preserving Logistic Regression via Tailored Numerical Optimizer"
    #note:     "Invited talk"
    journal:  "Invited talk, International Conference on Design of Experiments (ICODOE), Memphis, TN"
    year:     "2016"
    url:      "http://at.yorku.ca/c/b/l/o/78.htm"

  - title:    "Privacy Leaks in Meta-analysis Quality Control and Countermeasures"
    #author:   "**W Xie**, M Kantarcioglu, JC Denny, TL Edwards, NJ Cox, BA Malin"
    journal:  "Contributed, American Society of Human Genetics (ASHG) 65th Annual Meeting, Baltimore, MD"
    url:      "https://ep70.eventpilotadmin.com/web/page.php?page=IntHtml&project=ASHG15&id=150122886"
    year:     "2016"
---

*The bibliography (.bib) of my pubications with keywords annotated is available [elsewhere](/publicationbib).* <br />

Quick links: [Preprints](#preprints-work-in-progress), [Publications (peer-reviewed)](#publications-peer-reviewed), [Presentations](#presentations)

{% assign thumbnail="left" %}

{% for pub_type in (1..3) %}
{% if pub_type == 1 %}
## Preprints (work-in-progress)
{% assign publications=page.preprints %}

{% elsif pub_type == 2 %}
## Publications (peer reviewed)
{% assign publications=page.pubs %}

{% else pub_type == 3 %}
## Presentations
{% assign publications=page.presentations %}
{% endif %}


{% for pub in publications %}
{% if pub.image %}
{% include image.html url=pub.image caption="" height="100px" align=thumbnail %}
{% endif %}
<a name="{{pub.anchor}}"></a>
[**{{pub.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})<br />
{% if pub.author %}{{pub.author}}<br />{% endif %}
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} , *{{pub.year}}* {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}
{% if pub.media %} {% for article in pub.media %}[[{{article.name}}]({{article.url}})]{% endfor %}{% endif %}
{% if pub.tldr %}<pre><sup>*TL;DR* {{pub.tldr}}</sup></pre>
{% endif %}
{% endfor %}

{% endfor %}
