---
title: Portfolio - Akshay Aravind
display: Portfolio
description: My experience, skills & certificates 
wrapperClass: 'text-center'
art: dots
projects:
  Current Focus:
    - name: 'Vite DevTools'
      link: 'https://github.com/vitejs/devtools'
      desc: 'Inspect the intermediate state of Vite bundle and pipeline'
      icon: 'i-simple-icons-vite'
    - name: 'Nuxt DevTools'
      link: 'https://github.com/nuxt/devtools'
      desc: 'Unleash Nuxt Developer Experience'
      icon: 'i-logos-nuxt-icon saturate-0'
    - name: 'Nuxt Playground'
      link: 'https://github.com/nuxt/learn.nuxt.com'
      desc: 'Interactive Playground for learning Nuxt'
      icon: 'i-logos-nuxt-icon saturate-0'

  Nuxt Ecosystem:
    - name: 'Nuxt'
      link: 'https://github.com/nuxt/nuxt'
      desc: 'The intuitive Vue Framework. (Team member)'
      icon: 'i-logos-nuxt-icon saturate-0'
    - name: 'Nuxt Playground'
      link: 'https://github.com/nuxt/learn.nuxt.com'
      desc: 'Interactive Playground for learning Nuxt'
      icon: 'i-logos-nuxt-icon saturate-0'

  DevTools:
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
