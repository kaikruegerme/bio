<style>
:root {
  --bg: #05060a;
  --card-bg: #0b0e16;
  --accent: #4f8cff;
  --accent-soft: rgba(79,140,255,0.12);
  --text-main: #f5f7ff;
  --text-muted: #9aa0b8;
  --border-subtle: #1a1f2e;
  --radius-lg: 18px;
  --radius-md: 10px;
  --shadow-soft: 0 18px 45px rgba(0,0,0,0.55);
  --font-main: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

body {
  background: radial-gradient(circle at top, #101426 0, #05060a 55%, #020308 100%);
  color: var(--text-main);
  font-family: var(--font-main);
}

.main-wrap {
  max-width: 880px;
  margin: 40px auto 80px;
  padding: 0 18px 40px;
}

.hero-card {
  background: radial-gradient(circle at top left, #18213a 0, #0b0e16 55%, #05060a 100%);
  border-radius: 26px;
  padding: 26px 26px 22px;
  box-shadow: var(--shadow-soft);
  border: 1px solid rgba(255,255,255,0.04);
  position: relative;
  overflow: hidden;
}

.hero-pill {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 4px 11px;
  border-radius: 999px;
  background: rgba(10, 190, 255, 0.08);
  border: 1px solid rgba(10, 190, 255, 0.35);
  font-size: 11px;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #b7e7ff;
}

.hero-title {
  margin-top: 14px;
  font-size: 32px;
  letter-spacing: 0.02em;
}

.hero-sub {
  margin-top: 6px;
  font-size: 15px;
  color: var(--text-muted);
  max-width: 520px;
}

.hero-meta {
  margin-top: 18px;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  font-size: 12px;
  color: var(--text-muted);
}

.hero-meta span {
  padding: 4px 9px;
  border-radius: 999px;
  border: 1px solid var(--border-subtle);
  background: rgba(5,6,12,0.7);
}

.hero-actions {
  margin-top: 20px;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.btn-primary, .btn-ghost {
  font-size: 13px;
  padding: 7px 14px;
  border-radius: 999px;
  border: 1px solid transparent;
  cursor: default;
}

.btn-primary {
  background: linear-gradient(135deg, #4f8cff, #7a5cff);
  color: white;
  box-shadow: 0 10px 30px rgba(79,140,255,0.45);
}

.btn-ghost {
  background: rgba(5,6,12,0.7);
  border-color: var(--border-subtle);
  color: var(--text-muted);
}

.section {
  margin-top: 26px;
  padding: 18px 18px 16px;
  border-radius: var(--radius-lg);
  background: linear-gradient(145deg, rgba(15,18,30,0.96), rgba(6,8,16,0.98));
  border: 1px solid rgba(255,255,255,0.03);
}

.section h2 {
  margin-top: 0;
  font-size: 17px;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #c5c9ff;
}

.section p {
  margin-top: 6px;
  font-size: 14px;
  color: var(--text-muted);
}

.chip-row {
  margin-top: 10px;
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.chip {
  font-size: 12px;
  padding: 4px 9px;
  border-radius: 999px;
  background: var(--accent-soft);
  border: 1px solid rgba(79,140,255,0.4);
  color: #d5e1ff;
}

.list-clean {
  margin: 10px 0 4px;
  padding-left: 16px;
  font-size: 14px;
  color: var(--text-muted);
}

.list-clean li + li {
  margin-top: 4px;
}

.contact-grid {
  margin-top: 10px;
  display: grid;
  grid-template-columns: minmax(0,1fr);
  gap: 6px;
  font-size: 14px;
}

.contact-label {
  color: var(--text-muted);
}

.contact-value {
  color: var(--text-main);
}
</style>

<div class="main-wrap">

<div class="hero-card">
  <div class="hero-pill">
    <span>AI · Engineering · Strategy</span>
  </div>
  <div class="hero-title">Kai Krüger</div>
  <div class="hero-sub">
    Ich verbinde KI, Produktdenken und pragmatische Umsetzung – mit Fokus auf klare Ergebnisse statt Buzzwords.
  </div>
  <div class="hero-meta">
    <span>Standort: Henstedt-Ulzburg · DE</span>
    <span>Fokus: AI‑gestützte Workflows & Tools</span>
  </div>
  <div class="hero-actions">
    <span class="btn-primary">Kontakt aufnehmen</span>
    <span class="btn-ghost">Profil & Hintergrund</span>
  </div>
</div>

<div class="section">
  <h2>Profil</h2>
  <p>
    Kurzbeschreibung von dir – 2–3 Sätze, wer du bist, wie du arbeitest und was dir wichtig ist.
    Zum Beispiel: Klarheit, Verantwortung, saubere Systeme statt Chaos.
  </p>
</div>

<div class="section">
  <h2>Schwerpunkte</h2>
  <ul class="list-clean">
    <li>AI‑gestützte Wissensarbeit (Obsidian, Automatisierung, strukturierte Notizen)</li>
    <li>Produktives Arbeiten mit GitHub, Markdown und klaren Workflows</li>
    <li>Übersetzen von komplexer Technik in verständliche Entscheidungen</li>
  </ul>
  <div class="chip-row">
    <span class="chip">Obsidian</span>
    <span class="chip">GitHub Pages</span>
    <span class="chip">Markdown</span>
    <span class="chip">Automatisierung</span>
  </div>
</div>

<div class="section">
  <h2>Aktuelle Projekte</h2>
  <ul class="list-clean">
    <li><strong>Persönliche Bio‑Site:</strong> Zentrale, versionierte Anlaufstelle für Profil, Projekte und Experimente.</li>
    <li><strong>KI‑gestützte Workflows:</strong> Aufbau von Strukturen, die Denken, Schreiben und Entscheiden beschleunigen.</li>
  </ul>
</div>

<div class="section">
  <h2>Kontakt</h2>
  <div class="contact-grid">
    <div>
      <div class="contact-label">E‑Mail</div>
      <div class="contact-value">[deine Mailadresse hier]</div>
    </div>
    <div>
      <div class="contact-label">GitHub</div>
      <div class="contact-value">github.com/kaikruegerme</div>
    </div>
    <!-- Optional: LinkedIn, Website, etc. -->
  </div>
</div>

</div>

