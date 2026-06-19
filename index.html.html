<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Compounding Reference — Stability, Reconstitution & Hazard Stratification</title>
<style>
  :root{
    --bg:#FBFAF7; --panel:#FFFFFF; --ink:#181C20; --ink-soft:#4A555E;
    --line:#E4E0D7; --line-soft:#EFEDE6;
    --hi:#B23A2E; --hi-bg:#FBEEEC; --hi-line:#E8C3BD;
    --lo:#B07514; --lo-bg:#FBF3E4; --lo-line:#EAD6B0;
    --na:#5C6A75; --na-bg:#EEF1F3; --na-line:#D5DCE0;
    --teal:#0E6E66; --teal-bg:#E2F0EE;
    --gold:#C9A227;
    --light:#5B53B5; --filter:#1C6FB0; --cstd:#0E6E66;
    --mono:ui-monospace,"SF Mono",Menlo,Consolas,monospace;
    --sans:"Inter",-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,sans-serif;
  }
  /* Light green — easy on the eyes */
  [data-theme="green"]{
    --bg:#E4EEDC; --panel:#F3F8EE; --ink:#1E2A1B; --ink-soft:#4C5A45;
    --line:#CBDAC0; --line-soft:#DBE7D2;
    --hi:#A93729; --hi-bg:#F3E4DF; --hi-line:#DCBDB4;
    --lo:#9C6710; --lo-bg:#F1ECD8; --lo-line:#D9CAA0;
    --na:#516053; --na-bg:#E2EADD; --na-line:#C5D4BD;
    --teal:#0C6157; --teal-bg:#D7EAE0;
    --gold:#B8911F;
  }
  /* Dark mode reader */
  [data-theme="dark"]{
    --bg:#13181B; --panel:#1B2227; --ink:#E7ECEF; --ink-soft:#9CA9B1;
    --line:#2B353B; --line-soft:#232C31;
    --hi:#E8776C; --hi-bg:#33211E; --hi-line:#5A332D;
    --lo:#E0A94B; --lo-bg:#322813; --lo-line:#574516;
    --na:#92A1AB; --na-bg:#222B30; --na-line:#374249;
    --teal:#54C2B3; --teal-bg:#16302C;
    --gold:#E3C158;
    --light:#9A92E8; --filter:#67ADE0; --cstd:#54C2B3;
  }
  *{box-sizing:border-box}
  html{-webkit-text-size-adjust:100%}
  body{margin:0;background:var(--bg);color:var(--ink);font-family:var(--sans);
    font-size:15px;line-height:1.5;-webkit-font-smoothing:antialiased;
    transition:background .25s ease,color .25s ease}
  .wrap{max-width:1180px;margin:0 auto;padding:0 16px 64px}

  /* Header */
  header{padding:22px 0 14px;border-bottom:3px solid var(--teal)}
  .brandbar{display:flex;align-items:center;gap:13px;flex-wrap:wrap}
  .brandmark{flex-shrink:0;background:linear-gradient(135deg,var(--teal),#0b5a52);color:#fff;
    border-radius:11px;padding:9px 13px;font-weight:800;letter-spacing:.02em;font-size:15px;
    box-shadow:0 2px 8px rgba(14,110,102,.3)}
  .brandmark em{color:var(--gold);font-style:normal}
  .brandtxt{min-width:0}
  .inst{font-size:15px;font-weight:800;line-height:1.2;letter-spacing:-.01em}
  .dept{font-size:12px;color:var(--ink-soft);font-weight:600;margin-top:2px}
  .useflag{margin-left:auto;font-size:11px;font-weight:800;color:var(--lo);background:var(--lo-bg);
    border:1px solid var(--lo-line);border-radius:99px;padding:5px 11px;white-space:nowrap}
  h1{font-size:23px;line-height:1.15;margin:16px 0 0;font-weight:800;letter-spacing:-.02em}
  .sub{margin:8px 0 0;color:var(--ink-soft);font-size:13.5px;max-width:74ch;line-height:1.55}

  /* End-of-page disclaimers */
  .notes-h{font-size:15px;font-weight:800;margin:0 0 10px;color:var(--ink)}
  .enddisc{display:flex;flex-direction:column;gap:9px;margin-bottom:16px}
  .enddisc-row{background:var(--lo-bg);border:1px solid var(--lo-line);border-left:4px solid var(--lo);
    border-radius:9px;padding:11px 14px;font-size:12.5px;line-height:1.55;color:#7a5410}
  .enddisc-row b{color:#5e3f08}
  [data-theme="dark"] .enddisc-row{color:#e8c98a}
  [data-theme="dark"] .enddisc-row b{color:#f3dca8}

  /* Controls */
  .pagetabs{display:flex;gap:4px;margin:18px 0 4px;border-bottom:2px solid var(--line)}
  .pagetabs button{border:none;background:none;font-family:var(--sans);font-size:14.5px;font-weight:700;
    color:var(--ink-soft);padding:11px 16px;cursor:pointer;border-bottom:3px solid transparent;
    margin-bottom:-2px;display:inline-flex;align-items:center;gap:8px;border-radius:8px 8px 0 0}
  .pagetabs button svg{width:17px;height:17px}
  .pagetabs button[aria-pressed="true"]{color:var(--teal);border-bottom-color:var(--teal)}
  .pagetabs button:hover{background:var(--line-soft)}

  /* Study & exam */
  .studybar{display:flex;gap:8px;align-items:center;flex-wrap:wrap;margin:16px 0 6px;
    position:sticky;top:0;z-index:10;background:var(--bg);padding:6px 0}
  .studymeta{font-size:13px;color:var(--ink-soft);font-weight:700;font-variant-numeric:tabular-nums}
  .seg.deckseg button,.seg.modeseg button{padding:8px 14px;font-size:13px;font-weight:700;
    font-family:var(--sans);color:var(--ink-soft)}
  .studybar .spacer{flex:1}

  .flashcard{perspective:1600px;margin:14px 0 6px;cursor:pointer;min-height:330px}
  .fc-inner{position:relative;transition:transform .5s;transform-style:preserve-3d;min-height:330px}
  .flashcard.flipped .fc-inner{transform:rotateY(180deg)}
  .fc-face{position:absolute;inset:0;backface-visibility:hidden;-webkit-backface-visibility:hidden;
    border:1.5px solid var(--line);border-radius:16px;background:var(--panel);padding:24px;
    display:flex;flex-direction:column;overflow:auto;box-shadow:0 2px 10px rgba(0,0,0,.05)}
  .fc-front{align-items:center;justify-content:center;text-align:center}
  .fc-back{transform:rotateY(180deg)}
  .fc-front .fc-name{font-size:27px;font-weight:800;letter-spacing:-.02em;line-height:1.1}
  .fc-front .fc-sub{font-size:14px;color:var(--ink-soft);font-weight:600;margin-top:8px}
  .fc-front .fc-prompt{font-size:13px;color:var(--teal);font-weight:700;margin-top:18px;
    border:1px dashed var(--teal-bg);background:var(--teal-bg);padding:8px 14px;border-radius:10px}
  .fc-front .fc-badges{margin-top:14px;display:flex;gap:6px;flex-wrap:wrap;justify-content:center}
  .fc-back .fc-bname{font-size:18px;font-weight:800;margin-bottom:2px}
  .fc-back .fc-bsub{font-size:12.5px;color:var(--ink-soft);font-weight:600;margin-bottom:10px}
  .fc-row{display:flex;gap:10px;padding:6px 0;border-top:1px solid var(--line-soft);font-size:13px;line-height:1.4}
  .fc-row:first-of-type{border-top:none}
  .fc-row .fk{flex:0 0 38%;color:var(--ink-soft);font-weight:700;font-size:11px;letter-spacing:.04em;
    text-transform:uppercase;padding-top:2px}
  .fc-row .fv{flex:1;font-family:var(--mono);word-break:break-word}
  .fc-hint{text-align:center;font-size:12px;color:var(--ink-soft);margin-bottom:12px}
  .fc-ctrl{display:flex;gap:8px;align-items:center;justify-content:center}
  .navbtn{border:1.5px solid var(--line);background:var(--panel);color:var(--ink);width:46px;height:46px;
    border-radius:12px;cursor:pointer;display:inline-flex;align-items:center;justify-content:center}
  .navbtn:hover{border-color:var(--teal);color:var(--teal)}
  .navbtn svg{width:20px;height:20px}
  .gradebtn{flex:1;max-width:220px;border:none;border-radius:12px;padding:13px;font-size:14.5px;font-weight:800;
    font-family:var(--sans);cursor:pointer;color:#fff}
  .gradebtn.known{background:var(--teal)}
  .gradebtn.review{background:var(--lo)}
  .gradebtn:hover{opacity:.9}
  .fc-done,.quiz-done{text-align:center;padding:34px 18px;background:var(--panel);border:1.5px solid var(--line);
    border-radius:16px;margin-top:14px}
  .fc-done h3,.quiz-done h3{margin:0 0 6px;font-size:22px}
  .fc-done .big,.quiz-done .big{font-size:42px;font-weight:800;color:var(--teal);margin:8px 0}
  .fc-done .donebtns,.quiz-done .donebtns{display:flex;gap:10px;justify-content:center;flex-wrap:wrap;margin-top:16px}

  /* Quiz */
  .quizcard{background:var(--panel);border:1.5px solid var(--line);border-radius:16px;padding:22px;margin:14px 0 0;
    box-shadow:0 2px 10px rgba(0,0,0,.05)}
  .quiz-tag{font-size:10px;letter-spacing:.1em;text-transform:uppercase;color:var(--teal);font-weight:800;margin-bottom:8px}
  .quiz-q{font-size:19px;font-weight:700;line-height:1.3;margin-bottom:18px}
  .quiz-q b{color:var(--teal)}
  .quiz-opts{display:flex;flex-direction:column;gap:9px}
  .quiz-opt{text-align:left;border:1.5px solid var(--line);background:var(--panel);color:var(--ink);
    padding:13px 15px;border-radius:11px;font-size:14px;font-weight:600;font-family:var(--sans);cursor:pointer;
    transition:border-color .12s}
  .quiz-opt:hover:not(:disabled){border-color:var(--teal)}
  .quiz-opt.correct{background:var(--teal-bg);border-color:var(--teal);color:var(--teal);font-weight:800}
  .quiz-opt.wrong{background:var(--hi-bg);border-color:var(--hi);color:var(--hi);font-weight:800}
  .quiz-opt:disabled{cursor:default}
  .quiz-fb{margin-top:14px;font-size:13.5px;font-weight:700;padding:10px 14px;border-radius:10px}
  .quiz-fb.ok{background:var(--teal-bg);color:var(--teal)}
  .quiz-fb.no{background:var(--hi-bg);color:var(--hi)}
  .quiz-fb .ans{display:block;font-weight:600;color:var(--ink);margin-top:4px;font-size:13px}
  #quizNext{margin-top:16px}
  .study-note{font-size:11.5px;color:var(--ink-soft);text-align:center;margin-top:22px;line-height:1.5}

  .controls{position:sticky;top:0;z-index:20;background:var(--bg);
    padding:12px 0 10px;border-bottom:1px solid var(--line);margin-bottom:4px}
  .searchrow{display:flex;gap:8px;align-items:center}
  .search{flex:1;min-width:0;position:relative}
  .search input{width:100%;padding:11px 13px 11px 38px;border:1.5px solid var(--line);
    border-radius:10px;font-size:15px;font-family:var(--sans);background:var(--panel);color:var(--ink)}
  .search input:focus{outline:none;border-color:var(--teal);box-shadow:0 0 0 3px var(--teal-bg)}
  .search svg{position:absolute;left:12px;top:50%;transform:translateY(-50%);
    width:16px;height:16px;color:var(--ink-soft)}
  .filterbtn{flex-shrink:0;display:inline-flex;align-items:center;gap:7px;border:1.5px solid var(--line);
    background:var(--panel);color:var(--ink);padding:10px 14px;border-radius:10px;font-size:14px;
    font-weight:700;font-family:var(--sans);cursor:pointer;transition:border-color .12s}
  .filterbtn:hover{border-color:var(--teal)}
  .filterbtn[aria-expanded="true"]{border-color:var(--teal);color:var(--teal)}
  .filterbtn svg{width:16px;height:16px}
  .fcount{background:var(--teal);color:#fff;font-size:11px;font-weight:800;min-width:18px;height:18px;
    border-radius:99px;display:inline-flex;align-items:center;justify-content:center;padding:0 5px}

  .actionbar{display:flex;gap:8px;align-items:center;flex-wrap:wrap;margin-top:9px}
  .actionbar .spacer{flex:1}
  .count{font-size:12.5px;color:var(--ink-soft);white-space:nowrap;font-variant-numeric:tabular-nums}
  .count b{color:var(--ink);font-weight:700}
  .chartswitch{display:flex;border:2px solid var(--teal);border-radius:10px;overflow:hidden;margin-bottom:11px}
  .chartswitch button{flex:1;border:none;background:var(--panel);color:var(--teal);font-weight:700;
    font-family:var(--sans);font-size:13.5px;padding:10px 12px;cursor:pointer;border-right:2px solid var(--teal)}
  .chartswitch button:last-child{border-right:none}
  .chartswitch button[aria-pressed="true"]{background:var(--teal);color:#fff}
  .seg{display:inline-flex;border:1.5px solid var(--line);border-radius:9px;overflow:hidden;background:var(--panel)}
  .seg button{border:none;background:none;padding:8px 10px;cursor:pointer;color:var(--ink-soft);
    border-right:1.5px solid var(--line);display:inline-flex;align-items:center}
  .seg button:last-child{border-right:none}
  .seg button svg{width:16px;height:16px}
  .seg button[aria-pressed="true"]{background:var(--teal);color:#fff}
  .toolbtn{border:1.5px solid var(--line);background:var(--panel);color:var(--ink);
    padding:8px 12px;border-radius:9px;font-size:13px;font-weight:700;font-family:var(--sans);cursor:pointer;
    display:inline-flex;align-items:center;gap:6px;transition:border-color .12s}
  .toolbtn:hover{border-color:var(--teal);color:var(--teal)}
  .toolbtn svg{width:15px;height:15px}
  .toolbtn.primary{background:var(--teal);border-color:var(--teal);color:#fff}
  .toolbtn.primary:hover{opacity:.9;color:#fff}

  /* Active filter pills */
  .activefilters{display:flex;gap:6px;flex-wrap:wrap;margin-top:10px}
  .afchip{display:inline-flex;align-items:center;gap:6px;background:var(--teal-bg);color:var(--teal);
    border:1px solid #BFE0DB;border-radius:99px;padding:4px 6px 4px 11px;font-size:12.5px;font-weight:700}
  .afchip button{border:none;background:none;color:inherit;cursor:pointer;font-size:15px;line-height:1;
    width:18px;height:18px;border-radius:99px;display:inline-flex;align-items:center;justify-content:center}
  .afchip button:hover{background:rgba(0,0,0,.08)}
  [data-theme="dark"] .afchip{border-color:#1f4f48}

  /* Collapsible filter panel */
  .filterpanel{display:none;margin-top:11px;background:var(--panel);border:1.5px solid var(--line);
    border-radius:12px;padding:14px}
  .filterpanel.open{display:block}
  .filterpanel-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:14px 22px}
  .filterpanel-foot{display:flex;justify-content:space-between;align-items:center;gap:10px;
    margin-top:14px;padding-top:12px;border-top:1px solid var(--line)}
  .linkbtn{background:var(--teal);color:#fff;border:none;border-radius:9px;padding:9px 22px;
    font-size:14px;font-weight:700;font-family:var(--sans);cursor:pointer}
  .linkbtn:hover{opacity:.9}

  .filterpanel-head{display:none;font-size:16px;font-weight:800;padding-bottom:10px;margin-bottom:12px;
    border-bottom:1px solid var(--line)}
  .sheet-backdrop{position:fixed;inset:0;background:rgba(15,20,24,.45);z-index:40;display:none}

  .fgroup{display:flex;flex-direction:column;gap:6px}
  .fgroup-wide{grid-column:1 / -1}
  .flabel{font-size:10px;letter-spacing:.1em;text-transform:uppercase;color:var(--ink-soft);font-weight:700}
  .chips{display:flex;gap:6px;flex-wrap:wrap}
  .chip{border:1.5px solid var(--line);background:var(--panel);color:var(--ink-soft);
    padding:7px 12px;border-radius:99px;font-size:13px;cursor:pointer;font-weight:600;
    font-family:var(--sans);transition:all .12s;user-select:none;display:inline-flex;align-items:center;gap:5px}
  .chip:hover{border-color:var(--na)}
  .chip[aria-pressed="true"]{background:var(--ink);color:#fff;border-color:var(--ink)}
  .chip.dot::before{content:"";width:7px;height:7px;border-radius:99px;background:currentColor;opacity:.7}
  .chip.hi[aria-pressed="true"]{background:var(--hi);border-color:var(--hi)}
  .chip.lo[aria-pressed="true"]{background:var(--lo);border-color:var(--lo)}
  .chip.flag[aria-pressed="true"]{background:var(--teal);border-color:var(--teal)}
  .chip.alertchip[aria-pressed="true"]{background:var(--hi);border-color:var(--hi);color:#fff}
  .resetbtn{background:none;border:none;color:var(--teal);font-size:13.5px;font-weight:700;
    cursor:pointer;font-family:var(--sans);padding:4px 2px}
  .resetbtn:hover{text-decoration:underline}
  .general-only{display:none}
  body[data-chart="general"] .chemo-only{display:none}
  body[data-chart="general"] .general-only{display:flex}
  .flash{position:fixed;left:50%;bottom:24px;transform:translateX(-50%) translateY(20px);
    background:var(--ink);color:#fff;padding:12px 18px;border-radius:10px;font-size:13px;font-weight:600;
    max-width:90%;box-shadow:0 6px 24px rgba(0,0,0,.25);opacity:0;pointer-events:none;
    transition:opacity .2s,transform .2s;z-index:50}
  .flash.show{opacity:1;transform:translateX(-50%) translateY(0)}
  .offline-note{display:flex;align-items:center;gap:7px;margin-top:9px;font-size:11.5px;
    color:var(--teal);font-weight:600}
  .offline-note svg{width:15px;height:15px;flex-shrink:0}

  /* List */
  .list{margin-top:16px;display:grid;grid-template-columns:1fr;gap:10px}
  .card{background:var(--panel);border:1px solid var(--line);border-left-width:4px;
    border-radius:10px;overflow:hidden}
  .card.r-High{border-left-color:var(--hi)}
  .card.r-Low{border-left-color:var(--lo)}
  .card.r-na{border-left-color:var(--na)}

  .chead{display:flex;align-items:baseline;gap:9px;flex-wrap:wrap;padding:13px 15px 9px}
  .gname{font-size:16px;font-weight:800;letter-spacing:-.01em}
  .brand{font-size:13px;color:var(--ink-soft);font-weight:600}
  .mfr{font-size:12px;color:var(--ink-soft)}
  .mfr::before{content:"· "}
  .cat{flex-basis:100%;font-size:11.5px;color:var(--ink-soft);font-weight:600;margin-top:1px}
  .cat b{color:var(--teal);font-weight:700}
  .ind{flex-basis:100%;font-size:12px;color:var(--ink);margin-top:3px;line-height:1.4}
  .ind b{color:var(--filter);font-weight:700;font-size:10px;letter-spacing:.07em;text-transform:uppercase}
  .badges{margin-left:auto;display:flex;gap:6px;align-items:center;flex-wrap:wrap}
  .badge{font-size:10.5px;font-weight:800;letter-spacing:.04em;text-transform:uppercase;
    padding:3px 8px;border-radius:6px;white-space:nowrap}
  .b-High{background:var(--hi-bg);color:var(--hi);border:1px solid var(--hi-line)}
  .b-Low{background:var(--lo-bg);color:var(--lo);border:1px solid var(--lo-line)}
  .b-na{background:var(--na-bg);color:var(--na);border:1px solid var(--na-line)}
  .b-cls{background:#fff;color:var(--ink-soft);border:1px solid var(--line)}
  .b-gcat{background:var(--teal-bg);color:var(--teal);border:1px solid #BFE0DB;font-weight:800}
  .cell.span2{grid-column:1 / -1}
  .seg-vial{grid-column:1 / -1;background:var(--line-soft);border-top:1px solid var(--line-soft);
    padding:6px 15px 2px;font-size:10px;letter-spacing:.1em;text-transform:uppercase;color:var(--ink-soft);font-weight:800}
  .metarow{display:flex;gap:10px 14px;align-items:center;flex-wrap:wrap;padding:10px 15px 6px}
  .metarow .pots{padding:0;display:flex;gap:5px;align-items:center;flex-wrap:wrap}
  .formtag{display:inline-flex;align-items:center;gap:6px;font-size:11.5px;font-weight:800;
    padding:5px 12px;border-radius:99px;border:1px solid;white-space:nowrap}
  .formtag svg{width:13px;height:13px}
  .t-powder{background:#eceef5;color:#46506b;border-color:#d2d8e8}
  .t-solution{background:#e2f0f5;color:#0c6f8c;border-color:#c3e1ec}
  .t-oral{background:#f2ecd8;color:#85661a;border-color:#e1d2a4}
  [data-theme="dark"] .t-powder{background:#23282f;color:#aeb8cc;border-color:#39414f}
  [data-theme="dark"] .t-solution{background:#10303a;color:#7fc4d9;border-color:#1d4654}
  /* Category colour variety (does not affect hazard/chemo recognition) */
  .catdot{width:9px;height:9px;border-radius:99px;display:inline-block;margin-right:6px;vertical-align:middle;background:#8a97a4}
  .catdot.cc-rose{background:#c2557a}.catdot.cc-violet{background:#7e54c4}.catdot.cc-cyan{background:#0e90a8}
  .catdot.cc-green{background:#3f9152}.catdot.cc-amber{background:#c08a1e}.catdot.cc-blue{background:#3567b0}
  .catdot.cc-teal{background:#0e8d80}.catdot.cc-brown{background:#8a6038}.catdot.cc-indigo{background:#5a54c7}
  .catdot.cc-sky{background:#2487c4}.catdot.cc-plum{background:#9a4a9e}.catdot.cc-lime{background:#6f8a1c}
  .catdot.cc-slate{background:#5b6975}.catdot.cc-red{background:#bf4632}
  .badge.cc-blue{background:#e8eefb;color:#2b5fa8;border-color:#cedef6}
  .badge.cc-violet{background:#efe7fb;color:#6b46b8;border-color:#ddd0f3}
  .badge.cc-cyan{background:#def2f7;color:#0c7186;border-color:#c2e3ec}
  .badge.cc-indigo{background:#e9e8fb;color:#4944b8;border-color:#d6d4f3}
  .badge.cc-amber{background:#f7eed7;color:#8c6310;border-color:#e8d6a8}
  .badge.cc-rose{background:#fbe4eb;color:#a93a60;border-color:#f1c9d6}
  .badge.cc-red{background:#fce6e1;color:#b3402e;border-color:#f3cabf}
  .badge.cc-slate{background:#eceff2;color:#51606b;border-color:#d8dee3}
  .b-haz{background:var(--hi);color:#fff;border:1px solid var(--hi);font-weight:800;
    font-size:11.5px;padding:4px 11px;letter-spacing:.05em;
    box-shadow:0 1px 4px rgba(178,58,46,.35)}
  .b-haz svg{width:12px;height:12px;margin-right:3px;vertical-align:-1px}
  .b-nothaz{background:none;color:var(--na);border:1px dashed var(--na-line);font-weight:600;opacity:.7}
  .b-alert{background:none;color:var(--hi);border:1px solid var(--hi-line);font-weight:700;opacity:.92}
  [data-theme="dark"] .b-cls{background:var(--panel)}
  [data-theme="dark"] .b-haz{color:#1a1010}
  .card.alert{border-left-width:5px}
  .card.haz{box-shadow:inset 4px 0 0 -1px var(--hi)}

  .flags{display:flex;gap:5px;padding:0 15px 11px;flex-wrap:wrap}
  .flag-pill{font-size:11px;font-weight:700;padding:3px 9px;border-radius:99px;
    display:inline-flex;align-items:center;gap:5px;border:1px solid}
  .flag-pill svg{width:12px;height:12px}
  .fp-light{background:#EEEDF8;color:var(--light);border-color:#D5D2EE}
  .fp-filter{background:#E8F1F8;color:var(--filter);border-color:#CBE0EF}
  .fp-cstd{background:var(--teal-bg);color:var(--cstd);border-color:#BFE0DB}
  .fp-haz{background:var(--hi-bg);color:var(--hi);border-color:var(--hi-line)}
  .fp-off{background:var(--line-soft);color:var(--ink-soft);border-color:var(--line);font-weight:600;opacity:.75}

  .pots{display:flex;gap:5px;padding:0 15px 12px;flex-wrap:wrap;align-items:center}
  .pots .plabel{font-size:10px;letter-spacing:.08em;text-transform:uppercase;
    color:var(--ink-soft);font-weight:700;margin-right:2px}
  .pot{font-size:11px;font-weight:700;padding:3px 9px;border-radius:6px;border:1px solid;white-space:nowrap}
  .pot.danger{background:var(--hi-bg);color:var(--hi);border-color:var(--hi-line)}
  .pot.geno{background:#EEEDF8;color:#6A5FCB;border-color:#D5D2EE}
  .pot.irrit{background:var(--lo-bg);color:var(--lo);border-color:var(--lo-line)}
  .pot.cyto{background:var(--na-bg);color:var(--na);border-color:var(--na-line)}
  .pot.none{background:none;color:var(--ink-soft);border:1px dashed var(--line);font-weight:600;opacity:.8}
  [data-theme="dark"] .pot.geno{background:#262150;color:#A79DF0;border-color:#3A3370}

  .usebanner{display:flex;gap:9px;align-items:flex-start;margin-top:14px;
    background:var(--lo-bg);border:1px solid var(--lo-line);border-left:4px solid var(--lo);
    border-radius:9px;padding:10px 13px;font-size:12px;line-height:1.5;color:#7a5410}
  .usebanner b{color:#5e3f08}
  .usebanner svg{width:17px;height:17px;flex-shrink:0;color:var(--lo);margin-top:1px}
  [data-theme="dark"] .usebanner{color:#e8c98a}
  [data-theme="dark"] .usebanner b{color:#f3dca8}

  .grid{display:grid;grid-template-columns:1fr 1fr;gap:1px;background:var(--line-soft);
    border-top:1px solid var(--line-soft)}
  .cell{background:var(--panel);padding:9px 15px}
  .cell .k{font-size:10px;letter-spacing:.08em;text-transform:uppercase;color:var(--ink-soft);
    font-weight:700;margin-bottom:2px}
  .cell .v{font-size:13px;font-family:var(--mono);line-height:1.4;color:var(--ink);word-break:break-word}
  .cell .v.dash{color:var(--ink-soft);opacity:.55;font-family:var(--sans)}
  .seg-recon{grid-column:1 / -1;background:var(--line-soft);border-top:1px solid var(--line-soft);
    padding:6px 15px 2px;font-size:10px;letter-spacing:.1em;text-transform:uppercase;
    color:var(--teal);font-weight:800}
  .seg-dil{grid-column:1 / -1;background:var(--line-soft);border-top:1px solid var(--line-soft);
    padding:6px 15px 2px;font-size:10px;letter-spacing:.1em;text-transform:uppercase;
    color:var(--filter);font-weight:800}

  .empty{text-align:center;padding:60px 20px;color:var(--ink-soft)}
  .empty b{display:block;font-size:16px;color:var(--ink);margin-bottom:6px}

  footer{margin-top:30px;padding-top:16px;border-top:1px solid var(--line);
    font-size:11.5px;color:var(--ink-soft);line-height:1.6}
  footer .legend{display:flex;gap:14px;flex-wrap:wrap;margin-bottom:8px}
  footer .legend span{display:inline-flex;align-items:center;gap:6px;font-weight:600}
  footer .sw{width:11px;height:11px;border-radius:3px}
  .credit{margin-top:14px;padding-top:12px;border-top:1px solid var(--line);
    font-size:13px;color:var(--ink);font-weight:600}
  .credit b{color:var(--teal);font-weight:800}

  @media print{
    .controls,.offline-note{display:none!important}
    body{background:#fff;font-size:11px}
    .wrap{max-width:100%;padding:0}
    header{border-bottom:1px solid #000}
    .card{break-inside:avoid;page-break-inside:avoid;box-shadow:none;border:1px solid #999;margin-bottom:6px}
    .badge,.pot,.flag-pill,.disclaimer,.usebanner{-webkit-print-color-adjust:exact;print-color-adjust:exact}
  }
  /* Wide screens (PC / iPad landscape): two-column card grid */
  @media(min-width:920px){
    .list{grid-template-columns:1fr 1fr;gap:12px}
    .card{align-self:start}
  }
  /* Tablet / small laptop */
  @media(max-width:919px) and (min-width:621px){
    .wrap{padding:0 18px 64px}
  }
  /* Mobile */
  @media(max-width:620px){
    .wrap{padding:0 13px 56px}
    h1{font-size:20px}
    .sub{font-size:12.5px}
    .grid{grid-template-columns:1fr}
    .badges{width:100%;margin-left:0;margin-top:5px}
    .chead{padding-bottom:8px}
    .btxt{display:none}
    .toolbtn{padding:9px 11px}
    .actionbar{gap:6px}
    .actionbar .count{order:-1;flex-basis:100%;margin-bottom:2px}
    .actionbar .spacer{display:none}
    .chip{padding:9px 14px;font-size:13.5px}
    .filterbtn{padding:11px 14px}
    .search input{padding:12px 13px 12px 38px}
    .filterpanel-grid{grid-template-columns:1fr;gap:16px}
    .resetbtn{font-size:14px}
    .gname{font-size:15.5px}
    body.sheet-open .sheet-backdrop{display:block}
    .filterpanel.open{position:fixed;left:0;right:0;bottom:0;top:auto;z-index:45;margin:0;
      border-radius:18px 18px 0 0;max-height:86vh;overflow:auto;padding:18px 16px calc(18px + env(safe-area-inset-bottom));
      box-shadow:0 -8px 30px rgba(0,0,0,.28);animation:sheetUp .22s ease}
    .filterpanel-head{display:block}
    .filterpanel-foot{position:sticky;bottom:-1px;background:var(--panel);margin:14px -16px -18px;
      padding:12px 16px calc(12px + env(safe-area-inset-bottom));border-top:1px solid var(--line)}
    .filterpanel .chip{padding:10px 15px;font-size:14px}
  }
  @keyframes sheetUp{from{transform:translateY(100%)}to{transform:translateY(0)}}
  /* Honor reduced-motion */
  @media(prefers-reduced-motion:reduce){*{transition:none!important}}
</style>
</head>
<body>
<div class="wrap">
  <header>
    <div class="brandbar">
      <div class="brandmark"><span>KFSH<em>&amp;</em>RC</span></div>
      <div class="brandtxt">
        <div class="inst">King Faisal Specialist Hospital &amp; Research Centre</div>
        <div class="dept">Pharmaceutical Care Division · Oncology Compounding</div>
      </div>
      <span class="useflag" title="Not yet an institutionally approved reference">Internal use · pending approval</span>
    </div>
    <h1>IV Stability &amp; Reconstitution Reference</h1>
    <p class="sub">Reconstitution diluent &amp; volume, vial and post-dilution stability, light / filter / CSTD requirements, and hazard stratification for antineoplastic and general IV medications. See important notes at the end of the page.</p>
  </header>

  <div class="pagetabs" id="pagetabs">
    <button data-p="ref" aria-pressed="true"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 5h16M4 12h16M4 19h10"/></svg>Reference</button>
    <button data-p="study" aria-pressed="false"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="5" width="14" height="16" rx="2"/><path d="M7 3h12a2 2 0 0 1 2 2v14"/></svg>Study &amp; exam</button>
  </div>

  <div id="refPage">
  <div class="controls">
    <div class="chartswitch">
      <button data-c="chemo" aria-pressed="true">Antineoplastic &amp; hazard</button>
      <button data-c="general" aria-pressed="false">General IV meds</button>
    </div>
    <div class="searchrow">
      <div class="search">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="7"/><path d="m21 21-4.3-4.3"/></svg>
        <input id="q" type="text" placeholder="Search drug, brand, manufacturer…" autocomplete="off">
      </div>
      <button class="filterbtn" id="filterToggle" aria-expanded="false">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 5h18M6 12h12M10 19h4"/></svg>
        <span>Filters</span>
        <span class="fcount" id="fcount" hidden>0</span>
      </button>
    </div>
    <div class="actionbar">
      <span class="count" id="count"></span>
      <span class="spacer"></span>
      <div class="seg" id="themeseg" role="group" aria-label="Reader theme">
        <button data-t="light" aria-pressed="true" title="Light" aria-label="Light theme"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="4"/><path d="M12 2v2M12 20v2M2 12h2M20 12h2M5 5l1.5 1.5M17.5 17.5 19 19M19 5l-1.5 1.5M5 19l1.5-1.5"/></svg></button>
        <button data-t="green" aria-pressed="false" title="Light green" aria-label="Light green theme"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M11 20A7 7 0 0 1 9.8 6.1C15.5 5 17 4.5 19 2c1 2 2 4.18 2 8 0 5.5-4.78 10-10 10z"/><path d="M2 21c0-3 1.85-5.36 5.08-6"/></svg></button>
        <button data-t="dark" aria-pressed="false" title="Dark" aria-label="Dark theme"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 3a6 6 0 0 0 9 9 9 9 0 1 1-9-9z"/></svg></button>
      </div>
      <button class="toolbtn primary" id="export" title="Download current view as a spreadsheet">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 3v12M8 11l4 4 4-4"/><path d="M4 17v2a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-2"/></svg>
        <span class="btxt">Excel</span>
      </button>
      <button class="toolbtn" id="share" title="Save or share an interactive copy of this file">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="18" cy="5" r="3"/><circle cx="6" cy="12" r="3"/><circle cx="18" cy="19" r="3"/><path d="m8.6 13.5 6.8 4M15.4 6.5 8.6 10.5"/></svg>
        <span class="btxt">Share file</span>
      </button>
      <button class="toolbtn" id="print" title="Print or save as PDF">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M6 9V3h12v6M6 18H4a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-2M6 14h12v7H6z"/></svg>
        <span class="btxt">Print</span>
      </button>
    </div>
    <div class="activefilters" id="activefilters" hidden></div>
    <div class="filterpanel" id="filterpanel">
      <div class="filterpanel-head">Filters</div>
      <div class="filterpanel-grid">
      <div class="fgroup fgroup-wide">
        <span class="flabel">Form / preparation</span>
        <div class="chips" id="f-form">
          <button class="chip" data-v="Powder" aria-pressed="false">Powder — reconstitute</button>
          <button class="chip" data-v="Solution" aria-pressed="false">Liquid — ready solution</button>
        </div>
      </div>
      <div class="fgroup chemo-only">
        <span class="flabel">Class</span>
        <div class="chips" id="f-cls">
          <button class="chip" data-v="Antineoplastic" aria-pressed="false">Antineoplastic</button>
          <button class="chip" data-v="Non-antineoplastic" aria-pressed="false">Non-antineoplastic</button>
        </div>
      </div>
      <div class="fgroup chemo-only">
        <span class="flabel">Hazard risk (NIOSH)</span>
        <div class="chips" id="f-risk">
          <button class="chip hi dot" data-v="High" aria-pressed="false">High</button>
          <button class="chip lo dot" data-v="Low" aria-pressed="false">Low</button>
        </div>
      </div>
      <div class="fgroup chemo-only">
        <span class="flabel">Requires</span>
        <div class="chips" id="f-flag">
          <button class="chip flag" data-v="light" aria-pressed="false">Light protection</button>
          <button class="chip flag" data-v="filter" aria-pressed="false">In-line filter</button>
          <button class="chip flag" data-v="cstd" aria-pressed="false">CSTD</button>
          <button class="chip flag" data-v="haz" aria-pressed="false">Hazardous</button>
        </div>
      </div>
      <div class="fgroup chemo-only">
        <span class="flabel">Hazard potential</span>
        <div class="chips" id="f-pot">
          <button class="chip" data-v="Vesicant" aria-pressed="false">Vesicant</button>
          <button class="chip" data-v="Irritant" aria-pressed="false">Irritant</button>
          <button class="chip" data-v="Carcinogenic" aria-pressed="false">Carcinogenic</button>
          <button class="chip" data-v="Teratogenic" aria-pressed="false">Teratogenic</button>
          <button class="chip" data-v="Mutagenic" aria-pressed="false">Mutagenic</button>
          <button class="chip" data-v="Reproductive toxicity" aria-pressed="false">Reproductive</button>
        </div>
      </div>
      <div class="fgroup fgroup-wide chemo-only">
        <span class="flabel">Tumor group (used for)</span>
        <div class="chips" id="f-tumor">
          <button class="chip" data-v="Breast" aria-pressed="false">Breast</button>
          <button class="chip" data-v="Lung" aria-pressed="false">Lung</button>
          <button class="chip" data-v="GI" aria-pressed="false">GI</button>
          <button class="chip" data-v="Lymphoma" aria-pressed="false">Lymphoma</button>
          <button class="chip" data-v="Leukemia" aria-pressed="false">Leukemia</button>
          <button class="chip" data-v="Myeloma" aria-pressed="false">Myeloma</button>
          <button class="chip" data-v="GU" aria-pressed="false">GU</button>
          <button class="chip" data-v="Gynecologic" aria-pressed="false">Gynecologic</button>
          <button class="chip" data-v="Head & Neck" aria-pressed="false">Head &amp; Neck</button>
          <button class="chip" data-v="Melanoma/Skin" aria-pressed="false">Melanoma/Skin</button>
          <button class="chip" data-v="CNS" aria-pressed="false">CNS</button>
          <button class="chip" data-v="Sarcoma" aria-pressed="false">Sarcoma</button>
          <button class="chip" data-v="Pediatric" aria-pressed="false">Pediatric</button>
        </div>
      </div>
      <div class="fgroup chemo-only">
        <span class="flabel">Designation</span>
        <div class="chips" id="f-desig">
          <button class="chip alertchip" data-v="highAlert" aria-pressed="false">⚠ High alert</button>
        </div>
      </div>
      <div class="fgroup fgroup-wide general-only">
        <span class="flabel">Category</span>
        <div class="chips" id="f-gcat">
          <button class="chip" data-v="Antibiotic" aria-pressed="false">Antibiotic</button>
          <button class="chip" data-v="Antifungal" aria-pressed="false">Antifungal</button>
          <button class="chip" data-v="Antiviral" aria-pressed="false">Antiviral</button>
          <button class="chip" data-v="Biologic" aria-pressed="false">Biologic</button>
          <button class="chip" data-v="Corticosteroid" aria-pressed="false">Corticosteroid</button>
          <button class="chip" data-v="Immunosuppressant" aria-pressed="false">Immunosuppressant</button>
          <button class="chip" data-v="Thrombolytic" aria-pressed="false">Thrombolytic</button>
          <button class="chip" data-v="Other" aria-pressed="false">Other</button>
        </div>
      </div>
      </div>
      <div class="filterpanel-foot">
        <button class="resetbtn" id="reset">Clear all filters</button>
        <button class="linkbtn" id="filterDone">Done</button>
      </div>
    </div>
    <div class="offline-note" id="offlineNote">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12.5a7 7 0 0 1 14 0"/><path d="M2 9a11 11 0 0 1 20 0"/><circle cx="12" cy="18" r="1.2" fill="currentColor"/></svg>
      <span>Works fully offline. To share: save the file and open it in a browser (Safari/Chrome) — a Drive or chat preview shows it as static.</span>
    </div>
  </div>

  <div class="list" id="list"></div>
  </div><!-- /refPage -->

  <div id="studyPage" hidden>
    <div class="studybar">
      <div class="seg deckseg" id="deckseg" role="group" aria-label="Deck">
        <button data-d="chemo" aria-pressed="true">Antineoplastic</button>
        <button data-d="general" aria-pressed="false">General IV</button>
      </div>
      <div class="seg modeseg" id="modeseg" role="group" aria-label="Mode">
        <button data-m="flip" aria-pressed="true">Flip cards</button>
        <button data-m="quiz" aria-pressed="false">Quiz</button>
      </div>
      <span class="spacer"></span>
      <span class="studymeta" id="studymeta"></span>
      <button class="toolbtn" id="studyShuffle" title="Shuffle / new"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M16 3h5v5M4 20 21 3M21 16v5h-5M15 15l6 6M4 4l5 5"/></svg><span class="btxt">Shuffle</span></button>
    </div>

    <!-- Flip mode -->
    <div id="flipStage">
      <div class="flashcard" id="flashcard">
        <div class="fc-inner">
          <div class="fc-face fc-front" id="fcFront"></div>
          <div class="fc-face fc-back" id="fcBack"></div>
        </div>
      </div>
      <div class="fc-hint" id="fcHint">Tap the card to reveal the answer</div>
      <div class="fc-ctrl">
        <button class="navbtn" id="fcPrev" aria-label="Previous"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M15 18l-6-6 6-6"/></svg></button>
        <button class="gradebtn review" id="fcReview">Needs review</button>
        <button class="gradebtn known" id="fcKnown">Got it</button>
        <button class="navbtn" id="fcNext" aria-label="Next"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 18l6-6-6-6"/></svg></button>
      </div>
      <div class="fc-done" id="fcDone" hidden></div>
    </div>

    <!-- Quiz mode -->
    <div id="quizStage" hidden>
      <div class="quizcard" id="quizCard">
        <div class="quiz-tag" id="quizTag"></div>
        <div class="quiz-q" id="quizQ"></div>
        <div class="quiz-opts" id="quizOpts"></div>
        <div class="quiz-fb" id="quizFb" hidden></div>
        <button class="linkbtn" id="quizNext" hidden>Next question</button>
      </div>
      <div class="quiz-done" id="quizDone" hidden></div>
    </div>

    <p class="study-note">Study mode tests the data in this tool. It's a learning aid — always verify against the current SDS / package insert before clinical use.</p>
  </div><!-- /studyPage -->

  <footer>
    <h2 class="notes-h">Important notes &amp; disclaimers</h2>
    <div class="enddisc">
      <div class="enddisc-row"><b>Internal use — pending institutional approval.</b> Unofficial study / reference aid compiled from KFSH&amp;RC documents and the NIOSH hazardous-drug appendices. It is not an institutionally sanctioned reference. Do not host on public or external sites; for clinical use it should be approved by IT security / information governance and Pharmacy &amp; Therapeutics, and hosted on the hospital intranet.</div>
      <div class="enddisc-row"><b>Verify before use.</b> Transcribed from photographed reference sheets; some source cells were partly obscured. Always confirm every value against the current SDS / manufacturer package insert and your local protocol before preparing or administering any agent. Brand-specific rows differ — match the manufacturer you are dispensing.</div>
    </div>
    <div class="legend">
      <span><span class="sw" style="background:var(--hi)"></span>High hazard</span>
      <span><span class="sw" style="background:var(--lo)"></span>Low hazard</span>
      <span><span class="sw" style="background:var(--na)"></span>Not individually NIOSH-listed (e.g. mAbs)</span>
    </div>
    <div class="legend" style="margin-bottom:10px">
      <span><span class="sw" style="background:var(--hi)"></span>Vesicant / acutely toxic</span>
      <span><span class="sw" style="background:#6A5FCB"></span>Genotoxic — carcinogenic, mutagenic, teratogenic, reproductive, embryolethal</span>
      <span><span class="sw" style="background:var(--lo)"></span>Irritant</span>
      <span><span class="sw" style="background:var(--na)"></span>Cytotoxic / chemo</span>
    </div>
    R = refrigerated · RT = room temperature · SWFI = sterile water for injection · NS = normal saline 0.9% · D5W = 5% dextrose · LR = lactated Ringer's · CSTD = closed-system transfer device · IT = intrathecal. "Hazardous" reflects the source sheet's column, which may differ from NIOSH class for some monoclonal antibodies.
    <div style="margin-top:8px"><b>⚠ High Alert</b> = listed on the KFSH&amp;RC Formulary &amp; Therapeutic Committee "High Alert Antineoplastic Medications" appendix (approved Sep 2025). Agents not on that appendix (e.g. eribulin) are left unflagged.</div>
    <div style="margin-top:8px"><b>Used for</b> = common / approved oncology indications for general reference, not the institution's regimen-specific protocol list. For a specific patient, confirm the FTC-approved regimen and protocol number for that diagnosis.</div>
    <div style="margin-top:8px"><b>General IV meds</b> chart transcribed from the KFSH&amp;RC Pharmaceutical Care Division "IV Medication Vial Reconstitution and Stability Chart" (last updated 21 Oct 2021). References: package inserts, EMC, Trissel, DailyMed, Micromedex, Lexicomp. Verify against current SDS before use.</div>
    <div class="credit">Compiled by <b>Abdulrhman Suleiman AlJuwaiser</b> — Pharmacist II</div>
  </footer>
</div>

<script>
// Compiled from photographed NIOSH hazard appendices (Set A) + Antineoplastic
// stability chart (Set B), Oct 2025 reference sheets.
// class: Antineoplastic | Non-antineoplastic
// risk:  High | Low | "—" (not individually listed in NIOSH appendix, e.g. mAbs)
window.MEDS = [
  {g:"Ado-Trastuzumab Emtansine",b:"Kadcyla",m:"Roche",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"100 mg",rdil:"SWFI",rvol:"5 ml",rconc:"20 mg/ml",vstab:"RT: use immediately; R: 24 hr",dil:"NS",dvol:"250 ml",fconc:"NA",dstab:"RT: use immediately; R: 24 hr",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Aldesleukin",b:"Proleukin",m:"Prometheus Labs",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"22 million IU",rdil:"SWFI",rvol:"1.2 ml",rconc:"18 million units/ml (1.1 mg/ml)",vstab:"RT: 48 hrs; R: 48 hrs (preferred)",dil:"D5W",dvol:"50 ml",fconc:"30–70 mcg/ml",dstab:"RT: 48 hrs; R: 48 hrs (preferred)",light:"Yes",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Arsenic Trioxide",b:"Arsenic trioxide",m:"Amring Pharma",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"10 mg/10 ml",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"RT: use immediately, discard unused portion",dil:"NS or D5W",dvol:"100 ml, 250 ml",fconc:"NA",dstab:"RT: 24 hrs; R: 48 hr",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Arsenic Trioxide",b:"Phenasen",m:"Phebra Pty Ltd",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"mg/10 ml",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"RT: after opening use immediately, discard unused portion",dil:"NS or D5W",dvol:"100 ml, 250 ml",fconc:"NA",dstab:"RT: use immediately; R: 24 hr",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Asparaginase (Erwinia)",b:"Erwinase",m:"Porton Biopharma",cls:"Antineoplastic",risk:"Low",vstore:"R",vsize:"10,000 units",rdil:"NS",rvol:"1–2 ml",rconc:"5000–10,000 units",vstab:"RT: use within 15 min of reconstitution, discard unused portion",dil:"NS",dvol:"100 ml",fconc:"NA",dstab:"RT: use within 4 hrs of reconstitution",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Asparaginase (E-coli)",b:"Kidrolase",m:"Jazz Pharmaceuticals",cls:"Antineoplastic",risk:"Low",vstore:"R",vsize:"10,000 units",rdil:"IM: NS, IV: SWFI",rvol:"IM: 2 ml, IV: 4 ml",rconc:"IM: 5000 units/ml, IV: 2500 units/ml",vstab:"RT: use within 3 hrs; R: 24 hr",dil:"NS or D5W",dvol:"50 to 250 mL",fconc:"NA",dstab:"RT: use immediately; R: 24 hr",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Asparaginase (E-coli)",b:"Leunase",m:"Kyowa Hakko Kirin",cls:"Antineoplastic",risk:"Low",vstore:"R",vsize:"10,000 units",rdil:"SWFI",rvol:"2 ml to 5 ml",rconc:"2000–5000 units",vstab:"RT: use immediately; R: 24 hr",dil:"NS or D5W",dvol:"200 ml–500 ml",fconc:"NA",dstab:"RT: use immediately; R: 24 hr",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Asparaginase (E-coli)",b:"Spectrila",m:"Medac",cls:"Antineoplastic",risk:"Low",vstore:"R",vsize:"10,000 units",rdil:"SWFI",rvol:"IV only: 3.7 mL",rconc:"2500 units/mL",vstab:"RT: 24 hrs; R: 2 days",dil:"NS",dvol:"50–250 mL",fconc:"NA",dstab:"RT: use immediately; R: 24 hr",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Atezolizumab",b:"Tecentriq",m:"Roche",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"1200 mg",rdil:"NA",rvol:"NA",rconc:"60 mg/mL",vstab:"Use immediately",dil:"NS",dvol:"250 mL",fconc:"NA",dstab:"RT: 24 hrs; R: no more than 24 hr",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Avelumab",b:"Bavencio",m:"Merck",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"200 mg",rdil:"NA",rvol:"NA",rconc:"20 mg/ml",vstab:"RT: < 4 hrs; R: 24 hrs",dil:"NS 0.9% or 0.45%",dvol:"250 ml",fconc:"NA",dstab:"RT: < 4 hrs; R: 24 hrs",light:"Yes",filter:"Yes",haz:"Yes",cstd:"Yes"},
  {g:"Azacitidine",b:"Vidaza",m:"Baxter Oncology",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"100 mg",rdil:"SWFI",rvol:"SC: 4 ml, IV: 10 ml",rconc:"SC: 25 mg/ml, IV: 10 mg/ml",vstab:"SC (25 mg/ml) RT: use immediately; R: 8 hrs and 22 hr if prepared with refrigerated SWFI. IV (10 mg/ml): 1 hour",dil:"NS / LR",dvol:"50 ml, 100 ml",fconc:"NA",dstab:"IV: 1 hour",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Azacitidine",b:"Azacitidine SPC",m:"Dr. Reddy's Lab",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"100 mg",rdil:"SWFI",rvol:"SC: 4 ml, IV: 10 ml",rconc:"SC: 25 mg/ml, IV: 10 mg/ml",vstab:"SC (25 mg/ml) RT: use immediately; R: 8 hrs and 22 hr if prepared with refrigerated SWFI. IV (10 mg/ml): 1 hour",dil:"NS / LR",dvol:"50 ml, 100 ml",fconc:"NA",dstab:"IV: 1 hour",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Bendamustine",b:"Ribomustin",m:"Astellas",cls:"Antineoplastic",risk:"Low",vstore:"RT",vsize:"25 mg, 100 mg",rdil:"SWFI",rvol:"10 ml for 25 mg vial, 40 ml for 100 mg vial",rconc:"2.5 mg/ml",vstab:"Use immediately",dil:"NS",dvol:"500 ml",fconc:"NA",dstab:"RT: 3.5 hours; R: 48 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Bevacizumab",b:"Avastin",m:"Roche",cls:"Antineoplastic",risk:"—",vstore:"RT",vsize:"100 mg, 400 mg",rdil:"NA",rvol:"NA",rconc:"25 mg/ml",vstab:"Discard any unused portion left in a vial",dil:"NS",dvol:"100 ml",fconc:"1.4–16.5 mg/ml",dstab:"RT: use immediately; R: 8 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Bevacizumab",b:"Mvasi",m:"Roche",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"100 mg, 400 mg",rdil:"NA",rvol:"NA",rconc:"25 mg/ml",vstab:"Discard any unused portion left in a vial",dil:"NS",dvol:"100 ml",fconc:"1.4–16.5 mg/ml",dstab:"RT: use immediately; R: 8 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Bleomycin",b:"Bleomycin",m:"Fresenius Kabi",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"15 units",rdil:"IM/SC: SWFI/NS; IV: NS; Intrapleural: NS",rvol:"IM/SC: 1 ml to 5 ml; IV: 5 ml to 10 ml; Intrapleural: 60 units in 50 to 100 ml",rconc:"IM/SC: 3–15 units/mL; IV: 1.5–3 units/mL; Intrapleural: 0.6–1.2 units/mL",vstab:"Stored in refrigerator above freezing point for up to 48 hours",dil:"NS",dvol:"50 ml, 100 ml",fconc:"NA",dstab:"RT: 24 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Blinatumomab",b:"Blincyto",m:"Amgen",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"35 mcg",rdil:"IV",rvol:"3 mL SWFI",rconc:"12.5 mcg/mL",vstab:"2 days without stabilizer solution; 8 days with stabilizer solution",dil:"NS",dvol:"275 mL",fconc:"NA",dstab:"2 days without stabilizer solution; 8 days with stabilizer solution",light:"No",filter:"No",haz:"Yes",cstd:"No"},
  {g:"Bortezomib",b:"Veelbore",m:"JPI",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"3.5 mg",rdil:"NS",rvol:"IV: 3.5 ml, SC: 1.4 ml",rconc:"IV: 1 mg/ml, SC: 2.5 mg/ml",vstab:"Use within 8 hrs",dil:"NS",dvol:"NA",fconc:"NA",dstab:"NA",light:"No",filter:"No",haz:"Yes",cstd:"IV push: Yes"},
  {g:"Bortezomib",b:"Velcade",m:"Millennium",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"3.5 mg",rdil:"NS",rvol:"IV: 3.5 ml, SC: 1.4 ml",rconc:"IV: 1 mg/ml, SC: 2.5 mg/ml",vstab:"Use within 8 hrs",dil:"NS",dvol:"NA",fconc:"NA",dstab:"NA",light:"Yes",filter:"No",haz:"Yes",cstd:"IV push: Yes"},
  {g:"Bortezomib",b:"Bortezomib SPC",m:"Dr. Reddy's Lab",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"3.5 mg",rdil:"NS",rvol:"IV: 3.5 ml, SC: 1.4 ml",rconc:"IV: 1 mg/ml, SC: 2.5 mg/ml",vstab:"Use within 8 hrs",dil:"NS",dvol:"NA",fconc:"NA",dstab:"NA",light:"Yes",filter:"No",haz:"Yes",cstd:"IV push: Yes"},
  {g:"Brentuximab Vedotin",b:"Adcetris",m:"BSP Pharmaceutical",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"50 mg",rdil:"SWFI",rvol:"10.5 ml",rconc:"5 mg/ml",vstab:"RT: use immediately; R: 24 hr",dil:"NS or D5W or LR",dvol:"at least 100 ml",fconc:"0.4 to 1.2 mg/ml",dstab:"RT: use immediately; R: 24 hr from reconstitution",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Busulfan",b:"Busulcan",m:"Pharmascience",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"60 mg",rdil:"NA",rvol:"NA",rconc:"6 mg/ml",vstab:"Discard any unused portion left in a vial",dil:"NS or D5W",dvol:"Dilution volume should be 10 times the volume of busulfan injection",fconc:"0.5 mg/ml",dstab:"RT: 8 hrs; R: 12 hr",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Busulfan",b:"Busilvex",m:"Pierre Fabre",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"60 mg",rdil:"NA",rvol:"NA",rconc:"6 mg/ml",vstab:"Discard any unused portion left in a vial",dil:"NS or D5W",dvol:"Dilution volume should be 10 times the volume of busulfan injection",fconc:"0.5 mg/ml",dstab:"RT: 8 hrs; R: 12 hr",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Cabazitaxel",b:"Jevtana",m:"Sanofi",cls:"Antineoplastic",risk:"Low",vstore:"RT",vsize:"60 mg",rdil:"Diluent given by company",rvol:"4.5 ml",rconc:"10 mg/ml",vstab:"RT: 1 hr; R: NA",dil:"NS or D5W",dvol:"250 ml",fconc:"0.1 mg/ml–0.26 mg/ml",dstab:"RT: 8 HRS; R: 48 HRS",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Capecitabine — see oral list",b:"—",m:"—",cls:"Antineoplastic",risk:"Low",vstore:"—",vsize:"—",rdil:"—",rvol:"—",rconc:"—",vstab:"Oral agent (tablet) — not on injectable stability chart",dil:"—",dvol:"—",fconc:"—",dstab:"—",light:"—",filter:"—",haz:"Yes",cstd:"—"},
  {g:"Carboplatin",b:"Carboplatin",m:"Ebewe",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"450 mg",rdil:"NA",rvol:"NA",rconc:"10 mg/ml",vstab:"Discard unused portion",dil:"D5W",dvol:"250 ml, 500 ml",fconc:"up to 0.5 mg/ml",dstab:"RT: 24 hrs; R: 24 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Carboplatin",b:"Carboplatin",m:"Fresenius Kabi",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"150 mg",rdil:"NA",rvol:"NA",rconc:"10 mg/ml",vstab:"Discard unused portion",dil:"NS or D5W",dvol:"250 ml, 500 ml",fconc:"diluted to concentrations as low as 0.5 mg/ml",dstab:"RT: 8 HRS; R: NA",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Carboplatin",b:"Carboplatin",m:"Accord",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"150 mg, 450 mg",rdil:"NA",rvol:"NA",rconc:"10 mg/ml",vstab:"Discard unused portion",dil:"NS or D5W",dvol:"250 ml, 500 ml",fconc:"diluted to concentrations as low as 0.5 mg/ml",dstab:"RT: 24 hrs; R: 30 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Carfilzomib",b:"Kyprolis",m:"Amgen",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"60 mg",rdil:"SWFI",rvol:"29 ml",rconc:"2 mg/ml",vstab:"RT: 4 hrs; R: 24 hrs",dil:"D5W",dvol:"50 ml or 100 ml",fconc:"NA",dstab:"RT: 4 hrs; R: 24 hrs",light:"No",filter:"—",haz:"Yes",cstd:"Yes"},
  {g:"Carmustine",b:"BiCNU",m:"Heritage",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"100 mg",rdil:"SWFI — 3 ml sterile diluent (Dehydrated Alcohol) supplied from company, then add 27 ml",rvol:"30 ml total",rconc:"3.3 mg/ml",vstab:"RT: NA; R: 24 hrs",dil:"NS or D5W",dvol:"500 ml",fconc:"Diluted to concentration of 0.2 mg/ml",dstab:"RT: 8 HRS; R: 24 HRS",light:"Yes",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Cetuximab",b:"Erbitux",m:"Merck",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"500 mg, 100 mg",rdil:"NA",rvol:"NA",rconc:"5 mg/ml",vstab:"Discard unused portion",dil:"NS or D5W",dvol:"Given undiluted",fconc:"5 mg/ml",dstab:"RT: 48 hrs at 25 C",light:"No",filter:"No",haz:"No",cstd:"No"},
  {g:"Cisplatin",b:"Cisplatin",m:"Ebewe",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"10, 25, 50, 100 mg",rdil:"NA",rvol:"NA",rconc:"0.5 mg/ml, 1 mg/ml",vstab:"Discard unused portion",dil:"NS 0.9% or 0.45% and Dextrose 2.5%",dvol:"20 ml, 50 ml, 100 ml",fconc:"NA",dstab:"28 days if refrigerated and protected from light or at RT",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Cisplatin",b:"Cisplatin",m:"Accord",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"50 mg",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"RT: 28 days protected from light, 7 days under fluorescent room light",dil:"NS, don't use D5W",dvol:"500 ml–1000 ml",fconc:"NA",dstab:"RT: 24 hrs; R: do not refrigerate",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Cladribine",b:"Cladribine",m:"Hikma",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"10 mg",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"Discard unused portion",dil:"NS, don't use D5W",dvol:"500 ml",fconc:"NA",dstab:"RT: 24 hrs; R: <8 hrs prior to start administration",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Cladribine",b:"Cladribine",m:"Fresenius Kabi",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"10 mg",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"Discard unused portion",dil:"NS, don't use D5W",dvol:"500 ml",fconc:"NA",dstab:"RT: 24 hrs; R: no more than 8 hrs prior to start administration",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Clofarabine",b:"Evoltra",m:"Sanofi",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"20 mg",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"Discard unused portion",dil:"NS or D5W",dvol:"500 ml",fconc:"Diluted to a final concentration of 0.15 to 0.4 mg/ml",dstab:"RT: 24 hrs; R: 24 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Cyclophosphamide",b:"Endoxan",m:"Baxter",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"500 mg, 1000 mg",rdil:"SWFI, NS",rvol:"25 ml for 500 mg, 50 ml for 1000 mg",rconc:"20 mg/ml",vstab:"SWFI RT: use immediately; R: 24hrs. NS: RT 24 hrs; R: 6 days",dil:"NS or D5W",dvol:"Further dilute to a minimum concentration of 2 mg/ml",fconc:"30 min – 2 hrs",dstab:"Dilute in NS: RT 24 hrs; R 6 days. Dilute in D5: RT 24 hrs; R 36 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Cytarabine",b:"Alexan",m:"Ebewe",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"100 mg, 2000 mg",rdil:"NA",rvol:"NA",rconc:"20 mg/ml – 50 mg/ml",vstab:"24 hr",dil:"NS or D5W",dvol:"250 ml–1000 ml",fconc:"0.2–3.2 mg/ml",dstab:"RT: 24 hrs; R: 4 days",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Cytarabine",b:"Cytarabine",m:"Fresenius Kabi",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"2000 mg",rdil:"NA",rvol:"NA",rconc:"100 mg/mL",vstab:"24 hrs",dil:"NS or D5W",dvol:"250 ml–1000 ml",fconc:"0.2–3.2 mg/ml",dstab:"192 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Dacarbazine",b:"Dacarbazine medac",m:"Medac GmBH",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"100 mg, 200 mg",rdil:"SWFI",rvol:"10 ml for 100 mg, 20 ml for 200 mg",rconc:"10 mg/ml",vstab:"RT: 24 hr; R: 24 hr",dil:"NS or D5W",dvol:"500 ml",fconc:"NA",dstab:"RT: 24 hrs; R: 24 hrs",light:"Yes",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Dactinomycin (Actinomycin D)",b:"Cosmegen (Lyovac)",m:"Recordati Rare Diseases",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"500 mcg",rdil:"SWFI",rvol:"1.1 ml preservative free",rconc:"500 mcg/ml",vstab:"Discard unused portion",dil:"NS or D5W",dvol:"D5W or NS recommended concentration of >10 mcg/ml",fconc:"D5W or NS recommended concentration of >10 mcg/ml",dstab:"RT: 4hrs; R: 4hrs",light:"Yes",filter:"No",haz:"Yes",cstd:"—"},
  {g:"Daunorubicin",b:"CERUBIDINI",m:"Sanofi",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"20 mg",rdil:"SWFI",rvol:"4 ml",rconc:"5 mg/ml",vstab:"RT: 24 hr; R: 48 hr",dil:"NS or D5W",dvol:"100 ml",fconc:"NA",dstab:"RT: 24 hr; R: 48hr",light:"Yes",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Daunorubicin",b:"Daunorubicin",m:"Thmoorgan Pharmazie (Hikma)",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"20 mg",rdil:"NA",rvol:"4 ml",rconc:"5 mg/ml",vstab:"Discard unused portion",dil:"NS or D5W",dvol:"100 ml",fconc:"NA",dstab:"RT: 24 hrs",light:"Yes",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Dinutuximab",b:"Qarziba",m:"EUSA Pharma",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"20 mg",rdil:"NA",rvol:"NA",rconc:"4.5 mg/ml",vstab:"Discard unused portion",dil:"NS for infusion containing 1% human albumin",dvol:"NA",fconc:"NA",dstab:"RT: immediate; R: 24",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Docetaxel",b:"Taxotere",m:"Sanofi",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"80 mg",rdil:"NA",rvol:"NA",rconc:"20 mg/ml",vstab:"Use immediately",dil:"NS or D5W",dvol:"< 190 mg: 250 mL; > 190 mg: 500 mL",fconc:"≤ 0.74 mg/mL",dstab:"RT: 6 hrs; R: 48 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Docetaxel",b:"Docetaxel SPC",m:"Dr. Reddy's Lab",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"80 mg",rdil:"NA",rvol:"NA",rconc:"20 mg/ml",vstab:"Use immediately",dil:"NS or D5W",dvol:"< 190 mg: 250 mL; > 190 mg: 500 mL",fconc:"≤ 0.74 mg/mL",dstab:"RT: 6 hrs; R: 48 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Doxorubicin",b:"Doxorubicin Ebewe",m:"Ebewe Pharma",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"50 mg",rdil:"NA",rvol:"NA",rconc:"2 mg/ml",vstab:"R: 24 hrs",dil:"Undiluted (IV push) NS/D5W",dvol:"50–1000 mL",fconc:"NA",dstab:"R: 24 hrs",light:"Yes",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Doxorubicin",b:"Adrim",m:"Fresenius Kabi",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"50 mg",rdil:"NA",rvol:"NA",rconc:"2 mg/ml",vstab:"R: 24 hrs",dil:"Undiluted (IV push) NS/D5W",dvol:"50–1000 mL",fconc:"NA",dstab:"R: 24 hrs",light:"Yes",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Doxorubicin (Liposomal)",b:"Caelyx",m:"Janssen",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"20 mg",rdil:"NA",rvol:"NA",rconc:"2 mg/ml",vstab:"Use immediately",dil:"D5W",dvol:"≤ 90 mg: 250 mL; > 90 mg: 500 mL",fconc:"NA",dstab:"R: 24 hrs; RT: NA",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Doxorubicin (Liposomal)",b:"Doxorubicin (Liposomal)",m:"Dr. Reddy's Lab",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"50 mg",rdil:"NA",rvol:"NA",rconc:"2 mg/ml",vstab:"Discard unused portion",dil:"D5W",dvol:"≤ 90 mg: 250 mL; > 90 mg: 500 mL",fconc:"NA",dstab:"R: 24 hrs; RT: NA",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Durvalumab",b:"Imfinzi",m:"Astrazeneca",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"500 mg",rdil:"NA",rvol:"NA",rconc:"50 mg/ml",vstab:"Discard unused portion",dil:"NS, D5W",dvol:"100–500 ml",fconc:"1–15 mg/ml",dstab:"R: 24 hrs; RT: 8 hrs",light:"No",filter:"Yes",haz:"No",cstd:"Yes"},
  {g:"Enfortumab Vedotin",b:"Padcev",m:"Astellas Pharma",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"30 mg",rdil:"SWFI",rvol:"3.3 mL",rconc:"10 mg/mL",vstab:"R: 4hrs",dil:"NS or D5W",dvol:"0.3–4 mg/mL",fconc:"3–4 mg/ml",dstab:"R: 8 hrs",light:"No",filter:"No",haz:"Yes",cstd:"—"},
  {g:"Epirubicin",b:"Epirubicin Ebewe",m:"Ebewe Pharma",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"50 mg",rdil:"NA",rvol:"NA",rconc:"2 mg/ml",vstab:"R: 24 hrs; RT: NA",dil:"Undiluted (IV push) NS/D5W",dvol:"NA",fconc:"NA",dstab:"R: 24 hrs; RT: NA",light:"Yes",filter:"No",haz:"Yes",cstd:"—"},
  {g:"Eribulin",b:"Halaven",m:"BSP Pharmaceutical",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"0.88 mg/2 mL",rdil:"NA",rvol:"NA",rconc:"0.44 mg/ml",vstab:"R: 24 hrs; RT: 4 hrs",dil:"Undiluted (IV push) NS",dvol:"100 mL",fconc:"NA",dstab:"R: 24 hrs; RT: 4 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Etoposide",b:"Etoposid Ebewe",m:"Ebewe Pharma",cls:"Antineoplastic",risk:"Low",vstore:"RT",vsize:"100 mg",rdil:"NA",rvol:"NA",rconc:"20 mg/ml",vstab:"NA",dil:"NS & D5W (non-PVC)",dvol:"100–500 mL",fconc:"0.2–0.4 mg/mL",dstab:"RT: 24 hrs; R: 24 hrs (Yes for conc. > 0.4 mg/ml)",light:"Yes",filter:"Yes",haz:"Yes",cstd:"—"},
  {g:"Etoposide Phosphate",b:"Etopophos",m:"Cheplapharm",cls:"Antineoplastic",risk:"Low",vstore:"R",vsize:"100 mg",rdil:"SWFI, NS or D5W",rvol:"10 ml",rconc:"10 mg/mL",vstab:"R: 7 days; RT: 24 hrs",dil:"NS, D5W",dvol:"Undiluted (in glass bottle) may further dilute to 50 mL to 500 mL",fconc:"As low as 0.1 mg/mL",dstab:"R: 24 hrs; RT: 24 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Etoposide Phosphate",b:"Etopophos",m:"Bristol-Myers Squibb",cls:"Antineoplastic",risk:"Low",vstore:"R",vsize:"100 mg",rdil:"SWFI, NS or D5W",rvol:"10 ml",rconc:"10 mg/mL",vstab:"R: 7 days; RT: 24 hrs",dil:"NS, D5W",dvol:"Undiluted (in glass bottle) may further dilute to 50 mL to 500 mL",fconc:"As low as 0.1 mg/mL",dstab:"R: 24 hrs; RT: 24 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Fludarabine",b:"Fludara",m:"Genzyme (Sanofi)",cls:"Antineoplastic",risk:"High",vstore:"R or RT",vsize:"50 mg",rdil:"SWFI",rvol:"2 ml",rconc:"25 mg/ml",vstab:"R: 24 hrs; RT: 8 hrs",dil:"NS, D5W",dvol:"100–125 mL",fconc:"NA",dstab:"R: 24 hrs; RT: 8 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Fluorouracil (5-FU)",b:"5-Fluorouracil Ebewe",m:"Ebewe Pharma",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"1000 mg",rdil:"NA",rvol:"NA",rconc:"50 mg/ml",vstab:"Use immediately (4 hr)",dil:"IV push: undiluted. IV infusion: NS or D5W",dvol:"NA",fconc:"NA",dstab:"Depends on conc: 0.35 mg/ml–15 mg/ml + protect from light: 28 days RT; Other conc: 24 hr; Infusion Pump: 7 days at RT",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Gemcitabine",b:"Gemcitabine",m:"Athenex",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"200 mg, 1000 mg",rdil:"NS",rvol:"5 ml, 25 ml",rconc:"38 mg/ml",vstab:"R: Do not refrigerate; RT: 24 hr",dil:"NS",dvol:"NA",fconc:"Min: 0.1 mg/ml",dstab:"R: Do not refrigerate; RT: 24 hr",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Gemcitabine",b:"Gemcitabine",m:"Ebewe",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"1000 mg",rdil:"NA",rvol:"NA",rconc:"10 mg/ml",vstab:"NA",dil:"NS, D5W",dvol:"NA",fconc:"Min 0.1 mg/ml, Max 7.5 mg/ml",dstab:"R: Do not refrigerate; RT: 24 hr",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Gemcitabine",b:"Gemzar",m:"Lilly",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"200 mg",rdil:"NS",rvol:"5 ml",rconc:"38 mg/ml",vstab:"R: Do not refrigerate; RT: 24 hr",dil:"NS, D5W",dvol:"NA",fconc:"NA",dstab:"R: Do not refrigerate; RT: 24 hr",light:"No",filter:"Yes",haz:"Yes",cstd:"—"},
  {g:"Gemcitabine",b:"Gemcitabine",m:"Jazeera",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"200 mg, 1000 mg",rdil:"NS",rvol:"5 ml",rconc:"38 mg/ml",vstab:"R: Do not refrigerate; RT: 24 hr",dil:"NS, D5W",dvol:"NA",fconc:"NA",dstab:"R: Do not refrigerate; RT: 24 hr",light:"No",filter:"Yes",haz:"Yes",cstd:"—"},
  {g:"Gemcitabine",b:"Citabol",m:"Venus",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"200 mg, 1000 mg",rdil:"NS",rvol:"5 ml, 25 ml",rconc:"40 mg/ml",vstab:"R: Do not refrigerate; RT: 24 hr",dil:"NS, D5W",dvol:"NA",fconc:"NA",dstab:"R: Do not refrigerate; RT: 24 hr",light:"No",filter:"Yes",haz:"Yes",cstd:"—"},
  {g:"Gemtuzumab Ozogamicin",b:"Mylotarg",m:"Pfizer",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"4.5 mg",rdil:"SWFI",rvol:"5 mL, vial should stand for 5 min before reconstitution",rconc:"1 mg/ml",vstab:"R: 1 hr, protect from light & do not freeze",dil:"NS",dvol:"NA",fconc:"0.075–0.234 mg/ml. Doses < 3.9 mg prep in syringe with NS 0.9% & doses ≥ 3.9 mg diluted in a syringe or bag with NS 0.9%",dstab:"RT: 6 hrs; R: 12 hrs (includes 2 hrs infusion time & 1 hr to allow the refrigerated solution to equilibrate to RT)",light:"Yes",filter:"Yes",haz:"Yes",cstd:"Yes"},
  {g:"Idarubicin",b:"Zavedos",m:"Pfizer Australia",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"10 mg",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"R: 48 hrs; RT: 24 hrs",dil:"NS, D5W",dvol:"NA",fconc:"NA",dstab:"NA",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Idarubicin",b:"Idamycin PFS",m:"Pfizer USA",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"10 mg",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"NA",dil:"NS, D5W",dvol:"NA",fconc:"NA",dstab:"NA",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Ifosfamide",b:"Holoxan",m:"Baxter",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"2000 mg",rdil:"SWFI",rvol:"50 mL",rconc:"40 mg/mL",vstab:"R: 24 hrs",dil:"NS, D5W",dvol:"50–1000 mL",fconc:"0.6 to 20 mg/mL",dstab:"R: 24 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Inotuzumab Ozogamicin",b:"Besponsa",m:"Pfizer",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"0.9 mg",rdil:"SWFI",rvol:"4 mL",rconc:"0.25 mg/ml",vstab:"Use immediately or 4 hrs in refrigerator",dil:"NS",dvol:"50 mL",fconc:"NA",dstab:"Room temp and refrigerator 8 hrs",light:"Yes",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Ipilimumab",b:"Yervoy",m:"Baxter",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"50 mg",rdil:"NA",rvol:"NA",rconc:"5 mg/mL",vstab:"Discard unused portion",dil:"NS, D5W",dvol:"NA",fconc:"1–2 mg/mL",dstab:"Room temp and refrigerator 24 hrs",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Irinotecan",b:"Irinotel",m:"Fresenius Kabi",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"100 mg",rdil:"NA",rvol:"NA",rconc:"20 mg/ml",vstab:"RT: 24 hrs in ambient light",dil:"D5W (preferred), NS (may precipitate if refrigerated)",dvol:"NA",fconc:"0.12–1.1 mg/mL",dstab:"R: 48 hrs (when protected from light & placed in D5W); RT: 6 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"Yes/No"},
  {g:"Melphalan",b:"Alkeran",m:"Aspen",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"50 mg",rdil:"Diluent given by company",rvol:"10 ml",rconc:"5 mg/ml",vstab:"Use immediately, within 1 hour",dil:"NS",dvol:"NA",fconc:"≤ 0.45 mg/ml",dstab:"R: NA; RT: 1 hr",light:"No",filter:"Yes",haz:"Yes",cstd:"—"},
  {g:"Melphalan",b:"Megval",m:"Emcure Pharm Ltd",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"50 mg",rdil:"Diluent given by company",rvol:"10 ml",rconc:"5 mg/ml",vstab:"Use immediately, within 1 hour",dil:"NS",dvol:"NA",fconc:"≤ 0.45 mg/ml",dstab:"R: NA; RT: 1 hr",light:"No",filter:"Yes",haz:"Yes",cstd:"—"},
  {g:"Methotrexate",b:"Methotrexate",m:"Ebewe",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"5000 mg",rdil:"NA",rvol:"NA",rconc:"100 mg/ml",vstab:"NA",dil:"IT: preservative-free NS; IV: NS, D5W",dvol:"IT: up to 6 mL; IV: NA",fconc:"NA",dstab:"Intrathecal: 6 hr; Intramuscular: 7 IV; R/NA; RT: 24 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Mitomycin",b:"Mitocin",m:"Substipharm Ltd",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"20 mg",rdil:"SWFI",rvol:"40 ml",rconc:"0.5 mg/ml",vstab:"R: 14 days; RT: 7 days (protect from light)",dil:"NS",dvol:"NA",fconc:"20–40 mcg/mL",dstab:"R: NA; RT: 12 hrs NS",light:"No",filter:"Yes",haz:"Yes",cstd:"Yes"},
  {g:"Mitomycin",b:"Mitomycin",m:"Accord",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"20 mg, 40 mg",rdil:"SWFI",rvol:"40 ml, 80 ml",rconc:"0.5 mg/ml",vstab:"R: 14 days; RT: 7 days (protect from light)",dil:"NS",dvol:"NA",fconc:"20–40 mcg/mL",dstab:"R: NA; RT: 12 hrs NS",light:"No",filter:"Yes",haz:"Yes",cstd:"Yes"},
  {g:"Mitoxantrone",b:"Mitoxanthron",m:"Ebewe",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"20 mg",rdil:"NA",rvol:"NA",rconc:"2 mg/ml",vstab:"NA",dil:"NS or D5W",dvol:"at least 50 ml",fconc:"NA",dstab:"RT: 24 hrs",light:"NA",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Mitoxantrone",b:"Mitoxanthron",m:"Sandoz-Ebewe",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"10 mg, 20 mg",rdil:"SWFI",rvol:"5 ml, 10 ml",rconc:"2 mg/ml",vstab:"NA",dil:"NS or D5W",dvol:"at least 50 ml",fconc:"NA",dstab:"R: 24 hrs; RT: NA (will maintain potency for 72 hrs after prep)",light:"NA",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Nivolumab",b:"OPDIVO",m:"Bristol-Myers Squibb",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"100 mg, 40 mg",rdil:"NA",rvol:"NA",rconc:"10 mg/ml",vstab:"NA",dil:"NS or D5W",dvol:"must not exceed 160 mL",fconc:"1–10 mg/ml",dstab:"RT: 8 hrs; R: 7 days",light:"Yes",filter:"No",haz:"No",cstd:"No"},
  {g:"Oxaliplatin",b:"Eloxatin",m:"Sanofi",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"100 mg, 50 mg",rdil:"NA",rvol:"NA",rconc:"5 mg/ml",vstab:"NA",dil:"D5W",dvol:"250 ml to 500 ml",fconc:"NA",dstab:"RT: 24 hrs; R: 48 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Oxaliplatin",b:"Oxaliplatin",m:"Accord",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"50 mg",rdil:"NA",rvol:"NA",rconc:"5 mg/ml",vstab:"NA",dil:"D5W",dvol:"250 ml to 500 ml",fconc:"0.2–2 mg/ml",dstab:"RT: 24 hrs; R: 48 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Oxaliplatin",b:"Oxaliplatin",m:"Ebewe",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"50 mg, 100 mg",rdil:"NA",rvol:"NA",rconc:"5 mg/mL",vstab:"R: 24 hr",dil:"D5W",dvol:"250 ml to 500 ml",fconc:"0.2 mg/ml–0.7 mg/ml",dstab:"RT: 6 hrs; R: 24 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Oxaliplatin",b:"Xaliptine",m:"Hexal",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"50 mg, 100 mg",rdil:"NA",rvol:"NA",rconc:"5 mg/mL",vstab:"R: 24 hr",dil:"D5W",dvol:"250 ml to 500 ml",fconc:"0.2 mg/ml–2 mg/ml",dstab:"RT: 6 hrs; R: 48 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Oxaliplatin",b:"Batipan",m:"Tadawi Biomedical",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"50 mg, 100 mg",rdil:"SWFI, D5W",rvol:"10 ml, 20 ml",rconc:"5 mg/mL",vstab:"R: 24 hr",dil:"D5W",dvol:"250 ml to 500 ml",fconc:"0.2 mg/ml–0.7 mg/ml",dstab:"R: 24 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Paclitaxel",b:"Paclitaxel",m:"Hospira",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"100 mg",rdil:"NA",rvol:"NA",rconc:"6 mg/ml",vstab:"NA",dil:"NS (non-PVC), D5W (non-PVC)",dvol:"NA",fconc:"0.3–12 mg/ml",dstab:"R: NA; RT: 27 hrs",light:"Yes",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Paclitaxel",b:"Ebetaxel",m:"Ebewe",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"30 mg",rdil:"NA",rvol:"NA",rconc:"6 mg/ml",vstab:"NA",dil:"NS (non-PVC), D5W (non-PVC)",dvol:"NA",fconc:"0.3–1.2 mg/ml",dstab:"R: NA; RT: 48 hrs",light:"Yes",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Paclitaxel",b:"Intaxel",m:"Fresenius Kabi",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"30 mg, 100 mg",rdil:"NA",rvol:"NA",rconc:"6 mg/ml",vstab:"NA",dil:"NS (non-PVC), D5W (non-PVC)",dvol:"NA",fconc:"0.3–1.2 mg/ml",dstab:"R: NA; RT: 27 hr",light:"Yes",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Pegaspargase",b:"Oncaspar",m:"Servier",cls:"Antineoplastic",risk:"Low",vstore:"R",vsize:"3750 units",rdil:"SWFI",rvol:"5.2 ml (don't shake)",rconc:"750 mg/ml",vstab:"Use immediately or within 24 hrs when stored below 25",dil:"IV only: NS or D5W",dvol:"IV: 100 ml; IM: volume max 2 ml/syr in children and 3 ml/syr for adults",fconc:"NA",dstab:"R: 48 hrs; RT: use immediately",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Pemetrexed",b:"Alimta",m:"Lilly",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"500 mg",rdil:"NS",rvol:"20 ml",rconc:"25 mg/ml",vstab:"R: 24 hrs; RT: 24 hrs",dil:"NS",dvol:"100 ml",fconc:"NA",dstab:"R: 24 hrs; RT: 24 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Pemetrexed",b:"Pemitra",m:"JPI",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"500 mg",rdil:"NS",rvol:"21 ml",rconc:"26 mg/ml",vstab:"R: 24 hrs; RT: NA",dil:"NS",dvol:"101 ml",fconc:"NA",dstab:"R: 24 hrs; RT: NA",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Pemetrexed",b:"Almetra",m:"MS Pharma",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"500 mg",rdil:"NS",rvol:"20 ml",rconc:"25 mg/ml",vstab:"R: 24 hrs; RT: NA",dil:"NS",dvol:"100 ml",fconc:"NA",dstab:"R: 24 hrs; RT: NA",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Pemetrexed",b:"Pemetrexed SPC",m:"SPC",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"500 mg",rdil:"NS",rvol:"20 ml",rconc:"25 mg/ml",vstab:"R: 24 hrs; RT: NA",dil:"NS",dvol:"100 ml",fconc:"NA",dstab:"R: 24 hrs; RT: NA",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Pembrolizumab",b:"Keytruda",m:"MSD",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"100 mg",rdil:"NA",rvol:"NA",rconc:"25 mg/ml",vstab:"R: 90 hrs, RT: 6hrs",dil:"NS or D5W",dvol:"NA",fconc:"1–10 mg/ml",dstab:"R: 90 hrs; RT: 6hrs",light:"Yes",filter:"Yes",haz:"No",cstd:"No"},
  {g:"Pertuzumab",b:"Perjeta",m:"Roche",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"420 mg/14 ml",rdil:"NA",rvol:"NA",rconc:"30 mg/ml",vstab:"Discard unused portion",dil:"NS",dvol:"250 ml",fconc:"1.6 mg/ml–3 mg/ml",dstab:"RT: immediate; R: 24 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Ramucirumab",b:"Cyramza",m:"Eli Lilly",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"500 mg, 100 mg",rdil:"NA",rvol:"NA",rconc:"10 mg/mL",vstab:"Discard unused portion",dil:"NS",dvol:"250 mL",fconc:"NA",dstab:"R: 24 hrs; RT: 4 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"Yes"},
  {g:"Rituximab",b:"Truxima",m:"JPI",cls:"Antineoplastic",risk:"—",vstore:"R (protect from light)",vsize:"100 mg, 500 mg",rdil:"NA",rvol:"NA",rconc:"10 mg/ml",vstab:"R: 24hrs; RT: 24 hrs after ref for 24hrs",dil:"NS or D5W",dvol:"NA",fconc:"1 mg/ml–4 mg/ml",dstab:"R: 24hrs; RT: 24 hrs after ref for 24 hrs",light:"No",filter:"Yes",haz:"No",cstd:"No"},
  {g:"Sacituzumab Govitecan",b:"Trodelvy",m:"Immunomedics",cls:"Antineoplastic",risk:"Low",vstore:"R",vsize:"180 mg",rdil:"NS 0.9%",rvol:"20 ml (don't shake and allow to stand for 15 min)",rconc:"10 mg/ml",vstab:"R: 4 hrs (protect from light)",dil:"NS",dvol:"NS < 500 ml",fconc:"1.1 mg/ml–3.4 mg/ml",dstab:"R: 4 hrs (protect from light, do not shake or freeze)",light:"No",filter:"No",haz:"Yes",cstd:"Yes"},
  {g:"Teniposide",b:"Vumon",m:"Bristol-Myers",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"50 mg",rdil:"NA",rvol:"NA",rconc:"10 mg/ml",vstab:"Discard unused portion",dil:"NS or D5W (non-PVC + non-DEHP bags)",dvol:"NA",fconc:"0.1 mg/mL, 0.2 mg/mL, 0.4 mg/mL or 1 mg/mL",dstab:"RT if conc 0.1–0.4 mg/mL: 24 hrs; RT if conc 1 mg/mL: complete administration within 4 h of preparation",light:"No",filter:"No",haz:"Yes",cstd:"No"},
  {g:"Thiotepa",b:"Tepadina",m:"Rimser",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"15 mg, 100 mg",rdil:"SWFI",rvol:"10 ml",rconc:"10 mg/ml",vstab:"RT: immediate; R: 8 hrs",dil:"NS",dvol:"500 mL NS (1,000 mL NS if dose > 500 mg). If dose < 250 mg, dilute in appropriate volume of NS to achieve final conc",fconc:"0.5 to 1 mg/mL",dstab:"RT: 4 hrs; R: 24 hrs",light:"Yes",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Topotecan",b:"Hycamtin",m:"Novartis",cls:"Antineoplastic",risk:"High",vstore:"RT",vsize:"4 mg",rdil:"SWFI",rvol:"4 ml",rconc:"1 mg/ml",vstab:"RT: immediate; R: 24 hrs",dil:"NS or D5W",dvol:"NA",fconc:"25 mcg/ml–50 mcg/ml",dstab:"RT: 12 hrs; R: 24 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Topotecan",b:"Topotecan",m:"Hospira",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"4 mg",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"R + protected from light",dil:"NS or D5W",dvol:"NA",fconc:"25 mcg/ml–50 mcg/ml",dstab:"RT: 24 hrs at ambient lighting conditions",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Trastuzumab",b:"Herzuma",m:"PSI",cls:"Antineoplastic",risk:"—",vstore:"R",vsize:"440 mg",rdil:"SWFI",rvol:"20 ml",rconc:"21 mg/ml",vstab:"RT: NA; R: 48 hrs",dil:"NS",dvol:"250 ml",fconc:"NA",dstab:"R: 24 hrs; RT: 24 hrs",light:"No",filter:"Yes",haz:"Yes",cstd:"No"},
  {g:"Treosulfan",b:"Trecondi",m:"Medac",cls:"Antineoplastic",risk:"High",vstore:"R or RT",vsize:"1 g, 5 g",rdil:"Pre-warmed NS 0.45% to 25–30 C",rvol:"20 ml, 100 ml",rconc:"50 mg/ml",vstab:"RT: 3 days",dil:"undiluted",dvol:"NA",fconc:"50 mg/ml",dstab:"RT: 3 days, do not refrigerate",light:"No",filter:"No",haz:"Yes",cstd:"No"},
  {g:"Vinblastine",b:"Vinblastine",m:"Hospira",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"10 mg",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"Use immediately",dil:"NS or D5W",dvol:"25–50 ml. Dilution in larger volumes (≥100 mL) not recommended",fconc:"NA",dstab:"Conc. dependent",light:"No",filter:"Yes",haz:"Yes",cstd:"Yes"},
  {g:"Vinblastine",b:"Vinblastine",m:"Fresenius Kabi",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"10 mg",rdil:"NA",rvol:"NA",rconc:"1 mg/ml",vstab:"Use immediately",dil:"NS or D5W",dvol:"25–50 ml. Dilution in larger volumes (≥100 mL) not recommended",fconc:"NA",dstab:"NA",light:"No",filter:"Yes",haz:"Yes",cstd:"Yes"},
  {g:"Vincristine",b:"Vincristine",m:"Hospira",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"1 mg, 2 mg",rdil:"NA",rvol:"NA",rconc:"1 mg/mL",vstab:"Use immediately",dil:"NS",dvol:"25–50 mL",fconc:"NA",dstab:"RT: 24 hrs if protected from light, or 8 hrs under normal light",light:"No",filter:"Yes",haz:"Yes",cstd:"Yes"},
  {g:"Vinorelbine",b:"Navelbine",m:"Pierre Fabre",cls:"Antineoplastic",risk:"High",vstore:"R",vsize:"50 mg, 100 mg",rdil:"NA",rvol:"NA",rconc:"10 mg/ml",vstab:"Use immediately",dil:"NS or D5W",dvol:"25–50 mL",fconc:"NA",dstab:"RT + not protected from light: 24 hrs; R/RT + protected from light: 8 days",light:"No",filter:"Yes",haz:"Yes",cstd:"No/Yes"},
  {g:"Ganciclovir",b:"Ganciclovir",m:"Sagent",cls:"Non-antineoplastic",risk:"High",vstore:"RT",vsize:"500 mg",rdil:"SWFI",rvol:"10 ml",rconc:"50 mg/ml",vstab:"Use immediately",dil:"NS or D5W",dvol:"100 ml",fconc:"NA",dstab:"Diluted infusion should be refrigerated, do not freeze and used within 24 hrs",light:"No",filter:"Yes",haz:"No",cstd:"No"},
  {g:"Ganciclovir",b:"Cymevene",m:"Cheplapharm",cls:"Non-antineoplastic",risk:"High",vstore:"RT",vsize:"500 mg",rdil:"SWFI",rvol:"10 ml",rconc:"50 mg/ml",vstab:"Use immediately",dil:"NS or D5W",dvol:"100 ml",fconc:"< 10 mg/ml",dstab:"Diluted infusion should be refrigerated, do not freeze and used within 24 hrs",light:"No",filter:"Yes",haz:"No",cstd:"No"},
  {g:"Ganciclovir",b:"Ganciclovir",m:"Hikma",cls:"Non-antineoplastic",risk:"High",vstore:"RT",vsize:"500 mg",rdil:"SWFI",rvol:"10 ml",rconc:"50 mg/ml",vstab:"Use immediately",dil:"NS or D5W",dvol:"100 ml",fconc:"NA",dstab:"Diluted infusion should be refrigerated, do not freeze and used within 24 hrs",light:"No",filter:"Yes",haz:"No",cstd:"No"},
  {g:"Cidofovir",b:"Cidnavir",m:"Emcure Pharma",cls:"Non-antineoplastic",risk:"High",vstore:"RT",vsize:"375 mg",rdil:"NA",rvol:"NA",rconc:"75 mg/ml",vstab:"Use immediately",dil:"NS",dvol:"100 ml",fconc:"NA",dstab:"R: 24 hrs",light:"No",filter:"No",haz:"No",cstd:"No"}
];

// KFSH&RC Pharmaceutical Care Division — IV Medication Vial Reconstitution and
// Stability Chart (last updated 21 Oct 2021). Non-antineoplastic / supportive IV meds.
// Fields: g,b,m, vstore(intact-vial storage), vsize(initial vial strength),
// rdil(diluent), rvol(diluent volume), rconc(final conc), rt(RT stability),
// fr(refrigerated stability), special, gcat(category)
window.MEDS_GENERAL = [
  {g:"Abatacept",b:"Orencia",m:"Bristol-Myers Squibb",gcat:"Biologic",vstore:"Refrigerate; PFL",vsize:"250 mg vial",rdil:"SWFI",rvol:"10 mL",rconc:"25 mg/mL",rt:"Use immediately",fr:"24 hours",special:"Use the silicone-free disposable syringe included in the package and an 18–21 gauge needle. Swirl gently; do not shake."},
  {g:"Acyclovir Sodium",b:"Acyclovir JPI",m:"JPI",gcat:"Antiviral",vstore:"RT; PFL",vsize:"250 mg vial",rdil:"SWFI",rvol:"5 mL",rconc:"100 mg/mL",rt:"NA",fr:"24 hours",special:""},
  {g:"Acetazolamide",b:"Diamox",m:"Mercurypharma",gcat:"Other",vstore:"RT",vsize:"500 mg vial",rdil:"SWFI",rvol:"5 mL",rconc:"100 mg/mL",rt:"12 hours",fr:"3 days",special:"Do not use preservative-containing diluents such as bacteriostatic water."},
  {g:"Acetazolamide",b:"Acetazolamide",m:"X-GEN",gcat:"Other",vstore:"RT",vsize:"500 mg vial",rdil:"SWFI",rvol:"5 mL",rconc:"100 mg/mL",rt:"8 hours",fr:"24 hours",special:"Do not use preservative-containing diluents such as bacteriostatic water."},
  {g:"Alteplase",b:"Actilyse",m:"Boehringer Ingelheim",gcat:"Thrombolytic",vstore:"RT; PFL",vsize:"50 mg vial",rdil:"SWFI (supplied diluent)",rvol:"50 mL or 25 mL",rconc:"1 mg/mL or 2 mg/mL",rt:"8 hours",fr:"24 hours",special:"Use the transfer cannula supplied in the package. Swirl gently; do not shake."},
  {g:"Amphotericin B",b:"Fungizone",m:"Cheplapharm Arzneimittel",gcat:"Antifungal",vstore:"Refrigerate; PFL",vsize:"50 mg vial",rdil:"SWFI",rvol:"10 mL",rconc:"5 mg/mL",rt:"8 hours",fr:"24 hours",special:""},
  {g:"Amphotericin B",b:"Amphotericin B",m:"X-GEN",gcat:"Antifungal",vstore:"Refrigerate; PFL",vsize:"50 mg vial",rdil:"SWFI",rvol:"10 mL",rconc:"5 mg/mL",rt:"24 hours",fr:"7 days",special:""},
  {g:"Amphotericin B Liposomal",b:"AmBisome",m:"Gilead",gcat:"Antifungal",vstore:"RT; PFL; do not freeze",vsize:"50 mg vial",rdil:"SWFI (without bacteriostatic agent)",rvol:"12 mL",rconc:"4 mg/mL",rt:"Use immediately",fr:"24 hours",special:"Use a 5 µm filter to transfer the reconstituted solution."},
  {g:"Amoxicillin / Clavulanate",b:"Amoclan",m:"Hikma",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"1200 mg vial (1000 mg amoxicillin + 200 mg clavulanate)",rdil:"SWFI",rvol:"20 mL",rconc:"50/10 mg/mL",rt:"Use immediately within 20 minutes",fr:"NA",special:""},
  {g:"Amoxicillin / Clavulanate",b:"Amoclan",m:"Hikma",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"600 mg vial (500 mg amoxicillin + 100 mg clavulanate)",rdil:"SWFI",rvol:"10 mL",rconc:"50/10 mg/mL",rt:"Use immediately within 20 minutes",fr:"NA",special:""},
  {g:"Ampicillin Sodium",b:"Ampicillin",m:"Fresenius-Kabi",gcat:"Antibiotic",vstore:"RT",vsize:"250 mg vial",rdil:"SWFI",rvol:"5 mL",rconc:"50 mg/mL",rt:"1 hour",fr:"NA",special:"Prepare freshly. Do not freeze."},
  {g:"Ampicillin Sodium",b:"Ampicillin",m:"Sandoz",gcat:"Antibiotic",vstore:"RT",vsize:"1 g vial",rdil:"SWFI",rvol:"7.4 mL",rconc:"135 mg/mL",rt:"1 hour",fr:"NA",special:"Prepare freshly. Do not freeze."},
  {g:"Anidulafungin",b:"Ecalta",m:"Pharmacia Upjohn-Pfizer",gcat:"Antifungal",vstore:"Refrigerate",vsize:"100 mg vial",rdil:"SWFI",rvol:"30 mL",rconc:"3.33 mg/mL",rt:"1 hour",fr:"1 hour",special:"Refrigerate. Do not freeze."},
  {g:"Azathioprine",b:"Imuran",m:"Aspen",gcat:"Immunosuppressant",vstore:"RT",vsize:"50 mg vial",rdil:"SWFI",rvol:"10 mL",rconc:"5 mg/mL",rt:"Verify (current SDS)",fr:"Verify (current SDS)",special:"Shake vigorously. Added from an earlier KFSH&RC chart edition — confirm stability against the current SDS."},
  {g:"Aztreonam (sodium-free)",b:"Azactam",m:"BMS",gcat:"Antibiotic",vstore:"RT",vsize:"1 g vial",rdil:"SWFI",rvol:"10 mL",rconc:"100 mg/mL",rt:"NA",fr:"24 hours",special:"Shake immediately and vigorously."},
  {g:"Basiliximab",b:"Simulect",m:"Novartis",gcat:"Biologic",vstore:"Refrigerate",vsize:"20 mg vial",rdil:"SWFI",rvol:"5 mL",rconc:"4 mg/mL",rt:"4 hours",fr:"24 hours",special:""},
  {g:"Belimumab",b:"Benlysta",m:"GlaxoSmithKline",gcat:"Biologic",vstore:"Refrigerate; PFL; do not freeze",vsize:"400 mg vial",rdil:"SWFI",rvol:"4.8 mL",rconc:"80 mg/mL",rt:"Use immediately",fr:"Use immediately",special:"Gently swirl. Use a 21–25 gauge needle. Protect the reconstituted solution from direct sunlight."},
  {g:"Belimumab",b:"Benlysta",m:"GlaxoSmithKline",gcat:"Biologic",vstore:"Refrigerate; PFL; do not freeze",vsize:"120 mg vial",rdil:"SWFI",rvol:"1.5 mL",rconc:"80 mg/mL",rt:"Use immediately",fr:"Use immediately",special:"Gently swirl. Use a 21–25 gauge needle. Protect the reconstituted solution from direct sunlight."},
  {g:"Caspofungin",b:"Caspofungin Acetate",m:"Gland Pharma",gcat:"Antifungal",vstore:"Refrigerate",vsize:"50 mg vial",rdil:"SWFI",rvol:"10.5 mL",rconc:"5.2 mg/mL",rt:"24 hours",fr:"24 hours",special:"Refrigerate. Do not use any diluent containing glucose. Mix gently."},
  {g:"Caspofungin",b:"Caspofungin Acetate",m:"Gland Pharma",gcat:"Antifungal",vstore:"Refrigerate",vsize:"70 mg vial",rdil:"SWFI",rvol:"10.5 mL",rconc:"7.2 mg/mL",rt:"24 hours",fr:"24 hours",special:"Refrigerate. Do not use any diluent containing glucose. Mix gently."},
  {g:"Cefazolin Sodium",b:"Zolecin",m:"Hikma",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"1 g vial",rdil:"SWFI",rvol:"2.5 mL",rconc:"330 mg/mL",rt:"24 hours",fr:"10 days",special:"Shake well."},
  {g:"Cefepime Hydrochloride",b:"Protec",m:"Tabuk",gcat:"Antibiotic",vstore:"PFL",vsize:"2 g vial",rdil:"SWFI / D5W / NS / bacteriostatic WFI",rvol:"10 mL",rconc:"200 mg/mL",rt:"24 hours",fr:"7 days",special:"Protect from light."},
  {g:"Cefoxitin Sodium",b:"Foxitin",m:"Tabuk",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"1 g vial",rdil:"SWFI",rvol:"10 mL",rconc:"100 mg/mL",rt:"24 hours",fr:"48 hours",special:"Protect from light."},
  {g:"Ceftazidime",b:"Zidime",m:"Tabuk",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"1 g vial",rdil:"SWFI",rvol:"10 mL",rconc:"100 mg/mL",rt:"Use immediately within 30 minutes",fr:"NA",special:"Protect from light."},
  {g:"Ceftazidime / Avibactam",b:"Zavicefta",m:"Pfizer",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"2 g / 0.5 g vial",rdil:"SWFI / NS / D5W",rvol:"10 mL (expands to 12 mL)",rconc:"167.3 / 41.8 mg/mL",rt:"2 days",fr:"10 days",special:""},
  {g:"Ceftriaxone Sodium",b:"Samixon",m:"Hikma",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"1 g vial",rdil:"SWFI / NS / D5W",rvol:"10 mL",rconc:"100 mg/mL",rt:"NA",fr:"24 hours",special:""},
  {g:"Cefuroxime Sodium",b:"Maxil",m:"Hikma",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"1500 mg vial",rdil:"SWFI",rvol:"15 mL",rconc:"100 mg/mL",rt:"5 hours",fr:"48 hours",special:""},
  {g:"Cefuroxime Sodium",b:"Maxil",m:"Hikma",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"750 mg vial",rdil:"SWFI",rvol:"7.5 mL",rconc:"100 mg/mL",rt:"5 hours",fr:"48 hours",special:""},
  {g:"Chloramphenicol Sodium Succinate",b:"Chloromycetin",m:"—",gcat:"Antibiotic",vstore:"RT",vsize:"1 g vial",rdil:"SWFI",rvol:"10 mL",rconc:"100 mg/mL",rt:"30 days",fr:"NA",special:"Added from an earlier KFSH&RC chart edition — verify against the current SDS."},
  {g:"Cloxacillin Sodium",b:"Cloxacillin",m:"Fresenius",gcat:"Antibiotic",vstore:"RT",vsize:"250 mg vial",rdil:"SWFI",rvol:"2.5 mL",rconc:"100 mg/mL",rt:"24 hours",fr:"4 days",special:"Added from an earlier KFSH&RC chart edition — verify against the current SDS."},
  {g:"Colistimethate Sodium",b:"Colistin",m:"JPI",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"1 MU vial",rdil:"SWFI / NS",rvol:"7 mL",rconc:"≈142 IU/mL",rt:"8 hours",fr:"24 hours",special:""},
  {g:"Conjugated Estrogen",b:"Premarin",m:"Pfizer",gcat:"Other",vstore:"Refrigerate",vsize:"25 mg vial",rdil:"SWFI",rvol:"5 mL",rconc:"5 mg/mL",rt:"Use immediately",fr:"NA",special:"Do not shake violently."},
  {g:"Daptomycin",b:"Docine",m:"Tabuk",gcat:"Antibiotic",vstore:"Refrigerate",vsize:"500 mg vial",rdil:"NS",rvol:"10 mL",rconc:"50 mg/mL",rt:"Use immediately",fr:"24 hours",special:""},
  {g:"Desferrioxamine Methanesulphonate",b:"Desferal",m:"Novartis",gcat:"Other",vstore:"RT; PFL",vsize:"500 mg vial",rdil:"SWFI",rvol:"5 mL",rconc:"95 mg/mL",rt:"24 hours",fr:"NA",special:"Iron chelator."},
  {g:"Doxycycline",b:"Doxy 100",m:"Fresenius Kabi",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"100 mg vial",rdil:"SWFI / NS / D5W",rvol:"10 mL",rconc:"10 mg/mL",rt:"Use immediately",fr:"NA",special:"Protect from light. Reconstituted at 10 mg/mL in SWFI is stable 8 weeks frozen at -20°C; once thawed, do not refreeze."},
  {g:"Ertapenem",b:"Invanz",m:"MSD",gcat:"Antibiotic",vstore:"PFL",vsize:"1000 mg vial",rdil:"SWFI / NS",rvol:"10 mL",rconc:"100 mg/mL",rt:"Use immediately",fr:"NA",special:"Protect from light. Shake well to dissolve."},
  {g:"Erythromycin Lactobionate",b:"Erythromycin Inresa",m:"Inresa Arzneimittel",gcat:"Antibiotic",vstore:"RT",vsize:"1 g vial",rdil:"SWFI",rvol:"20 mL",rconc:"50 mg/mL",rt:"24 hours",fr:"14 days",special:""},
  {g:"Ganciclovir",b:"Ganciclovir for Injection",m:"Hikma",gcat:"Antiviral",vstore:"RT",vsize:"500 mg vial",rdil:"SWFI",rvol:"10 mL",rconc:"50 mg/mL",rt:"12 hours",fr:"Do not refrigerate",special:"Gently swirl."},
  {g:"Ganciclovir",b:"Ganciclovir",m:"Sagent Pharmaceuticals",gcat:"Antiviral",vstore:"RT",vsize:"500 mg vial (sterile solution for injection)",rdil:"NA",rvol:"NA",rconc:"NA",rt:"Use immediately",fr:"NA",special:""},
  {g:"Hydrocortisone Sodium Succinate",b:"Solu-Cortef",m:"Pfizer",gcat:"Corticosteroid",vstore:"RT",vsize:"100 mg Act-O-Vial",rdil:"SWFI (supplied diluent)",rvol:"2 mL",rconc:"50 mg/mL",rt:"3 days",fr:"NA",special:"Protect from light."},
  {g:"Hydrocortisone Sodium Succinate",b:"Solu-Cortef",m:"Pfizer",gcat:"Corticosteroid",vstore:"RT",vsize:"250 mg Act-O-Vial",rdil:"SWFI (supplied diluent)",rvol:"2 mL",rconc:"125 mg/mL",rt:"3 days",fr:"NA",special:"Protect from light."},
  {g:"Imipenem / Cilastatin Sodium",b:"Tienam",m:"MSD",gcat:"Antibiotic",vstore:"PFL",vsize:"500 mg vial",rdil:"NS",rvol:"10 mL",rconc:"50 mg/mL",rt:"Use immediately",fr:"NA",special:"Interval between start of reconstitution and end of IV infusion should not exceed 2 hours."},
  {g:"Imipenem / Cilastatin",b:"Imipenem/Cilastatin Kabi",m:"Fresenius Kabi",gcat:"Antibiotic",vstore:"RT",vsize:"500 mg vial",rdil:"NS",rvol:"10 mL",rconc:"50 mg/mL",rt:"4 hours",fr:"24 hours",special:"Interval between start of reconstitution and end of IV infusion should not exceed 2 hours."},
  {g:"Indomethacin",b:"Indomethacin",m:"Fresenius Kabi",gcat:"Other",vstore:"RT",vsize:"1 mg vial",rdil:"Preservative-free NS or preservative-free SWFI",rvol:"1 mL or 2 mL",rconc:"1 mg/mL or 0.5 mg/mL",rt:"Use immediately",fr:"NA",special:"NSAID (PDA closure)."},
  {g:"Infliximab",b:"Remicade",m:"Cilag AG",gcat:"Biologic",vstore:"Refrigerate",vsize:"100 mg vial",rdil:"SWFI",rvol:"10 mL",rconc:"10 mg/mL",rt:"3 hours",fr:"NA",special:"Do not shake. Interval between start of reconstitution and end of infusion should not exceed 24 hours. Intact vial may be stored at RT up to 6 months; do not refrigerate again."},
  {g:"Isoniazid",b:"Isozid",m:"Riemser Pharma",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"0.5 g",rdil:"SWFI",rvol:"10 mL",rconc:"50 mg/mL",rt:"Use immediately",fr:"NA",special:"May crystallize at low temperatures; warm vial to RT to redissolve crystals before use."},
  {g:"Meropenem",b:"Meropenem Kabi",m:"Fresenius Kabi",gcat:"Antibiotic",vstore:"RT",vsize:"1 g vial",rdil:"SWFI / NS",rvol:"20 mL",rconc:"50 mg/mL",rt:"3 hours",fr:"12 hours",special:"Do not freeze. Bolus injection: reconstitute with SWFI. Infusion: reconstitute directly with NS."},
  {g:"Meropenem",b:"Meropenem Kabi",m:"Fresenius Kabi",gcat:"Antibiotic",vstore:"RT",vsize:"500 mg vial",rdil:"SWFI / NS",rvol:"10 mL",rconc:"50 mg/mL",rt:"3 hours",fr:"12 hours",special:"Do not freeze. Bolus injection: reconstitute with SWFI. Infusion: reconstitute directly with NS."},
  {g:"Methylprednisolone Sodium Succinate",b:"Medrolone",m:"JPI",gcat:"Corticosteroid",vstore:"RT; PFL",vsize:"500 mg vial",rdil:"Bacteriostatic SWFI",rvol:"7.8 mL",rconc:"62.5 mg/mL",rt:"48 hours",fr:"48 hours",special:""},
  {g:"Methylprednisolone Sodium Succinate",b:"Solu-Medrol",m:"Pfizer",gcat:"Corticosteroid",vstore:"RT",vsize:"40 mg Act-O-Vial",rdil:"SWFI (supplied diluent)",rvol:"1 mL",rconc:"40 mg/mL",rt:"6 hours",fr:"12 hours",special:""},
  {g:"Multivitamins",b:"Cernevit",m:"Baxter",gcat:"Other",vstore:"RT; PFL",vsize:"5 mL vial",rdil:"SWFI",rvol:"5 mL",rconc:"—",rt:"Use immediately",fr:"24 hours",special:""},
  {g:"Multivitamins",b:"Soluvit N",m:"Fresenius Kabi",gcat:"Other",vstore:"RT; PFL",vsize:"10 mL vial",rdil:"SWFI",rvol:"10 mL",rconc:"—",rt:"Use immediately",fr:"24 hours",special:""},
  {g:"Mycophenolate Mofetil",b:"CellCept",m:"Roche",gcat:"Immunosuppressant",vstore:"RT",vsize:"500 mg vial",rdil:"D5W",rvol:"14 mL (expands to 15 mL)",rconc:"33.3 mg/mL",rt:"Use immediately",fr:"NA",special:"Gently shake. Interval between start of reconstitution and end of IV infusion should not exceed 3 hours."},
  {g:"Nafcillin Sodium",b:"Nafcillin",m:"Sagent Pharmaceuticals",gcat:"Antibiotic",vstore:"RT",vsize:"2000 mg",rdil:"SWFI / NS",rvol:"6.6 mL (expands to 8 mL)",rconc:"250 mg/mL",rt:"24 hours",fr:"7 days",special:""},
  {g:"Omalizumab",b:"Xolair",m:"Novartis",gcat:"Biologic",vstore:"Refrigerate; PFL; do not freeze",vsize:"150 mg vial",rdil:"SWFI (2 mL supplied diluent)",rvol:"1.4 mL",rconc:"NA",rt:"4 hours",fr:"8 hours",special:"Do not shake. After reconstitution the vial delivers 1.2 mL. Subcutaneous use only."},
  {g:"Omeprazole Sodium",b:"Oprazole",m:"Hikma",gcat:"Other",vstore:"RT; PFL",vsize:"40 mg vial",rdil:"NS / D5W",rvol:"5 mL",rconc:"8 mg/mL",rt:"12 hours in NS, or 6 hours in D5W",fr:"NA",special:"Proton-pump inhibitor."},
  {g:"Benzylpenicillin Sodium",b:"Penicillin G Sodium",m:"Novartis",gcat:"Antibiotic",vstore:"RT",vsize:"1 MU vial",rdil:"SWFI",rvol:"10 mL",rconc:"100,000 IU/mL",rt:"Use immediately",fr:"NA",special:"Shake well."},
  {g:"Pentamidine Isetionate",b:"Pentacarinat",m:"Sanofi",gcat:"Antibiotic",vstore:"RT",vsize:"300 mg vial",rdil:"SWFI",rvol:"5 mL",rconc:"60 mg/mL",rt:"NA",fr:"24 hours",special:"Antiprotozoal."},
  {g:"Piperacillin / Tazobactam",b:"Piperacillin/Tazobactam Sandoz",m:"Sandoz",gcat:"Antibiotic",vstore:"RT",vsize:"4.5 g vial",rdil:"SWFI / NS / D5W",rvol:"20 mL",rconc:"200 mg/mL piperacillin; 25 mg/mL tazobactam",rt:"24 hours",fr:"48 hours",special:""},
  {g:"Rasburicase",b:"Fasturtec",m:"Sanofi Aventis",gcat:"Other",vstore:"Refrigerate; PFL; do not freeze",vsize:"1.5 mg vial",rdil:"Diluent provided",rvol:"1 mL",rconc:"1.5 mg/mL",rt:"Use immediately",fr:"24 hours",special:"Enzyme (urate oxidase). Do not shake."},
  {g:"Rifampicin",b:"Rifadin",m:"Sanofi",gcat:"Antibiotic",vstore:"RT",vsize:"600 mg vial",rdil:"SWFI (diluent provided)",rvol:"10 mL",rconc:"60 mg/mL",rt:"30 hours",fr:"NA",special:""},
  {g:"Romiplostim",b:"Nplate",m:"Amgen Europe B.V.",gcat:"Biologic",vstore:"Refrigerate; PFL; do not freeze",vsize:"250 mcg vial",rdil:"SWFI",rvol:"0.72 mL",rconc:"500 mcg/mL",rt:"24 hours",fr:"24 hours",special:"Do not shake vigorously. Resultant volume after reconstitution is 0.5 mL."},
  {g:"Sodium Valproate",b:"Depakine",m:"Sanofi",gcat:"Other",vstore:"RT",vsize:"400 mg vial",rdil:"SWFI (diluent provided)",rvol:"4 mL",rconc:"100 mg/mL",rt:"24 hours",fr:"NA",special:"Anticonvulsant."},
  {g:"Streptokinase",b:"Streptokinase",m:"Beacon",gcat:"Thrombolytic",vstore:"RT",vsize:"250,000 IU vial",rdil:"SWFI / NS",rvol:"5 mL",rconc:"50,000 IU/mL",rt:"NA",fr:"12 hours",special:"Mix gently to avoid foaming."},
  {g:"Teicoplanin",b:"Targocid",m:"Sanofi",gcat:"Antibiotic",vstore:"RT",vsize:"200 mg vial",rdil:"SWFI (diluent provided)",rvol:"3.14 mL",rconc:"66.7 mg/mL",rt:"Use immediately",fr:"24 hours",special:"Withdraw 3 mL from the vial following reconstitution."},
  {g:"Tigecycline",b:"Tygacil",m:"Wyeth",gcat:"Antibiotic",vstore:"RT",vsize:"50 mg vial",rdil:"NS / D5W",rvol:"5.3 mL",rconc:"10 mg/mL",rt:"6 hours",fr:"NA",special:"Swirl gently."},
  {g:"Vancomycin HCl",b:"Vanco",m:"JPI",gcat:"Antibiotic",vstore:"RT; PFL",vsize:"500 mg vial",rdil:"SWFI",rvol:"10 mL",rconc:"50 mg/mL",rt:"24 hours",fr:"96 hours",special:""},
  {g:"Vedolizumab",b:"Entyvio",m:"Takeda Pharma",gcat:"Biologic",vstore:"Refrigerate; PFL",vsize:"300 mg vial",rdil:"SWFI",rvol:"4.8 mL",rconc:"60 mg/mL",rt:"Use immediately within 30 minutes",fr:"8 hours",special:""},
  {g:"Voriconazole",b:"Vfend",m:"Pfizer",gcat:"Antifungal",vstore:"RT",vsize:"200 mg vial",rdil:"SWFI / NS",rvol:"19 mL (expands to 20 mL)",rconc:"10 mg/mL",rt:"Use immediately",fr:"24 hours",special:""}
];

</script>
<script>
(function(){
  var MEDS = window.MEDS || [];
  var GEN = window.MEDS_GENERAL || [];

  // ---- Pharmacologic category (drug class) by generic ----
  var CAT={
    "ado-trastuzumab emtansine":"Antibody–drug conjugate (anti-HER2)","aldesleukin":"Recombinant cytokine (IL-2)",
    "arsenic trioxide":"Differentiating agent","asparaginase":"Enzyme (asparagine depleter)",
    "atezolizumab":"Monoclonal antibody (anti–PD-L1)","avelumab":"Monoclonal antibody (anti–PD-L1)",
    "azacitidine":"Antimetabolite (hypomethylating)","bendamustine":"Alkylating agent",
    "bevacizumab":"Monoclonal antibody (anti-VEGF)","bleomycin":"Antitumor antibiotic",
    "blinatumomab":"Bispecific T-cell engager (BiTE)","bortezomib":"Proteasome inhibitor",
    "brentuximab vedotin":"Antibody–drug conjugate (anti-CD30)","busulfan":"Alkylating agent",
    "cabazitaxel":"Taxane","capecitabine":"Antimetabolite (fluoropyrimidine)","carboplatin":"Platinum agent",
    "carfilzomib":"Proteasome inhibitor","carmustine":"Nitrosourea (alkylating)",
    "cetuximab":"Monoclonal antibody (anti-EGFR)","chlorambucil":"Alkylating agent","cisplatin":"Platinum agent",
    "cladribine":"Antimetabolite (purine analog)","clofarabine":"Antimetabolite (purine analog)",
    "cyclophosphamide":"Alkylating agent","cytarabine":"Antimetabolite (pyrimidine analog)",
    "dacarbazine":"Alkylating agent","dactinomycin":"Antitumor antibiotic","daunorubicin":"Anthracycline",
    "dinutuximab":"Monoclonal antibody (anti-GD2)","docetaxel":"Taxane","doxorubicin":"Anthracycline",
    "doxorubicin (liposomal)":"Anthracycline (liposomal)","durvalumab":"Monoclonal antibody (anti–PD-L1)",
    "enfortumab vedotin":"Antibody–drug conjugate (anti-Nectin-4)","epirubicin":"Anthracycline",
    "eribulin":"Microtubule inhibitor (halichondrin)","etoposide":"Topoisomerase II inhibitor",
    "etoposide phosphate":"Topoisomerase II inhibitor","fludarabine":"Antimetabolite (purine analog)",
    "fluorouracil":"Antimetabolite (fluoropyrimidine)","gemcitabine":"Antimetabolite (pyrimidine analog)",
    "gemtuzumab ozogamicin":"Antibody–drug conjugate (anti-CD33)","idarubicin":"Anthracycline",
    "ifosfamide":"Alkylating agent","inotuzumab ozogamicin":"Antibody–drug conjugate (anti-CD22)",
    "ipilimumab":"Monoclonal antibody (anti–CTLA-4)","irinotecan":"Topoisomerase I inhibitor",
    "melphalan":"Alkylating agent","methotrexate":"Antimetabolite (antifolate)","mitomycin":"Antitumor antibiotic",
    "mitoxantrone":"Anthracenedione","nivolumab":"Monoclonal antibody (anti–PD-1)","oxaliplatin":"Platinum agent",
    "paclitaxel":"Taxane","pegaspargase":"Enzyme (pegylated asparaginase)","pembrolizumab":"Monoclonal antibody (anti–PD-1)",
    "pemetrexed":"Antimetabolite (antifolate)","pertuzumab":"Monoclonal antibody (anti-HER2)",
    "ramucirumab":"Monoclonal antibody (anti-VEGFR2)","rituximab":"Monoclonal antibody (anti-CD20)",
    "sacituzumab govitecan":"Antibody–drug conjugate (anti-Trop-2)","teniposide":"Topoisomerase II inhibitor",
    "thiotepa":"Alkylating agent","topotecan":"Topoisomerase I inhibitor","trastuzumab":"Monoclonal antibody (anti-HER2)",
    "treosulfan":"Alkylating agent","vinblastine":"Vinca alkaloid","vincristine":"Vinca alkaloid",
    "vinorelbine":"Vinca alkaloid","ganciclovir":"Antiviral agent","cidofovir":"Antiviral agent"
  };
  // ---- NIOSH hazard-potential codes by generic ----
  var POT={
    "ado-trastuzumab emtansine":["re","m"],"dactinomycin":["+","c","v"],"arsenic trioxide":["c","tcld","+"],
    "asparaginase":["t"],"azacitidine":["c","+"],"bendamustine":["cce","m","t"],"bleomycin":["c","t","re","+"],
    "bortezomib":["e","t","+"],"brentuximab vedotin":["c","i","tcld","+"],"busulfan":["c","t","re","+"],
    "cabazitaxel":["i","re","tcld"],"capecitabine":["re","+"],"carboplatin":["c","t","m","+"],
    "carfilzomib":["i","re","tcld","+"],"carmustine":["c","t","m","+"],"chlorambucil":["c","re","+"],
    "cisplatin":["e","c","t","m","+"],"cladribine":["e","c","t","m","+"],"clofarabine":["t","+"],
    "cyclophosphamide":["t","c","+"],"cytarabine":["t","c","+"],"dacarbazine":["t","m","c","i"],
    "dasatinib":["t","+"],"daunorubicin":["t","m","c","v","+"],"docetaxel":["+"],
    "doxorubicin":["t","m","v","c","+"],"doxorubicin (liposomal)":["t","m","v","c","+"],
    "epirubicin":["t","m","v","c","+"],"erdafitinib":["re","tcld"],"enfortumab vedotin":["c"],
    "etoposide":["t","m","re","c","cce","e","+"],"etoposide phosphate":["t","m","re","c","cce","e","+"],
    "eribulin":["m","re","c"],"everolimus":["tcld"],"fam-trastuzumab deruxtecan":["+"],
    "fludarabine":["t","m","re","c","+"],"fluorouracil":["t","m","re","c","+"],"flutamide":["re","i","+"],
    "fulvestrant":["e","+"],"gemcitabine":["+","re","m"],"gemtuzumab ozogamicin":["re","c"],
    "hydroxyurea":["i","m","c"],"idarubicin":["t","m","c","v","+"],"ifosfamide":["t","c","i","+"],
    "imatinib":["t"],"inotuzumab ozogamicin":["re","c"],"irinotecan":["t","re","c","+"],"lenalidomide":["re","+"],
    "lomustine":["re","tcld"],"melphalan":["t","m","re","c","+"],"mercaptopurine":["m","re","c","v","+"],
    "methotrexate":["t","re","c","+"],"mitomycin":["t","m","re","c","tcld","+"],"mitotane":["t","m","c","v","+"],
    "mitoxantrone":["t","c","tcld","+"],"osimertinib":["m","c","i","tcld","+"],"oxaliplatin":["i","e","tld"],
    "paclitaxel":["m","c","re","tcld","+"],"nelarabine":["m","re","tcld","+"],"pegaspargase":["t"],
    "pemetrexed":["t","re","+"],"polatuzumab vedotin":["re","m"],"pomalidomide":["re"],
    "procarbazine":["t","m","re","c","+"],"sacituzumab govitecan":["re","e"],"tamoxifen":["i","re"],
    "temozolomide":["+"],"teniposide":["m","t","i","f","+"],"thioguanine":["t","re","c","+"],
    "thiotepa":["m","t","c","+"],"topotecan":["t","m","re","+"],"trifluridine and tipiracil":["re","e"],
    "venetoclax":["re","t"],"vinblastine":["m","t","re","v","+"],"vincristine":["m","t","re","v","+"],
    "vinorelbine":["m","t","c","+"],"ganciclovir":["m","re"],"cidofovir":["c","re","+"]
  };
  // code -> {label, group}
  var DECODE={
    v:["Vesicant","danger"], i:["Irritant","irrit"], cce:["Carcinogenic (chronic)","geno"],
    cc:["Carcinogenic (chronic)","geno"], t:["Teratogenic","geno"], m:["Mutagenic","geno"],
    re:["Reproductive toxicity","geno"], e:["Embryolethal","geno"], dt:["Developmental toxicity","geno"],
    c:["Cytotoxic","cyto"], "+":["Chemo/cytotoxic","cyto"], tld:["Toxic in low doses","danger"],
    tcld:["Toxic (chronic low-dose)","danger"], f:["Flammable","danger"], vf:["Vapour-flammable","danger"]
  };
  // ---- High Alert Antineoplastic Medications (KFSH&RC Appendix B, Sep 2025) ----
  var HIGH_ALERT=new Set([
    "abiraterone","acalabrutinib","ado-trastuzumab emtansine","aldesleukin","alectinib","amivantamab",
    "arsenic trioxide","asciminib","asparaginase","atezolizumab","avelumab","azacitidine","bendamustine",
    "bevacizumab","bicalutamide","bleomycin","blinatumomab","bortezomib","brentuximab vedotin","burosumab",
    "buserelin acetate","busulfan","cabazitaxel","cabozantinib","capecitabine","carboplatin","carfilzomib",
    "carmustine","cetuximab","chlorambucil","cisplatin","cladribine","clofarabine","crizotinib",
    "cyclophosphamide","cyproterone","cytarabine","dabrafenib","dacarbazine","dactinomycin","daratumumab",
    "dasatinib","daunorubicin","deruxtecan","dexrazoxane","dinutuximab","docetaxel","doxorubicin",
    "doxorubicin (liposomal)","durvalumab","elacestrant","emtansine","encorafenib","enfortumab vedotin",
    "enzalutamide","epirubicin","etoposide","etoposide phosphate","everolimus","exemestane",
    "fam-trastuzumab","fam-trastuzumab deruxtecan","fludarabine","fluorouracil","flutamide","fulvestrant",
    "gemcitabine","gemtuzumab ozogamicin","hydroxyurea","ibrutinib","idarubicin","ifosfamide","imatinib",
    "interferon alfa-2b","inotuzumab ozogamicin","ipilimumab","irinotecan","lapatinib","lenalidomide",
    "lenvatinib","letrozole","leuprolide","lomustine","lorlatinib","megestrol","melphalan","mercaptopurine",
    "methotrexate","midostaurin","mitomycin","mitotane","mitoxantrone","mogamulizumab","nelarabine",
    "nilotinib","nivolumab","olaparib","osimertinib","oxaliplatin","paclitaxel","pazopanib","pegaspargase",
    "pembrolizumab","pemetrexed","pertuzumab","polatuzumab vedotin","pomalidomide","ponatinib","procarbazine",
    "ramucirumab","regorafenib","ribociclib","rituximab","ruxolitinib","sacituzumab govitecan","selpercatinib",
    "sorafenib","sunitinib","tamoxifen","temozolomide","teniposide","thioguanine","thiotepa","topotecan",
    "trastuzumab","treosulfan","tretinoin","trifluridine and tipiracil","venetoclax","vinblastine",
    "vincristine","vinorelbine"
  ]);
  function baseKey(g){
    g=g.toLowerCase();
    if(g.indexOf("(liposomal)")>-1) return "doxorubicin (liposomal)";
    g=g.split(" — ")[0];                 // drop "— see oral list"
    g=g.replace(/\s*\(.*$/,"");          // drop trailing parenthetical
    return g.trim();
  }
  // ---- Common / approved indications (diagnoses treated) by generic ----
  var IND={
    "ado-trastuzumab emtansine":"HER2-positive breast cancer","aldesleukin":"Metastatic renal cell carcinoma; metastatic melanoma",
    "arsenic trioxide":"Acute promyelocytic leukemia (APL)","asparaginase":"Acute lymphoblastic leukemia (ALL)",
    "atezolizumab":"NSCLC; SCLC; urothelial; triple-negative breast; hepatocellular","avelumab":"Merkel cell carcinoma; urothelial; renal cell carcinoma",
    "azacitidine":"Myelodysplastic syndromes (MDS); AML","bendamustine":"CLL; indolent non-Hodgkin lymphoma",
    "bevacizumab":"Colorectal, NSCLC, ovarian, cervical, glioblastoma, renal cell","bleomycin":"Hodgkin & non-Hodgkin lymphoma; testicular germ cell; pleurodesis",
    "blinatumomab":"B-cell precursor ALL","bortezomib":"Multiple myeloma; mantle cell lymphoma",
    "brentuximab vedotin":"Hodgkin lymphoma; CD30-positive lymphomas (incl. ALCL)","busulfan":"CML; conditioning for stem-cell transplant",
    "cabazitaxel":"Metastatic castration-resistant prostate cancer","capecitabine":"Colorectal, breast, gastric cancers",
    "carboplatin":"Ovarian, lung, head & neck; many solid tumors","carfilzomib":"Multiple myeloma",
    "carmustine":"Brain tumors (glioma); lymphoma; myeloma (conditioning)","cetuximab":"Colorectal (RAS wild-type); head & neck squamous cell",
    "cisplatin":"Testicular, ovarian, bladder, lung, head & neck, cervical, gastric","cladribine":"Hairy cell leukemia; CLL",
    "clofarabine":"Pediatric relapsed/refractory ALL","cyclophosphamide":"Lymphoma, breast, ovarian, leukemia; conditioning",
    "cytarabine":"AML; ALL; lymphoma (incl. intrathecal CNS prophylaxis)","dacarbazine":"Hodgkin lymphoma; metastatic melanoma; sarcoma",
    "dactinomycin":"Wilms tumor; rhabdomyosarcoma; Ewing sarcoma; gestational trophoblastic disease","daunorubicin":"AML; ALL",
    "dinutuximab":"High-risk neuroblastoma","docetaxel":"Breast, NSCLC, prostate, gastric, head & neck",
    "doxorubicin":"Breast, lymphoma, sarcoma, leukemia; many solid tumors","doxorubicin (liposomal)":"Ovarian cancer; Kaposi sarcoma; multiple myeloma",
    "durvalumab":"NSCLC; SCLC; biliary tract cancer","enfortumab vedotin":"Locally advanced / metastatic urothelial carcinoma",
    "epirubicin":"Breast cancer; gastric cancer","eribulin":"Metastatic breast cancer; liposarcoma",
    "etoposide":"SCLC, testicular germ cell, lymphoma, leukemia","etoposide phosphate":"SCLC; testicular germ cell",
    "fludarabine":"CLL; conditioning for stem-cell transplant","fluorouracil":"Colorectal, breast, gastric, pancreatic, head & neck",
    "gemcitabine":"Pancreatic, NSCLC, breast, ovarian, bladder","gemtuzumab ozogamicin":"CD33-positive acute myeloid leukemia",
    "idarubicin":"Acute myeloid leukemia (AML)","ifosfamide":"Sarcoma; testicular germ cell; lymphoma",
    "inotuzumab ozogamicin":"B-cell precursor ALL","ipilimumab":"Melanoma; renal cell; MSI-H colorectal; NSCLC",
    "irinotecan":"Colorectal; pancreatic; small-cell lung","melphalan":"Multiple myeloma; conditioning; ovarian cancer",
    "methotrexate":"ALL & CNS prophylaxis, lymphoma, osteosarcoma, gestational trophoblastic; breast","mitomycin":"Anal, bladder (intravesical), gastric; breast with radiotherapy",
    "mitoxantrone":"AML; prostate cancer; (multiple sclerosis)","nivolumab":"Melanoma, NSCLC, renal cell, Hodgkin lymphoma, head & neck, urothelial",
    "oxaliplatin":"Colorectal; gastric; pancreatic","paclitaxel":"Breast, ovarian, NSCLC, head & neck, Kaposi sarcoma",
    "pegaspargase":"Acute lymphoblastic leukemia (ALL)","pembrolizumab":"Melanoma, NSCLC, head & neck, urothelial, MSI-H/dMMR tumors",
    "pemetrexed":"Non-squamous NSCLC; mesothelioma","pertuzumab":"HER2-positive breast cancer",
    "ramucirumab":"Gastric/GEJ, NSCLC, colorectal, hepatocellular","rituximab":"B-cell non-Hodgkin lymphoma; CLL",
    "sacituzumab govitecan":"Triple-negative breast cancer; urothelial carcinoma","teniposide":"Refractory childhood ALL",
    "thiotepa":"Breast, ovarian, bladder; conditioning for stem-cell transplant","topotecan":"Ovarian, small-cell lung, cervical",
    "trastuzumab":"HER2-positive breast & gastric cancer","treosulfan":"Conditioning for allogeneic stem-cell transplant (with fludarabine)",
    "vinblastine":"Hodgkin lymphoma; testicular; bladder","vincristine":"ALL; lymphoma; many pediatric solid tumors",
    "vinorelbine":"NSCLC; breast cancer","ganciclovir":"CMV infection / prophylaxis (non-oncology)",
    "cidofovir":"CMV retinitis; refractory viral infections (non-oncology)"
  };
  // ---- Tumor-group classification from indication text ----
  var TUMOR=[
    ["Breast", /breast/i],
    ["Lung", /nsclc|sclc|lung|mesothelioma/i],
    ["GI", /colorectal|gastric|gej|pancreatic|\banal\b|hepatocellular|biliary|esophag/i],
    ["Lymphoma", /lymphoma|hodgkin|alcl/i],
    ["Leukemia", /leukemia|myelodysplastic|\bmds\b|hairy cell|\b(all|aml|cml|cll|apl)\b/i],
    ["Myeloma", /myeloma/i],
    ["GU", /prostate|bladder|urothelial|renal|testicular|germ cell/i],
    ["Gynecologic", /ovarian|cervical|endometrial|gestational trophoblastic/i],
    ["Head & Neck", /head & neck/i],
    ["Melanoma/Skin", /melanoma|merkel|kaposi/i],
    ["CNS", /glioblastoma|glioma|brain/i],
    ["Sarcoma", /sarcoma/i],
    ["Pediatric", /neuroblastoma|wilms|pediatric|\bewing\b|childhood|rhabdomyosarcoma/i]
  ];
  MEDS.forEach(function(d){
    var k=baseKey(d.g);
    d.cat = CAT[k] || (d.cls==="Antineoplastic"?"Antineoplastic agent":"—");
    d.highAlert = HIGH_ALERT.has(k);
    d.ind = IND[k] || "";
    d._indGroups = TUMOR.filter(function(t){return t[1].test(d.ind);}).map(function(t){return t[0];});
    var codes = POT[k] || [];
    var seen={}, labels=[], groups=[];
    codes.forEach(function(c){
      var dec=DECODE[c]; if(!dec) return;
      if(seen[dec[0]]) return; seen[dec[0]]=1;
      labels.push(dec[0]); groups.push(dec[1]);
    });
    d._potLabels=labels; d._potGroups=groups;
    d.pot = labels.join("; ");
    d.chart="chemo";
    var noRecon=(d.rdil==null||d.rdil===""||/^NA$/i.test(d.rdil)||d.rdil==="—");
    d.needsRecon=!noRecon;
    d.form=/oral/i.test(d.g)?"Oral":(d.needsRecon?"Powder":"Solution");
  });
  GEN.forEach(function(d){
    d.chart="general";
    var noRecon=(d.rdil==null||d.rdil===""||/^NA$/i.test(d.rdil)||d.rdil==="—");
    d.needsRecon=!noRecon;
    d.form=d.needsRecon?"Powder":"Solution";
  });
  GEN.sort(function(a,b){return a.g.localeCompare(b.g) || a.m.localeCompare(b.m);});

  MEDS.sort(function(a,b){return a.g.localeCompare(b.g) || a.m.localeCompare(b.m);});
  var state={q:"",cls:new Set(),risk:new Set(),flag:new Set(),pot:new Set(),desig:new Set(),tumor:new Set(),gcat:new Set(),form:new Set(),chart:"chemo"};
  function active(){return state.chart==="general"?GEN:MEDS;}
  // Category colour family (variety on labels; does NOT touch hazard/chemo recognition)
  function catColor(d){
    if(d.chart==="general"){
      return {Antibiotic:"cc-blue",Antifungal:"cc-violet",Antiviral:"cc-cyan",Biologic:"cc-indigo",
        Corticosteroid:"cc-amber",Immunosuppressant:"cc-rose",Thrombolytic:"cc-red",Other:"cc-slate"}[d.gcat]||"cc-slate";
    }
    var c=(d.cat||"").toLowerCase();
    if(/anthracyc|anthracened/.test(c))return "cc-rose";
    if(/taxane/.test(c))return "cc-violet";
    if(/platinum/.test(c))return "cc-cyan";
    if(/vinca/.test(c))return "cc-green";
    if(/alkylat|nitrosourea/.test(c))return "cc-amber";
    if(/antimetabolite/.test(c))return "cc-blue";
    if(/topoisomerase/.test(c))return "cc-teal";
    if(/antitumor antibiotic/.test(c))return "cc-brown";
    if(/antibody.?drug conjugate/.test(c))return "cc-indigo";
    if(/monoclonal/.test(c))return "cc-sky";
    if(/proteasome/.test(c))return "cc-plum";
    if(/kinase|mtor|bcl|inhibitor/.test(c))return "cc-lime";
    if(/enzyme|cytokine|differen|immunomod|microtubule/.test(c))return "cc-slate";
    return "cc-slate";
  }
  var listEl=document.getElementById('list');
  var countEl=document.getElementById('count');
  var current=[];

  function riskClass(r){return r==="High"?"High":r==="Low"?"Low":"na";}
  function esc(s){return (s==null?"":String(s)).replace(/[&<>]/g,function(c){return{'&':'&amp;','<':'&lt;','>':'&gt;'}[c];});}
  function isY(v){return /^y/i.test(String(v||""));}

  var ic={
    light:'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 3v2M5 5l1.5 1.5M3 12h2M19 5l-1.5 1.5M21 12h-2M9 18h6M10 21h4"/><circle cx="12" cy="12" r="4"/></svg>',
    filter:'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 5h18l-7 8v6l-4 2v-8z"/></svg>',
    cstd:'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 3h6v4l3 6v6a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-6l3-6z"/><path d="M6 13h12"/></svg>',
    haz:'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 3 2 20h20z"/><path d="M12 9v5M12 17v.5"/></svg>'
  };

  function pill(on,key,label){
    if(on) return '<span class="flag-pill fp-'+key+'">'+ic[key]+label+'</span>';
    return '<span class="flag-pill fp-off">'+label+': No</span>';
  }
  function val(v){
    var dash = v==null||v===""||v==="—"||/^NA$/i.test(v);
    return '<div class="v'+(dash?' dash':'')+'">'+esc(dash?'—':v)+'</div>';
  }

  function formTag(d){
    if(d.form==="Oral") return '<span class="formtag t-oral">Oral — no reconstitution</span>';
    if(d.form==="Powder") return '<span class="formtag t-powder"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M8 2h8M9 2v5l-4 9a3 3 0 0 0 3 4h8a3 3 0 0 0 3-4l-4-9V2"/><path d="M6 15h12"/></svg>Powder — reconstitute first</span>';
    return '<span class="formtag t-solution"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M7 2h10M8 2v6l-3 11a2 2 0 0 0 2 3h10a2 2 0 0 0 2-3L18 8V2"/><path d="M5.5 14h13"/></svg>Ready solution — dilute only</span>';
  }
  function card(d){
    if(d.chart==="general") return cardGeneral(d);
    var rc=riskClass(d.risk);
    var riskLabel = d.risk==="High"?"High risk":d.risk==="Low"?"Low risk":"Not listed";
    var pots = d._potLabels.length
      ? d._potLabels.map(function(l,i){return '<span class="pot '+d._potGroups[i]+'">'+esc(l)+'</span>';}).join('')
      : '<span class="pot none">Not individually NIOSH-classified</span>';
    var reconSeg = d.needsRecon
      ? '<div class="seg-recon">Step 1 · Reconstitution</div>'+
        '<div class="cell"><div class="k">Diluent</div>'+val(d.rdil)+'</div>'+
        '<div class="cell"><div class="k">Volume</div>'+val(d.rvol)+'</div>'+
        '<div class="cell"><div class="k">Conc. after reconstitution</div>'+val(d.rconc)+'</div>'+
        '<div class="cell"><div class="k">Reconstituted-vial stability</div>'+val(d.vstab)+'</div>'
      : '';
    return '<div class="card r-'+rc+(d.highAlert?' alert':'')+(isY(d.haz)?' haz':'')+'">'+
      '<div class="chead">'+
        '<span class="gname">'+esc(d.g)+'</span>'+
        (d.b&&d.b!=="—"?'<span class="brand">'+esc(d.b)+'</span>':'')+
        (d.m&&d.m!=="—"?'<span class="mfr">'+esc(d.m)+'</span>':'')+
        '<span class="badges">'+
          (isY(d.haz)
            ? '<span class="badge b-haz"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><path d="M12 3 2 20h20z"/><path d="M12 10v4M12 17v.5"/></svg>HAZARDOUS</span>'
            : '<span class="badge b-nothaz">Non-hazardous</span>')+
          (d.highAlert?'<span class="badge b-alert">⚠ High alert</span>':'')+
          '<span class="badge b-'+rc+'">'+riskLabel+'</span>'+
        '</span>'+
        (d.cat&&d.cat!=="—"?'<span class="cat"><span class="catdot '+catColor(d)+'"></span><b>Class:</b> '+esc(d.cat)+'</span>':'')+
        (d.ind?'<span class="ind"><b>Used for</b> &nbsp;'+esc(d.ind)+'</span>':'')+
      '</div>'+
      '<div class="metarow">'+formTag(d)+'<span class="pots"><span class="plabel">Hazard potential</span>'+pots+'</span></div>'+
      '<div class="flags">'+
        pill(isY(d.light),'light','Protect from light')+
        pill(isY(d.filter),'filter','In-line filter')+
        pill(isY(d.cstd),'cstd','CSTD')+
      '</div>'+
      '<div class="grid">'+
        '<div class="seg-vial">Vial</div>'+
        '<div class="cell"><div class="k">Storage (intact vial)</div>'+val(d.vstore)+'</div>'+
        '<div class="cell"><div class="k">Vial size</div>'+val(d.vsize)+'</div>'+
        reconSeg+
        '<div class="seg-dil">'+(d.needsRecon?'Step 2 · Dilution &amp; administration':'Dilution &amp; administration')+'</div>'+
        '<div class="cell"><div class="k">Diluent</div>'+val(d.dil)+'</div>'+
        '<div class="cell"><div class="k">Dilution volume</div>'+val(d.dvol)+'</div>'+
        '<div class="cell"><div class="k">Final concentration</div>'+val(d.fconc)+'</div>'+
        '<div class="cell"><div class="k">Stability after dilution</div>'+val(d.dstab)+'</div>'+
      '</div>'+
    '</div>';
  }

  function cardGeneral(d){
    var reconSeg = d.needsRecon
      ? '<div class="seg-recon">Reconstitution</div>'+
        '<div class="cell"><div class="k">Diluent</div>'+val(d.rdil)+'</div>'+
        '<div class="cell"><div class="k">Volume</div>'+val(d.rvol)+'</div>'+
        '<div class="cell span2"><div class="k">Final concentration</div>'+val(d.rconc)+'</div>'
      : '<div class="cell span2"><div class="k">Final concentration</div>'+val(d.rconc)+'</div>';
    return '<div class="card r-na">'+
      '<div class="chead">'+
        '<span class="gname">'+esc(d.g)+'</span>'+
        (d.b&&d.b!=="—"?'<span class="brand">'+esc(d.b)+'</span>':'')+
        (d.m&&d.m!=="—"?'<span class="mfr">'+esc(d.m)+'</span>':'')+
        '<span class="badges"><span class="badge b-gcat '+catColor(d)+'">'+esc(d.gcat)+'</span></span>'+
      '</div>'+
      '<div class="metarow">'+formTag(d)+'</div>'+
      '<div class="grid">'+
        '<div class="seg-vial">Vial</div>'+
        '<div class="cell"><div class="k">Initial strength</div>'+val(d.vsize)+'</div>'+
        '<div class="cell"><div class="k">Storage (intact vial)</div>'+val(d.vstore)+'</div>'+
        reconSeg+
        '<div class="seg-dil">Stability after reconstitution</div>'+
        '<div class="cell"><div class="k">Room temperature</div>'+val(d.rt)+'</div>'+
        '<div class="cell"><div class="k">Refrigerated</div>'+val(d.fr)+'</div>'+
        (d.special?'<div class="cell span2"><div class="k">Special conditions</div>'+val(d.special)+'</div>':'')+
      '</div>'+
    '</div>';
  }

  function match(d){
    if(state.form.size && !state.form.has(d.form)) return false;
    if(state.gcat.size && !state.gcat.has(d.gcat)) return false;
    if(state.cls.size && !state.cls.has(d.cls)) return false;
    if(state.risk.size && !state.risk.has(d.risk)) return false;
    if(state.flag.size){
      for(var f of state.flag){ if(!isY(d[f])) return false; }
    }
    if(state.pot.size){
      var hit=false;
      for(var p of state.pot){ if(d._potLabels.indexOf(p)>-1){hit=true;break;} }
      if(!hit) return false;
    }
    if(state.tumor.size){
      var hitT=false;
      for(var tg of state.tumor){ if(d._indGroups.indexOf(tg)>-1){hitT=true;break;} }
      if(!hitT) return false;
    }
    if(state.desig.has("highAlert") && !d.highAlert) return false;
    if(state.q){
      var hay=((d.g||"")+" "+(d.b||"")+" "+(d.m||"")+" "+(d.cat||"")+" "+(d.ind||"")+" "+(d.gcat||"")).toLowerCase();
      if(hay.indexOf(state.q)===-1) return false;
    }
    return true;
  }

  function render(){
    var data=active();
    var rows=data.filter(match);
    current=rows;
    var label=state.chart==="general"?"IV medications":"antineoplastic products";
    countEl.innerHTML='<b>'+rows.length+'</b> of '+data.length+' '+label;
    if(!rows.length){
      listEl.innerHTML='<div class="empty"><b>No matches</b>Try clearing a filter or adjusting your search.</div>';
      return;
    }
    listEl.innerHTML=rows.map(card).join('');
  }

  document.getElementById('q').addEventListener('input',function(e){
    state.q=e.target.value.trim().toLowerCase();render();updateActive();
  });

  // Active-filter tracking
  var FILTERSETS=[
    {key:"form",id:"f-form"},
    {key:"cls",id:"f-cls"},
    {key:"risk",id:"f-risk",suffix:" risk"},
    {key:"flag",id:"f-flag",labels:{light:"Light protection",filter:"In-line filter",cstd:"CSTD",haz:"Hazardous"}},
    {key:"pot",id:"f-pot"},
    {key:"tumor",id:"f-tumor"},
    {key:"desig",id:"f-desig",labels:{highAlert:"High alert"}},
    {key:"gcat",id:"f-gcat"}
  ];
  var afEl=document.getElementById('activefilters');
  var fcountEl=document.getElementById('fcount');
  function labelFor(fs,v){return (fs.labels&&fs.labels[v])||v+(fs.suffix||"");}
  function removeFilter(key,v){
    state[key].delete(v);
    var fs=FILTERSETS.filter(function(f){return f.key===key;})[0];
    var btn=document.querySelector('#'+fs.id+' .chip[data-v="'+(window.CSS&&CSS.escape?CSS.escape(v):v)+'"]');
    if(!btn){document.querySelectorAll('#'+fs.id+' .chip').forEach(function(c){if(c.dataset.v===v)btn=c;});}
    if(btn) btn.setAttribute('aria-pressed','false');
    render();updateActive();
  }
  function updateActive(){
    var total=0, html="";
    FILTERSETS.forEach(function(fs){
      if(fs.key==="form"){ /* applies to both charts */ }
      else if(state.chart==="general" && fs.key!=="gcat") return;
      else if(state.chart==="chemo" && fs.key==="gcat") return;
      state[fs.key].forEach(function(v){
        total++;
        html+='<span class="afchip">'+esc(labelFor(fs,v))+'<button data-k="'+fs.key+'" data-v="'+esc(v)+'" aria-label="Remove filter">\u00d7</button></span>';
      });
    });
    if(total){afEl.innerHTML=html;afEl.hidden=false;fcountEl.textContent=total;fcountEl.hidden=false;}
    else{afEl.innerHTML="";afEl.hidden=true;fcountEl.hidden=true;}
  }
  afEl.addEventListener('click',function(e){
    var b=e.target.closest('button');if(!b)return;
    removeFilter(b.dataset.k,b.dataset.v);
  });

  function wire(id,key){
    document.getElementById(id).addEventListener('click',function(e){
      var b=e.target.closest('.chip');if(!b)return;
      var v=b.dataset.v, on=b.getAttribute('aria-pressed')==="true";
      b.setAttribute('aria-pressed',String(!on));
      if(on) state[key].delete(v); else state[key].add(v);
      render();updateActive();
    });
  }
  wire('f-cls','cls');wire('f-risk','risk');wire('f-flag','flag');wire('f-pot','pot');wire('f-desig','desig');wire('f-tumor','tumor');wire('f-gcat','gcat');wire('f-form','form');

  // Filter panel open/close
  var panel=document.getElementById('filterpanel');
  var fToggle=document.getElementById('filterToggle');
  var backdrop=document.createElement('div');backdrop.className='sheet-backdrop';document.body.appendChild(backdrop);
  function setPanel(o){
    panel.classList.toggle('open',o);
    fToggle.setAttribute('aria-expanded',String(o));
    document.body.classList.toggle('sheet-open',o);
  }
  fToggle.addEventListener('click',function(){setPanel(!panel.classList.contains('open'));});
  document.getElementById('filterDone').addEventListener('click',function(){setPanel(false);});
  backdrop.addEventListener('click',function(){setPanel(false);});

  function clearFilters(){
    var chart=state.chart;
    state={q:"",cls:new Set(),risk:new Set(),flag:new Set(),pot:new Set(),desig:new Set(),tumor:new Set(),gcat:new Set(),form:new Set(),chart:chart};
    document.getElementById('q').value="";
    document.querySelectorAll('.chip').forEach(function(c){c.setAttribute('aria-pressed','false');});
    updateActive();
  }
  document.getElementById('reset').addEventListener('click',function(){clearFilters();render();});

  // Chart switch (antineoplastic vs general IV)
  document.querySelector('.chartswitch').addEventListener('click',function(e){
    var b=e.target.closest('button');if(!b)return;
    if(state.chart===b.dataset.c) return;
    this.querySelectorAll('button').forEach(function(x){x.setAttribute('aria-pressed',String(x===b));});
    state.chart=b.dataset.c;
    document.body.setAttribute('data-chart',state.chart);
    clearFilters();
    render();
  });

  // Theme switcher
  document.getElementById('themeseg').addEventListener('click',function(e){
    var b=e.target.closest('button');if(!b)return;
    document.documentElement.setAttribute('data-theme',b.dataset.t);
    this.querySelectorAll('button').forEach(function(x){
      x.setAttribute('aria-pressed',String(x===b));});
  });

  // Share / Print
  document.getElementById('print').addEventListener('click',function(){window.print();});

  function buildSelfContainedHTML(){
    // Serialize the current document so the shared/saved copy is fully interactive
    // and self-contained (all data + scripts are inline). Reset to default view first.
    var doc=document.documentElement.cloneNode(true);
    var list=doc.querySelector('#list'); if(list) list.innerHTML="";       // scripts rebuild on open
    var af=doc.querySelector('#activefilters'); if(af){af.innerHTML="";af.setAttribute('hidden','');}
    var fp=doc.querySelector('#filterpanel'); if(fp) fp.classList.remove('open');
    return "<!DOCTYPE html>\n"+doc.outerHTML;
  }
  function shareOrDownloadFile(){
    var html=buildSelfContainedHTML();
    var fname="compounding-reference.html";
    var blob=new Blob([html],{type:"text/html"});
    // Try native file share (best on phones — AirDrop / WhatsApp / email as a real file)
    try{
      if(navigator.canShare){
        var file=new File([blob],fname,{type:"text/html"});
        if(navigator.canShare({files:[file]})){
          navigator.share({files:[file],title:"Compounding Reference",
            text:"Open this file in your browser (Safari/Chrome) for the full interactive reference."})
            .then(function(){flash("Shared. Tell the recipient to OPEN IT IN A BROWSER, not a preview.");})
            .catch(function(){downloadFile(blob,fname);});
          return;
        }
      }
    }catch(e){}
    downloadFile(blob,fname);
  }
  function downloadFile(blob,fname){
    var a=document.createElement("a");
    a.href=URL.createObjectURL(blob);a.download=fname;
    document.body.appendChild(a);a.click();
    setTimeout(function(){URL.revokeObjectURL(a.href);a.remove();},100);
    flash("Saved an interactive copy. Open the .html file in a browser (Safari/Chrome) — not a Drive/chat preview — for full interactivity.");
  }
  document.getElementById('share').addEventListener('click',shareOrDownloadFile);

  function flash(msg){
    var n=document.getElementById('flash');
    if(!n){n=document.createElement('div');n.id='flash';n.className='flash';document.body.appendChild(n);}
    n.textContent=msg;n.classList.add('show');
    clearTimeout(n._t);n._t=setTimeout(function(){n.classList.remove('show');},6000);
  }

  // Export current (filtered) view to Excel — fully offline, no libraries
  var COLS_CHEMO=[
    ["Generic name","g"],["Brand","b"],["Manufacturer","m"],
    ["High alert","_ha"],
    ["Class (drug category)","cat"],["Used for (indications)","ind"],["NIOSH group","cls"],["Hazard risk (NIOSH)","risk"],
    ["Hazard potential","pot"],
    ["Vial storage","vstore"],["Vial size","vsize"],
    ["Recon. diluent","rdil"],["Recon. volume","rvol"],["Conc. after recon.","rconc"],
    ["Stability after recon. (vial)","vstab"],
    ["Diluent","dil"],["Dilution volume","dvol"],["Final concentration","fconc"],
    ["Stability after dilution","dstab"],
    ["Protect from light","light"],["In-line filter","filter"],["CSTD","cstd"],["Hazardous","haz"]
  ];
  var COLS_GENERAL=[
    ["Generic name","g"],["Brand","b"],["Manufacturer","m"],["Category","gcat"],
    ["Initial vial strength","vsize"],["Intact-vial storage","vstore"],
    ["Diluent","rdil"],["Diluent volume","rvol"],["Final concentration","rconc"],
    ["Stability — room temp","rt"],["Stability — refrigerated","fr"],["Special conditions","special"]
  ];
  function cols(){return state.chart==="general"?COLS_GENERAL:COLS_CHEMO;}
  function stamp(){var d=new Date();return d.toISOString().slice(0,10);}
  function rowsForExport(){
    var C=cols();
    return current.map(function(d){
      return C.map(function(c){
        if(c[1]==="_ha") return d.highAlert?"Yes":"";
        var v=d[c[1]];return (v==null||v==="")?"":String(v);
      });
    });
  }

  // --- minimal CRC32 ---
  var CRCT=(function(){var t=[],c,n,k;for(n=0;n<256;n++){c=n;for(k=0;k<8;k++)c=(c&1)?(0xEDB88320^(c>>>1)):(c>>>1);t[n]=c>>>0;}return t;})();
  function crc32(u8){var c=0xFFFFFFFF;for(var i=0;i<u8.length;i++)c=CRCT[(c^u8[i])&0xFF]^(c>>>8);return (c^0xFFFFFFFF)>>>0;}
  function u8(s){return new TextEncoder().encode(s);}
  function xesc(s){return String(s).replace(/[&<>]/g,function(c){return{'&':'&amp;','<':'&lt;','>':'&gt;'}[c];});}
  function colLetter(n){var s="";n++;while(n>0){var m=(n-1)%26;s=String.fromCharCode(65+m)+s;n=(n-m-1)/26;}return s;}

  // --- minimal store-method ZIP ---
  function zip(files){
    var parts=[],central=[],offset=0;
    function push16(arr,v){arr.push(v&0xFF,(v>>8)&0xFF);}
    function push32(arr,v){arr.push(v&0xFF,(v>>8)&0xFF,(v>>16)&0xFF,(v>>24)&0xFF);}
    files.forEach(function(f){
      var name=u8(f.name), data=f.data, crc=crc32(data);
      var lh=[];push32(lh,0x04034b50);push16(lh,20);push16(lh,0);push16(lh,0);push16(lh,0);push16(lh,0);
      push32(lh,crc);push32(lh,data.length);push32(lh,data.length);push16(lh,name.length);push16(lh,0);
      var lhu=new Uint8Array(lh);
      parts.push(lhu,name,data);
      var ch=[];push32(ch,0x02014b50);push16(ch,20);push16(ch,20);push16(ch,0);push16(ch,0);push16(ch,0);push16(ch,0);
      push32(ch,crc);push32(ch,data.length);push32(ch,data.length);push16(ch,name.length);
      push16(ch,0);push16(ch,0);push16(ch,0);push16(ch,0);push32(ch,0);push32(ch,offset);
      central.push(new Uint8Array(ch),name);
      offset += lhu.length+name.length+data.length;
    });
    var cdStart=offset, cdSize=0;
    central.forEach(function(p){cdSize+=p.length;});
    var eo=[];function p16(v){eo.push(v&0xFF,(v>>8)&0xFF);}function p32(v){eo.push(v&0xFF,(v>>8)&0xFF,(v>>16)&0xFF,(v>>24)&0xFF);}
    p32(0x06054b50);p16(0);p16(0);p16(files.length);p16(files.length);p32(cdSize);p32(cdStart);p16(0);
    var blobParts=parts.concat(central);blobParts.push(new Uint8Array(eo));
    return new Blob(blobParts,{type:"application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"});
  }

  function sheetXml(header,rows){
    var widths=cols().map(function(c,i){
      var w=c[0].length;rows.forEach(function(r){if(r[i]&&r[i].length>w)w=r[i].length;});
      return Math.min(Math.max(w+2,12),52);
    });
    var cols='<cols>'+widths.map(function(w,i){return '<col min="'+(i+1)+'" max="'+(i+1)+'" width="'+w+'" customWidth="1"/>';}).join('')+'</cols>';
    function rowXml(arr,rn){
      var cells=arr.map(function(v,i){
        return '<c r="'+colLetter(i)+rn+'" t="inlineStr"><is><t xml:space="preserve">'+xesc(v)+'</t></is></c>';
      }).join('');
      return '<row r="'+rn+'">'+cells+'</row>';
    }
    var body=[rowXml(header,1)];
    rows.forEach(function(r,i){body.push(rowXml(r,i+2));});
    return '<?xml version="1.0" encoding="UTF-8" standalone="yes"?>'+
      '<worksheet xmlns="http://schemas.openxmlformats.org/spreadsheetml/2006/main">'+
      '<sheetViews><sheetView workbookViewId="0"><pane ySplit="1" topLeftCell="A2" activePane="bottomLeft" state="frozen"/></sheetView></sheetViews>'+
      cols+'<sheetData>'+body.join('')+'</sheetData></worksheet>';
  }

  function exportXLSX(){
    var header=cols().map(function(c){return c[0];});
    var rows=rowsForExport();
    var ct='<?xml version="1.0" encoding="UTF-8" standalone="yes"?><Types xmlns="http://schemas.openxmlformats.org/package/2006/content-types"><Default Extension="rels" ContentType="application/vnd.openxmlformats-package.relationships+xml"/><Default Extension="xml" ContentType="application/xml"/><Override PartName="/xl/workbook.xml" ContentType="application/vnd.openxmlformats-officedocument.spreadsheetml.sheet.main+xml"/><Override PartName="/xl/worksheets/sheet1.xml" ContentType="application/vnd.openxmlformats-officedocument.spreadsheetml.worksheet+xml"/></Types>';
    var rels='<?xml version="1.0" encoding="UTF-8" standalone="yes"?><Relationships xmlns="http://schemas.openxmlformats.org/package/2006/relationships"><Relationship Id="rId1" Type="http://schemas.openxmlformats.org/officeDocument/2006/relationships/officeDocument" Target="xl/workbook.xml"/></Relationships>';
    var wb='<?xml version="1.0" encoding="UTF-8" standalone="yes"?><workbook xmlns="http://schemas.openxmlformats.org/spreadsheetml/2006/main" xmlns:r="http://schemas.openxmlformats.org/officeDocument/2006/relationships"><sheets><sheet name="Stability Reference" sheetId="1" r:id="rId1"/></sheets></workbook>';
    var wbr='<?xml version="1.0" encoding="UTF-8" standalone="yes"?><Relationships xmlns="http://schemas.openxmlformats.org/package/2006/relationships"><Relationship Id="rId1" Type="http://schemas.openxmlformats.org/officeDocument/2006/relationships/worksheet" Target="worksheets/sheet1.xml"/></Relationships>';
    var files=[
      {name:"[Content_Types].xml",data:u8(ct)},
      {name:"_rels/.rels",data:u8(rels)},
      {name:"xl/workbook.xml",data:u8(wb)},
      {name:"xl/_rels/workbook.xml.rels",data:u8(wbr)},
      {name:"xl/worksheets/sheet1.xml",data:u8(sheetXml(header,rows))}
    ];
    var blob=zip(files);
    var a=document.createElement("a");
    a.href=URL.createObjectURL(blob);
    a.download=(state.chart==="general"?"iv-reconstitution-":"compounding-stability-")+stamp()+".xlsx";
    document.body.appendChild(a);a.click();
    setTimeout(function(){URL.revokeObjectURL(a.href);a.remove();},100);
  }
  function exportCSV(){
    var header=cols().map(function(c){return c[0];});
    var lines=[header].concat(rowsForExport()).map(function(r){
      return r.map(function(v){v=String(v==null?"":v);return /[",\n]/.test(v)?'"'+v.replace(/"/g,'""')+'"':v;}).join(",");
    });
    var blob=new Blob(["\ufeff"+lines.join("\r\n")],{type:"text/csv;charset=utf-8;"});
    var a=document.createElement("a");a.href=URL.createObjectURL(blob);
    a.download=(state.chart==="general"?"iv-reconstitution-":"compounding-stability-")+stamp()+".csv";
    document.body.appendChild(a);a.click();
    setTimeout(function(){URL.revokeObjectURL(a.href);a.remove();},100);
  }
  document.getElementById('export').addEventListener('click',function(){
    if(!current.length){return;}
    try{exportXLSX();}catch(err){try{exportCSV();}catch(e){}}
  });

  // ---------------- Study & Exam ----------------
  var study={deck:"chemo",mode:"flip",order:[],pos:0,known:new Set(),review:new Set(),
             qn:0,qtotal:15,score:0,answered:false,curQ:null,_init:false};
  function studyDeck(){return study.deck==="general"?GEN:MEDS;}
  function shuffle(a){for(var i=a.length-1;i>0;i--){var j=Math.floor(Math.random()*(i+1));var t=a[i];a[i]=a[j];a[j]=t;}return a;}

  function factsRows(d){
    var rows=[];
    function row(k,v){if(v==null||v===""||v==="—")v="—";rows.push('<div class="fc-row"><div class="fk">'+esc(k)+'</div><div class="fv">'+esc(v)+'</div></div>');}
    if(d.chart==="general"){
      row("Category",d.gcat);row("Vial strength",d.vsize);row("Intact-vial storage",d.vstore);
      row("Diluent",d.rdil);row("Diluent volume",d.rvol);row("Final concentration",d.rconc);
      row("Stability — room temp",d.rt);row("Stability — refrigerated",d.fr);
      if(d.special)row("Special conditions",d.special);
    }else{
      row("Class",d.cat);row("Hazardous",isY(d.haz)?"Yes":"No");row("High alert",d.highAlert?"Yes":"No");
      row("NIOSH risk",d.risk);row("Hazard potential",d.pot||"—");
      row("Recon. diluent",d.rdil);row("Recon. volume",d.rvol);row("Conc. after recon.",d.rconc);
      row("Vial stability",d.vstab);row("Diluent (dilution)",d.dil);row("Dilution volume",d.dvol);
      row("Stability after dilution",d.dstab);
      var req=[isY(d.light)?"Light":"",isY(d.filter)?"Filter":"",isY(d.cstd)?"CSTD":""].filter(Boolean).join(", ");
      row("Requires",req||"none of light/filter/CSTD");
      row("Used for",d.ind);
    }
    return rows.join('');
  }
  function subOf(d){return [d.b&&d.b!=="—"?d.b:"",d.m&&d.m!=="—"?d.m:""].filter(Boolean).join(" · ");}

  // ----- Flip cards -----
  function startFlip(indices){
    study.order=shuffle(indices.slice());study.pos=0;study.known=new Set();study.review=new Set();
    renderFlip();
  }
  function renderFlip(){
    var deck=studyDeck();
    if(study.pos>=study.order.length){return showFlipDone();}
    document.getElementById('fcDone').hidden=true;
    document.getElementById('flashcard').style.display='';
    document.querySelector('#flipStage .fc-ctrl').style.display='';
    document.getElementById('fcHint').style.display='';
    var d=deck[study.order[study.pos]];
    var fc=document.getElementById('flashcard');fc.classList.remove('flipped');
    var badges="";
    if(d.chart!=="general"){
      if(isY(d.haz))badges+='<span class="badge b-haz">HAZARDOUS</span>';
      if(d.highAlert)badges+='<span class="badge b-alert">⚠ High alert</span>';
    }else{badges+='<span class="badge b-gcat">'+esc(d.gcat)+'</span>';}
    var prompt=d.chart==="general"?"Recall: diluent, volume, final conc & stability":"Recall: reconstitution, stability & hazard profile";
    document.getElementById('fcFront').innerHTML='<div class="fc-name">'+esc(d.g)+'</div>'+(subOf(d)?'<div class="fc-sub">'+esc(subOf(d))+'</div>':'')+'<div class="fc-badges">'+badges+'</div><div class="fc-prompt">'+prompt+'</div>';
    document.getElementById('fcBack').innerHTML='<div class="fc-bname">'+esc(d.g)+'</div><div class="fc-bsub">'+esc(subOf(d))+'</div>'+factsRows(d);
    updateStudyMeta();
  }
  function gradeFlip(good){
    var idx=study.order[study.pos];
    if(good){study.known.add(idx);study.review.delete(idx);}else{study.review.add(idx);study.known.delete(idx);}
    study.pos++;renderFlip();
  }
  function showFlipDone(){
    document.getElementById('flashcard').style.display='none';
    document.querySelector('#flipStage .fc-ctrl').style.display='none';
    document.getElementById('fcHint').style.display='none';
    var done=document.getElementById('fcDone');done.hidden=false;
    var total=study.order.length,known=study.known.size,review=study.review.size;
    done.innerHTML='<h3>Deck complete</h3><div class="big">'+known+'/'+total+'</div><div>marked “got it”'+(review?', '+review+' to review':'')+'.</div><div class="donebtns">'+(review?'<button class="linkbtn" id="fcReviewOnly">Review the '+review+' missed</button>':'')+'<button class="toolbtn" id="fcRestart">Restart deck</button></div>';
    document.getElementById('fcRestart').onclick=function(){startFlip(studyDeck().map(function(_,i){return i;}));};
    if(review)document.getElementById('fcReviewOnly').onclick=function(){startFlip(Array.from(study.review));};
    updateStudyMeta();
  }

  // ----- Quiz (MCQ) -----
  var TUMOR_NAMES=["Breast","Lung","GI","Lymphoma","Leukemia","Myeloma","GU","Gynecologic","Head & Neck","Melanoma/Skin","CNS","Sarcoma","Pediatric"];
  function uniqVals(deck,f){var s=[];deck.forEach(function(d){var v=d[f];if(v&&v!=="—"&&!/^NA$/i.test(v)&&s.indexOf(v)<0)s.push(v);});return s;}
  function pickN(arr,n,exclude){var pool=arr.filter(function(x){return exclude.indexOf(x)<0;});shuffle(pool);return pool.slice(0,n);}
  function buildQuestion(){
    var deck=studyDeck();
    var fields=study.deck==="general"
      ?[{tag:"Reconstitution diluent",q:"Which diluent is used to reconstitute",f:"rdil"},
        {tag:"Reconstitution volume",q:"What reconstitution (diluent) volume is used for",f:"rvol"},
        {tag:"Concentration after reconstitution",q:"What is the concentration after reconstitution of",f:"rconc"},
        {tag:"Stability — room temperature",q:"Room-temperature stability after reconstitution of",f:"rt"},
        {tag:"Stability — refrigerated",q:"Refrigerated stability after reconstitution of",f:"fr"}]
      :[{tag:"Reconstitution diluent",q:"Which diluent is used to reconstitute",f:"rdil"},
        {tag:"Reconstitution volume",q:"What reconstitution volume is used for",f:"rvol"},
        {tag:"Concentration after reconstitution",q:"What is the concentration after reconstitution of",f:"rconc"},
        {tag:"Reconstituted-vial stability",q:"What is the reconstituted-vial stability of",f:"vstab"},
        {tag:"Dilution volume",q:"What is the typical dilution volume for",f:"dvol"},
        {tag:"Stability after dilution",q:"What is the stability after dilution of",f:"dstab"}];
    for(var a=0;a<80;a++){
      var d=deck[Math.floor(Math.random()*deck.length)];
      var fld=fields[Math.floor(Math.random()*fields.length)];
      var v=d[fld.f];
      if(!v||v==="—"||/^NA$/i.test(v)||/^verify/i.test(v))continue;
      var dis2=pickN(uniqVals(deck,fld.f),3,[v]);
      if(dis2.length<3)continue;
      return {tag:fld.tag,q:fld.q+" <b>"+esc(d.g)+"</b>?",correct:v,opts:shuffle([v].concat(dis2))};
    }
    return null;
  }
  function startQuiz(){study.qn=0;study.score=0;study.qtotal=Math.min(15,studyDeck().length);renderQuiz();}
  function renderQuiz(){
    document.getElementById('quizDone').hidden=true;
    document.getElementById('quizCard').style.display='';
    if(study.qn>=study.qtotal)return showQuizDone();
    var Q=buildQuestion();if(!Q)return showQuizDone();
    study.curQ=Q;study.answered=false;
    document.getElementById('quizTag').textContent=Q.tag;
    document.getElementById('quizQ').innerHTML=Q.q;
    var opts=document.getElementById('quizOpts');opts.innerHTML='';
    Q.opts.forEach(function(o){var b=document.createElement('button');b.className='quiz-opt';b.textContent=o;b.dataset.v=o;b.onclick=function(){answerQuiz(o,b);};opts.appendChild(b);});
    document.getElementById('quizFb').hidden=true;
    document.getElementById('quizNext').hidden=true;
    updateStudyMeta();
  }
  function answerQuiz(val,btn){
    if(study.answered)return;study.answered=true;study.qn++;
    var Q=study.curQ,ok=val===Q.correct;if(ok)study.score++;
    document.querySelectorAll('#quizOpts .quiz-opt').forEach(function(b){b.disabled=true;if(b.dataset.v===Q.correct)b.classList.add('correct');else if(b===btn)b.classList.add('wrong');});
    var fb=document.getElementById('quizFb');fb.className='quiz-fb '+(ok?'ok':'no');
    fb.innerHTML=(ok?'Correct':'Not quite')+'<span class="ans">Answer: '+esc(Q.correct)+'</span>';
    fb.hidden=false;document.getElementById('quizNext').hidden=false;updateStudyMeta();
  }
  function showQuizDone(){
    document.getElementById('quizCard').style.display='none';
    var done=document.getElementById('quizDone');done.hidden=false;
    var pct=study.qn?Math.round(study.score/study.qn*100):0;
    done.innerHTML='<h3>Quiz complete</h3><div class="big">'+study.score+'/'+study.qn+'</div><div>'+pct+'% correct</div><div class="donebtns"><button class="linkbtn" id="quizAgain">New quiz</button></div>';
    document.getElementById('quizAgain').onclick=startQuiz;
  }

  function updateStudyMeta(){
    var m=document.getElementById('studymeta');if(!m)return;
    if(study.mode==="flip"){
      var total=study.order.length;
      m.textContent=(study.pos>=total?'Done':'Card '+(study.pos+1)+'/'+total)+'  ·  ✓ '+study.known.size+'  ⟳ '+study.review.size;
    }else{
      m.textContent='Q '+Math.min(study.qn+1,study.qtotal)+'/'+study.qtotal+'  ·  Score '+study.score;
    }
  }
  function applyStudyMode(){
    document.getElementById('flipStage').hidden=study.mode!=="flip";
    document.getElementById('quizStage').hidden=study.mode!=="quiz";
    if(study.mode==="flip")startFlip(studyDeck().map(function(_,i){return i;}));
    else startQuiz();
  }

  // Study wiring
  document.getElementById('flashcard').addEventListener('click',function(){this.classList.toggle('flipped');});
  document.getElementById('fcKnown').addEventListener('click',function(){gradeFlip(true);});
  document.getElementById('fcReview').addEventListener('click',function(){gradeFlip(false);});
  document.getElementById('fcNext').addEventListener('click',function(){study.pos++;renderFlip();});
  document.getElementById('fcPrev').addEventListener('click',function(){study.pos=Math.max(0,study.pos-1);renderFlip();});
  document.getElementById('quizNext').addEventListener('click',renderQuiz);
  document.getElementById('studyShuffle').addEventListener('click',function(){study.mode==="flip"?startFlip(studyDeck().map(function(_,i){return i;})):startQuiz();});
  document.getElementById('deckseg').addEventListener('click',function(e){var b=e.target.closest('button');if(!b||study.deck===b.dataset.d)return;this.querySelectorAll('button').forEach(function(x){x.setAttribute('aria-pressed',String(x===b));});study.deck=b.dataset.d;applyStudyMode();});
  document.getElementById('modeseg').addEventListener('click',function(e){var b=e.target.closest('button');if(!b||study.mode===b.dataset.m)return;this.querySelectorAll('button').forEach(function(x){x.setAttribute('aria-pressed',String(x===b));});study.mode=b.dataset.m;applyStudyMode();});

  // Page tabs (Reference / Study)
  document.getElementById('pagetabs').addEventListener('click',function(e){
    var b=e.target.closest('button');if(!b)return;
    var p=b.dataset.p;
    this.querySelectorAll('button').forEach(function(x){x.setAttribute('aria-pressed',String(x===b));});
    document.getElementById('refPage').hidden=p!=="ref";
    document.getElementById('studyPage').hidden=p!=="study";
    if(p==="study"&&!study._init){study._init=true;applyStudyMode();}
    window.scrollTo(0,0);
  });

  document.body.setAttribute('data-chart','chemo');
  updateActive();
  render();
})();
</script>
</body>
</html>
