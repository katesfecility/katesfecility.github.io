---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "Hi, I’m Jone Lee"
  text: "a Professional Coder"
  tagline: I use animation as a third dimension by which to simplify experiences and kuiding thro each and every interaction. I’m not adding motion just to spruce things up, but doing it in ways that.
  image: 'img/banner-01.png'
  actions:
    - theme: brand
      text: Checkout my resume
      link: /markdown-examples

features:
  - title: Business Strategy
    details: I throw myself down among the tall grass by the stream as Ilie close to the earth.
    icon: 🛠️
    link: /markdown-examples
  - title: App Development
    details: We’ll handle everything from to app development process until it is time to make your project live.
    icon: 🛠️
  - title: Business Strategy
    details: We’ll help you optimize your business processes to maximize profitability and eliminate unnecessary costs.
    icon: 🛠️
  - title: Mobile App
    details: Using our expertise in mobile application development to create beautiful pixel-perfect designs.
    icon: 📱
  - title: SEO Optimisation
    details: Your website ranking matters. Our SEO services will help you get to the top of the ranks and stay there!
    icon: 🛜
  - title: UX Consulting
    details: A UX consultant is responsible for many of the same tasks as a UX designer, but they typically.
    icon: 🔥
---

<script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers
} from 'vitepress/theme'

const members = [
  {
    avatar: 'https://www.github.com/yyx990803.png',
    name: 'Evan You',
    title: 'Creator',
    links: [
      { icon: 'github', link: 'https://github.com/yyx990803' },
      { icon: 'twitter', link: 'https://twitter.com/youyuxi' }
    ]
  },
  {
    avatar: 'https://www.github.com/yyx990803.png',
    name: 'Evan You',
    title: 'Creator',
    links: [
      { icon: 'github', link: 'https://github.com/yyx990803' },
      { icon: 'twitter', link: 'https://twitter.com/youyuxi' }
    ]
  },
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>
      Our Team
    </template>
    <template #lead>
      The development of VitePress is guided by an international
      team, some of whom have chosen to be featured below.
    </template>
  </VPTeamPageTitle>
  <VPTeamMembers
    :members="members"
  />
</VPTeamPage>