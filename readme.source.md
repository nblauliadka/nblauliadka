```aura width=800 height=220
<div style={{ position: 'relative', display: 'flex', width: '100%', height: '100%', background: '#0a0a0f', borderRadius: 16, overflow: 'hidden', border: '1px solid rgba(255,255,255,0.05)', fontFamily: 'Inter, sans-serif' }}>
  
  <svg width="100%" height="100%" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="card1-g1" cx="20%" cy="80%" r="60%">
        <stop offset="0%" stopColor="rgba(45, 20, 200, 0.4)" />
        <stop offset="100%" stopColor="rgba(45, 20, 200, 0)" />
      </radialGradient>
      <radialGradient id="card1-g2" cx="80%" cy="20%" r="50%">
        <stop offset="0%" stopColor="rgba(120, 40, 200, 0.2)" />
        <stop offset="100%" stopColor="rgba(120, 40, 200, 0)" />
      </radialGradient>
    </defs>
    <rect width="100%" height="100%" fill="url(#card1-g1)" />
    <rect width="100%" height="100%" fill="url(#card1-g2)" />
  </svg>

  <div style={{ position: 'relative', display: 'flex', flexDirection: 'row', alignItems: 'center', padding: '0 40px', zIndex: 10, width: '100%' }}>
    
    <img src="./profile.png" style={{ width: 120, height: 120, borderRadius: 60, border: '3px solid rgba(255,255,255,0.1)', objectFit: 'cover' }} />
    
    <div style={{ display: 'flex', flexDirection: 'column', marginLeft: 30, flex: 1, justifyContent: 'center' }}>
      <span style={{ fontSize: 36, fontWeight: 700, color: '#ffffff', letterSpacing: -1 }}>Nabil Aulia Dika</span>
      <span style={{ fontSize: 14, color: '#b4a6ff', fontWeight: 500, marginTop: 4 }}>Full Stack Web Developer | Informatics Student @ USK</span>
      
      <div style={{ display: 'flex', gap: 10, marginTop: 20 }}>
        {['React', 'TypeScript', 'Node.js', 'Linux'].map((tech, i) => (
          <span key={i} style={{ padding: '5px 14px', background: 'rgba(255,255,255,0.05)', color: 'rgba(255,255,255,0.7)', borderRadius: 100, fontSize: 11, border: '1px solid rgba(255,255,255,0.1)' }}>
            {tech}
          </span>
        ))}
      </div>
    </div>
  </div>
</div>
```

```aura width=800 height=140
<div style={{ position: 'relative', display: 'flex', flexDirection: 'row', alignItems: 'center', justifyContent: 'space-around', width: '100%', height: '100%', background: '#0a0a0f', borderRadius: 16, overflow: 'hidden', border: '1px solid rgba(255,255,255,0.05)', fontFamily: 'Inter, sans-serif' }}>
  
  <svg width="100%" height="100%" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="card2-g1" cx="16%" cy="100%" r="50%">
        <stop offset="0%" stopColor="rgba(180, 166, 255, 0.25)" />
        <stop offset="100%" stopColor="rgba(180, 166, 255, 0)" />
      </radialGradient>
      <radialGradient id="card2-g2" cx="50%" cy="100%" r="50%">
        <stop offset="0%" stopColor="rgba(77, 166, 255, 0.25)" />
        <stop offset="100%" stopColor="rgba(77, 166, 255, 0)" />
      </radialGradient>
      <radialGradient id="card2-g3" cx="84%" cy="100%" r="50%">
        <stop offset="0%" stopColor="rgba(255, 179, 71, 0.2)" />
        <stop offset="100%" stopColor="rgba(255, 179, 71, 0)" />
      </radialGradient>
    </defs>
    <rect width="100%" height="100%" fill="url(#card2-g1)" />
    <rect width="100%" height="100%" fill="url(#card2-g2)" />
    <rect width="100%" height="100%" fill="url(#card2-g3)" />
  </svg>

  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 10, width: 150 }}>
    <span style={{ fontSize: 32, fontWeight: 700, color: '#b4a6ff' }}>{(github && github.user && github.user.public_repos) || 14}</span>
    <span style={{ fontSize: 10, color: 'rgba(255,255,255,0.4)', letterSpacing: 2, marginTop: 4, textTransform: 'uppercase' }}>REPOS</span>
  </div>
  
  <div style={{ position: 'relative', width: 1, height: 60, background: 'rgba(255,255,255,0.05)', zIndex: 10 }}></div>

  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 10, width: 150 }}>
    <span style={{ fontSize: 32, fontWeight: 700, color: '#4da6ff' }}>{(github && github.user && github.user.followers) || 10}</span>
    <span style={{ fontSize: 10, color: 'rgba(255,255,255,0.4)', letterSpacing: 2, marginTop: 4, textTransform: 'uppercase' }}>FOLLOWERS</span>
  </div>

  <div style={{ position: 'relative', width: 1, height: 60, background: 'rgba(255,255,255,0.05)', zIndex: 10 }}></div>

  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 10, width: 150 }}>
    <span style={{ fontSize: 32, fontWeight: 700, color: '#ffb347' }}>100+</span>
    <span style={{ fontSize: 10, color: 'rgba(255,255,255,0.4)', letterSpacing: 2, marginTop: 4, textTransform: 'uppercase' }}>COMMITS</span>
  </div>
</div>
```

```aura width=800 height=200
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', padding: 30, width: '100%', height: '100%', background: '#0a0a0f', borderRadius: 16, overflow: 'hidden', border: '1px solid rgba(255,255,255,0.05)', fontFamily: 'Inter, sans-serif' }}>
  
  <svg width="100%" height="100%" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="card3-g1" cx="80%" cy="80%" r="60%">
        <stop offset="0%" stopColor="rgba(100, 30, 200, 0.25)" />
        <stop offset="100%" stopColor="rgba(100, 30, 200, 0)" />
      </radialGradient>
    </defs>
    <rect width="100%" height="100%" fill="url(#card3-g1)" />
  </svg>

  <span style={{ position: 'relative', fontSize: 10, color: 'rgba(255,255,255,0.3)', letterSpacing: 3, textTransform: 'uppercase', marginBottom: 20, zIndex: 10 }}>TECH STACK</span>

  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', gap: 16, zIndex: 10 }}>
    
    <div style={{ display: 'flex', alignItems: 'center' }}>
      <span style={{ fontSize: 11, color: '#b4a6ff', width: 120, fontWeight: 600, letterSpacing: 1 }}>LANGUAGES</span>
      <div style={{ display: 'flex', gap: 10 }}>
        {['TypeScript', 'JavaScript', 'C', 'HTML/CSS'].map((tech, i) => (
          <span key={i} style={{ padding: '4px 14px', background: 'rgba(255,255,255,0.03)', color: 'rgba(255,255,255,0.8)', borderRadius: 6, fontSize: 12, border: '1px solid rgba(255,255,255,0.08)' }}>{tech}</span>
        ))}
      </div>
    </div>

    <div style={{ display: 'flex', alignItems: 'center' }}>
      <span style={{ fontSize: 11, color: '#4da6ff', width: 120, fontWeight: 600, letterSpacing: 1 }}>FRAMEWORKS</span>
      <div style={{ display: 'flex', gap: 10 }}>
        {['React', 'Next.js', 'Express', 'Tailwind'].map((tech, i) => (
          <span key={i} style={{ padding: '4px 14px', background: 'rgba(255,255,255,0.03)', color: 'rgba(255,255,255,0.8)', borderRadius: 6, fontSize: 12, border: '1px solid rgba(255,255,255,0.08)' }}>{tech}</span>
        ))}
      </div>
    </div>

    <div style={{ display: 'flex', alignItems: 'center' }}>
      <span style={{ fontSize: 11, color: '#ffb347', width: 120, fontWeight: 600, letterSpacing: 1 }}>INFRA/TOOLS</span>
      <div style={{ display: 'flex', gap: 10 }}>
        {['Arch Linux', 'Git', 'Firebase', 'Figma'].map((tech, i) => (
          <span key={i} style={{ padding: '4px 14px', background: 'rgba(255,255,255,0.03)', color: 'rgba(255,255,255,0.8)', borderRadius: 6, fontSize: 12, border: '1px solid rgba(255,255,255,0.08)' }}>{tech}</span>
        ))}
      </div>
    </div>

  </div>
</div>
```