<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>PCIe Gen5 NVMe SSD Comparison — 2026</title>
<style>
  :root {
    --bg: #0b0e14;
    --panel: #11151d;
    --line: #232a36;
    --line-soft: #1a2029;
    --text: #d7dce3;
    --text-dim: #838d9c;
    --text-faint: #5c6675;
    --mono: ui-monospace, "SF Mono", Menlo, Consolas, monospace;
    --sans: -apple-system, "Segoe UI", Inter, Helvetica, Arial, sans-serif;

    /* controller family accents */
    --sm2508: #4fc3d9;
    --sm2508-bg: rgba(79,195,217,0.10);
    --e26: #e0a458;
    --e26-bg: rgba(224,164,88,0.10);
    --e28: #6fd68a;
    --e28-bg: rgba(111,214,138,0.10);
    --presto: #b083f0;
    --presto-bg: rgba(176,131,240,0.10);
    --aries: #ec7fb0;
    --aries-bg: rgba(236,127,176,0.10);
    --budget: #8a93a3;
    --budget-bg: rgba(138,147,163,0.10);
  }

  * { box-sizing: border-box; }

  body {
    margin: 0;
    background: var(--bg);
    color: var(--text);
    font-family: var(--sans);
    padding: 40px 32px 80px;
  }

  .wrap { max-width: 1400px; margin: 0 auto; }

  header {
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 12px;
    margin-bottom: 6px;
  }

  h1 {
    font-size: 20px;
    font-weight: 650;
    letter-spacing: -0.01em;
    margin: 0;
    color: #f0f2f5;
  }

  .subtitle {
    color: var(--text-dim);
    font-size: 13px;
    margin: 4px 0 24px;
    max-width: 760px;
    line-height: 1.5;
  }

  .legend {
    display: flex;
    flex-wrap: wrap;
    gap: 8px 16px;
    margin-bottom: 22px;
    padding: 12px 16px;
    background: var(--panel);
    border: 1px solid var(--line);
    border-radius: 8px;
  }

  .legend-item {
    display: flex;
    align-items: center;
    gap: 7px;
    font-size: 11.5px;
    color: var(--text-dim);
    font-family: var(--mono);
  }

  .dot {
    width: 9px;
    height: 9px;
    border-radius: 2px;
    flex-shrink: 0;
  }

  .table-scroll {
    overflow-x: auto;
    border: 1px solid var(--line);
    border-radius: 8px;
    background: var(--panel);
  }

  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 12.5px;
    min-width: 1180px;
  }

  thead th {
    position: sticky;
    top: 0;
    background: #161b25;
    color: var(--text-faint);
    text-align: left;
    font-weight: 600;
    font-size: 10.5px;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    padding: 12px 14px;
    border-bottom: 1px solid var(--line);
    white-space: nowrap;
  }

  tbody td {
    padding: 10px 14px;
    border-bottom: 1px solid var(--line-soft);
    vertical-align: top;
    color: var(--text);
  }

  tbody tr:hover td { background: #151b25; }

  /* group model rows visually */
  tr.group-start td { border-top: 1px solid var(--line); }

  td.model {
    font-weight: 600;
    color: #eef1f5;
    white-space: nowrap;
  }

  td.model .brand {
    display: block;
    font-weight: 400;
    color: var(--text-faint);
    font-size: 10.5px;
    text-transform: uppercase;
    letter-spacing: 0.04em;
    margin-bottom: 1px;
  }

  td.date {
    font-family: var(--mono);
    font-size: 11.5px;
    color: var(--text-faint);
    white-space: nowrap;
  }

  td.cap {
    font-family: var(--mono);
    font-weight: 600;
    color: var(--text);
    white-space: nowrap;
  }

  td.part {
    font-family: var(--mono);
    font-size: 11.5px;
    color: var(--text-dim);
    white-space: nowrap;
  }

  .badge {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    padding: 3px 8px;
    border-radius: 5px;
    font-family: var(--mono);
    font-size: 11px;
    font-weight: 600;
    white-space: nowrap;
  }
  .badge .dot { width: 6px; height: 6px; border-radius: 50%; }

  .badge.sm2508 { color: var(--sm2508); background: var(--sm2508-bg); }
  .badge.sm2508 .dot { background: var(--sm2508); }
  .badge.e26 { color: var(--e26); background: var(--e26-bg); }
  .badge.e26 .dot { background: var(--e26); }
  .badge.e28 { color: var(--e28); background: var(--e28-bg); }
  .badge.e28 .dot { background: var(--e28); }
  .badge.presto { color: var(--presto); background: var(--presto-bg); }
  .badge.presto .dot { background: var(--presto); }
  .badge.aries { color: var(--aries); background: var(--aries-bg); }
  .badge.aries .dot { background: var(--aries); }
  .badge.budget { color: var(--budget); background: var(--budget-bg); }
  .badge.budget .dot { background: var(--budget); }

  td.nand {
    color: var(--text-dim);
    font-size: 12px;
    max-width: 190px;
  }

  td.speed {
    font-family: var(--mono);
    white-space: nowrap;
  }
  td.speed .r { color: #8fd6ea; }
  td.speed .w { color: #e8b976; }
  td.speed .sep { color: var(--text-faint); }

  td.tbw {
    font-family: var(--mono);
    color: var(--text-dim);
    white-space: nowrap;
  }

  td.notes {
    color: var(--text-dim);
    font-size: 12px;
    max-width: 260px;
    line-height: 1.45;
  }

  
  footer {
    margin-top: 22px;
    font-size: 12px;
    color: var(--text-faint);
    line-height: 1.6;
    max-width: 900px;
  }
  footer strong { color: var(--text-dim); }
</style>
</head>
<body>
<div class="wrap">

  <header>
    <h1>PCIe Gen5 NVMe SSD Comparison</h1>
  </header>
  <p class="subtitle">
    All drives: PCIe 5.0 x4, M.2 2280, NVMe 2.0. One row per capacity. Colors mark the controller family — same color, same underlying silicon platform. Figures are manufacturer-rated; treat as a snapshot, 2026.
  </p>

  <div class="legend">
    <div class="legend-item"><span class="dot" style="background:#4fc3d9"></span>Silicon Motion SM2508</div>
    <div class="legend-item"><span class="dot" style="background:#e0a458"></span>Phison E26</div>
    <div class="legend-item"><span class="dot" style="background:#6fd68a"></span>Phison E28</div>
    <div class="legend-item"><span class="dot" style="background:#b083f0"></span>Samsung Presto (in-house)</div>
    <div class="legend-item"><span class="dot" style="background:#ec7fb0"></span>SK hynix Aries (in-house)</div>
    <div class="legend-item"><span class="dot" style="background:#8a93a3"></span>Budget / other controller</div>
  </div>

  <div class="table-scroll">
  <table>
    <thead>
      <tr>
        <th>Model</th>
        <th>Released</th>
        <th>Capacity</th>
        <th>Part Number</th>
        <th>Controller</th>
        <th>NAND</th>
        <th>DRAM</th>
        <th>Seq Read / Write</th>
        <th>Endurance (TBW)</th>
        <th>Notes</th>
      </tr>
    </thead>
    <tbody>

      <!-- WD_Black SN8100 -->
      <tr class="group-start">
        <td class="model"><span class="brand">Western Digital</span>SN8100</td>
        <td class="date">May 2025</td>
        <td class="cap">1TB</td>
        <td class="part">WDS100T1XHE</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Kioxia/SanDisk BiCS8 218L TLC</td>
        <td>LPDDR4</td>
        <td class="speed"><span class="r">~14,900R</span> <span class="sep">/</span> <span class="w">~7,500W</span></td>
        <td class="tbw">~600 TBW</td>
        <td class="notes">Lower write speed at 1TB — fewer dies in parallel</td>
      </tr>
      <tr >
        <td class="model"><span class="brand">Western Digital</span>SN8100</td>
        <td class="date">May 2025</td>
        <td class="cap">2TB</td>
        <td class="part">WDS200T1XHE</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Kioxia/SanDisk BiCS8 218L TLC</td>
        <td>LPDDR4</td>
        <td class="speed"><span class="r">14,900R</span> <span class="sep">/</span> <span class="w">11,000W</span></td>
        <td class="tbw">~1,200 TBW</td>
        <td class="notes">Best 4K random performance in class</td>
      </tr>
      <tr >
        <td class="model"><span class="brand">Western Digital</span>SN8100</td>
        <td class="date">May 2025</td>
        <td class="cap">4TB</td>
        <td class="part">WDS400T1XHE</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Kioxia/SanDisk BiCS8 218L TLC</td>
        <td>LPDDR4</td>
        <td class="speed"><span class="r">14,900R</span> <span class="sep">/</span> <span class="w">11,000W</span></td>
        <td class="tbw">~2,400 TBW</td>
        <td class="notes">Best thermals among top-tier Gen5 drives</td>
      </tr>

      <!-- Kingston FURY Renegade G5 -->
      <tr class="group-start">
        <td class="model"><span class="brand">Kingston</span>FURY Renegade G5</td>
        <td class="date">May 2025</td>
        <td class="cap">1TB</td>
        <td class="part">SFYRD1000G</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Kioxia BiCS8 218L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~14,800R</span> <span class="sep">/</span> <span class="w">~10,000W</span></td>
        <td class="tbw">1,000 TBW</td>
        <td class="notes">Rated 1,000 TBW/TB — notably higher endurance than most Gen5 rivals</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Kingston</span>FURY Renegade G5</td>
        <td class="date">May 2025</td>
        <td class="cap">2TB</td>
        <td class="part">SFYRD2000G</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Kioxia BiCS8 218L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">14,800R</span> <span class="sep">/</span> <span class="w">14,000W</span></td>
        <td class="tbw">2,000 TBW</td>
        <td class="notes">Trails SN8100 slightly in speed, but leads it in endurance</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Kingston</span>FURY Renegade G5</td>
        <td class="date">May 2025</td>
        <td class="cap">4TB</td>
        <td class="part">SFYRD4000G</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Kioxia BiCS8 218L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">14,800R</span> <span class="sep">/</span> <span class="w">14,000W</span></td>
        <td class="tbw">4,000 TBW</td>
        <td class="notes">No 8TB model yet; nearly double SN8100's 2,400 TBW at 4TB</td>
      </tr>

      <!-- Crucial T710 -->
      <tr class="group-start">
        <td class="model"><span class="brand">Crucial</span>T710</td>
        <td class="date">Aug 2025</td>
        <td class="cap">1TB</td>
        <td class="part">CT1000T710SSD5</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Micron (own fab) 276L G9 TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~13,000R</span> <span class="sep">/</span> <span class="w">~10,000W</span></td>
        <td class="tbw">~600 TBW</td>
        <td class="notes"></td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Crucial</span>T710</td>
        <td class="date">Aug 2025</td>
        <td class="cap">2TB</td>
        <td class="part">CT2000T710SSD5</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Micron (own fab) 276L G9 TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~14,000R</span> <span class="sep">/</span> <span class="w">~12,000W</span></td>
        <td class="tbw">~1,200 TBW</td>
        <td class="notes">Underperforms SN8100/Renegade despite same controller</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Crucial</span>T710</td>
        <td class="date">Aug 2025</td>
        <td class="cap">4TB</td>
        <td class="part">CT4000T710SSD5</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Micron (own fab) 276L G9 TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~14,000R</span> <span class="sep">/</span> <span class="w">~12,000W</span></td>
        <td class="tbw">~2,400 TBW</td>
        <td class="notes"></td>
      </tr>

      <!-- Crucial T705 -->
      <tr class="group-start">
        <td class="model"><span class="brand">Crucial</span>T705</td>
        <td class="date">Mar 2024</td>
        <td class="cap">1TB</td>
        <td class="part">CT1000T705SSD3</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron 232L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~13,500R</span> <span class="sep">/</span> <span class="w">~10,000W</span></td>
        <td class="tbw">~600 TBW</td>
        <td class="notes">Discontinued — Micron exited consumer market Feb 2026</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Crucial</span>T705</td>
        <td class="date">Mar 2024</td>
        <td class="cap">2TB</td>
        <td class="part">CT2000T705SSD3</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron 232L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">14,500R</span> <span class="sep">/</span> <span class="w">12,700W</span></td>
        <td class="tbw">~1,200 TBW</td>
        <td class="notes">Discontinued — Micron exited consumer market Feb 2026</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Crucial</span>T705</td>
        <td class="date">Mar 2024</td>
        <td class="cap">4TB</td>
        <td class="part">CT4000T705SSD3</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron 232L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">14,500R</span> <span class="sep">/</span> <span class="w">12,700W</span></td>
        <td class="tbw">~2,400 TBW</td>
        <td class="notes">Discontinued — Micron exited consumer market Feb 2026</td>
      </tr>

      <!-- Samsung 9100 Pro -->
      <tr class="group-start">
        <td class="model"><span class="brand">Samsung</span>9100 Pro</td>
        <td class="date">Mar 2025</td>
        <td class="cap">1TB</td>
        <td class="part">MZ-V9P1T0BW</td>
        <td><span class="badge presto"><span class="dot"></span>Presto</span></td>
        <td class="nand">Samsung 236L V8 TLC V-NAND</td>
        <td>LPDDR4X</td>
        <td class="speed"><span class="r">~14,700R</span> <span class="sep">/</span> <span class="w">~10,000W</span></td>
        <td class="tbw">600 TBW</td>
        <td class="notes"></td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Samsung</span>9100 Pro</td>
        <td class="date">Mar 2025</td>
        <td class="cap">2TB</td>
        <td class="part">MZ-V9P2T0BW</td>
        <td><span class="badge presto"><span class="dot"></span>Presto</span></td>
        <td class="nand">Samsung 236L V8 TLC V-NAND</td>
        <td>LPDDR4X</td>
        <td class="speed"><span class="r">14,800R</span> <span class="sep">/</span> <span class="w">13,400W</span></td>
        <td class="tbw">1,200 TBW</td>
        <td class="notes">Best sequential read numbers; runs cooler than most flagships</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Samsung</span>9100 Pro</td>
        <td class="date">Mar 2025</td>
        <td class="cap">4TB</td>
        <td class="part">MZ-V9P4T0BW</td>
        <td><span class="badge presto"><span class="dot"></span>Presto</span></td>
        <td class="nand">Samsung 236L V8 TLC V-NAND</td>
        <td>LPDDR4X</td>
        <td class="speed"><span class="r">14,700R</span> <span class="sep">/</span> <span class="w">13,300W</span></td>
        <td class="tbw">2,400 TBW</td>
        <td class="notes">Premium pricing (~$0.14/GB); dual-package design</td>
      </tr>

      <!-- SK hynix Platinum P51 -->
      <tr class="group-start">
        <td class="model"><span class="brand">SK hynix</span>Platinum P51</td>
        <td class="date">~Late 2025</td>
        <td class="cap">1TB</td>
        <td class="part">—</td>
        <td><span class="badge aries"><span class="dot"></span>Aries</span></td>
        <td class="nand">SK hynix 238L+ TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~13,500R</span></td>
        <td class="tbw">~600 TBW</td>
        <td class="notes"></td>
      </tr>
      <tr>
        <td class="model"><span class="brand">SK hynix</span>Platinum P51</td>
        <td class="date">~Late 2025</td>
        <td class="cap">2TB</td>
        <td class="part">—</td>
        <td><span class="badge aries"><span class="dot"></span>Aries</span></td>
        <td class="nand">SK hynix 238L+ TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~14,200R</span></td>
        <td class="tbw">~1,200 TBW</td>
        <td class="notes">Best sustained write performance in class</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">SK hynix</span>Platinum P51</td>
        <td class="date">~Late 2025</td>
        <td class="cap">4TB</td>
        <td class="part">—</td>
        <td><span class="badge aries"><span class="dot"></span>Aries</span></td>
        <td class="nand">SK hynix 238L+ TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~14,200R</span></td>
        <td class="tbw">~2,400 TBW</td>
        <td class="notes">Strong pick for video editing (ProRes RAW, multicam 8K)</td>
      </tr>

      <!-- Corsair MP700 Pro / Pro SE -->
      <tr class="group-start">
        <td class="model"><span class="brand">Corsair</span>MP700 Pro / Pro SE</td>
        <td class="date">Nov 2023</td>
        <td class="cap">1TB</td>
        <td class="part">CSSD-F1000GBMP700PRO</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron or Kioxia TLC (varies by batch)</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~12,000R</span> <span class="sep">/</span> <span class="w">~9,500W</span></td>
        <td class="tbw">~600 TBW</td>
        <td class="notes"></td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Corsair</span>MP700 Pro / Pro SE</td>
        <td class="date">Nov 2023</td>
        <td class="cap">2TB</td>
        <td class="part">CSSD-F2000GBMP700PRO</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron or Kioxia TLC (varies by batch)</td>
        <td>Yes</td>
        <td class="speed"><span class="r">12,400R</span> <span class="sep">/</span> <span class="w">11,800W</span></td>
        <td class="tbw">~1,200 TBW</td>
        <td class="notes">Pro SE adds active-fan cooling variant</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Corsair</span>MP700 Pro / Pro SE</td>
        <td class="date">Nov 2023</td>
        <td class="cap">4TB</td>
        <td class="part">CSSD-F4000GBMP700PRO</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron or Kioxia TLC (varies by batch)</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~12,400R</span> <span class="sep">/</span> <span class="w">~11,800W</span></td>
        <td class="tbw">~2,400 TBW</td>
        <td class="notes"></td>
      </tr>

      <!-- Corsair MP700 Pro XT -->
      <tr class="group-start">
        <td class="model"><span class="brand">Corsair</span>MP700 Pro XT</td>
        <td class="date">Oct 2025</td>
        <td class="cap">1TB</td>
        <td class="part">CSSD-F1000GBMP700PROXT</td>
        <td><span class="badge e28"><span class="dot"></span>E28</span></td>
        <td class="nand">Kioxia BiCS8 218L TLC</td>
        <td>SK hynix, 1GB/TB</td>
        <td class="speed"><span class="r">~14,900R</span> <span class="sep">/</span> <span class="w">~11,000W</span></td>
        <td class="tbw">700 TBW</td>
        <td class="notes">$159 MSRP</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Corsair</span>MP700 Pro XT</td>
        <td class="date">Oct 2025</td>
        <td class="cap">2TB</td>
        <td class="part">CSSD-F2000GBMP700PROXT</td>
        <td><span class="badge e28"><span class="dot"></span>E28</span></td>
        <td class="nand">Kioxia BiCS8 218L TLC</td>
        <td>SK hynix, 1GB/TB</td>
        <td class="speed"><span class="r">14,900R</span> <span class="sep">/</span> <span class="w">14,500W</span></td>
        <td class="tbw">1,400 TBW</td>
        <td class="notes">$249 MSRP; near-Gen4 power draw (~5.7–6.5W), no heatsink needed for most workloads</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Corsair</span>MP700 Pro XT</td>
        <td class="date">Oct 2025</td>
        <td class="cap">4TB</td>
        <td class="part">CSSD-F4000GBMP700PROXT</td>
        <td><span class="badge e28"><span class="dot"></span>E28</span></td>
        <td class="nand">Kioxia BiCS8 218L TLC</td>
        <td>SK hynix, 1GB/TB</td>
        <td class="speed"><span class="r">~14,900R</span> <span class="sep">/</span> <span class="w">~14,000W</span></td>
        <td class="tbw">2,800 TBW</td>
        <td class="notes">$459 MSRP; single-sided design even at 4TB</td>
      </tr>

      <!-- Corsair MP700 Elite -->
      <tr class="group-start">
        <td class="model"><span class="brand">Corsair</span>MP700 Elite</td>
        <td class="date">~2025</td>
        <td class="cap">1TB</td>
        <td class="part">CSSD-F1000GBMP700ELT</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Kioxia BiCS8 218L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~9,500R</span></td>
        <td class="tbw">~600 TBW</td>
        <td class="notes"></td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Corsair</span>MP700 Elite</td>
        <td class="date">~2025</td>
        <td class="cap">2TB</td>
        <td class="part">CSSD-F2000GBMP700ELT</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Kioxia BiCS8 218L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~10,000R</span></td>
        <td class="tbw">~1,200 TBW</td>
        <td class="notes">Entry-level Gen5; better power efficiency than Pro/Pro XT</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Corsair</span>MP700 Elite</td>
        <td class="date">~2025</td>
        <td class="cap">4TB</td>
        <td class="part">CSSD-F4000GBMP700ELT</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Kioxia BiCS8 218L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~10,000R</span></td>
        <td class="tbw">~2,400 TBW</td>
        <td class="notes"></td>
      </tr>

      <!-- Seagate FireCuda 540 -->
      <tr class="group-start">
        <td class="model"><span class="brand">Seagate</span>FireCuda 540</td>
        <td class="date">~Early 2024</td>
        <td class="cap">1TB</td>
        <td class="part">ZP1000GM3A013</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron 232L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~9,500R</span></td>
        <td class="tbw">High (TBW)</td>
        <td class="notes">Seagate rates endurance generously</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Seagate</span>FireCuda 540</td>
        <td class="date">~Early 2024</td>
        <td class="cap">2TB</td>
        <td class="part">ZP2000GM3A013</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron 232L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~10,000R</span></td>
        <td class="tbw">High (TBW)</td>
        <td class="notes">Runs hottest of the group under sustained load</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Seagate</span>FireCuda 540</td>
        <td class="date">~Early 2024</td>
        <td class="cap">4TB</td>
        <td class="part">ZP4000GM3A013</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron 232L TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~10,000R</span></td>
        <td class="tbw">High (TBW)</td>
        <td class="notes">Seagate rates endurance generously</td>
      </tr>

      <!-- Gigabyte Aorus Gen5 -->
      <tr class="group-start">
        <td class="model"><span class="brand">Gigabyte</span>Aorus Gen5 10000/14000</td>
        <td class="date">~2023</td>
        <td class="cap">1TB</td>
        <td class="part">AG510K1TB</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Varies (Kioxia/Micron by batch)</td>
        <td>DDR4</td>
        <td class="speed"><span class="r">10,000R</span> <span class="sep">/</span> <span class="w">~9,000W</span></td>
        <td class="tbw">~600 TBW</td>
        <td class="notes">"10000" model tier</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Gigabyte</span>Aorus Gen5 10000/14000</td>
        <td class="date">~2023</td>
        <td class="cap">2TB</td>
        <td class="part">AG514K2TB</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Varies (Kioxia/Micron by batch)</td>
        <td>DDR4</td>
        <td class="speed"><span class="r">12,400R</span> <span class="sep">/</span> <span class="w">11,800W</span></td>
        <td class="tbw">~1,200 TBW</td>
        <td class="notes">"14000" model tier; includes RGB heatsink</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Gigabyte</span>Aorus Gen5 10000/14000</td>
        <td class="date">~2023</td>
        <td class="cap">4TB</td>
        <td class="part">AG514K4TB</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Varies (Kioxia/Micron by batch)</td>
        <td>DDR4</td>
        <td class="speed"><span class="r">12,400R</span> <span class="sep">/</span> <span class="w">11,800W</span></td>
        <td class="tbw">~2,400 TBW</td>
        <td class="notes"></td>
      </tr>

      <!-- Sabrent Rocket 5 -->
      <tr class="group-start">
        <td class="model"><span class="brand">Sabrent</span>Rocket 5</td>
        <td class="date">Feb 2024</td>
        <td class="cap">1TB</td>
        <td class="part">SB-RKT5P-1TB</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron/Kioxia TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~13,500R</span> <span class="sep">/</span> <span class="w">~10,000W</span></td>
        <td class="tbw">~600 TBW</td>
        <td class="notes"></td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Sabrent</span>Rocket 5</td>
        <td class="date">Feb 2024</td>
        <td class="cap">2TB</td>
        <td class="part">SB-RKT5P-2TB</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron/Kioxia TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">14,000R</span> <span class="sep">/</span> <span class="w">12,000W</span></td>
        <td class="tbw">~1,200 TBW</td>
        <td class="notes">Comparable to Crucial T705 in real-world numbers</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Sabrent</span>Rocket 5</td>
        <td class="date">Feb 2024</td>
        <td class="cap">4TB</td>
        <td class="part">SB-RKT5P-4TB</td>
        <td><span class="badge e26"><span class="dot"></span>E26</span></td>
        <td class="nand">Micron/Kioxia TLC</td>
        <td>Yes</td>
        <td class="speed"><span class="r">14,000R</span> <span class="sep">/</span> <span class="w">12,000W</span></td>
        <td class="tbw">~2,400 TBW</td>
        <td class="notes"></td>
      </tr>

      <!-- Lexar NM1090 Pro -->
      <tr class="group-start">
        <td class="model"><span class="brand">Lexar</span>NM1090 Pro</td>
        <td class="date">Jun 2025</td>
        <td class="cap">1TB</td>
        <td class="part">LNM1090P001T-RNNNG</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Micron 232L G8 TLC (Longsys-rebranded)</td>
        <td>Foresee LPDDR4X</td>
        <td class="speed"><span class="r">14,000R</span> <span class="sep">/</span> <span class="w">10,000W</span></td>
        <td class="tbw">700 TBW</td>
        <td class="notes">Same SM2508 platform as SN8100/Renegade G5/T710, but older Micron G8 NAND — a half-generation behind on flash</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Lexar</span>NM1090 Pro</td>
        <td class="date">Jun 2025</td>
        <td class="cap">2TB</td>
        <td class="part">LNM1090P002T-RNNNG</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Micron 232L G8 TLC (Longsys-rebranded)</td>
        <td>Foresee LPDDR4X</td>
        <td class="speed"><span class="r">14,000R</span> <span class="sep">/</span> <span class="w">13,000W</span></td>
        <td class="tbw">1,400 TBW</td>
        <td class="notes">Best $/GB entry into "real" Gen5 speeds; ~1-3% behind Renegade G5/T710 in benchmarks</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Lexar</span>NM1090 Pro</td>
        <td class="date">Jun 2025</td>
        <td class="cap">4TB</td>
        <td class="part">LNM1090P004T-RNNNG</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Micron 232L G8 TLC (Longsys-rebranded)</td>
        <td>Foresee LPDDR4X</td>
        <td class="speed"><span class="r">14,000R</span> <span class="sep">/</span> <span class="w">13,000W</span></td>
        <td class="tbw">2,800 TBW</td>
        <td class="notes"></td>
      </tr>

      <!-- Patriot Viper PV553 -->
      <tr class="group-start">
        <td class="model"><span class="brand">Patriot</span>Viper PV553</td>
        <td class="date">Feb 2024</td>
        <td class="cap">1TB</td>
        <td class="part">PV553P1TBM28H</td>
        <td><span class="badge budget"><span class="dot"></span>InnoGrit</span></td>
        <td class="nand">232L TLC (maker unspecified)</td>
        <td>Yes</td>
        <td class="speed"><span class="r">11,700R</span> <span class="sep">/</span> <span class="w">9,500W</span></td>
        <td class="tbw">700 TBW</td>
        <td class="notes">First-gen Patriot Gen5 drive; 1TB notably slower than 2TB/4TB siblings</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Patriot</span>Viper PV553</td>
        <td class="date">Feb 2024</td>
        <td class="cap">2TB</td>
        <td class="part">PV553P2TBM28H</td>
        <td><span class="badge budget"><span class="dot"></span>InnoGrit</span></td>
        <td class="nand">232L TLC (maker unspecified)</td>
        <td>Yes</td>
        <td class="speed"><span class="r">12,400R</span> <span class="sep">/</span> <span class="w">11,800W</span></td>
        <td class="tbw">1,400 TBW</td>
        <td class="notes">Active blower-fan cooling design</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Patriot</span>Viper PV553</td>
        <td class="date">Feb 2024</td>
        <td class="cap">4TB</td>
        <td class="part">PV553P4TBM28H</td>
        <td><span class="badge budget"><span class="dot"></span>InnoGrit</span></td>
        <td class="nand">232L TLC (maker unspecified)</td>
        <td>Yes</td>
        <td class="speed"><span class="r">12,400R</span> <span class="sep">/</span> <span class="w">11,800W</span></td>
        <td class="tbw">3,000 TBW</td>
        <td class="notes"></td>
      </tr>

      <!-- Patriot Viper PV573 -->
      <tr class="group-start">
        <td class="model"><span class="brand">Patriot</span>Viper PV573</td>
        <td class="date">Oct 2024</td>
        <td class="cap">1TB</td>
        <td class="part">Not publicly listed by SKU</td>
        <td><span class="badge budget"><span class="dot"></span>InnoGrit IG5666</span></td>
        <td class="nand">232L TLC (maker unspecified)</td>
        <td>Yes</td>
        <td class="speed"><span class="r">~14,000R</span> <span class="sep">/</span> <span class="w">~12,000W</span></td>
        <td class="tbw">~700 TBW</td>
        <td class="notes">Successor to PV553 with same "vital specs" per reviewers, but higher headline speed rating; 8,000 RPM active blower cooler</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Patriot</span>Viper PV573</td>
        <td class="date">Oct 2024</td>
        <td class="cap">2TB</td>
        <td class="part">Not publicly listed by SKU</td>
        <td><span class="badge budget"><span class="dot"></span>InnoGrit IG5666</span></td>
        <td class="nand">232L TLC (maker unspecified)</td>
        <td>Yes</td>
        <td class="speed"><span class="r">14,000R</span> <span class="sep">/</span> <span class="w">12,000W</span></td>
        <td class="tbw">~1,400 TBW</td>
        <td class="notes">Rated to stay below 45°C under stress thanks to blower cooler</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Patriot</span>Viper PV573</td>
        <td class="date">Oct 2024</td>
        <td class="cap">4TB</td>
        <td class="part">Not publicly listed by SKU</td>
        <td><span class="badge budget"><span class="dot"></span>InnoGrit IG5666</span></td>
        <td class="nand">232L TLC (maker unspecified)</td>
        <td>Yes</td>
        <td class="speed"><span class="r">14,000R</span> <span class="sep">/</span> <span class="w">12,000W</span></td>
        <td class="tbw">~3,000 TBW</td>
        <td class="notes"></td>
      </tr>

      <!-- Patriot Viper PV593 -->
      <tr class="group-start">
        <td class="model"><span class="brand">Patriot</span>Viper PV593</td>
        <td class="date">Jul 2025</td>
        <td class="cap">1TB</td>
        <td class="part">Not publicly listed by SKU</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Micron 232L G8 TLC ("Fortis Flash" B58r)</td>
        <td>Yes (DDR4)</td>
        <td class="speed"><span class="r">14,000R</span> <span class="sep">/</span> <span class="w">10,000W</span></td>
        <td class="tbw">700 TBW</td>
        <td class="notes">$160 MSRP; 5-year warranty (longest in this list)</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Patriot</span>Viper PV593</td>
        <td class="date">Jul 2025</td>
        <td class="cap">2TB</td>
        <td class="part">Not publicly listed by SKU</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Micron 232L G8 TLC ("Fortis Flash" B58r)</td>
        <td>Yes (DDR4)</td>
        <td class="speed"><span class="r">14,000R</span> <span class="sep">/</span> <span class="w">13,000W</span></td>
        <td class="tbw">1,400 TBW</td>
        <td class="notes">Patriot's flagship Gen5 drive; same silicon family as SN8100/T710/Renegade G5/NM1090 Pro</td>
      </tr>
      <tr>
        <td class="model"><span class="brand">Patriot</span>Viper PV593</td>
        <td class="date">Jul 2025</td>
        <td class="cap">4TB</td>
        <td class="part">Not publicly listed by SKU</td>
        <td><span class="badge sm2508"><span class="dot"></span>SM2508</span></td>
        <td class="nand">Micron 232L G8 TLC ("Fortis Flash" B58r)</td>
        <td>Yes (DDR4)</td>
        <td class="speed"><span class="r">14,000R</span> <span class="sep">/</span> <span class="w">13,000W</span></td>
        <td class="tbw">3,000 TBW</td>
        <td class="notes">$400 MSRP at review; runs cooler than most Phison E26 rivals</td>
      </tr>

    </tbody>
  </table>
  </div>

  <footer>
    <strong>Reading the colors:</strong> rows sharing a controller badge color run the same physical controller silicon — SM2508 (cyan), Phison E26 (amber), Phison E28 (green), Samsung Presto (violet), SK hynix Aries (pink), and budget/other (gray). Values marked with <code>~</code> are approximate — manufacturers don't always publish 1TB-specific figures or exact release dates as prominently as 2TB/4TB flagship specs. Patriot's PV573/PV593 exact retail part numbers aren't consistently published by SKU across retailers, so those are marked accordingly.
  </footer>

</div>
</body>
</html>
