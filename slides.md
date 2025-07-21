---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Sibendu
info: |
  ## Slidev Starter Template
  Akamai to Cloudfare Journey.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
---

# Sibendu Das

Enterprise Architect, Solution Architect

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/sibendu" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---



# Executive Summary

<div class="grid grid-cols-1 gap-8 pt-6">

<div class="bg-white/90 backdrop-blur-sm p-8 rounded-2xl shadow-2xl border border-white/20">
  <div class="flex items-center gap-4 mb-6">
    <div class="w-16 h-16 bg-gradient-to-br from-purple-500 to-pink-500 rounded-full flex items-center justify-center">
      <carbon:user-avatar class="text-2xl text-white"/>
    </div>
    <div>
      <h2 class="text-2xl font-bold text-gray-800">Innovative Full-Stack Developer</h2>
      <p class="text-purple-600 font-medium">8+ Years of Technical Excellence</p>
    </div>
  </div>
  
  <p class="text-lg text-gray-700 leading-relaxed mb-6">
    Passionate technology leader with extensive experience in building scalable web applications and leading high-performing development teams. Specialized in modern JavaScript frameworks, cloud infrastructure, and agile methodologies with a proven track record of delivering innovative solutions that drive business growth.
  </p>
  
  <div class="grid grid-cols-3 gap-6">
    <div class="text-center p-4 bg-gradient-to-br from-blue-50 to-blue-100 rounded-xl">
      <div class="text-3xl font-bold text-blue-600 mb-2">120+</div>
      <div class="text-sm font-medium text-blue-800">Projects Delivered</div>
    </div>
    <div class="text-center p-4 bg-gradient-to-br from-green-50 to-green-100 rounded-xl">
      <div class="text-3xl font-bold text-green-600 mb-2">$2.5M+</div>
      <div class="text-sm font-medium text-green-800">Revenue Impact</div>
    </div>
    <div class="text-center p-4 bg-gradient-to-br from-purple-50 to-purple-100 rounded-xl">
      <div class="text-3xl font-bold text-purple-600 mb-2">15+</div>
      <div class="text-sm font-medium text-purple-800">Team Members Led</div>
    </div>
  </div>
</div>

</div>

<style>
h1 {
  color: white;
  text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
  font-size: 3rem;
  margin-bottom: 2rem;
}
</style>

---
background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%)
class: 'px-10'
---



# Professional Highlights

<div class="grid grid-cols-2 gap-6 pt-6">

<div class="space-y-4">
  <div class="bg-white/95 backdrop-blur-sm p-6 rounded-2xl shadow-xl border border-white/30 transform hover:scale-105 transition-all duration-300">
    <div class="flex items-center gap-4 mb-4">
      <div class="w-12 h-12 bg-gradient-to-br from-green-400 to-green-600 rounded-xl flex items-center justify-center">
        <carbon:rocket class="text-xl text-white"/>
      </div>
      <h3 class="text-xl font-bold text-gray-800">Product Innovation Leader</h3>
    </div>
    <p class="text-gray-600 text-sm leading-relaxed">
      Spearheaded the development of 3 flagship products that generated <strong>$2.5M in revenue</strong> and increased user engagement by <strong>78%</strong>. Led cross-functional teams through complete product lifecycle from ideation to market launch.
    </p>
  </div>

  <div class="bg-white/95 backdrop-blur-sm p-6 rounded-2xl shadow-xl border border-white/30 transform hover:scale-105 transition-all duration-300">
    <div class="flex items-center gap-4 mb-4">
      <div class="w-12 h-12 bg-gradient-to-br from-purple-400 to-purple-600 rounded-xl flex items-center justify-center">
        <carbon:lightning class="text-xl text-white"/>
      </div>
      <h3 class="text-xl font-bold text-gray-800">Performance Optimization Expert</h3>
    </div>
    <p class="text-gray-600 text-sm leading-relaxed">
      Architected microservices infrastructure that reduced system latency by <strong>65%</strong> and increased throughput to handle <strong>10M+ daily requests</strong>. Implemented caching strategies saving <strong>$80K annually</strong> in server costs.
    </p>
  </div>
</div>

<div class="space-y-4">
  <div class="bg-white/95 backdrop-blur-sm p-6 rounded-2xl shadow-xl border border-white/30 transform hover:scale-105 transition-all duration-300">
    <div class="flex items-center gap-4 mb-4">
      <div class="w-12 h-12 bg-gradient-to-br from-blue-400 to-blue-600 rounded-xl flex items-center justify-center">
        <carbon:user-multiple class="text-xl text-white"/>
      </div>
      <h3 class="text-xl font-bold text-gray-800">Technical Leadership</h3>
    </div>
    <p class="text-gray-600 text-sm leading-relaxed">
      Built and mentored development teams of <strong>15+ engineers</strong>, establishing coding standards and best practices. Implemented agile methodologies that improved delivery velocity by <strong>45%</strong> while maintaining 99.9% uptime.
    </p>
  </div>

  <div class="bg-white/95 backdrop-blur-sm p-6 rounded-2xl shadow-xl border border-white/30 transform hover:scale-105 transition-all duration-300">
    <div class="flex items-center gap-4 mb-4">
      <div class="w-12 h-12 bg-gradient-to-br from-orange-400 to-orange-600 rounded-xl flex items-center justify-center">
        <carbon:trophy class="text-xl text-white"/>
      </div>
      <h3 class="text-xl font-bold text-gray-800">Industry Recognition</h3>
    </div>
    <p class="text-gray-600 text-sm leading-relaxed">
      <strong>2024 Tech Excellence Award</strong> recipient, AWS Solutions Architect Professional certified, and frequent speaker at tech conferences. Published 12+ technical articles with <strong>50K+ total views</strong>.
    </p>
  </div>
</div>

</div>

<style>
h1 {
  color: white;
  text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
  font-size: 3rem;
  margin-bottom: 2rem;
}
</style>


---
background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%)
class: 'px-10'
---

# Employment History

<div class="space-y-6 pt-6">

<div class="bg-white/95 backdrop-blur-sm p-8 rounded-2xl shadow-2xl border border-white/30">
  <div class="flex justify-between items-start mb-6">
    <div class="flex items-center gap-4">
      <div class="w-16 h-16 bg-gradient-to-br from-blue-500 to-purple-600 rounded-2xl flex items-center justify-center shadow-lg">
        <span class="text-white font-bold text-xl">TC</span>
      </div>
      <div>
        <h3 class="text-2xl font-bold text-gray-800">Senior Full-Stack Developer</h3>
        <p class="text-xl text-blue-600 font-semibold">TechCorp Inc.</p>
        <p class="text-sm text-gray-500">Series B SaaS Company • 500+ employees</p>
      </div>
    </div>
    <div class="text-right">
      <div class="bg-blue-100 px-4 py-2 rounded-full">
        <span class="text-blue-800 font-semibold">Mar 2021 - Present</span>
      </div>
      <p class="text-sm text-gray-600 mt-2">San Francisco, CA</p>
    </div>
  </div>
  
  <div class="grid grid-cols-3 gap-4 mb-6">
    <div class="bg-gradient-to-r from-green-50 to-green-100 p-4 rounded-xl text-center">
      <div class="text-2xl font-bold text-green-600">$2.5M</div>
      <div class="text-xs text-green-800">Revenue Generated</div>
    </div>
    <div class="bg-gradient-to-r from-purple-50 to-purple-100 p-4 rounded-xl text-center">
      <div class="text-2xl font-bold text-purple-600">78%</div>
      <div class="text-xs text-purple-800">Performance Improvement</div>
    </div>
    <div class="bg-gradient-to-r from-orange-50 to-orange-100 p-4 rounded-xl text-center">
      <div class="text-2xl font-bold text-orange-600">15+</div>
      <div class="text-xs text-orange-800">Team Members</div>
    </div>
  </div>
  
  <div class="space-y-2 text-gray-700">
    <p>• <strong>Led architecture redesign</strong> of core platform serving 2M+ users, implementing microservices with Node.js and React</p>
    <p>• <strong>Mentored and managed</strong> team of 15 developers, establishing code review processes and technical standards</p>
    <p>• <strong>Built real-time analytics dashboard</strong> processing 10M+ events daily using Redis, WebSockets, and D3.js</p>
    <p>• <strong>Implemented CI/CD pipeline</strong> reducing deployment time from 4 hours to 12 minutes with 99.9% uptime</p>
  </div>
</div>

<div class="bg-white/95 backdrop-blur-sm p-8 rounded-2xl shadow-2xl border border-white/30">
  <div class="flex justify-between items-start mb-6">
    <div class="flex items-center gap-4">
      <div class="w-16 h-16 bg-gradient-to-br from-green-500 to-teal-600 rounded-2xl flex items-center justify-center shadow-lg">
        <span class="text-white font-bold text-xl">SX</span>
      </div>
      <div>
        <h3 class="text-2xl font-bold text-gray-800">Full-Stack Developer</h3>
        <p class="text-xl text-green-600 font-semibold">StartupXYZ</p>
        <p class="text-sm text-gray-500">Early-stage FinTech • 25-50 employees</p>
      </div>
    </div>
    <div class="text-right">
      <div class="bg-green-100 px-4 py-2 rounded-full">
        <span class="text-green-800 font-semibold">Jun 2019 - Mar 2021</span>
      </div>
      <p class="text-sm text-gray-600 mt-2">Remote</p>
    </div>
  </div>
  
  <div class="space-y-2 text-gray-700">
    <p>• <strong>Developed full-stack applications</strong> using React, TypeScript, Node.js, and PostgreSQL for financial services platform</p>
    <p>• <strong>Collaborated with product team</strong> to design and implement responsive, accessible user interfaces following WCAG guidelines</p>
    <p>• <strong>Integrated third-party APIs</strong> for payment processing, KYC verification, and fraud detection systems</p>
    <p>• <strong>Optimized database queries</strong> improving application performance by 45% and reducing server response times</p>
  </div>
</div>

</div>

<style>
h1 {
  color: #2d3748;
  font-size: 3rem;
  margin-bottom: 2rem;
  text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
}
</style>

---

# Skills

<div class="grid grid-cols-2 gap-6 pt-4">

<div>
  <h3 class="text-xl font-bold mb-4 text-blue-600 dark:text-blue-400">Technical Skills</h3>
  
  <div class="space-y-3">
    <div>
      <div class="flex justify-between text-sm mb-1">
        <span class="font-medium">JavaScript/TypeScript</span>
        <span class="text-gray-500">Expert</span>
      </div>
      <div class="w-full bg-gray-200 dark:bg-gray-700 rounded-full h-2">
        <div class="bg-blue-500 h-2 rounded-full" style="width: 95%"></div>
      </div>
    </div>
    
  </div>
</div>

<div>
  <h3 class="text-xl font-bold mb-4 text-green-600 dark:text-green-400">Core Competencies</h3>
  
  <div class="grid grid-cols-2 gap-2">
    <div class="bg-blue-100 dark:bg-blue-900/30 px-3 py-2 rounded-lg text-center">
      <span class="text-sm font-medium">Team Leadership</span>
    </div>
    <div class="bg-green-100 dark:bg-green-900/30 px-3 py-2 rounded-lg text-center">
      <span class="text-sm font-medium">Agile/Scrum</span>
    </div>
    <div class="bg-purple-100 dark:bg-purple-900/30 px-3 py-2 rounded-lg text-center">
      <span class="text-sm font-medium">System Design</span>
    </div>
    <div class="bg-orange-100 dark:bg-orange-900/30 px-3 py-2 rounded-lg text-center">
      <span class="text-sm font-medium">DevOps</span>
    </div>
    <div class="bg-red-100 dark:bg-red-900/30 px-3 py-2 rounded-lg text-center">
      <span class="text-sm font-medium">Code Review</span>
    </div>
    <div class="bg-indigo-100 dark:bg-indigo-900/30 px-3 py-2 rounded-lg text-center">
      <span class="text-sm font-medium">Mentoring</span>
    </div>
  </div>
</div>

</div>

---

# Education

<div class="space-y-6 pt-4">

<div class="bg-gradient-to-r from-indigo-50 to-purple-50 dark:from-indigo-900/20 dark:to-purple-900/20 p-6 rounded-lg border-l-4 border-indigo-500">
  <div class="flex justify-between items-start mb-3">
    <div>
      <h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">Master of Science in Computer Science</h3>
      <p class="text-lg text-indigo-600 dark:text-indigo-400 font-semibold">Stanford University</p>
    </div>
    <div class="text-right">
      <p class="text-sm font-medium text-gray-600 dark:text-gray-400">2017 - 2019</p>
      <p class="text-sm text-gray-500 dark:text-gray-500">GPA: 3.8/4.0</p>
    </div>
  </div>
  <p class="text-sm text-gray-600 dark:text-gray-300">Specialization: Distributed Systems and Machine Learning</p>
</div>

<div class="bg-gradient-to-r from-blue-50 to-cyan-50 dark:from-blue-900/20 dark:to-cyan-900/20 p-6 rounded-lg border-l-4 border-blue-500">
  <div class="flex justify-between items-start mb-3">
    <div>
      <h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">Bachelor of Engineering in Software Engineering</h3>
      <p class="text-lg text-blue-600 dark:text-blue-400 font-semibold">University of California, Berkeley</p>
    </div>
    <div class="text-right">
      <p class="text-sm font-medium text-gray-600 dark:text-gray-400">2013 - 2017</p>
      <p class="text-sm text-gray-500 dark:text-gray-500">Magna Cum Laude</p>
    </div>
  </div>
  <p class="text-sm text-gray-600 dark:text-gray-300">Relevant Coursework: Data Structures, Algorithms, Database Systems, Software Architecture</p>
</div>

<div class="grid grid-cols-3 gap-4 mt-6">
  <div class="bg-white dark:bg-gray-800 p-4 rounded-lg shadow-sm text-center">
    <h4 class="font-semibold text-green-600 dark:text-green-400 mb-1">AWS Certified</h4>
    <p class="text-xs text-gray-500">Solutions Architect</p>
  </div>
  <div class="bg-white dark:bg-gray-800 p-4 rounded-lg shadow-sm text-center">
    <h4 class="font-semibold text-blue-600 dark:text-blue-400 mb-1">Scrum Master</h4>
    <p class="text-xs text-gray-500">Certified (CSM)</p>
  </div>
  <div class="bg-white dark:bg-gray-800 p-4 rounded-lg shadow-sm text-center">
    <h4 class="font-semibold text-purple-600 dark:text-purple-400 mb-1">Google Cloud</h4>
    <p class="text-xs text-gray-500">Professional</p>
  </div>
</div>

</div>

---

# Projects

<div class="grid grid-cols-1 gap-6 pt-2">

<div class="bg-gradient-to-r from-blue-50 to-indigo-50 dark:from-blue-900/20 dark:to-indigo-900/20 p-6 rounded-lg border-l-4 border-blue-500">
  <div class="flex justify-between items-start mb-3">
    <h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">E-Commerce Platform Redesign</h3>
    <div class="flex gap-2">
      <span class="px-2 py-1 bg-blue-200 dark:bg-blue-800 text-blue-800 dark:text-blue-200 rounded text-xs">React</span>
      <span class="px-2 py-1 bg-green-200 dark:bg-green-800 text-green-800 dark:text-green-200 rounded text-xs">Node.js</span>
    </div>
  </div>
  <p class="text-sm text-gray-600 dark:text-gray-300 mb-2">Led complete redesign of e-commerce platform serving 100K+ customers, resulting in 45% increase in conversion rate and 30% improvement in page load times.</p>
  <p class="text-xs text-gray-500 dark:text-gray-400">Key Features: Microservices architecture, real-time inventory, payment gateway integration</p>
</div>

<div class="bg-gradient-to-r from-green-50 to-emerald-50 dark:from-green-900/20 dark:to-emerald-900/20 p-6 rounded-lg border-l-4 border-green-500">
  <div class="flex justify-between items-start mb-3">
    <h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">Data Analytics Dashboard</h3>
    <div class="flex gap-2">
      <span class="px-2 py-1 bg-green-200 dark:bg-green-800 text-green-800 dark:text-green-200 rounded text-xs">Python</span>
      <span class="px-2 py-1 bg-purple-200 dark:bg-purple-800 text-purple-800 dark:text-purple-200 rounded text-xs">D3.js</span>
    </div>
  </div>
  <p class="text-sm text-gray-600 dark:text-gray-300 mb-2">Built real-time analytics dashboard processing 1M+ events daily, providing business insights that influenced strategic decisions worth $2M+ in revenue.</p>
  <p class="text-xs text-gray-500 dark:text-gray-400">Technologies: Redis, PostgreSQL, WebSocket connections, automated reporting</p>
</div>

<div class="bg-gradient-to-r from-purple-50 to-pink-50 dark:from-purple-900/20 dark:to-pink-900/20 p-6 rounded-lg border-l-4 border-purple-500">
  <div class="flex justify-between items-start mb-3">
    <h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">Mobile-First SaaS Application</h3>
    <div class="flex gap-2">
      <span class="px-2 py-1 bg-purple-200 dark:bg-purple-800 text-purple-800 dark:text-purple-200 rounded text-xs">React Native</span>
      <span class="px-2 py-1 bg-orange-200 dark:bg-orange-800 text-orange-800 dark:text-orange-200 rounded text-xs">AWS</span>
    </div>
  </div>
  <p class="text-sm text-gray-600 dark:text-gray-300 mb-2">Developed cross-platform mobile application with offline capabilities, achieving 50K+ downloads and 4.8-star rating on app stores.</p>
  <p class="text-xs text-gray-500 dark:text-gray-400">Features: Offline sync, push notifications, biometric authentication, cloud integration</p>
</div>

</div>

---
layout: center
class: text-center
---


# Thank You

<div class="pt-8">
  
  <div class="flex justify-center gap-6 mb-8">
    <a href="mailto:sibendu.das@gmail.com" class="flex items-center gap-2 px-4 py-2 bg-blue-500 text-white rounded-lg hover:bg-blue-600 transition-colors">
      <carbon:email />
      Email
    </a>
    <a href="https://www.linkedin.com/in/sibendu-das/" class="flex items-center gap-2 px-4 py-2 bg-indigo-500 text-white rounded-lg hover:bg-indigo-600 transition-colors">
      <carbon:logo-linkedin />
      LinkedIn
    </a>
    <a href="https://github.com/sibendu" class="flex items-center gap-2 px-4 py-2 bg-gray-800 dark:bg-gray-600 text-white rounded-lg hover:bg-gray-900 dark:hover:bg-gray-700 transition-colors">
      <carbon:logo-github />
      GitHub
    </a>
  </div>
  
  <div class="mb-6">
    <h2 class="text-2xl mb-4 text-gray-400 dark:text-gray-100">'Work is love made visible'</h2> 
  </div>

</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>
