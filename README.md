export default function Home() {
  return (
    <main style={{
      backgroundColor: '#000',
      color: '#d4af37',
      fontFamily: 'Poppins, sans-serif',
      textAlign: 'center',
      padding: '80px 20px',
      minHeight: '100vh'
    }}>
      <h1 style={{ fontSize: '36px', letterSpacing: '2px' }}>夜色轻奢 · Bohan Club</h1>
      <p style={{ marginTop: '20px', fontSize: '18px', opacity: 0.8 }}>
        每一个夜晚，都是独属于你的奢华时刻。
      </p>

      <a href="/reserve"
        style={{
          display: 'inline-block',
          marginTop: '40px',
          padding: '12px 32px',
          border: '1px solid #d4af37',
          borderRadius: '50px',
          color: '#d4af37',
          textDecoration: 'none',
          transition: '0.3s'
        }}
        onMouseOver={(e) => e.target.style.backgroundColor = '#d4af37'}
        onMouseOut={(e) => e.target.style.backgroundColor = 'transparent'}
      >
        立即预约体验
      </a>
    </main>
  )
}# 123wu