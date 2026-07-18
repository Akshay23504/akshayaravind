---
title: Portfolio - Akshay Aravind
display: Portfolio
description: My experience, skills & certificates 
wrapperClass: 'text-center'
art: random
projects:
  Experience:
    - name: 'AVP | Senior Software Engineer'
      link: 'https://www.barclays.com'
      desc: "Barclays"
      icon: 'i-simple-icons:barclays'
    - name: 'Technology Intern'
      link: 'https://www.barclays.com'
      desc: "Barclays"
      icon: 'i-simple-icons:barclays'
    - name: 'Software Engineer'
      link: 'https://www.betsol.com'
      desc: "Betsol"
      icon: 'i-mdi:work'

  Education:
    - name: 'MS in Computer Science'
      link: 'https://www.syracuse.edu/'
      desc: "Syracuse University"
      icon: 'i-mdi:university'
    - name: 'BE in Information Science'
      link: 'https://bit-bangalore.edu.in/'
      desc: "Bangalore Institute of Technology"
      icon: 'i-mdi:university'

  Certifications:
    - name: 'Google Generative AI Leader Certification'
      link: 'https://www.credly.com/badges/ef989029-a73a-473b-b24b-f81b02d819b1/public_url'
      desc: 'Jan 2026'
      icon: 'i-mdi:certificate'
    - name: 'AWS Certified Cloud Practitioner'
      link: 'https://www.credly.com/badges/d4fc882c-4e03-4e45-b2ab-5fba2109f057/public_url'
      desc: 'Jan 2025'
      icon: 'i-mdi:certificate'
  
  Expertise:
    - name: 'Python'
      link: 'https://www.python.org/'
      desc: 'Languages'
      icon: 'i-simple-icons:python'
    - name: 'Scala'
      link: 'https://www.scala-lang.org/'
      desc: 'Languages'
      icon: 'i-simple-icons:scala'
    - name: 'Java'
      link: 'https://www.java.com/en/'
      desc: 'Languages'
      icon: 'i-mdi:language-java'
    - name: 'YAML'
      link: 'https://yaml.org/'
      desc: 'Languages'
      icon: 'i-simple-icons:yaml'
    - name: 'AWS'
      link: 'https://aws.amazon.com/'
      desc: 'Cloud & DevOps'
      icon: 'i-mdi:aws'
    - name: 'GCP'
      link: 'https://cloud.google.com/'
      desc: 'Cloud & DevOps'
      icon: 'i-material-icon-theme:gcp'
    - name: 'Docker'
      link: 'https://www.docker.com/'
      desc: 'Cloud & DevOps'
      icon: 'i-mdi:docker'
    - name: 'GitLab'
      link: 'https://about.gitlab.com/'
      desc: 'Cloud & DevOps'
      icon: 'i-mdi:gitlab'
    - name: 'The Hadoop Ecosystem'
      link: 'https://hadoop.apache.org/'
      desc: 'Data & Distributed Systems'
      icon: 'i-simple-icons:apachehadoop'
---

<!-- @layout-full-width -->
<ListProjects :projects="frontmatter.projects" />
