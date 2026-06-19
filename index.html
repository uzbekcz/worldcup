import { useState } from "react";

const flagEmoji = {
  ARG: "🇦🇷", DZA: "🇩🇿", AUT: "🇦🇹", JOR: "🇯🇴", POR: "🇵🇹", COD: "🇨🇩",
  ENG: "🏴󠁧󠁢󠁥󠁮󠁧󠁿", CRO: "🇭🇷", GHA: "🇬🇭", PAN: "🇵🇦", UZB: "🇺🇿", COL: "🇨🇴",
  CZE: "🇨🇿", RSA: "🇿🇦", SUI: "🇨🇭", BIH: "🇧🇦", CAN: "🇨🇦", QAT: "🇶🇦",
  MEX: "🇲🇽", KOR: "🇰🇷", USA: "🇺🇸", AUS: "🇦🇺", SCO: "🏴󠁧󠁢󠁳󠁣󠁴󠁿", MAR: "🇲🇦",
  BRA: "🇧🇷", HTI: "🇭🇹", TUR: "🇹🇷", PAR: "🇵🇾", NED: "🇳🇱", SWE: "🇸🇪",
  GER: "🇩🇪", CIV: "🇨🇮", ECU: "🇪🇨", CUW: "🇨🇼", TUN: "🇹🇳", JPN: "🇯🇵",
  ESP: "🇪🇸", KSA: "🇸🇦", BEL: "🇧🇪", IRN: "🇮🇷", NOR: "🇳🇴", FRA: "🇫🇷",
  SEN: "🇸🇳", IRQ: "🇮🇶", URU: "🇺🇾", CPV: "🇨🇻", NZL: "🇳🇿", EGY: "🇪🇬",
};

const SCORES = [
  { home: "ARG", away: "DZA", hs: 3, as: 0, status: "final", time: "Jun 17" },
  { home: "AUT", away: "JOR", hs: 3, as: 1, status: "final", time: "Jun 17" },
  { home: "POR", away: "COD", hs: 1, as: 1, status: "final", time: "Jun 17" },
  { home: "ENG", away: "CRO", hs: 4, as: 2, status: "final", time: "Jun 17" },
  { home: "GHA", away: "PAN", hs: 1, as: 0, status: "final", time: "Jun 18" },
  { home: "COL", away: "UZB", hs: 3, as: 1, status: "final", time: "Jun 18" },
  { home: "CZE", away: "RSA", hs: 1, as: 1, status: "final", time: "Jun 18" },
  { home: "SUI", away: "BIH", hs: 4, as: 1, status: "final", time: "Jun 18" },
  { home: "CAN", away: "QAT", hs: 6, as: 0, status: "final", time: "Jun 18" },
  { home: "MEX", away: "KOR", hs: 1, as: 0, status: "final", time: "Jun 19" },
  { home: "USA", away: "AUS", hs: null, as: null, status: "upcoming", time: "Jun 19 21:00" },
  { home: "SCO", away: "MAR", hs: null, as: null, status: "upcoming", time: "Jun 20 00:00" },
  { home: "BRA", away: "HTI", hs: null, as: null, status: "upcoming", time: "Jun 20 02:30" },
  { home: "GER", away: "CIV", hs: null, as: null, status: "upcoming", time: "Jun 20 22:00" },
];

const STANDINGS = {
  A: [
    { team: "MEX", w: 2, d: 0, l: 0, pts: 6 },
    { team: "KOR", w: 1, d: 0, l: 1, pts: 3 },
    { team: "CZE", w: 0, d: 1, l: 1, pts: 1 },
    { team: "RSA", w: 0, d: 1, l: 1, pts: 1 },
  ],
  B: [
    { team: "CAN", w: 1, d: 1, l: 0, pts: 4 },
    { team: "SUI", w: 1, d: 1, l: 0, pts: 4 },
    { team: "BIH", w: 0, d: 1, l: 1, pts: 1 },
    { team: "QAT", w: 0, d: 1, l: 1, pts: 1 },
  ],
  J: [
    { team: "ARG", w: 1, d: 0, l: 0, pts: 3 },
    { team: "AUT", w: 1, d: 0, l: 0, pts: 3 },
    { team: "JOR", w: 0, d: 0, l: 1, pts: 0 },
    { team: "DZA", w: 0, d: 0, l: 1, pts: 0 },
  ],
  L: [
    { team: "ENG", w: 1, d: 0, l: 0, pts: 3 },
    { team: "GHA", w: 1, d: 0, l: 0, pts: 3 },
    { team: "CRO", w: 0, d: 0, l: 1, pts: 0 },
    { team: "PAN", w: 0, d: 0, l: 1, pts: 0 },
  ],
};

export default function WorldCupWidget() {
  const [tab, setTab] = useState("scores");
  const [selectedGroup, setSelectedGroup] = useState("A");

  const recentScores = SCORES.filter(g => g.status === "final").slice(-5).reverse();
  const upcoming = SCORES.filter(g => g.status === "upcoming");

  return (
    <div style={{
      fontFamily: "'SF Pro Display', -apple-system, BlinkMacSystemFont, sans-serif",
      background: "linear-gradient(145deg, #0a0e1a 0%, #0d1f3c 50%, #0a1628 100%)",
      minHeight: "100vh",
      color: "#fff",
      maxWidth: 420,
      margin: "0 auto",
      padding: "0 0 32px",
    }}>
      {/* Header */}
      <div style={{
        background: "linear-gradient(135deg, #1a3a6e 0%, #0d2244 100%)",
        padding: "20px 20px 16px",
        borderBottom: "1px solid rgba(255,255,255,0.08)",
      }}>
        <div style={{ display: "flex", alignItems: "center", gap: 10, marginBottom: 4 }}>
          <span style={{ fontSize: 28 }}>🏆</span>
          <div>
            <div style={{ fontSize: 11, color: "#7ba7d4", fontWeight: 600, letterSpacing: 2, textTransform: "uppercase" }}>FIFA</div>
            <div style={{ fontSize: 20, fontWeight: 800, lineHeight: 1.1 }}>World Cup 2026</div>
          </div>
          <div style={{
            marginLeft: "auto",
            background: "#e8f437",
            color: "#000",
            fontSize: 10,
            fontWeight: 800,
            padding: "3px 8px",
            borderRadius: 20,
            letterSpacing: 1,
          }}>LIVE</div>
        </div>
        <div style={{ fontSize: 12, color: "#7ba7d4" }}>🇺🇸 USA • 🇨🇦 Canada • 🇲🇽 Mexico</div>
      </div>

      {/* Tabs */}
      <div style={{
        display: "flex",
        background: "rgba(255,255,255,0.04)",
        margin: "16px 16px 0",
        borderRadius: 12,
        padding: 4,
        gap: 4,
      }}>
        {[
          { key: "scores", label: "⚽ Natijalar" },
          { key: "upcoming", label: "📅 Keyingi" },
          { key: "standings", label: "📊 Guruhlar" },
        ].map(t => (
          <button key={t.key} onClick={() => setTab(t.key)} style={{
            flex: 1,
            padding: "8px 4px",
            border: "none",
            borderRadius: 9,
            cursor: "pointer",
            fontSize: 12,
            fontWeight: 700,
            transition: "all 0.2s",
            background: tab === t.key ? "#1a5fcb" : "transparent",
            color: tab === t.key ? "#fff" : "#7ba7d4",
          }}>{t.label}</button>
        ))}
      </div>

      <div style={{ padding: "16px" }}>
        {/* SCORES TAB */}
        {tab === "scores" && (
          <div>
            <div style={{ fontSize: 11, color: "#7ba7d4", fontWeight: 700, letterSpacing: 1.5, marginBottom: 10, textTransform: "uppercase" }}>So'nggi natijalar</div>
            {recentScores.map((g, i) => (
              <div key={i} style={{
                background: "rgba(255,255,255,0.05)",
                borderRadius: 14,
                padding: "14px 16px",
                marginBottom: 10,
                border: "1px solid rgba(255,255,255,0.06)",
              }}>
                <div style={{ display: "flex", alignItems: "center", justifyContent: "space-between" }}>
                  <div style={{ display: "flex", alignItems: "center", gap: 8, flex: 1 }}>
                    <span style={{ fontSize: 22 }}>{flagEmoji[g.home] || "🏳️"}</span>
                    <span style={{ fontWeight: 700, fontSize: 14 }}>{g.home}</span>
                  </div>
                  <div style={{
                    background: "rgba(255,255,255,0.1)",
                    borderRadius: 10,
                    padding: "8px 16px",
                    textAlign: "center",
                    minWidth: 80,
                  }}>
                    <div style={{ fontSize: 22, fontWeight: 900, letterSpacing: 2 }}>
                      {g.hs} – {g.as}
                    </div>
                    <div style={{ fontSize: 10, color: "#4caf50", fontWeight: 700, marginTop: 2 }}>YAKUNLANDI</div>
                  </div>
                  <div style={{ display: "flex", alignItems: "center", gap: 8, flex: 1, justifyContent: "flex-end" }}>
                    <span style={{ fontWeight: 700, fontSize: 14 }}>{g.away}</span>
                    <span style={{ fontSize: 22 }}>{flagEmoji[g.away] || "🏳️"}</span>
                  </div>
                </div>
                <div style={{ textAlign: "center", marginTop: 6, fontSize: 11, color: "#5a7fa8" }}>{g.time}</div>
              </div>
            ))}
          </div>
        )}

        {/* UPCOMING TAB */}
        {tab === "upcoming" && (
          <div>
            <div style={{ fontSize: 11, color: "#7ba7d4", fontWeight: 700, letterSpacing: 1.5, marginBottom: 10, textTransform: "uppercase" }}>Kutilayotgan o'yinlar</div>
            {upcoming.map((g, i) => (
              <div key={i} style={{
                background: "rgba(26, 95, 203, 0.15)",
                borderRadius: 14,
                padding: "14px 16px",
                marginBottom: 10,
                border: "1px solid rgba(26, 95, 203, 0.3)",
              }}>
                <div style={{ display: "flex", alignItems: "center", justifyContent: "space-between" }}>
                  <div style={{ display: "flex", alignItems: "center", gap: 8, flex: 1 }}>
                    <span style={{ fontSize: 22 }}>{flagEmoji[g.home] || "🏳️"}</span>
                    <span style={{ fontWeight: 700, fontSize: 14 }}>{g.home}</span>
                  </div>
                  <div style={{
                    background: "rgba(26, 95, 203, 0.3)",
                    borderRadius: 10,
                    padding: "8px 12px",
                    textAlign: "center",
                    minWidth: 80,
                  }}>
                    <div style={{ fontSize: 13, fontWeight: 800, color: "#e8f437" }}>VS</div>
                    <div style={{ fontSize: 10, color: "#7ba7d4", marginTop: 2 }}>{g.time}</div>
                  </div>
                  <div style={{ display: "flex", alignItems: "center", gap: 8, flex: 1, justifyContent: "flex-end" }}>
                    <span style={{ fontWeight: 700, fontSize: 14 }}>{g.away}</span>
                    <span style={{ fontSize: 22 }}>{flagEmoji[g.away] || "🏳️"}</span>
                  </div>
                </div>
              </div>
            ))}
          </div>
        )}

        {/* STANDINGS TAB */}
        {tab === "standings" && (
          <div>
            <div style={{ display: "flex", gap: 6, marginBottom: 14, flexWrap: "wrap" }}>
              {Object.keys(STANDINGS).map(g => (
                <button key={g} onClick={() => setSelectedGroup(g)} style={{
                  padding: "6px 14px",
                  borderRadius: 20,
                  border: "none",
                  cursor: "pointer",
                  fontSize: 12,
                  fontWeight: 700,
                  background: selectedGroup === g ? "#e8f437" : "rgba(255,255,255,0.08)",
                  color: selectedGroup === g ? "#000" : "#aaa",
                }}>Guruh {g}</button>
              ))}
            </div>
            <div style={{
              background: "rgba(255,255,255,0.04)",
              borderRadius: 14,
              overflow: "hidden",
              border: "1px solid rgba(255,255,255,0.07)",
            }}>
              <div style={{
                display: "grid",
                gridTemplateColumns: "32px 1fr 36px 36px 36px 36px",
                padding: "8px 14px",
                background: "rgba(255,255,255,0.06)",
                fontSize: 11,
                color: "#5a7fa8",
                fontWeight: 700,
                gap: 4,
              }}>
                <span>#</span><span>Jamoa</span><span style={{textAlign:"center"}}>G</span><span style={{textAlign:"center"}}>D</span><span style={{textAlign:"center"}}>Y</span><span style={{textAlign:"center"}}>Bal</span>
              </div>
              {(STANDINGS[selectedGroup] || []).map((t, i) => (
                <div key={i} style={{
                  display: "grid",
                  gridTemplateColumns: "32px 1fr 36px 36px 36px 36px",
                  padding: "12px 14px",
                  borderTop: "1px solid rgba(255,255,255,0.05)",
                  alignItems: "center",
                  gap: 4,
                  background: i < 2 ? "rgba(26, 95, 203, 0.08)" : "transparent",
                }}>
                  <span style={{
                    fontSize: 12,
                    fontWeight: 800,
                    color: i < 2 ? "#e8f437" : "#5a7fa8",
                  }}>{i + 1}</span>
                  <div style={{ display: "flex", alignItems: "center", gap: 8 }}>
                    <span style={{ fontSize: 18 }}>{flagEmoji[t.team] || "🏳️"}</span>
                    <span style={{ fontSize: 14, fontWeight: 700 }}>{t.team}</span>
                    {i < 2 && <span style={{ fontSize: 9, background: "#1a5fcb", borderRadius: 4, padding: "1px 5px", color: "#a8c8ff" }}>OLDIN</span>}
                  </div>
                  <span style={{ textAlign: "center", fontSize: 13, color: "#4caf50", fontWeight: 700 }}>{t.w}</span>
                  <span style={{ textAlign: "center", fontSize: 13, color: "#ffa726", fontWeight: 700 }}>{t.d}</span>
                  <span style={{ textAlign: "center", fontSize: 13, color: "#ef5350", fontWeight: 700 }}>{t.l}</span>
                  <span style={{ textAlign: "center", fontSize: 16, fontWeight: 900, color: "#e8f437" }}>{t.pts}</span>
                </div>
              ))}
            </div>
            <div style={{ display: "flex", gap: 16, marginTop: 12, fontSize: 11, color: "#5a7fa8" }}>
              <span>G = Galaba</span><span>D = Durang</span><span>Y = Yutqaziq</span>
            </div>
          </div>
        )}
      </div>

      <div style={{ textAlign: "center", fontSize: 11, color: "#2a4a6a", marginTop: 8 }}>
        FIFA World Cup 2026 • Jonli ma'lumotlar
      </div>
    </div>
  );
}
