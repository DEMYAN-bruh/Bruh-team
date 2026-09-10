# Bruh-team
app de sport
:root {
  color: #edf2f7;
  background: #101827;
  font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

* { box-sizing: border-box; }

body { margin: 0; min-width: 320px; }

.page { width: min(100% - 32px, 720px); margin: 0 auto; padding: 64px 0; }

.hero { margin-bottom: 28px; }
.eyebrow { color: #61e2a7; font-size: .78rem; font-weight: 800; letter-spacing: .14em; margin: 0 0 8px; }
h1 { font-size: clamp(2rem, 7vw, 3.2rem); letter-spacing: -.04em; margin: 0; }
.hero > p:last-child { color: #aeb9c9; margin: 10px 0 0; }

.card, .confirmation { background: #192336; border: 1px solid #2c3a52; border-radius: 18px; padding: 28px; }
.card + .card, .confirmation + .card { margin-top: 20px; }
h2 { font-size: 1.2rem; margin: 0 0 20px; }

.field { border: 0; margin: 0 0 22px; padding: 0; }
label, legend { display: block; font-weight: 650; margin-bottom: 9px; }
input[type="text"] { background: #0f1725; border: 1px solid #52627d; border-radius: 10px; color: inherit; font: inherit; padding: 13px; width: 100%; }
input[type="text"]:focus { border-color: #61e2a7; box-shadow: 0 0 0 3px #61e2a733; outline: none; }

.session-options { display: grid; gap: 8px; grid-template-columns: repeat(auto-fit, minmax(130px, 1fr)); }
.session-options label { background: #0f1725; border: 1px solid #3c4b65; border-radius: 10px; cursor: pointer; font-weight: 500; margin: 0; padding: 11px; }
.session-options input { accent-color: #61e2a7; margin-right: 7px; }

button { background: #61e2a7; border: 0; border-radius: 10px; color: #092016; cursor: pointer; font: inherit; font-weight: 800; padding: 13px 18px; }
button:hover { background: #8bf0c0; }
.secondary-button { background: transparent; border: 1px solid #52627d; color: #d7deea; font-size: .88rem; padding: 8px 12px; }
.secondary-button:hover { background: #293751; }

.error { color: #ff9a9a; font-size: .9rem; min-height: 1.2em; margin: 6px 0 0; }
.confirmation { align-items: center; background: #123526; border-color: #2b8d60; display: flex; gap: 15px; margin-top: 20px; }
.confirmation span { align-items: center; background: #61e2a7; border-radius: 50%; color: #092016; display: flex; font-weight: 900; height: 32px; justify-content: center; width: 32px; }
.confirmation h2 { margin-bottom: 4px; }.confirmation p { color: #c3f7db; margin: 0; }
.section-heading { align-items: center; display: flex; justify-content: space-between; gap: 16px; }.section-heading h2 { margin: 0; }
#empty-state { color: #aeb9c9; margin: 20px 0 0; } #program-list { list-style: none; margin: 20px 0 0; padding: 0; }
#program-list li { align-items: center; background: #0f1725; border-radius: 10px; display: flex; justify-content: space-between; margin-top: 8px; padding: 13px; }
#program-list span { color: #aeb9c9; font-size: .9rem; }

@media (max-width: 480px) { .page { padding: 36px 0; }.card, .confirmation { padding: 20px; } }
