---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    id: experience
    content:
      title: Work Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Data Scientist
          company: Vayana Network
          company_url: 'https://vayana.com/'
          company_logo: vayana
          location: Bengaluru, India | Full time, Hybrid
          date_start: '2022-06-01'
          date_end: ''
          description: |-
            * Processing and managing the company’s data efficiently and securely by building a central data repository on AWS through data pipelines and internal libraries.
            * Investigating the company's business network through data analysis and graph modeling to identify key patterns, trends, and potential customers shaping the company's business growth strategies.
        - title: Data Science Intern
          company: Ageless Partners
          company_url: 'https://agelesspartners.com/'
          company_logo: ageless
          location: California, US | Part time, Remote
          date_start: '2021-11-01'
          date_end: '2022-03-31'
          description: |-
            * Designed the architecture for a fitness recommendation application based on wearable devices and led the team toward implementing the first milestone.
            * Assessed the effectiveness of different anti-aging drugs and products endorsed by the company through analysis of customer feedback data.
        - title: Undergraduate Teaching Assistant
          company: CS Department, Ashoka University 
          company_url: 'https://cs.ashoka.edu.in/'
          company_logo: ashoka
          location: Sonipat, India | Full time
          date_start: '2020-09-01'
          date_end: '2021-05-31'
          description: |-
            * Teaching Assistant for Discrete Mathematics course, offered in Spring 2021 semester by Professor Subhash Bhalla and Probability & Statistics course, offered in Monsoon 2020 semester by Professor Mahavir Jhawar.
            * Responsibilities included assisting in conducting online classes, grading student submissions, conducting lab hours, and holding office hours to clarify student doubts.
        - title: Web Developer
          company: Techvik 
          company_url: 'https://www.linkedin.com/company/techvik-blog/'
          company_logo: techvik
          location: Lucknow, India | Internship, Remote
          date_start: '2020-06-01'
          date_end: '2020-08-31'
          description: |-
            * Redesigned and remodeled the platform’s website on WIX, increasing the user traffic by up to 20 %.
            * Optimized the website’s load time and increased its SEO performance by 30 % through media optimization and extensive keyword tagging.
    design:
      columns: '2'
  - block: experience
    id: research
    content:
      title: Research 
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Privacy-Preserving Machine Learning
          company: CS Department, Ashoka University 
          company_url: 'https://cs.ashoka.edu.in/'
          company_logo: ashoka
          location: Sonipat, India | Capstone Project
          date_start: '2021-09-01'
          date_end: '2022-01-31' 
          description: |-
            * Mentors: [Prof. Mahavir Jhawar](https://sites.google.com/site/homeofmahavir/Home) & [Prof. Debayan Gupta](https://debayangupta.com/)
            * Researched and explored various methods and techniques for securely and efficiently training neural networks in multi-party settings (MPC).
            * Thoroughly analyzed and implemented( in C++) the SecureNN paper for my Capstone Project
            * [Presentation](https://drive.google.com/file/d/1JFS6bBeWm4UlAQ_fubEqCSSNgYww8_8V/view) | [Report](https://drive.google.com/file/d/1JFLW0w2Oa1HfzXtYYAXC0Qk_HXl9MO2p/view) | [Code](https://github.com/kubershahi/ashoka-capstone) 
        - title: Research Intern
          company: Mphasis Lab 
          company_url: 'https://ml2ct.ashoka.edu.in/en/'
          company_logo: mphasis
          location: Sonipat, India | Internship
          date_start: '2021-06-01'
          date_end: '2021-08-31'
          description: |-
            * Mentor: [Prof. Mahavir Jhawar](https://sites.google.com/site/homeofmahavir/Home)
            * Successfully studied and implemented (in C++) different PPML (Privacy Preserving Machine Learning) protocols such as SecureML and BLAZE highlighting their merits and demerits
            * Designed a faster protocol tailored to meet business requirements by developing a novel algorithm to securely evaluate non-linear functions using arithmetic shares.
            * [Details](https://ml2ct.ashoka.edu.in/en/research-groups/archived/privacy-preserving-machine-learning/) | [Code](https://github.com/kubershahi/mphasis_ppml)
        - title: Secure ML & Applied Cryptography
          company: CS Department, Ashoka University 
          company_url: 'https://cs.ashoka.edu.in/'
          company_logo: ashoka
          location: Sonipat, India | Independent Study Modules
          date_start: '2021-01-01'
          date_end: '2022-05-31'
          description: |-
            * Mentors: [Prof. Debayan Gupta](https://debayangupta.com/) for Secure ML & [Prof. Mahavir Jhawar](https://sites.google.com/site/homeofmahavir/Home) for Applied Cryptography
            * Secure ML: Studied and demonstrated the impact of Data Poisoning attacks on the performance and reliability omachine learning (ML) models. [Presentation](https://drive.google.com/file/d/1JPf0sTzcB3c_PVW-k8DXiCt2MOkmAww4/view) | [Code](https://github.com/kubershahi/ashoka-secureml)
            * Applied Cryptography: Evaluated and illustrated the security vulnerabilities in email clients that support the two primary forms of end-to-end email encryption (OpenPGP and S/MIME) and suggested countermeasures against them. [Report](https://drive.google.com/file/d/1Jgb1thphAf9mahwAORPcuwF-_jH0lWi_/view) | [Code](https://github.com/kubershahi/ashoka-applied-cryptography)
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Machine Learning
          tag: ml
        - name: Statistics
          tag: stat
        - name: Cryptography
          tag: crypto
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
    # design:
    #   columns: '2'
    #   view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      email: shahikuber97@gmail.com
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/_shahikuber'
        - icon: linkedin
          icon_pack: fab
          name: Connect with me
          link: https://linkedin.com/in/kubershahi
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
