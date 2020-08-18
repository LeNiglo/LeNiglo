### Hello World 👋

```javascript
'use strict'

const leniglo = {
  user: {
    name: 'Guillaume Lefrant',
    gender: 'male',
    birthyear: 1994,
  },
  contact: {
    email: 'lefrantguillaume@gmail.com',
    website: 'https://www.lefrantguillaume.com',
  },
  interests: ['motorsport', 'volleyball', 'vegetable garden'],
  technologies: {
    languages: ['PHP', 'Javascript', 'C/C++', 'Java', 'C#.Net', 'Python', 'Bash'],
    backend: {
      php: ['laravel (⚡️)', 'homemade'],
      javascript: ['node', 'express', 'adonis', 'meteor (⚡️)', 'sails'],
      python: ['django', 'flask'],
      other: ['spring boot', 'dotnet core']
    },
    frontend: {
      mobile: ['react native', 'flutter', 'android'],
      javascript: ['react (⚡️)', 'vue', 'jquery', 'vanilla'],
    },
    devOps: {
      architecture: ['docker', 'kubernetes', 'microservices', 'kong'],
      tools: ['gitlab ci/cd', 'github actions', 'jenkins', 'atlassian suite'],
      softwares: ['nginx', 'apache2', 'pm2', 'supervisor', 'init.d'],
      systems: ['osx', 'linux/ubuntu', 'windows'],
    },
    databases: {
      sql: ['mysql', 'mssql', 'sqlite', 'mariadb'],
      nosql: ['firebase', 'mongodb', 'minimongo', 'redis', 'cassandradb'],
    },
    concepts: ['ssr', 'realtime', 'pwa', 'mobile first'],
  }
}

```

<!--
```javascript
import React, { useState, useEffect } from 'react'
import axios from 'axios'
import world from 'google-news-foryou'

const LeNiglo = ({ name }) => {
  const [ technos, setTechnos ] = useState([])
  
  const loadTechnos = async () => {
    return await axios.get(`/technologies/all`)
  }
  
  useEffect(() => {
    loadTechnos().then(technos => {
      setTechnos(technos.data)
    })
  }, [])
  
  world.channel(`techno`)
  .listen(`newTechno`, techno => {
    setTechnos(technos => [...technos, techno])
  })
  
  return (
    <>
      <h1>{ name } - Enthousiast Web Developer</h1>
      
      <div className="technologies">
        {technos.map(t => <div className="technology">{ t.name }</div>)}
      </div>
    </>
  )
}

export default LeNiglo
```

Eager to approach, tame and enjoy (or not) every technology
-->

<!--
**LeNiglo/LeNiglo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
