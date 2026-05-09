# hi, i'm [your name] 👋

<!-- satori:start -->
```jsx
// This React component gets compiled to SVG via satori
export default function Banner() {
  return (
    <div style={{
      display: 'flex', flexDirection: 'column',
      background: 'linear-gradient(135deg, #0f0f0f, #1a1a2e)',
      width: 800, height: 200, padding: 40,
      fontFamily: 'sans-serif', color: '#fff',
      borderRadius: 16
    }}>
      <h1 style={{ fontSize: 40, margin: 0, fontWeight: 700 }}>
        your name
      </h1>
      <p style={{ fontSize: 18, opacity: 0.7, marginTop: 8 }}>
        full-stack dev · open source · coffee-driven
      </p>
    </div>
  )
}
```
<!-- satori:end -->
<!-- satori:output banner.svg -->

---

## about me

- 🔭 currently working on **[your project]**
- 🌱 learning **[technology]**
- 💬 ask me about **[your expertise]**
- 📫 reach me at **[your email]**

---

## tech stack

<!-- satori:start -->
```jsx
// Tech stack grid compiled by satori
export default function TechStack() {
  const techs = ['React','Node.js','TypeScript','PostgreSQL','Docker','Rust']
  return (
    <div style={{ display:'flex', flexWrap:'wrap', gap:12, padding:20 }}>
      {techs.map(t => (
        <div key={t} style={{
          background:'#1e1e2e', color:'#cdd6f4',
          padding:'8px 16px', borderRadius:8,
          fontSize:14, fontFamily:'monospace'
        }}>{t}</div>
      ))}
    </div>
  )
}
```
<!-- satori:end -->
<!-- satori:output techstack.svg -->

---

## github stats

![stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=tokyonight)

---

## connect

[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat&logo=twitter&logoColor=white)](https://twitter.com/yourhandle)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
