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
      icon: 'i-material-symbols:work'

  Education:
    - name: 'MS in Computer Science'
      link: 'https://www.syracuse.edu/'
      desc: "Syracuse University"
      icon: 'i-ion:university'
    - name: 'BE in Information Science'
      link: 'https://bit-bangalore.edu.in/'
      desc: "Bangalore Institute of Technology"
      icon: 'i-ion:university'

  Certifications:
    - name: 'Nuxt DevTools'
      link: 'https://github.com/nuxt/devtools'
      desc: 'Unleash Nuxt Developer Experience'
      icon: 'i-logos-nuxt-icon saturate-0'
    - name: 'Node Modules Inspector'
      link: 'https://github.com/antfu/node-modules-inspector'
      desc: 'Visualize and inspect your node_modules'
      icon: 'i-solar-black-hole-line-duotone'
  
  Expertise:
    - name: 'Nuxt DevTools'
      link: 'https://github.com/nuxt/devtools'
      desc: 'Unleash Nuxt Developer Experience'
      icon: 'i-logos-nuxt-icon saturate-0'
    - name: 'Node Modules Inspector'
      link: 'https://github.com/antfu/node-modules-inspector'
      desc: 'Visualize and inspect your node_modules'
      icon: 'i-solar-black-hole-line-duotone'
---

<!-- @layout-full-width -->
<ListProjects :projects="frontmatter.projects" />
