---
# Leave the homepage title empty to use the site title
title: Cavalli
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle: 
      text: |
        <h1 class="visually-hidden">Cavalli Lab — Chromatin and Epigenetics, IGH, CNRS, UMR9002, Montpellier</h1>
        <img class="tiny-banner-center" src="media/Cavalli_v2_landscape_cropped_tiny.png" alt="Cavalli lab banner">
    design:
      columns: '1'
      background:
        image: 
          filename: Cavalli_v2_landscape_cropped_tiny.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['0', '0', '0', '0']
      css_class: tiny-banner

  - block: markdown
    content:
      title: Research
      text: |
        The Cavalli lab aims at understanding epigenetic inheritance, namely the information that is <strong> contained in our chromosomes and transmitted to daughter cells and to future generations beyond the sequence of DNA </strong>. We employ a <strong> wide range of molecular and in vivo approaches </strong> — single-cell omics, super-resolution microscopy, CRISPR editing, genomics, and physical modeling — to uncover how the <strong> 3D epigenome in general, and <strong> Polycomb proteins </strong> in particular, can establish and maintains transcriptional programs in development and disease</strong>. Our main research topics include:

        <div class="research-flex">
          <div class="research-flex-item left">
            <a href="research/#research_topic_1">
              <img src="media/HiC_Micro.png" alt="3D organization and function of the genome">
              <div class="research-grid-caption">
                3D organization and function of the genome
              </div>
            </a>
          </div>
          <div class="research-flex-item center">
            <a href="research/#research_topic_2">
              <img src="media/EB_fly.png" alt="Role of Polycomb Group Proteins in genome regulation">
              <div class="research-grid-caption">
                Role of Polycomb Group Proteins in genome regulation
              </div>
            </a>
          </div>
          <div class="research-flex-item center">
            <a href="research/#research_topic_3">
              <img src="media/cancer_ED.png" alt="Epigenetic inheritance in development and cancer">
              <div class="research-grid-caption">
                Epigenetic inheritance in development and cancer
              </div>
            </a>
          </div>
          <div class="research-flex-item right">
            <a href="research/#research_topic_4">
              <img src="media/microscopy.png" alt="Methods used in our lab">
              <div class="research-grid-caption">
                Methods used in our lab
              </div>
            </a>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']

  - block: collection
    content:
      title: News
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '5'   # Show 5 cards in a row
      spacing:
        padding: ['40px', '0', '40px', '0']
      
  - block: collection
    content:
      title: Publications
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'
      spacing:
        padding: ['50px', '0', '40px', '0']
      css_class: home-publications
  
  - block: markdown
    content:
      title: Funding
      text: |
        <div class="funders-grid">
          <a href="https://erc.europa.eu/homepage" target="_blank" rel="noopener">
            <img src="logos/ERC.png" alt="Funder 1 logo">
          </a>
          <a href="https://anr.fr/" target="_blank" rel="noopener">
            <img src="logos/ANR.png" alt="Funder 2 logo">
          </a>
          <a href="https://www.cnrs.fr/fr" target="_blank" rel="noopener">
            <img src="logos/CNRS_logo.png" alt="Funder 3 logo">
          </a>
          <a href="https://www.umontpellier.fr/recherche/unites-de-recherche/pole-biologie-sante/labum-epigenmed" target="_blank" rel="noopener">
            <img src="logos/epigenmed.png" alt="Funder 4 logo">
          </a>
          <a href="https://commission.europa.eu/index_en" target="_blank" rel="noopener">
            <img src="logos/EuropeanCommission.png" alt="Funder 5 logo">
          </a>
          <a href="https://anr.fr/en/france-2030/france-2030/" target="_blank" rel="noopener">
            <img src="logos/France2030.jpeg" alt="Funder 6 logo">
          </a>
          <a href="https://www.inserm.fr/" target="_blank" rel="noopener">
            <img src="logos/INSERM.webp" alt="Funder 7 logo">
          </a>
          <a href="https://www.cancer.fr/" target="_blank" rel="noopener">
            <img src="logos/InstitutNationalDuCancer.png" alt="Funder 8 logo">
          </a>
          <a href="https://www.msdavenir.fr/" target="_blank" rel="noopener">
            <img src="logos/MSD_avenir.png" alt="Funder 9 logo">
          </a>
          <a href="https://www.frm.org/en" target="_blank" rel="noopener">
            <img src="logos/FRM.jpg" alt="Funder 10 logo">
          </a>
          <!-- repeat... -->
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['50px', '0', '40px', '0']
      css_class: funders-section

  - block: markdown
    content:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
        {{% cta cta_link="./vacancies/" cta_text="Open positions →" %}}
    design:
      columns: '1'
---