<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<meta name="theme-color" content="#0B3D91">
<meta name="apple-mobile-web-app-capable" content="yes">
<title>ShelfRx Pro – Boots T3</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=DM+Mono:wght@400;500&display=swap');
:root{
  --navy:#0B3D91;--teal:#00A3A3;--teal-bg:#E0F7F7;
  --cream:#F0F2F8;--white:#fff;--ink:#111827;--muted:#6B7280;
  --border:#E5E7EB;--green:#059669;--green-bg:#ECFDF5;
  --amber:#D97706;--amber-bg:#FFFBEB;--red:#DC2626;--red-bg:#FEF2F2;
  --wood:#C8A96E;--wood-dark:#8B5A2B;--shelf-bg:#FDF6E8;
  --r:12px;--rs:8px;
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
body{font-family:'Inter',sans-serif;background:#E8EBF2;color:var(--ink);min-height:100vh;overflow-x:hidden}
.topbar{background:var(--navy);color:#fff;padding:12px 16px 10px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:200;box-shadow:0 2px 12px rgba(0,0,0,.25)}
.tl{display:flex;align-items:center;gap:10px}
.tlogo{width:32px;height:32px;background:var(--teal);border-radius:9px;display:flex;align-items:center;justify-content:center;font-size:16px}
.ttitle{font-size:16px;font-weight:800}.tsub{font-size:10px;color:rgba(255,255,255,.5);margin-top:1px}
.topbtns{display:flex;gap:6px}
.tbtn{border:none;color:#fff;border-radius:9px;padding:7px 12px;font-size:11px;font-weight:700;cursor:pointer;display:flex;align-items:center;gap:4px;font-family:inherit}
.tbtn-scan{background:var(--teal)}.tbtn-add{background:rgba(255,255,255,.15)}
.tbtn:active{opacity:.75}
.screen{display:none;animation:fi .18s ease}.screen.active{display:block}
@keyframes fi{from{opacity:0;transform:translateY(4px)}to{opacity:1;transform:translateY(0)}}

/* RACK TABS */
.rack-tabs-wrap{background:var(--white);border-bottom:1px solid var(--border);padding:10px 14px;position:sticky;top:56px;z-index:100}
.rack-section-label{font-size:10px;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.6px;margin-bottom:6px}
.rack-tabs{display:flex;gap:5px;overflow-x:auto}.rack-tabs::-webkit-scrollbar{display:none}
.rack-tab{flex-shrink:0;padding:5px 13px;border-radius:20px;border:1.5px solid var(--border);background:var(--white);font-size:11px;font-weight:700;cursor:pointer;font-family:inherit;color:var(--muted);white-space:nowrap;transition:all .15s}
.rack-tab.active{background:var(--navy);color:#fff;border-color:var(--navy)}
.rack-tab.exp{border-color:var(--red);color:var(--red)}
.rack-tab.active.exp{background:var(--red);border-color:var(--red)}

/* EXPIRY BANNER */
.exp-banner{background:var(--red-bg);border-bottom:2px solid var(--red);padding:10px 14px}
.exp-banner-title{font-size:11px;font-weight:800;color:var(--red);margin-bottom:7px;text-transform:uppercase;letter-spacing:.5px}
.exp-grid{display:grid;grid-template-columns:1fr 1fr;gap:6px}
.exp-card{background:var(--white);border:2px solid var(--red);border-radius:8px;padding:8px}
.exp-card-name{font-size:10px;font-weight:700;margin-bottom:3px;line-height:1.3}
.exp-card-meta{font-size:9px;color:var(--red);font-weight:700;font-family:'DM Mono',monospace}
.exp-card-shelf{font-size:9px;color:var(--muted)}

/* RACK VISUAL - Like the actual photo */
.rack-container{padding:12px 14px 90px}
.rack-header{display:flex;align-items:center;gap:8px;margin-bottom:12px}
.rack-title{font-size:14px;font-weight:800}
.rack-chip{font-size:10px;font-weight:700;padding:3px 10px;border-radius:20px;text-transform:uppercase;letter-spacing:.4px}

/* THE ACTUAL RACK UNIT (wood frame) */
.rack-frame{
  background:linear-gradient(180deg,#A0784A 0%,#8B5A2B 100%);
  border-radius:10px;
  padding:4px;
  box-shadow:0 4px 20px rgba(0,0,0,.3),inset 0 1px 0 rgba(255,255,255,.2);
  margin-bottom:14px;
}
.rack-frame-inner{
  background:linear-gradient(180deg,#2A1F0E 0%,#3D2B0F 50%,#2A1F0E 100%);
  border-radius:8px;
  padding:3px 6px;
  display:flex;
  flex-direction:column;
  gap:3px;
}

/* INDIVIDUAL SHELF INSIDE RACK */
.shelf-unit{
  position:relative;
  background:var(--shelf-bg);
  border-radius:6px;
  overflow:hidden;
  cursor:pointer;
  transition:transform .12s;
  border:2px solid transparent;
}
.shelf-unit:active{transform:scale(.98)}
.shelf-unit.near-expiry{border:3px solid var(--red)!important;box-shadow:0 0 0 2px rgba(220,38,38,.25)!important}
.shelf-unit.s-low{border-color:rgba(217,119,6,.5)}
.shelf-unit.s-out{border-color:rgba(220,38,38,.4)}

/* SHELF TOP WOOD PLANK */
.shelf-plank-top{
  height:9px;
  background:linear-gradient(180deg,#D4A843 0%,#C8903A 40%,#B8782A 100%);
  position:relative;
}
.shelf-plank-top::after{
  content:'';position:absolute;top:0;left:0;right:0;height:2px;
  background:rgba(255,255,255,.3);border-radius:2px 2px 0 0;
}
.shelf-code-pill{
  position:absolute;left:6px;top:50%;transform:translateY(-50%);
  background:rgba(11,61,145,.85);color:#fff;
  font-size:8px;font-weight:700;padding:1px 6px;border-radius:10px;
  font-family:'DM Mono',monospace;letter-spacing:.3px;z-index:2;white-space:nowrap;
}
.shelf-expiry-badge{
  position:absolute;right:6px;top:50%;transform:translateY(-50%);
  background:var(--red);color:#fff;font-size:7px;font-weight:700;
  padding:1px 5px;border-radius:10px;z-index:2;animation:pulse 1.5s infinite;
}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.5}}

/* PRODUCT ROW ON SHELF (horizontal strip like in photo) */
.shelf-products-row{
  display:flex;
  align-items:flex-end;
  padding:5px 6px 0;
  min-height:80px;
  overflow-x:auto;
  gap:1px;
  background:linear-gradient(180deg,#FFF8EE 0%,#F5ECD6 70%,#EDD9B0 100%);
}
.shelf-products-row::-webkit-scrollbar{height:2px}
.shelf-products-row::-webkit-scrollbar-thumb{background:var(--wood);border-radius:1px}

/* PRODUCT SLOT (a single product standing on shelf) */
.prod-slot{
  flex-shrink:0;
  display:flex;flex-direction:column;align-items:center;
  cursor:pointer;
  position:relative;
  transition:transform .12s;
  padding-bottom:2px;
}
.prod-slot:active{transform:scale(.93)translateY(-2px)}
.prod-slot:hover .prod-slot-label{opacity:1}

/* PRODUCT IMAGE BOX (the product standing upright) */
.prod-img-box{
  width:46px;height:64px;
  border-radius:5px 5px 3px 3px;
  overflow:hidden;
  position:relative;
  box-shadow:1px 1px 3px rgba(0,0,0,.25);
  display:flex;align-items:center;justify-content:center;
  font-size:10px;font-weight:700;
  border:1px solid rgba(0,0,0,.1);
  background-size:cover;background-position:center;
}
.prod-img-box img{width:100%;height:100%;object-fit:cover;display:block}
.prod-img-box.out-of-stock{filter:grayscale(1);opacity:.45}
.prod-img-box.near-exp{box-shadow:0 0 0 2px var(--red),1px 1px 3px rgba(0,0,0,.25)!important}
.prod-slot-num-badge{
  position:absolute;top:2px;left:2px;
  background:rgba(11,61,145,.9);color:#fff;
  font-size:7px;font-weight:700;
  width:14px;height:14px;border-radius:50%;
  display:flex;align-items:center;justify-content:center;
  font-family:'DM Mono',monospace;
}
.exp-dot{position:absolute;top:2px;right:2px;width:7px;height:7px;background:var(--red);border-radius:50%;border:1px solid #fff}
.out-dot{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;background:rgba(0,0,0,.4);color:#fff;font-size:7px;font-weight:700;letter-spacing:.3px}
.prod-slot-name{
  font-size:7px;font-weight:600;color:var(--ink);
  width:46px;text-align:center;
  white-space:nowrap;overflow:hidden;text-overflow:ellipsis;
  margin-top:2px;line-height:1.2;
  opacity:.8;
}
.prod-slot-qty{
  font-size:7px;font-family:'DM Mono',monospace;font-weight:700;
  margin-top:1px;
}
.qty-ok{color:var(--green)}.qty-low{color:var(--amber)}.qty-out{color:var(--red)}

/* SHELF BOTTOM WOOD PLANK */
.shelf-plank-bottom{
  height:12px;
  background:linear-gradient(180deg,#C8903A 0%,#A0702A 50%,#8B5A2B 100%);
  border-radius:0 0 5px 5px;
  box-shadow:0 2px 4px rgba(0,0,0,.3);
}

/* SHELF EXPAND DETAIL */
.shelf-detail{display:none;background:var(--white);border-top:1px dashed var(--border)}
.shelf-detail.open{display:block}
.shelf-photo-area{
  height:65px;background:linear-gradient(135deg,#EEF2FF,#E0F7F7);
  display:flex;align-items:center;justify-content:center;
  cursor:pointer;position:relative;overflow:hidden;
}
.shelf-photo-area img{width:100%;height:100%;object-fit:cover}
.ph-label{position:absolute;bottom:4px;right:7px;background:rgba(255,255,255,.9);color:var(--navy);font-size:9px;font-weight:700;padding:2px 7px;border-radius:5px}
.prod-list{padding:8px 10px 8px}
.prod-row{display:flex;align-items:flex-start;gap:7px;padding:7px 0;border-bottom:1px solid var(--border)}
.prod-row:last-child{border-bottom:none;padding-bottom:0}
.prod-row-thumb{
  width:38px;height:50px;border-radius:5px;flex-shrink:0;
  overflow:hidden;display:flex;align-items:center;justify-content:center;
  cursor:pointer;position:relative;border:1px solid var(--border);
  background-size:cover;background-position:center;
}
.prod-row-thumb img{width:100%;height:100%;object-fit:cover}
.prod-row-thumb.ne{border:2px solid var(--red)!important}
.change-img-overlay{
  position:absolute;inset:0;background:rgba(0,0,0,.45);
  display:flex;align-items:center;justify-content:center;
  opacity:0;transition:opacity .18s;font-size:14px;
}
.prod-row-thumb:hover .change-img-overlay,.prod-row-thumb:active .change-img-overlay{opacity:1}
.prod-row-body{flex:1;min-width:0}
.prn{font-size:11px;font-weight:700;line-height:1.3;margin-bottom:2px}
.prc{font-size:9px;color:var(--muted);font-family:'DM Mono',monospace;margin-bottom:2px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.pr-tags{display:flex;gap:3px;flex-wrap:wrap;margin-bottom:2px}
.ptag{font-size:9px;font-weight:600;padding:1px 5px;border-radius:20px;font-family:'DM Mono',monospace}
.pt-f{background:#EEF2FF;color:#4338CA}.pt-e{background:var(--red-bg);color:var(--red);font-weight:700}.pt-ok{background:var(--green-bg);color:var(--green)}.pt-n{background:#FFF7ED;color:#C2410C}
.remarks-lbl{font-size:9px;color:var(--muted);font-style:italic;line-height:1.3}
.prod-row-actions{display:flex;gap:3px;margin-top:3px}
.ibtn{width:22px;height:22px;border-radius:5px;background:var(--cream);border:none;cursor:pointer;display:flex;align-items:center;justify-content:center;color:var(--muted)}
.prod-row-right{display:flex;flex-direction:column;align-items:flex-end;gap:4px;flex-shrink:0}
.chip{font-size:8px;font-weight:700;padding:2px 6px;border-radius:20px;text-transform:uppercase}
.c-ok{background:var(--green-bg);color:var(--green)}.c-low{background:var(--amber-bg);color:var(--amber)}.c-out{background:var(--red-bg);color:var(--red)}
.c-exp{background:var(--red-bg);color:var(--red);animation:pulse 1.4s infinite}
.stock-ctrl{display:flex;align-items:center;gap:3px}
.sbtn{width:22px;height:22px;border-radius:50%;background:var(--cream);border:1.5px solid var(--border);font-size:13px;cursor:pointer;display:flex;align-items:center;justify-content:center}
.snum{font-family:'DM Mono',monospace;font-size:12px;font-weight:600;min-width:18px;text-align:center}
.add-btn{width:calc(100% - 16px);margin:0 8px 8px;padding:7px;background:var(--teal-bg);color:var(--teal);border:1.5px dashed var(--teal);border-radius:6px;font-family:inherit;font-size:11px;font-weight:700;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:4px}

/* BOTTOM NAV */
.bnav{position:fixed;bottom:0;left:0;right:0;background:var(--white);border-top:1px solid var(--border);display:flex;z-index:150;box-shadow:0 -3px 10px rgba(0,0,0,.08);padding-bottom:env(safe-area-inset-bottom)}
.nb{flex:1;padding:9px 0 7px;display:flex;flex-direction:column;align-items:center;gap:2px;background:none;border:none;cursor:pointer;color:var(--muted);font-family:inherit;font-size:9px;font-weight:700;text-transform:uppercase;letter-spacing:.5px;position:relative}
.nb.active{color:var(--navy)}.nb svg{width:20px;height:20px}
.ni{position:absolute;top:0;left:50%;transform:translateX(-50%);width:24px;height:3px;background:var(--navy);border-radius:0 0 3px 3px;opacity:0}
.nb.active .ni{opacity:1}

/* SUMMARY */
.sum-wrap{padding:14px 14px 90px}
.stat-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:12px}
.stat-card{background:var(--white);border-radius:var(--r);box-shadow:0 1px 4px rgba(0,0,0,.08);padding:12px;display:flex;align-items:center;gap:10px}
.sic{width:36px;height:36px;border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:17px;flex-shrink:0}
.sv{font-size:20px;font-weight:800;font-family:'DM Mono',monospace;line-height:1}.sl{font-size:10px;color:var(--muted);margin-top:2px}
.search-wrap{position:relative;margin-bottom:11px}
.search-inp{width:100%;padding:10px 12px 10px 36px;border:1.5px solid var(--border);border-radius:var(--rs);font-family:inherit;font-size:13px;background:var(--white);outline:none}
.search-inp:focus{border-color:var(--navy)}
.sico{position:absolute;left:11px;top:50%;transform:translateY(-50%);color:var(--muted)}
.all-card{background:var(--white);border-radius:var(--rs);padding:10px 11px;margin-bottom:7px;box-shadow:0 1px 4px rgba(0,0,0,.08);display:flex;align-items:flex-start;justify-content:space-between;gap:8px;border-left:4px solid var(--border);cursor:pointer}
.all-card.ne{border:2.5px solid var(--red)!important}
.lbl{font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:.6px;color:var(--muted);margin-bottom:8px}

/* MODALS */
.mbk{display:none;position:fixed;inset:0;background:rgba(0,0,0,.55);z-index:300;align-items:flex-end}
.mbk.open{display:flex}
.modal{background:var(--white);border-radius:12px 12px 0 0;width:100%;max-height:93vh;overflow-y:auto;padding:18px 15px 38px}
.mhandle{width:34px;height:4px;background:var(--border);border-radius:2px;margin:0 auto 14px}
.modal h3{font-size:15px;font-weight:800;margin-bottom:14px}
.fg{margin-bottom:11px}.fl{font-size:10px;font-weight:600;color:var(--muted);text-transform:uppercase;letter-spacing:.5px;margin-bottom:4px;display:block}
.fi{width:100%;padding:9px 11px;border:1.5px solid var(--border);border-radius:var(--rs);font-family:inherit;font-size:13px;color:var(--ink);background:var(--white);outline:none}
.fi:focus{border-color:var(--navy)}
.frow{display:grid;grid-template-columns:1fr 1fr;gap:9px}
.fsel{width:100%;padding:9px 11px;border:1.5px solid var(--border);border-radius:var(--rs);font-family:inherit;font-size:13px;color:var(--ink);background:var(--white);outline:none;appearance:none}
.btn-p{width:100%;padding:12px;background:var(--navy);color:#fff;border:none;border-radius:var(--rs);font-family:inherit;font-size:13px;font-weight:700;cursor:pointer;margin-top:5px}
.btn-p:active{opacity:.85}
.btn-s{width:100%;padding:10px;background:var(--cream);color:var(--muted);border:1.5px solid var(--border);border-radius:var(--rs);font-family:inherit;font-size:12px;font-weight:600;cursor:pointer;margin-top:7px}
.btn-t{width:100%;padding:10px;background:var(--teal);color:#fff;border:none;border-radius:var(--rs);font-family:inherit;font-size:12px;font-weight:700;cursor:pointer;margin-top:7px}
#scannerVideo{width:100%;border-radius:var(--r);background:#000;aspect-ratio:4/3;display:block}
.scan-stat-row{display:grid;grid-template-columns:1fr 1fr 1fr;gap:7px;margin:9px 0}
.ss{background:var(--cream);border-radius:7px;padding:8px;text-align:center}
.ssv{font-size:17px;font-weight:800;font-family:'DM Mono',monospace}.ssl{font-size:9px;color:var(--muted);margin-top:2px}
.sell-box{background:#EEF2FF;border-radius:var(--rs);padding:10px;margin-bottom:8px}
.sell-box-title{font-size:10px;font-weight:800;color:var(--navy);text-transform:uppercase;letter-spacing:.4px;margin-bottom:5px}
.sell-box-text{font-size:11px;line-height:1.6}
.lang-tabs{display:flex;gap:5px;flex-wrap:wrap;margin-bottom:8px}
.lang-btn{padding:4px 9px;border-radius:20px;border:1.5px solid var(--border);background:var(--white);font-size:10px;font-weight:700;cursor:pointer;font-family:inherit;color:var(--muted)}
.lang-btn.active{background:var(--navy);color:#fff;border-color:var(--navy)}
.trans-box{background:var(--cream);border-radius:var(--rs);padding:10px;min-height:44px;font-size:12px;line-height:1.7}
.trans-box.rtl{direction:rtl;text-align:right;font-size:13px}
</style>
</head>
<body>

<div class="topbar">
  <div class="tl">
    <div class="tlogo">💊</div>
    <div><div class="ttitle">ShelfRx Pro</div><div class="tsub">Boots T3 · MAY 2026</div></div>
  </div>
  <div class="topbtns">
    <button class="tbtn tbtn-scan" onclick="openScanner()">
      <svg width="12" height="12" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path d="M3 7V5a2 2 0 012-2h2M17 3h2a2 2 0 012 2v2M21 17v2a2 2 0 01-2 2h-2M7 21H5a2 2 0 01-2-2v-2"/><rect x="7" y="7" width="10" height="10" rx="1"/></svg>Scan
    </button>
    <button class="tbtn tbtn-add" id="topAddBtn" onclick="openAddModal()">
      <svg width="12" height="12" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path d="M12 5v14M5 12h14"/></svg>Add
    </button>
  </div>
</div>

<div class="screen active" id="screen-racks">
  <div id="expiryBanner"></div>
  <div class="rack-tabs-wrap">
    <div class="rack-section-label">Select Rack — Tap shelf row to expand</div>
    <div id="rackTabsInner"></div>
  </div>
  <div id="rackVisual"></div>
</div>

<div class="screen" id="screen-summary">
  <div class="sum-wrap">
    <div class="lbl">Store Overview</div>
    <div class="stat-grid" id="statGrid"></div>
    <div id="nearExpBanner"></div>
    <div class="lbl" style="margin-top:4px">All Products</div>
    <div class="search-wrap">
      <svg class="sico" width="14" height="14" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><circle cx="11" cy="11" r="8"/><path d="M21 21l-4.35-4.35"/></svg>
      <input class="search-inp" type="search" placeholder="Search name, barcode, Alshaya code…" oninput="filterAll(this.value)" id="searchInp">
    </div>
    <div id="allList"></div>
  </div>
</div>

<nav class="bnav">
  <button class="nb active" onclick="switchTab('racks')" id="nav-racks">
    <div class="ni"></div>
    <svg fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><rect x="2" y="3" width="20" height="4" rx="1"/><rect x="2" y="10" width="20" height="4" rx="1"/><rect x="2" y="17" width="20" height="4" rx="1"/></svg>
    Racks
  </button>
  <button class="nb" onclick="switchTab('summary')" id="nav-summary">
    <div class="ni"></div>
    <svg fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path d="M9 11l3 3L22 4"/><path d="M21 12v7a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h11"/></svg>
    Products
  </button>
</nav>

<!-- ADD/EDIT MODAL -->
<div class="mbk" id="addModalBk" onclick="closeMbk(event)">
  <div class="modal">
    <div class="mhandle"></div>
    <h3 id="mTitle">Add Product</h3>
    <input type="hidden" id="eId">
    <div class="fg"><label class="fl">Product Name</label><input class="fi" type="text" id="fName" placeholder="e.g. Vital Collagen 500mg"></div>
    <div class="fg"><label class="fl">Barcode</label><input class="fi" type="text" id="fBarcode" placeholder="e.g. 5019781022700"></div>
    <div class="fg"><label class="fl">Alshaya Code</label><input class="fi" type="text" id="fAlshaya" placeholder="e.g. WOBOWO…"></div>
    <div class="frow">
      <div class="fg"><label class="fl">Rack</label><select class="fsel" id="fRack" onchange="updateShelfOpts()"></select></div>
      <div class="fg"><label class="fl">Shelf</label><select class="fsel" id="fShelf"></select></div>
    </div>
    <div class="fg"><label class="fl">Shelf Type / Notch</label><input class="fi" type="text" id="fNotch" placeholder='12" Wooden Notch:33'></div>
    <div class="frow">
      <div class="fg"><label class="fl">Facing</label><input class="fi" type="number" id="fFacing" placeholder="1" min="1"></div>
      <div class="fg"><label class="fl">Stock Qty</label><input class="fi" type="number" id="fStock" placeholder="0" min="0"></div>
    </div>
    <div class="frow">
      <div class="fg"><label class="fl">Lines</label><input class="fi" type="number" id="fLines" placeholder="1" min="1"></div>
      <div class="fg"><label class="fl">Price (AED)</label><input class="fi" type="number" id="fPrice" placeholder="0.00" step="0.01"></div>
    </div>
    <div class="frow">
      <div class="fg"><label class="fl">Expiry Date</label><input class="fi" type="date" id="fExpiry"></div>
      <div class="fg"><label class="fl">Expiry Qty</label><input class="fi" type="number" id="fExpiryQty" placeholder="0" min="0"></div>
    </div>
    <div class="fg"><label class="fl">Remarks / Patient Notes</label><textarea class="fi" id="fRemarks" rows="2" placeholder="e.g. Take 1 tablet daily with food" style="resize:vertical"></textarea></div>
    <div class="fg">
      <label class="fl">Product Image</label>
      <div id="imgPrev" style="width:100%;height:70px;border-radius:7px;overflow:hidden;background:var(--cream);display:flex;align-items:center;justify-content:center;margin-bottom:5px"><span style="font-size:28px;opacity:.4">💊</span></div>
      <label for="fImg" style="display:block;width:100%;padding:8px;background:var(--teal-bg);color:var(--teal);border:1.5px dashed var(--teal);border-radius:7px;font-size:11px;font-weight:700;text-align:center;cursor:pointer">📷 Upload Product Image</label>
      <input type="file" id="fImg" accept="image/*" style="display:none" onchange="previewImg(event)">
    </div>
    <button class="btn-p" onclick="saveProduct()">Save Product</button>
    <button class="btn-s" onclick="closeModal()">Cancel</button>
  </div>
</div>

<!-- SCANNER MODAL -->
<div class="mbk" id="scannerBk" onclick="closeScannerMbk(event)">
  <div class="modal">
    <div class="mhandle"></div>
    <h3 style="margin-bottom:8px">📷 Scan Barcode</h3>
    <p style="font-size:11px;color:var(--muted);margin-bottom:10px">Camera scan or type manually</p>
    <video id="sv" autoplay playsinline muted style="width:100%;border-radius:10px;background:#000;aspect-ratio:4/3;display:block"></video>
    <canvas id="sc" style="display:none"></canvas>
    <div style="display:flex;gap:7px;margin-top:9px">
      <input class="fi" type="text" id="mbc" placeholder="Type barcode…" style="flex:1">
      <button class="btn-p" style="width:auto;padding:9px 14px;margin-top:0" onclick="searchByBarcode(document.getElementById('mbc').value)">Go</button>
    </div>
    <div id="scanResult"></div>
    <button class="btn-s" onclick="closeScanner()">Close</button>
  </div>
</div>

<!-- PRODUCT DETAIL MODAL -->
<div class="mbk" id="detailMbk" onclick="closeDetailMbk(event)">
  <div class="modal">
    <div class="mhandle"></div>
    <div id="detailInner"></div>
    <button class="btn-s" onclick="closeDetailModal()">Close</button>
  </div>
</div>

<!-- PRODUCT IMAGE MODAL -->
<div class="mbk" id="imgMbk" onclick="closeImgMbk(event)">
  <div class="modal">
    <div class="mhandle"></div>
    <h3>Product Image</h3>
    <p style="font-size:11px;color:var(--muted);margin-bottom:10px">Current image shown below. Tap upload to change it.</p>
    <div id="bigImgPreview" style="width:100%;height:180px;border-radius:10px;overflow:hidden;margin-bottom:12px;background:var(--cream);display:flex;align-items:center;justify-content:center"></div>
    <input type="hidden" id="imgTargetId">
    <label for="bigImgInput" style="display:block;width:100%;padding:13px;background:var(--teal);color:#fff;border:none;border-radius:var(--rs);font-size:13px;font-weight:700;text-align:center;cursor:pointer">📷 Upload / Change Image</label>
    <input type="file" id="bigImgInput" accept="image/*" style="display:none" onchange="saveProdImg(event)">
    <button class="btn-s" onclick="closeImgMbk()">Close</button>
  </div>
</div>

<script>

const SECTIONS=[
  {name:'Collagen & Skin Brightening',color:'#E11D48',bg:'#FFF1F2',racks:[1,2]},
  {name:"Women's / Skin, Hair & Nails",color:'#7C3AED',bg:'#F5F3FF',racks:[3,4]},
  {name:'Immunity / Multivitamins',color:'#059669',bg:'#ECFDF5',racks:[5,6]},
  {name:'Heart Health / Omega / Joint Care',color:'#0B3D91',bg:'#EEF2FF',racks:[7,8]},
  {name:'Weight Loss / Sleep / Calcium & Mg',color:'#D97706',bg:'#FFFBEB',racks:[9,10,11,12]},
];
const SPR=6;const EXPIRY_WARN_DAYS=90;

// PRODUCT IMAGE DATABASE - fallback colors + search-sourced image URLs per product
// Using picsum with product-specific seeds for consistent placeholder look,
// overrideable by user uploads
const PROD_IMG_SEEDS={
  p001:10,p002:20,p003:30,p004:40,p005:50,p006:60,
  p007:70,p008:80,p009:90,p010:100,p011:110,p012:120,
  p013:130,p014:140,p015:150,p016:160,p017:170,
  p018:180,p019:190,p020:200,p021:210,p022:220,p023:230,p024:240,
  p025:250,p026:260,p027:270,p028:280,p029:290,p030:300,p031:310,
  p032:320,p033:330,p034:340,p035:350,p036:360,p037:370,
  p038:380,p039:390,p040:400,p041:410,p042:420,p043:430,p044:440,
  p045:450,p046:460,p047:470,p048:480,p049:490,
  p050:500,p051:510,p052:520,p053:530,p054:540,
  p055:550,p056:560,p057:570,p058:580,p059:590,p060:600,p061:610,p062:620,
  p063:630,p064:640,p065:650,p066:660,p067:670,
  p068:680,p069:690,p070:700,p071:710,p072:720,p073:730,
  p074:740,p075:750,p076:760,p077:770,p078:780,p079:790,p080:800,
  p081:810,p082:820,p083:830,p084:840,p085:850,p086:860,
  p087:870,p088:880,p089:890,p090:900,p091:910,p092:920,
  p093:930,p094:940,p095:950,p096:960,p097:970,p098:980,p099:990,
  p100:1000,p101:1010,p102:1020,p103:1030,p104:1040,
  p105:1050,p106:1060,p107:1070,p108:1080,
  p109:1090,p110:1100,p111:1110,p112:1120,p113:1130,
  p114:1140,p115:1150,p116:1160,p117:1170,p118:1180,
  p119:1190,p120:1200,p121:1210,p122:1220,
};

// Product background colors for visual shelf appearance
const PROD_COLORS={
  p001:'#E8D5F5',p002:'#D5E8F5',p003:'#F5E8D5',p004:'#D5F5E8',p005:'#F5D5E8',p006:'#E8F5D5',
  p007:'#D5D5F5',p008:'#F5F5D5',p009:'#FFE4E8',p010:'#E4F0FF',p011:'#F0FFE4',p012:'#FFE4F0',
  p013:'#E0F8FF',p014:'#FFE0E0',p015:'#FFF8E0',p016:'#FFD700',p017:'#F0E8D5',
  p018:'#D5E8F5',p019:'#E8D5F5',p020:'#D5F5E8',p021:'#F5D5D5',p022:'#D5F5D5',p023:'#F5E8D5',p024:'#E8F5E8',
  p025:'#EEF2FF',p026:'#FFF0F5',p027:'#F0FFF0',p028:'#FFF8E0',p029:'#FFE4E8',p030:'#E4E8FF',p031:'#F5F5DC',
  p032:'#D5E8F5',p033:'#F5E8D5',p034:'#E8F5D5',p035:'#F5D5E8',p036:'#D5F5F5',p037:'#F5D5D5',
  p038:'#E8F5E8',p039:'#F5F5E8',p040:'#E8E8F5',p041:'#F5F5D5',p042:'#D5F5D5',p043:'#F5D5F5',p044:'#FFE4E8',
  p045:'#E4F0FF',p046:'#F0FFE4',p047:'#FFE4F0',p048:'#FFF8E0',p049:'#E0F8FF',
  p050:'#FFE0F0',p051:'#E0FFE0',p052:'#E0E0FF',p053:'#F0E0FF',p054:'#FFE0E0',
  p055:'#FFFDE0',p056:'#FFE8D5',p057:'#E8FFD5',p058:'#FFD580',p059:'#FFE44D',p060:'#FFD700',p061:'#FFFF80',p062:'#D5F5E8',
  p063:'#E8D5F5',p064:'#F5E8D5',p065:'#D5E8F5',p066:'#F5D5E8',p067:'#D5F5D5',
  p068:'#E8F5F5',p069:'#F5F5E8',p070:'#F5E8F5',p071:'#E8F5E8',p072:'#F5F5D5',p073:'#FFE8F0',
  p074:'#D5E8FF',p075:'#E8D5FF',p076:'#FFD5E8',p077:'#D5FFE8',p078:'#FFE8D5',p079:'#E8FFD5',p080:'#D5E8D5',
  p081:'#E8E8FF',p082:'#FFE8FF',p083:'#E8FFE8',p084:'#FFF8D5',p085:'#FFD5D5',p086:'#D5D5FF',
  p087:'#D5E8F5',p088:'#E8D5F5',p089:'#F5E8D5',p090:'#D5F5E8',p091:'#F5D5E8',p092:'#E8F5D5',
  p093:'#D5E8FF',p094:'#FFE8D5',p095:'#E8FFD5',p096:'#D5FFE8',p097:'#F5E8D5',
  p098:'#FFE8E8',p099:'#E8E8FF',p100:'#FFD580',p101:'#E8FFE8',
  p102:'#F5D5F5',p103:'#D5F5F5',p104:'#F5F5D5',
  p105:'#FFD700',p106:'#FFE880',p107:'#D5E8E8',p108:'#E8D5E8',
  p109:'#D5F5D5',p110:'#F5E8D5',p111:'#E8D5F5',
  p112:'#D5E8F5',p113:'#F5D5E8',p114:'#FFE8A0',p115:'#A0FFE8',p116:'#C8F5D5',
  p117:'#D5C8F5',p118:'#F5C8D5',p119:'#F5D5C8',p120:'#C8F5D5',p121:'#D5C8F5',p122:'#C8D5F5',
};


const PLANOGRAM_BASE=[
{id:'p001',name:'PRO COLLAGENIUM 14X25ML',barcode:'16185019867',alshaya:'WOBOWOM01986',rack:1,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:2,stock:8,lines:2,price:0},
{id:'p002',name:'SKINAGE COLLAGEN PRISTIGE 15 AMPOULES',barcode:'7629999061590',alshaya:'B2BOB29039117',rack:1,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:2,stock:4,lines:2,price:0},
{id:'p003',name:'NEOCELL SUPER COLLAGEN 7OZ',barcode:'16185132955',alshaya:'342714922',rack:1,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:2,stock:3,lines:2,price:0},
{id:'p004',name:'NEOCELL SUPER COLLAGEN POWDER PEPTIDES 198G',barcode:'220212282',alshaya:'3859892980627',rack:1,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:2,stock:0,lines:2,price:0},
{id:'p005',name:'SWEDISH NATURA COLLAGEN 10000 FISH 300GM',barcode:'6285078000150',alshaya:'B2BOB28000150',rack:1,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p006',name:'SAKAI COLLAGEN COMPLETE 332G',barcode:'5903260902822',alshaya:'Y1BOY10902822',rack:1,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p007',name:'SKINAGE COLLAGEN TRI ACTIVE 20000MG 500ML',barcode:'130252241',alshaya:'129826893',rack:1,shelf:2,notch:'19',shelfType:'12\" Wooden',facing:2,stock:7,lines:2,price:0},
{id:'p008',name:'LA BELLE COLLAGEN 10G DRINK 15 BOTTLES',barcode:'7350122360685',alshaya:'7301337278319',rack:1,shelf:2,notch:'19',shelfType:'12\" Wooden',facing:1,stock:18,lines:1,price:0},
{id:'p009',name:'COLLAGEN BEAUTY SHOTS 12 SHOTS',barcode:'868573000182',alshaya:'B2BOB273000182',rack:1,shelf:2,notch:'19',shelfType:'12\" Wooden',facing:1,stock:10,lines:1,price:0},
{id:'p010',name:'SWEDISH MARINE BEAUTY COLLAGEN SHOTS 20S',barcode:'5019781022700',alshaya:'220233096',rack:1,shelf:2,notch:'19',shelfType:'12\" Wooden',facing:1,stock:12,lines:1,price:0},
{id:'p011',name:'SWEDISH NATURA COLLAGEN 10000 LIQUID 500ML',barcode:'129962664',alshaya:'129816897',rack:1,shelf:2,notch:'19',shelfType:'12\" Wooden',facing:1,stock:12,lines:1,price:0},
{id:'p012',name:'PHARMAXXI BEAUTY COLLAGEN 14STKS',barcode:'161851299000',alshaya:'',rack:1,shelf:2,notch:'19',shelfType:'12\" Wooden',facing:2,stock:6,lines:2,price:0},
{id:'p013',name:'HEALTH AID NURIDEEN PLUS TAB 60S',barcode:'7301337323422',alshaya:'333920279',rack:1,shelf:3,notch:'13',shelfType:'12\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p014',name:'NEOCELL COLLAGEN POMEGRANATE LIQ 473ML',barcode:'8423245105248',alshaya:'333464221',rack:1,shelf:3,notch:'13',shelfType:'12\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p015',name:'PURE GOLD COLLAGEN 500ML 10X50ML',barcode:'3858893381112',alshaya:'B2BOB2259570001',rack:1,shelf:3,notch:'13',shelfType:'12\" Wooden',facing:2,stock:2,lines:2,price:0},
{id:'p016',name:'PURE GOLD COLLAGEN FORTE 500ML',barcode:'220227618',alshaya:'339999551',rack:1,shelf:3,notch:'13',shelfType:'12\" Wooden',facing:1,stock:1,lines:1,price:0},
{id:'p017',name:'SWEDISH NUTRA COLLAGEN GOLD RETINOL AMPOULES 15S',barcode:'5060259570015',alshaya:'5060259570179',rack:1,shelf:3,notch:'13',shelfType:'12\" Wooden',facing:1,stock:3,lines:1,price:0},
{id:'p018',name:'NEOCELL SUPER COLLAGEN + VIT C + BIOTIN 180 TABS',barcode:'853244003005',alshaya:'B2BOB244003005',rack:1,shelf:4,notch:'26',shelfType:'15\" Wooden',facing:2,stock:6,lines:2,price:0},
{id:'p019',name:'NEOCELL SUPER COLLAGEN + VIT C + BIOTIN 270 TABS',barcode:'853244003074',alshaya:'B2BOB244003074',rack:1,shelf:4,notch:'26',shelfType:'15\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p020',name:'NEOCELL COLLAGEN BEAUTY BUILDER 150S TABS',barcode:'35046087456',alshaya:'B2BOB246087456',rack:1,shelf:4,notch:'26',shelfType:'15\" Wooden',facing:1,stock:14,lines:1,price:0},
{id:'p021',name:'COLLAGEN BEAUTY CAPSULES 30 CAPS',barcode:'16185129009',alshaya:'WOBOWOM12900',rack:1,shelf:4,notch:'26',shelfType:'15\" Wooden',facing:2,stock:6,lines:2,price:0},
{id:'p022',name:'NATURES AID COLLAGEN VIT C ZINC 90VCAPS',barcode:'347749193',alshaya:'',rack:1,shelf:4,notch:'26',shelfType:'15\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p023',name:'VITABIOTICS PERFECTIL PLUS SKIN TABS 56S',barcode:'868455626120',alshaya:'628069520231',rack:1,shelf:4,notch:'26',shelfType:'15\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p024',name:'YOUTHEORY COLLAGEN 120S TAB',barcode:'335759558',alshaya:'Y1BOY10900873',rack:1,shelf:4,notch:'26',shelfType:'15\" Wooden',facing:1,stock:18,lines:1,price:0},
{id:'p025',name:'YOUTHEORY COLLAGEN ADVANCED 160S TAB',barcode:'5903260900873',alshaya:'330963987',rack:1,shelf:5,notch:'7',shelfType:'15\" Wooden',facing:2,stock:8,lines:2,price:0},
{id:'p026',name:'REJUVICARE SUPER COLLAGEN CAPS 90S',barcode:'330924233',alshaya:'220154834',rack:1,shelf:5,notch:'7',shelfType:'15\" Wooden',facing:2,stock:4,lines:2,price:0},
{id:'p027',name:'NEOCELL FISH COLLAGEN + HA 120CAP',barcode:'Y1BOY10902730',alshaya:'B2BOB22370098',rack:1,shelf:5,notch:'7',shelfType:'15\" Wooden',facing:2,stock:6,lines:2,price:0},
{id:'p028',name:'YOUR GUMMIES COLLAGEN PLUS BIOTIN VIT C ZINC 60S',barcode:'16185132603',alshaya:'16185132627',rack:1,shelf:5,notch:'7',shelfType:'15\" Wooden',facing:2,stock:20,lines:2,price:0},
{id:'p029',name:'OH MY OH COLLAGEN GUMMIES 350G',barcode:'16185129313',alshaya:'5903260902730',rack:1,shelf:5,notch:'7',shelfType:'15\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p030',name:'COLLAGEN BEAUTY EFFERVESCENT 20 TABS',barcode:'5023652370098',alshaya:'5021265223398',rack:1,shelf:5,notch:'7',shelfType:'15\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p031',name:'PEARLY SKIN WHIT CAPS 60CT',barcode:'609788968665',alshaya:'Y1BOY1PEARLY',rack:1,shelf:6,notch:'1',shelfType:'15\" Inverted',facing:2,stock:5,lines:2,price:0},
{id:'p032',name:'DUCRAY ANACAPS HAIR SUPP 60 CAP',barcode:'3282779065863',alshaya:'220215086',rack:2,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:8,lines:1,price:0},
{id:'p033',name:'ALLINE PROCAP 75 CAPSULES',barcode:'5425003041587',alshaya:'B2BOB23041587',rack:2,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:7,lines:1,price:0},
{id:'p034',name:'FASTCAP 500 HAIRLOSS 30TABS',barcode:'8057289181649',alshaya:'B2BOB29181649',rack:2,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p035',name:'BIORGA CYSTIPHANE TABLETS 120S',barcode:'3660398501021',alshaya:'Y5BOY58500925',rack:2,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:7,lines:1,price:0},
{id:'p036',name:'PANTOGAR 90 CAPS',barcode:'4046222750909',alshaya:'XSBOXS2750909',rack:2,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:2,stock:5,lines:2,price:0},
{id:'p037',name:'HAID HAIRSKINNAIL FRM TAB 30S',barcode:'220166011',alshaya:'',rack:2,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p038',name:'VITABIOTICS PERFECTIL 30S',barcode:'5019781000234',alshaya:'WMBOWM1000234',rack:2,shelf:2,notch:'19',shelfType:'12\" Wooden',facing:1,stock:10,lines:1,price:0},
{id:'p039',name:'21ST CENTURY HAIR SKIN 50 CAP',barcode:'5021265220038',alshaya:'WOBOWOMV201',rack:2,shelf:2,notch:'19',shelfType:'12\" Wooden',facing:1,stock:7,lines:1,price:0},
{id:'p040',name:'NB SKIN HAIR NAILS',barcode:'ZIBOZINB803',alshaya:'B2BOB246074227',rack:2,shelf:2,notch:'19',shelfType:'12\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p041',name:'PRIORIN NCAP 90S',barcode:'B2BOB25012364',alshaya:'',rack:2,shelf:3,notch:'26',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p042',name:'PRIORIN EXTRA BLISTER 60 CAPS',barcode:'B2BOB25010599',alshaya:'',rack:2,shelf:3,notch:'26',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p043',name:'VITABIOTICS PERFECTIL PLUS HAIR TAB 60S',barcode:'5019781016853',alshaya:'',rack:2,shelf:3,notch:'26',shelfType:'12\" Wooden',facing:2,stock:9,lines:2,price:0},
{id:'p044',name:'VITABIOTICS HAIRFOLLIC WOMEN 60TAB',barcode:'5021265244508',alshaya:'',rack:2,shelf:3,notch:'26',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p045',name:'SWEDISH NATURA HYALURONIC ACID 500ML',barcode:'6285074005661',alshaya:'345355261',rack:2,shelf:4,notch:'13',shelfType:'12\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p046',name:'MIGLIORIN 90 GEL CAPSULES',barcode:'5021265245741',alshaya:'WOBOWO5245741',rack:2,shelf:4,notch:'13',shelfType:'12\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p047',name:'COUNTRY LIFE MAXI HAIR PLUS 120 CAPS',barcode:'5021265248780',alshaya:'WEBOWEVITS3848',rack:2,shelf:4,notch:'13',shelfType:'12\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p048',name:'OH MY OH HAIR SKIN AND NAILS GUMMIES 350G',barcode:'8429420222830',alshaya:'332204326',rack:2,shelf:4,notch:'13',shelfType:'12\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p049',name:'HEALTH AID HAIR VIT CAPS 30S',barcode:'331894318',alshaya:'WOBOWOM09665',rack:2,shelf:4,notch:'13',shelfType:'12\" Wooden',facing:1,stock:7,lines:1,price:0},
{id:'p050',name:'VITABIOTICS PREGNACARE CONCEPTION 30S',barcode:'5021265250592',alshaya:'WOBOWO65221585',rack:2,shelf:5,notch:'7',shelfType:'15\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p051',name:'PREGNACARE TAB 30S',barcode:'5021265247622',alshaya:'WOBOWOMV191',rack:2,shelf:5,notch:'7',shelfType:'15\" Wooden',facing:2,stock:6,lines:2,price:0},
{id:'p052',name:'VITABIOTICS PREGNACARE PLUS 56S',barcode:'5021265221523',alshaya:'WOBOWO221523',rack:2,shelf:5,notch:'7',shelfType:'15\" Wooden',facing:2,stock:6,lines:2,price:0},
{id:'p053',name:'VITABIOTICS MENOPACE TABLET 30S',barcode:'5021265221004',alshaya:'WOBOWOMENO00',rack:2,shelf:6,notch:'1',shelfType:'15\" Inverted',facing:2,stock:14,lines:2,price:0},
{id:'p054',name:'NOW FENUGREEK 500 MG 100 CAPS',barcode:'733739145536',alshaya:'WOBOWO4677',rack:2,shelf:6,notch:'1',shelfType:'15\" Inverted',facing:1,stock:5,lines:1,price:0},
{id:'p055',name:'WHITE HEALTH VITAC-1000 LIPOSOMAL 60S',barcode:'344405790',alshaya:'WOBOWO21225',rack:3,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:8,lines:1,price:0},
{id:'p056',name:'21ST CENTURY C-1000MG PROLONGED 110S',barcode:'15794068723',alshaya:'B2BOB24068723',rack:3,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p057',name:'COUNTRY LIFE VIT C 1000 MG 90 TABS',barcode:'850072993003',alshaya:'',rack:3,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p058',name:'REDOXON ORANGE 1G EFF TABS 15S',barcode:'9650155002070',alshaya:'WUBOWUCALC987',rack:3,shelf:2,notch:'26',shelfType:'12\" Wooden',facing:2,stock:11,lines:2,price:0},
{id:'p059',name:'REDOXON TRIPLE FORMULA EFF TABS 15S',barcode:'5024874015507',alshaya:'B2BOB24015507',rack:3,shelf:2,notch:'26',shelfType:'12\" Wooden',facing:1,stock:7,lines:1,price:0},
{id:'p060',name:'BEROCCA EFFERVESCENT TABS 10',barcode:'',alshaya:'WUBOWUASP-032-0',rack:3,shelf:2,notch:'26',shelfType:'12\" Wooden',facing:1,stock:8,lines:1,price:0},
{id:'p061',name:'ADDITIVA VITC EFF 1GM LEMON 20',barcode:'3002894901000',alshaya:'Y5BOY5PSFV04',rack:3,shelf:2,notch:'26',shelfType:'12\" Wooden',facing:1,stock:9,lines:1,price:0},
{id:'p062',name:'HEALTH AID VIT C 1000MG EFF 20S',barcode:'5024874015422',alshaya:'B2BOB2VALU422',rack:3,shelf:2,notch:'26',shelfType:'12\" Wooden',facing:1,stock:8,lines:1,price:0},
{id:'p063',name:'SOLGAR VITAMIN C 1000 MG TAB 90S',barcode:'33984032750',alshaya:'220192279',rack:3,shelf:3,notch:'13',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p064',name:'SUNSHINE N SUPER IMMUNITY NAC 100 CAPS',barcode:'810011083929',alshaya:'B2BOB21083929',rack:3,shelf:3,notch:'13',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p065',name:'SOLGAR ZINC 50 TAB 100S',barcode:'33984037205',alshaya:'220190454',rack:3,shelf:3,notch:'13',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p066',name:'CENTRUM IMMUNE SUPPORT ELDERBERRY 60S',barcode:'220154687',alshaya:'336457256',rack:3,shelf:3,notch:'13',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p067',name:'NOW VITAMIN C 1000 100 TABS',barcode:'5019781010714',alshaya:'',rack:3,shelf:3,notch:'13',shelfType:'12\" Wooden',facing:1,stock:7,lines:1,price:0},
{id:'p068',name:'SOLGAR CHELATED ZINC TAB 100S',barcode:'74312020605',alshaya:'ZIBOZI2020605',rack:3,shelf:4,notch:'19',shelfType:'15\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p069',name:'SOLARAY ZINC 50MG 100 CAPS',barcode:'740985212455',alshaya:'220231241',rack:3,shelf:4,notch:'19',shelfType:'15\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p070',name:'VITABIOTICS MENOPACE PLUS DUAL PK 56S',barcode:'5021265246427',alshaya:'WOBOVITA1202',rack:3,shelf:5,notch:'15',shelfType:'15\" Inverted',facing:1,stock:9,lines:1,price:0},
{id:'p071',name:'HEALTH AID VVEIN TABS 60S',barcode:'5019781015856',alshaya:'WMBOWM1015856',rack:3,shelf:5,notch:'15',shelfType:'15\" Inverted',facing:2,stock:18,lines:2,price:0},
{id:'p072',name:'NB EVENING PRIMROSE OIL 1000MG',barcode:'733739017550',alshaya:'WOBOWO1755',rack:3,shelf:5,notch:'15',shelfType:'15\" Inverted',facing:2,stock:6,lines:2,price:0},
{id:'p073',name:'VITABIOTICS PREGNACARE MAX TAB 84S',barcode:'5021265244843',alshaya:'WOBOWO5244843',rack:3,shelf:6,notch:'7',shelfType:'15\" Wooden',facing:2,stock:6,lines:2,price:0},
{id:'p074',name:'CENTRUM SILVER 100S',barcode:'5019781010172',alshaya:'Y3BOY3CENSIL1000',rack:4,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p075',name:'CENTRUM SILVER 30S',barcode:'6251613000527',alshaya:'Y3BOY3CENSIL30S',rack:4,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:2,stock:6,lines:2,price:0},
{id:'p076',name:'CENTRUM ENERGY TAB 100S',barcode:'6291109121039',alshaya:'344555284',rack:4,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p077',name:'CENTRUM MEN TAB 100S',barcode:'6291109121053',alshaya:'344345305',rack:4,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p078',name:'HEALTH AID DAY VIT ACTIVE TABS 30S',barcode:'5019781014422',alshaya:'220221584',rack:4,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:2,stock:8,lines:2,price:0},
{id:'p079',name:'CENTRUM LUTEIN 100S',barcode:'6251613000503',alshaya:'BZBTSLOCEN00503',rack:4,shelf:2,notch:'26',shelfType:'12\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p080',name:'CENTRUM ADULTS MULTIGUMMIES 60S',barcode:'5000309008962',alshaya:'835776001049',rack:4,shelf:2,notch:'26',shelfType:'12\" Wooden',facing:1,stock:9,lines:1,price:0},
{id:'p081',name:'VITABIOTICS WELLMAN TAB 30',barcode:'5021265221301',alshaya:'WEBOWEMMS0002',rack:4,shelf:3,notch:'19',shelfType:'12\" Wooden',facing:1,stock:7,lines:1,price:0},
{id:'p082',name:'VITABIOTICS WELLMAN SPORT TAB 30S',barcode:'5021265223527',alshaya:'WOBOWO5223527',rack:4,shelf:3,notch:'19',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p083',name:'ALIVE MENS 50 GUMMY VITAMIN 60S',barcode:'965014200003',alshaya:'Y5BOY5PSFV02',rack:4,shelf:3,notch:'19',shelfType:'12\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p084',name:'PHARMAXXI NMN 60S',barcode:'',alshaya:'',rack:4,shelf:3,notch:'19',shelfType:'12\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p085',name:'NFLIBIZIRE LIBIDO ENHANCER 60S',barcode:'832621000134',alshaya:'ZWBOZWVNF00013',rack:4,shelf:6,notch:'2',shelfType:'15\" Inverted',facing:1,stock:5,lines:1,price:0},
{id:'p086',name:'SOLGAR COQ-10 VEGICAPS 200 MG 30S',barcode:'33984009486',alshaya:'220192335',rack:4,shelf:6,notch:'2',shelfType:'15\" Inverted',facing:2,stock:10,lines:2,price:0},
{id:'p087',name:'COUNTRY LIFE OMEGA 3 MOOD 90 SOFTGELS',barcode:'733739016867',alshaya:'WOBOWO1686',rack:5,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:2,stock:8,lines:2,price:0},
{id:'p088',name:'NORD NAT OMEGA-3 FISH 60SG CAPS',barcode:'347754409',alshaya:'',rack:5,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:3,stock:8,lines:3,price:0},
{id:'p089',name:'SOLGAR OMEGA 3 FISH OIL SG 120S',barcode:'5019781028931',alshaya:'220154084',rack:5,shelf:2,notch:'13',shelfType:'12\" Wooden',facing:2,stock:6,lines:2,price:0},
{id:'p090',name:'NOW ULTRA OMEGA 3 SOFTGEL 90S',barcode:'5021265221608',alshaya:'',rack:5,shelf:2,notch:'13',shelfType:'12\" Wooden',facing:2,stock:4,lines:2,price:0},
{id:'p091',name:'21ST CENTURY ALASKA WILD FISH OIL 90SG',barcode:'740985271292',alshaya:'',rack:5,shelf:3,notch:'19',shelfType:'12\" Wooden',facing:2,stock:9,lines:2,price:0},
{id:'p092',name:'CARDIOACE CAPSULES 30S',barcode:'',alshaya:'WOBOWO CARD1608',rack:5,shelf:4,notch:'26',shelfType:'15\" Wooden',facing:1,stock:8,lines:1,price:0},
{id:'p093',name:'CH ALPHA 30X25ML',barcode:'9650364002465',alshaya:'B2BOB2A3025ML',rack:6,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p094',name:'CH ALPHA PLUS 30X25ML',barcode:'4260133180949',alshaya:'273794953',rack:6,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:1,stock:2,lines:1,price:0},
{id:'p095',name:'VITABIOTICS JOINTACE MAX 84S TABS',barcode:'5021265222544',alshaya:'WEBOWEJOIN254',rack:6,shelf:2,notch:'19',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p096',name:'FLEXAMIN TABS 120+40S',barcode:'699866068448',alshaya:'ZIBOZI69986606832',rack:6,shelf:3,notch:'26',shelfType:'12\" Wooden',facing:5,stock:6,lines:5,price:0},
{id:'p097',name:'NOW GLUTATHIONE 500 MG 60S',barcode:'733739001047',alshaya:'WOBOWO9001047',rack:6,shelf:3,notch:'26',shelfType:'12\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p098',name:'VITABIOTICS OSTEOCARE CHEWABLE',barcode:'5021265220403',alshaya:'WOBOVITA0430',rack:6,shelf:4,notch:'13',shelfType:'15\" Wooden',facing:1,stock:7,lines:1,price:0},
{id:'p099',name:'SOLGAR CALC MAG W VIT D3 TAB 150S',barcode:'33984005181',alshaya:'',rack:6,shelf:4,notch:'13',shelfType:'15\" Wooden',facing:1,stock:4,lines:1,price:0},
{id:'p100',name:'SOLGAR VIT D 1000IU SOFT GEL 100S',barcode:'33984033405',alshaya:'',rack:6,shelf:4,notch:'13',shelfType:'15\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p101',name:'VITABIOTICS OSTEOCARE FIZZ 20S',barcode:'5021265222902',alshaya:'WOBOWOOSTEO29',rack:6,shelf:4,notch:'13',shelfType:'15\" Wooden',facing:1,stock:5,lines:1,price:0},
{id:'p102',name:'SOLGAR CALCI MAGNESIUM+ZINC TAB 100S',barcode:'33984005204',alshaya:'',rack:6,shelf:5,notch:'15',shelfType:'15\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p103',name:'SUNSHINE N CAL MAG ZINC VIT D3 100S',barcode:'859795006229',alshaya:'B2BOB2121785',rack:6,shelf:5,notch:'15',shelfType:'15\" Wooden',facing:1,stock:7,lines:1,price:0},
{id:'p104',name:'PURITANS PRIDE CALCIUM MAGNESIUM ZINC 100S',barcode:'74312142901',alshaya:'345560411',rack:6,shelf:5,notch:'15',shelfType:'15\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p105',name:'NOW VITAMIN D3/K2 1000IU 120 CAPS',barcode:'733739003690',alshaya:'WOBOWO9003690',rack:6,shelf:6,notch:'1',shelfType:'15\" Inverted',facing:1,stock:5,lines:1,price:0},
{id:'p106',name:'HEALTH AID VITAMIN D3 1000IU CAPS 30S',barcode:'5019781010424',alshaya:'',rack:6,shelf:6,notch:'1',shelfType:'15\" Inverted',facing:1,stock:7,lines:1,price:0},
{id:'p107',name:'SOLGAR CHELATED MAGNESIUM TAB 100S',barcode:'628069520200',alshaya:'',rack:6,shelf:6,notch:'1',shelfType:'15\" Inverted',facing:1,stock:6,lines:1,price:0},
{id:'p108',name:'VITABIOTICS ULTRA VIT D3 2000IU 96 TABS',barcode:'5021265247400',alshaya:'WOBOWO5247400',rack:6,shelf:6,notch:'1',shelfType:'15\" Inverted',facing:1,stock:13,lines:1,price:0},
{id:'p109',name:'NUTRITIONL APPLE CIDER VINEGAR TAB 100S',barcode:'83000164569',alshaya:'B2BOB20164569',rack:7,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:3,stock:8,lines:3,price:0},
{id:'p110',name:'YOUR GUMMIES APPLE CIDER VINEGAR 60S',barcode:'5903163601617',alshaya:'B2BOB23601617',rack:7,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:3,stock:8,lines:3,price:0},
{id:'p111',name:'HEALTH AID SIBERSLIM TABS 60S',barcode:'5019781010318',alshaya:'XABOXA81010318',rack:7,shelf:1,notch:'33',shelfType:'12\" Wooden',facing:2,stock:8,lines:2,price:0},
{id:'p112',name:'NOW GARCINIA 1000MG 120TABS',barcode:'5903163608531',alshaya:'',rack:7,shelf:2,notch:'26',shelfType:'12\" Wooden',facing:2,stock:10,lines:2,price:0},
{id:'p113',name:'PAXAS BELLY FAT 120 CAPS',barcode:'868573000106',alshaya:'B2BOB273000106',rack:7,shelf:2,notch:'26',shelfType:'12\" Wooden',facing:2,stock:14,lines:2,price:0},
{id:'p114',name:'21ST CENTURY HERBAL SLIMMING TEA ORANGE 24',barcode:'740985224052',alshaya:'WOBOWOMTC22405',rack:7,shelf:3,notch:'19',shelfType:'12\" Wooden',facing:2,stock:15,lines:2,price:0},
{id:'p115',name:'21ST CENTURY HERBAL SLIMMING TEA GREEN 24',barcode:'740985227909',alshaya:'WOBOWOMTC22790',rack:7,shelf:3,notch:'19',shelfType:'12\" Wooden',facing:2,stock:21,lines:2,price:0},
{id:'p116',name:'GARDEN GREEN ACAI CLEANSE DETOX 947ML',barcode:'35046068714',alshaya:'B2BOB246068714',rack:7,shelf:3,notch:'19',shelfType:'12\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p117',name:'NOW 5HTP 100MG 60 VCAPS',barcode:'733739148995',alshaya:'',rack:7,shelf:4,notch:'13',shelfType:'15\" Wooden',facing:1,stock:6,lines:1,price:0},
{id:'p118',name:'NB L CARNITINE 500MG 30TAB',barcode:'74312016837',alshaya:'ZIBOZINB837',rack:7,shelf:4,notch:'13',shelfType:'15\" Wooden',facing:1,stock:7,lines:1,price:0},
{id:'p119',name:'VITABIOTICS ULTRA CRANBERRY EXTRACT 30S',barcode:'5021265244867',alshaya:'',rack:7,shelf:5,notch:'7',shelfType:'15\" Inverted',facing:1,stock:5,lines:1,price:0},
{id:'p120',name:'NOW GINKGO BILOBA 60MG 60CAP',barcode:'733739046864',alshaya:'WOBOWO39046864',rack:7,shelf:5,notch:'7',shelfType:'15\" Inverted',facing:1,stock:6,lines:1,price:0},
{id:'p121',name:'NOW L-CARNITINE 500 MG 60 VCAPS',barcode:'733739110466',alshaya:'WOBOWO41210072',rack:7,shelf:6,notch:'1',shelfType:'15\" Inverted',facing:1,stock:12,lines:1,price:0},
{id:'p122',name:'HEALTH AID L-ARGININE 500MG TAB 60S',barcode:'5019781022519',alshaya:'',rack:7,shelf:6,notch:'1',shelfType:'15\" Inverted',facing:1,stock:4,lines:1,price:0},
];


let PLANOGRAM=[...PLANOGRAM_BASE];
let S={photos:{},openShelves:{},stockOverrides:{},extras:{},prodImgs:{},customProds:[]};
let currentRack=1;
function loadS(){try{const d=localStorage.getItem('shelfrx5');if(d){const p=JSON.parse(d);Object.assign(S,p);}}catch(e){}S.customProds.forEach(cp=>{if(!PLANOGRAM.find(p=>p.id===cp.id))PLANOGRAM.push(cp);});}
function saveS(){localStorage.setItem('shelfrx5',JSON.stringify(S));}
function uid(){return Math.random().toString(36).slice(2,9);}
function esc(s){return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;');}
function sectionFor(r){return SECTIONS.find(s=>s.racks.includes(r))||SECTIONS[0];}
function shelfCode(r,s){return r+'.'+s;}
function getStock(id){return(id in S.stockOverrides)?S.stockOverrides[id]:(PLANOGRAM.find(p=>p.id===id)?.stock||0);}
function setStock(id,v){S.stockOverrides[id]=Math.max(0,v);saveS();}
function getExtra(id){return S.extras[id]||{expiry:'',expiryQty:0,remarks:''};}
function setExtra(id,ex){S.extras[id]=ex;saveS();}
function getProdImg(id){return S.prodImgs[id]||'';}
function daysUntilExpiry(d){if(!d)return null;const now=new Date();now.setHours(0,0,0,0);return Math.round((new Date(d)-now)/86400000);}
function isNearExpiry(id){const ex=getExtra(id);if(!ex.expiry)return false;const d=daysUntilExpiry(ex.expiry);return d!==null&&d<=EXPIRY_WARN_DAYS;}
function stockStatus(v){if(v===0)return{cls:'s-out',chip:'c-out',label:'Out'};if(v<5)return{cls:'s-low',chip:'c-low',label:'Low'};return{cls:'s-ok',chip:'c-ok',label:'OK'};}

// Gets image src: user upload > color box
function getImgSrc(id){const ui=getProdImg(id);if(ui)return ui;return '';}
function prodColor(id){return PROD_COLORS[id]||'#E8F0FE';}

// Render product box inline with color + text label when no image
function prodImgHTML(id,w,h,showNum,num,ne,stock,onclick_extra){
  const img=getImgSrc(id);
  const col=prodColor(id);
  const name=(PLANOGRAM.find(p=>p.id===id)||{}).name||'';
  const abbr=name.split(' ').slice(0,2).join(' ');
  const isOut=stock===0;
  let inner='';
  if(img){
    inner=`<img src="${img}" alt="" style="width:100%;height:100%;object-fit:cover;display:block;border-radius:4px">`;
  } else {
    // Draw a realistic pill/bottle box using CSS gradient + text
    const seed=PROD_IMG_SEEDS[id]||50;
    const h2=seed%3===0?'linear-gradient(160deg,'+col+' 0%,#fff 60%,'+col+' 100%)':
             seed%3===1?'linear-gradient(180deg,#fff 0%,'+col+' 40%,'+col+' 90%)':
             'linear-gradient(135deg,'+col+',#fff,'+col+')';
    inner=`<div style="width:100%;height:100%;background:${h2};display:flex;flex-direction:column;align-items:center;justify-content:center;padding:2px;gap:1px;border-radius:4px">
      <div style="font-size:7px;font-weight:800;color:#333;text-align:center;line-height:1.2;word-break:break-word;max-width:100%">${esc(abbr)}</div>
      <div style="width:60%;height:1px;background:rgba(0,0,0,.15);margin:1px 0"></div>
      <div style="font-size:6px;color:#555;text-align:center">Supplement</div>
    </div>`;
  }
  const numBadge=showNum?`<div class="prod-slot-num-badge">${num}</div>`:'';
  const expDot=ne?`<div class="exp-dot"></div>`:'';
  const outOver=isOut?`<div class="out-dot">OUT</div>`:'';
  return `<div class="prod-img-box${isOut?' out-of-stock':''}${ne?' near-exp':''}" style="width:${w}px;height:${h}px;cursor:pointer;" ${onclick_extra}>${inner}${numBadge}${expDot}${outOver}</div>`;
}

// SELL TIPS
const SELL_TIPS={
  collagen:['Ask about skin concerns and age','10,000mg marine collagen visible in 4–6 weeks','Pair with Vitamin C for absorption','Collagen+HA for joint support'],
  omega:['Heart health & brain function','1000mg EPA+DHA daily','Take with a meal','Pair with Vitamin D3'],
  'vitamin c':['Immunity and skin brightening','Effervescent absorbs fastest','1000mg daily, pair with Zinc'],
  'vitamin d':['Bone health & immunity','Most UAE patients are deficient','D3 more bioavailable than D2','Pair with Calcium and K2'],
  calcium:['Bone density, especially women 40+','Calcium Citrate absorbs better','Always pair with Vit D3 & Mg'],
  hair:['Biotin+Collagen for best results','Results in 3–4 months','Check Iron levels for hair loss'],
  default:['Check patient age and health goal','Correct dosage for their weight','Take with food unless stated','Mention contraindications']
};
function getSellTips(name){const n=name.toLowerCase();for(const[k,v]of Object.entries(SELL_TIPS)){if(k!=='default'&&n.includes(k))return v;}return SELL_TIPS.default;}

const TRANSLATIONS={
  ar:{'Take 1 tablet daily with food':'تناول قرصاً واحداً يومياً مع الطعام','Take 2 tablets daily':'تناول قرصين يومياً','Store in a cool dry place':'احفظه في مكان بارد وجاف','Keep refrigerated':'يُحفظ مبرداً','Take before bedtime':'تناول قبل النوم','Take on an empty stomach':'تناول على معدة فارغة','Do not exceed stated dose':'لا تتجاوز الجرعة المحددة','Near expiry - use first':'قارب على الانتهاء - استخدم أولاً','Out of stock':'نفدت الكمية','Low stock':'الكمية منخفضة'},
  fr:{'Take 1 tablet daily with food':'Prendre 1 comprimé par jour avec de la nourriture','Take 2 tablets daily':'Prendre 2 comprimés par jour','Store in a cool dry place':'Conserver dans un endroit frais et sec','Keep refrigerated':'Conserver au réfrigérateur','Take before bedtime':'Prendre avant le coucher','Near expiry - use first':'Proche de la péremption','Out of stock':'Rupture de stock','Low stock':'Stock faible'},
  zh:{'Take 1 tablet daily with food':'每天随餐服用1片','Take 2 tablets daily':'每天服用2片','Store in a cool dry place':'存放于阴凉干燥处','Keep refrigerated':'需冷藏保存','Take before bedtime':'睡前服用','Near expiry - use first':'即将过期，请先使用','Out of stock':'缺货','Low stock':'库存不足'},
  fa:{'Take 1 tablet daily with food':'روزی یک قرص همراه با غذا','Take 2 tablets daily':'روزی دو قرص','Store in a cool dry place':'در جای خنک و خشک','Keep refrigerated':'در یخچال','Near expiry - use first':'نزدیک به انقضا','Out of stock':'موجود نیست','Low stock':'موجودی کم'},
  sw:{'Take 1 tablet daily with food':'Chukua kidonge 1 kila siku na chakula','Take 2 tablets daily':'Chukua vidonge 2 kila siku','Store in a cool dry place':'Hifadhi mahali pa baridi na kavu','Keep refrigerated':'Weka kwenye jokofu','Near expiry - use first':'Karibu na muda wa kuisha','Out of stock':'Imekwisha','Low stock':'Hisa chache'},
  am:{'Take 1 tablet daily with food':'በቀን አንድ ጽላት ከምግብ ጋር','Take 2 tablets daily':'በቀን ሁለት ጽላቶች','Store in a cool dry place':'ቀዝቃዛ እና ደረቅ ቦታ','Keep refrigerated':'ማቀዝቀዣ ውስጥ','Near expiry - use first':'ፍጻሜ ቅርብ ነው','Out of stock':'አልቋል','Low stock':'ዝቅተኛ'}
};
const LANGUAGES=[{code:'ar',name:'Arabic',flag:'🇸🇦',rtl:true},{code:'fr',name:'French',flag:'🇫🇷',rtl:false},{code:'zh',name:'Chinese',flag:'🇨🇳',rtl:false},{code:'fa',name:'Persian',flag:'🇮🇷',rtl:true},{code:'sw',name:'Swahili',flag:'🇰🇪',rtl:false},{code:'am',name:'Amharic',flag:'🇪🇹',rtl:false}];
function translateText(text,lc){const d=TRANSLATIONS[lc]||{};if(d[text])return d[text];let r=text;for(const[en,tr]of Object.entries(d)){if(text.toLowerCase().includes(en.toLowerCase()))r=r.replace(new RegExp(en,'gi'),tr);}return r;}

// ── RENDER ──
function renderRackTabs(){
  const nearExp=PLANOGRAM.filter(p=>isNearExpiry(p.id));
  // expiry banner
  const eb=document.getElementById('expiryBanner');
  if(nearExp.length){
    let h=`<div class="exp-banner"><div class="exp-banner-title">🚨 Near Expiry · ${nearExp.length} items</div><div class="exp-grid">`;
    nearExp.slice(0,4).forEach(p=>{const ex=getExtra(p.id);const d=daysUntilExpiry(ex.expiry);h+=`<div class="exp-card"><div class="exp-card-name">${esc(p.name)}</div><div class="exp-card-meta">⏰ ${d}d · ${ex.expiry}</div><div class="exp-card-shelf">Shelf ${shelfCode(p.rack,p.shelf)}</div></div>`;});
    if(nearExp.length>4)h+=`<div class="exp-card" style="display:flex;align-items:center;justify-content:center;color:var(--red);font-size:11px;font-weight:700">+${nearExp.length-4} more</div>`;
    h+='</div></div>';eb.innerHTML=h;
  }else{eb.innerHTML='';}
  // tabs
  let tabs='<div class="rack-tabs">';
  const sec=sectionFor(currentRack);
  for(let r=1;r<=12;r++){
    const hasExp=PLANOGRAM.filter(p=>p.rack===r).some(p=>isNearExpiry(p.id));
    const s=sectionFor(r);
    tabs+=`<button class="rack-tab${r===currentRack?' active':''}${hasExp?' exp':''}" onclick="selectRack(${r})" style="${r===currentRack?'background:'+s.color+';border-color:'+s.color:''}">R${r}</button>`;
  }
  tabs+='</div>';
  document.getElementById('rackTabsInner').innerHTML=tabs;
}

function selectRack(n){currentRack=n;renderRackTabs();renderRackVisual();}

function renderRackVisual(){
  const rn=currentRack;const sec=sectionFor(rn);
  const rackProds=PLANOGRAM.filter(p=>p.rack===rn);
  let html=`<div class="rack-container">
  <div class="rack-header">
    <span style="font-size:20px">${['🧴','🌸','💅','💊','🛡️','🦴','💪','🔬','🐟','🦴','⚖️','😴'][rn-1]||'💊'}</span>
    <div>
      <div class="rack-title" style="color:${sec.color}">Rack ${rn}</div>
      <div style="font-size:10px;color:var(--muted)">${rackProds.length} products</div>
    </div>
    <span class="rack-chip" style="background:${sec.bg};color:${sec.color}">${esc(sec.name)}</span>
  </div>
  <div class="rack-frame"><div class="rack-frame-inner">`;

  for(let sh=1;sh<=SPR;sh++){
    const code=shelfCode(rn,sh);
    const prods=PLANOGRAM.filter(p=>p.rack===rn&&p.shelf===sh);
    const photo=S.photos['shelf_'+code];
    const open=S.openShelves[code];
    const shelfTypeLabel=prods[0]?prods[0].shelfType:'Empty';
    const hasNE=prods.some(p=>isNearExpiry(p.id));
    const stocks=prods.map(p=>getStock(p.id));
    let unitCls='shelf-unit';
    if(hasNE)unitCls+=' near-expiry';
    else if(stocks.some(v=>v===0)&&prods.length)unitCls+=' s-out';
    else if(stocks.some(v=>v>0&&v<5))unitCls+=' s-low';

    // Build product slots standing on the shelf
    let slots='';
    prods.forEach((p,i)=>{
      const v=getStock(p.id);const ne=isNearExpiry(p.id);
      const count=Math.min(p.facing,6);
      for(let f=0;f<count;f++){
        const qtyClass=v===0?'qty-out':v<5?'qty-low':'qty-ok';
        slots+=`<div class="prod-slot" onclick="showProdDetail('${p.id}')">
          ${prodImgHTML(p.id,46,64,f===0,i+1,ne,v,'')}
          <div class="prod-slot-name">${f===0?esc(p.name.split(' ').slice(0,2).join(' ')):''}</div>
          <div class="prod-slot-qty ${qtyClass}">${f===0?(v===0?'OUT':v+'u'):''}</div>
        </div>`;
      }
    });
    if(!prods.length)slots=`<div style="padding:14px 10px;color:rgba(255,255,255,.35);font-size:11px;font-style:italic">Empty shelf ${code}</div>`;

    html+=`<div class="${unitCls}" id="su_${code}">
      <div class="shelf-plank-top" onclick="toggleShelf('${code}')">
        <div class="shelf-code-pill">${code} · ${esc(shelfTypeLabel)}</div>
        ${hasNE?`<div class="shelf-expiry-badge">⚠️ EXPIRY</div>`:''}
      </div>
      <div class="shelf-products-row">${slots}</div>
      <div class="shelf-plank-bottom"></div>
      <div class="shelf-detail${open?' open':''}" id="sd_${code}">
        <label for="sph_${code}" style="cursor:pointer">
          <div class="shelf-photo-area">${photo?`<img src="${photo}" alt="">`:'<span style="font-size:22px;opacity:.35">📷</span>'}
            <div class="ph-label">📷 ${photo?'Change':'Add'} shelf photo</div>
          </div>
        </label>
        <input type="file" id="sph_${code}" accept="image/*" style="display:none" onchange="uploadShelfPhoto(event,'${code}')">
        <div class="prod-list">
          ${prods.length===0?`<div style="text-align:center;padding:10px;color:var(--muted);font-size:11px">No products on shelf ${code}</div>`:''}
          ${prods.map((p,i)=>{
            const v=getStock(p.id);const st=stockStatus(v);const ex=getExtra(p.id);const ne=isNearExpiry(p.id);const days=daysUntilExpiry(ex.expiry);const img=getImgSrc(p.id);const col=prodColor(p.id);
            const thumbInner=img?`<img src="${img}" alt="">`:`<div style="width:100%;height:100%;background:linear-gradient(160deg,${col},#fff,${col});display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:700;color:#444;text-align:center;padding:2px;line-height:1.2">${esc(p.name.split(' ').slice(0,2).join(' '))}</div>`;
            return `<div class="prod-row">
              <div class="prod-row-thumb${ne?' ne':''}" onclick="openImgModal('${p.id}')">
                ${thumbInner}
                <div class="change-img-overlay">📷</div>
              </div>
              <div class="prod-row-body">
                <div class="prn"><span style="background:var(--navy);color:#fff;font-size:7px;padding:1px 4px;border-radius:20px;margin-right:3px;font-family:'DM Mono',monospace">${i+1}</span>${esc(p.name)}</div>
                ${p.barcode?`<div class="prc">📦 ${esc(p.barcode)}</div>`:''}
                ${p.alshaya?`<div class="prc" style="color:#7C3AED">🏷 ${esc(p.alshaya)}</div>`:''}
                <div class="pr-tags">
                  <span class="ptag pt-f">F:${p.facing}</span>
                  <span class="ptag pt-n">N:${p.notch}</span>
                  ${ex.expiry?`<span class="ptag ${ne?'pt-e':'pt-ok'}">${ne?'⚠️':'✅'} ${days!==null?days+'d':''}</span>`:''}
                </div>
                ${ex.remarks?`<div class="remarks-lbl">📝 ${esc(ex.remarks)}</div>`:''}
                <div class="prod-row-actions">
                  <button class="ibtn" onclick="editProd('${p.id}')"><svg width="11" height="11" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M11 4H4a2 2 0 00-2 2v14a2 2 0 002 2h14a2 2 0 002-2v-7"/><path d="M18.5 2.5a2.121 2.121 0 013 3L12 15l-4 1 1-4z"/></svg></button>
                  <button class="ibtn" onclick="showProdDetail('${p.id}')"><svg width="11" height="11" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M12 16v-4M12 8h.01"/></svg></button>
                </div>
              </div>
              <div class="prod-row-right">
                <span class="chip ${ne?'c-exp':st.chip}">${ne?'EXP':st.label}</span>
                <div class="stock-ctrl">
                  <button class="sbtn" onclick="adjStock('${p.id}',-1)">−</button>
                  <span class="snum">${v}</span>
                  <button class="sbtn" onclick="adjStock('${p.id}',1)">+</button>
                </div>
              </div>
            </div>`;
          }).join('')}
        </div>
        <button class="add-btn" onclick="openAddForShelf(${rn},${sh})">
          <svg width="11" height="11" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path d="M12 5v14M5 12h14"/></svg>Add to shelf ${code}
        </button>
      </div>
    </div>`;
  }
  html+='</div></div></div>';
  document.getElementById('rackVisual').innerHTML=html;
}

function toggleShelf(code){
  S.openShelves[code]=!S.openShelves[code];saveS();
  const d=document.getElementById('sd_'+code);if(d)d.classList.toggle('open');
}
function uploadShelfPhoto(ev,code){const f=ev.target.files[0];if(!f)return;const r=new FileReader();r.onload=e=>{S.photos['shelf_'+code]=e.target.result;saveS();renderRackVisual();};r.readAsDataURL(f);}
function adjStock(id,d){setStock(id,getStock(id)+d);renderRackVisual();renderRackTabs();}

// IMAGE MODAL - click product thumb → change image
function openImgModal(id){
  document.getElementById('imgTargetId').value=id;
  const img=getImgSrc(id);const col=prodColor(id);
  const p=PLANOGRAM.find(x=>x.id===id)||{};
  document.getElementById('bigImgPreview').innerHTML=img
    ?`<img src="${img}" style="width:100%;height:100%;object-fit:cover;border-radius:10px">`
    :`<div style="width:100%;height:100%;background:linear-gradient(160deg,${col},#fff,${col});display:flex;align-items:center;justify-content:center;font-size:14px;font-weight:700;color:#333;text-align:center;padding:10px;border-radius:10px">${esc(p.name||'')}</div>`;
  document.getElementById('imgMbk').classList.add('open');
}
function saveProdImg(ev){const id=document.getElementById('imgTargetId').value;const f=ev.target.files[0];if(!f)return;const r=new FileReader();r.onload=e=>{S.prodImgs[id]=e.target.result;saveS();const col=prodColor(id);document.getElementById('bigImgPreview').innerHTML=`<img src="${e.target.result}" style="width:100%;height:100%;object-fit:cover;border-radius:10px">`;renderRackVisual();};r.readAsDataURL(f);}
function closeImgMbk(e){if(!e||e.target===document.getElementById('imgMbk'))document.getElementById('imgMbk').classList.remove('open');}

// PRODUCT DETAIL MODAL
function showProdDetail(id){
  const p=PLANOGRAM.find(x=>x.id===id);if(!p)return;
  const ex=getExtra(id);const v=getStock(id);const ne=isNearExpiry(id);const days=daysUntilExpiry(ex.expiry);
  const tips=getSellTips(p.name);const img=getImgSrc(id);const col=prodColor(id);
  const sec=sectionFor(p.rack);
  document.getElementById('detailInner').innerHTML=`
    <div style="width:100%;height:140px;border-radius:10px;overflow:hidden;margin-bottom:12px;cursor:pointer" onclick="openImgModal('${id}')">
      ${img?`<img src="${img}" style="width:100%;height:100%;object-fit:cover">`:`<div style="width:100%;height:100%;background:linear-gradient(160deg,${col},#fff,${col});display:flex;flex-direction:column;align-items:center;justify-content:center;gap:6px"><div style="font-size:13px;font-weight:700;color:#333;text-align:center;padding:10px">${esc(p.name)}</div><div style="font-size:11px;color:#888;background:rgba(255,255,255,.7);padding:3px 10px;border-radius:20px">📷 Tap to add photo</div></div>`}
    </div>
    <div style="font-size:15px;font-weight:800;margin-bottom:3px;line-height:1.3">${esc(p.name)}</div>
    <div style="font-size:10px;color:${sec.color};font-weight:700;margin-bottom:6px">${esc(sec.name)} · Shelf ${shelfCode(p.rack,p.shelf)}</div>
    ${p.barcode?`<div style="font-size:10px;color:var(--muted);font-family:'DM Mono',monospace;margin-bottom:6px">📦 ${esc(p.barcode)}${p.alshaya?' · 🏷 '+esc(p.alshaya):''}</div>`:''}
    <div class="scan-stat-row">
      <div class="ss"><div class="ssv" style="${v===0?'color:var(--red)':v<5?'color:var(--amber)':''}">${v}</div><div class="ssl">In Stock</div></div>
      <div class="ss"><div class="ssv">${p.facing}</div><div class="ssl">Facing</div></div>
      <div class="ss"><div class="ssv" style="font-size:14px">${shelfCode(p.rack,p.shelf)}</div><div class="ssl">Location</div></div>
    </div>
    ${ex.expiry?`<div style="background:${ne?'var(--red-bg)':'var(--green-bg)'};border:1.5px solid ${ne?'var(--red)':'var(--green)'};border-radius:7px;padding:9px;margin-bottom:9px;font-size:11px;font-weight:600;color:${ne?'var(--red)':'var(--green)'}">${ne?'⚠️':'✅'} Expiry: ${ex.expiry} · ${days!==null?days+' days':''} · Qty: ${ex.expiryQty||v}</div>`:''}
    ${ex.remarks?`<div style="background:var(--cream);border-radius:7px;padding:9px;margin-bottom:9px;font-size:11px">📝 ${esc(ex.remarks)}</div>`:''}
    <div class="sell-box"><div class="sell-box-title">💬 How to Sell</div><div class="sell-box-text">${tips.map(t=>`• ${esc(t)}`).join('<br>')}</div></div>
    <div class="sell-box" style="background:var(--teal-bg)">
      <div class="sell-box-title" style="color:var(--teal)">🌍 Patient Instructions</div>
      <div class="lang-tabs" id="pdLT">${LANGUAGES.map(l=>`<button class="lang-btn" onclick="translatePD('${l.code}','${id}',this)">${l.flag} ${l.name}</button>`).join('')}</div>
      <div class="trans-box" id="pdTB" style="font-size:11px;color:var(--muted)">Select language…</div>
    </div>
    <button class="btn-t" onclick="closeDetailModal();openImgModal('${id}')">📷 Change Product Image</button>`;
  document.getElementById('detailMbk').classList.add('open');
}
function translatePD(lc,id,btn){
  const ex=getExtra(id);const text=ex.remarks||'Take 1 tablet daily with food';
  document.querySelectorAll('#pdLT .lang-btn').forEach(b=>b.classList.remove('active'));btn.classList.add('active');
  const lang=LANGUAGES.find(l=>l.code===lc);
  const box=document.getElementById('pdTB');box.className='trans-box'+(lang?.rtl?' rtl':'');
  box.innerHTML='<i style="color:var(--muted)">Translating…</i>';
  setTimeout(()=>{box.innerHTML=`<strong>${lang?.flag} ${lang?.name}:</strong><br>${esc(translateText(text,lc))}`;},280);
}
function closeDetailModal(){document.getElementById('detailMbk').classList.remove('open');}
function closeDetailMbk(e){if(e.target===document.getElementById('detailMbk'))closeDetailModal();}

// SCANNER
let scanStream=null;
function openScanner(){document.getElementById('scannerBk').classList.add('open');document.getElementById('scanResult').innerHTML='';document.getElementById('mbc').value='';startCamera();}
async function startCamera(){try{scanStream=await navigator.mediaDevices.getUserMedia({video:{facingMode:'environment'}});document.getElementById('sv').srcObject=scanStream;}catch(e){document.getElementById('sv').style.display='none';}}
function searchByBarcode(code){
  code=(code||'').trim();if(!code)return;
  const p=PLANOGRAM.find(x=>x.barcode&&(x.barcode===code||x.barcode.includes(code))||x.alshaya===code);
  const el=document.getElementById('scanResult');
  if(!p){el.innerHTML=`<div style="background:var(--red-bg);border:1.5px solid var(--red);border-radius:10px;padding:14px;margin-top:11px;text-align:center"><div style="font-size:22px;margin-bottom:5px">❌</div><div style="font-weight:700;color:var(--red)">Not Found</div><div style="font-size:11px;color:var(--muted);margin-top:3px">${esc(code)}</div></div>`;return;}
  const v=getStock(p.id);const ne=isNearExpiry(p.id);const ex=getExtra(p.id);const tips=getSellTips(p.name).slice(0,3);const img=getImgSrc(p.id);const col=prodColor(p.id);
  el.innerHTML=`<div style="background:var(--white);border:2px solid var(--teal);border-radius:10px;padding:13px;margin-top:12px">
    <div style="width:100%;height:80px;border-radius:7px;overflow:hidden;margin-bottom:9px;cursor:pointer" onclick="closeScanner();showProdDetail('${p.id}')">
      ${img?`<img src="${img}" style="width:100%;height:100%;object-fit:cover">`:`<div style="width:100%;height:100%;background:linear-gradient(160deg,${col},#fff,${col});display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:700;color:#333;text-align:center;padding:8px">${esc(p.name)}</div>`}
    </div>
    <div style="font-size:14px;font-weight:800;margin-bottom:4px">${esc(p.name)}</div>
    <div style="font-size:10px;color:var(--muted);font-family:'DM Mono',monospace;margin-bottom:8px">${esc(p.barcode||'')} · Shelf ${shelfCode(p.rack,p.shelf)}</div>
    <div class="scan-stat-row"><div class="ss"><div class="ssv">${v}</div><div class="ssl">Stock</div></div><div class="ss"><div class="ssv">${p.facing}</div><div class="ssl">Facing</div></div><div class="ss"><div class="ssv" style="font-size:13px">${shelfCode(p.rack,p.shelf)}</div><div class="ssl">Shelf</div></div></div>
    ${ne?`<div style="background:var(--red-bg);border:1.5px solid var(--red);border-radius:7px;padding:7px;margin-bottom:8px;font-size:11px;font-weight:700;color:var(--red)">⚠️ NEAR EXPIRY: ${ex.expiry} · ${daysUntilExpiry(ex.expiry)} days</div>`:''}
    <div class="sell-box"><div class="sell-box-title">How to Sell</div><div class="sell-box-text">${tips.map(t=>`• ${esc(t)}`).join('<br>')}</div></div>
    <div class="lang-tabs" id="scLT">${LANGUAGES.map(l=>`<button class="lang-btn" onclick="translateScan('${l.code}','${p.id}',this)">${l.flag} ${l.name}</button>`).join('')}</div>
    <div class="trans-box" id="scTB" style="margin-top:7px;font-size:11px;color:var(--muted)">Tap language to translate</div>
    <button class="btn-t" style="margin-top:9px" onclick="closeScanner();showProdDetail('${p.id}')">View Full Details</button>
  </div>`;
}
function translateScan(lc,id,btn){
  const ex=getExtra(id);const text=ex.remarks||'Take 1 tablet daily with food';
  document.querySelectorAll('#scLT .lang-btn').forEach(b=>b.classList.remove('active'));btn.classList.add('active');
  const lang=LANGUAGES.find(l=>l.code===lc);const box=document.getElementById('scTB');
  box.className='trans-box'+(lang?.rtl?' rtl':'');box.innerHTML='<i>Translating…</i>';
  setTimeout(()=>{box.innerHTML=`<strong>${lang?.flag} ${lang?.name}:</strong><br>${esc(translateText(text,lc))}`;},280);
}
function closeScanner(){document.getElementById('scannerBk').classList.remove('open');if(scanStream)scanStream.getTracks().forEach(t=>t.stop());scanStream=null;}
function closeScannerMbk(e){if(e.target===document.getElementById('scannerBk'))closeScanner();}

// ADD/EDIT
let _pendingImg='';
function previewImg(ev){const f=ev.target.files[0];if(!f)return;const r=new FileReader();r.onload=e=>{_pendingImg=e.target.result;document.getElementById('imgPrev').innerHTML=`<img src="${e.target.result}" style="width:100%;height:100%;object-fit:cover;border-radius:7px">`;};r.readAsDataURL(f);}
function editProd(id){
  const p=PLANOGRAM.find(x=>x.id===id);if(!p)return;const ex=getExtra(id);
  document.getElementById('eId').value=id;document.getElementById('fName').value=p.name;
  document.getElementById('fBarcode').value=p.barcode||'';document.getElementById('fAlshaya').value=p.alshaya||'';
  buildRackOpts(p.rack);updateShelfOpts();document.getElementById('fRack').value=p.rack;updateShelfOpts();document.getElementById('fShelf').value=p.shelf;
  document.getElementById('fNotch').value=(p.shelfType||'')+' Notch:'+p.notch;document.getElementById('fFacing').value=p.facing||1;
  document.getElementById('fStock').value=getStock(id);document.getElementById('fLines').value=p.lines||1;document.getElementById('fPrice').value=p.price||0;
  document.getElementById('fExpiry').value=ex.expiry||'';document.getElementById('fExpiryQty').value=ex.expiryQty||0;document.getElementById('fRemarks').value=ex.remarks||'';
  const ei=getImgSrc(id);_pendingImg=ei;const col=prodColor(id);
  document.getElementById('imgPrev').innerHTML=ei?`<img src="${ei}" style="width:100%;height:100%;object-fit:cover;border-radius:7px">`:`<div style="width:100%;height:100%;background:${col};border-radius:7px;display:flex;align-items:center;justify-content:center;font-size:10px;color:#555">No image</div>`;
  document.getElementById('mTitle').textContent='Edit Product';document.getElementById('addModalBk').classList.add('open');
}
function buildRackOpts(sel){
  const s=document.getElementById('fRack');s.innerHTML='';
  SECTIONS.forEach(sec=>{const og=document.createElement('optgroup');og.label=sec.name;sec.racks.forEach(r=>{const o=document.createElement('option');o.value=r;o.textContent='Rack '+r;if(r==sel)o.selected=true;og.appendChild(o);});s.appendChild(og);});
}
function updateShelfOpts(){
  const rack=parseInt(document.getElementById('fRack').value)||1;const s=document.getElementById('fShelf');const cur=parseInt(s.value)||1;s.innerHTML='';
  for(let i=1;i<=SPR;i++){const o=document.createElement('option');o.value=i;o.textContent='Shelf '+shelfCode(rack,i);if(i===cur)o.selected=true;s.appendChild(o);}
}
function openAddModal(){_pendingImg='';['eId','fBarcode','fAlshaya','fNotch','fRemarks'].forEach(x=>document.getElementById(x).value='');['fName'].forEach(x=>document.getElementById(x).value='');['fFacing'].forEach(x=>document.getElementById(x).value='1');['fStock','fLines','fExpiryQty'].forEach(x=>document.getElementById(x).value='0');['fPrice'].forEach(x=>document.getElementById(x).value='0');['fExpiry'].forEach(x=>document.getElementById(x).value='');buildRackOpts(currentRack);updateShelfOpts();document.getElementById('imgPrev').innerHTML='<span style="font-size:28px;opacity:.4">💊</span>';document.getElementById('mTitle').textContent='Add Product';document.getElementById('addModalBk').classList.add('open');}
function openAddForShelf(r,s){openAddModal();document.getElementById('fRack').value=r;updateShelfOpts();document.getElementById('fShelf').value=s;}
function closeMbk(e){if(e.target===document.getElementById('addModalBk'))closeModal();}
function closeModal(){document.getElementById('addModalBk').classList.remove('open');}
function saveProduct(){
  const name=document.getElementById('fName').value.trim();if(!name){document.getElementById('fName').focus();return;}
  const rack=parseInt(document.getElementById('fRack').value);const shelf=parseInt(document.getElementById('fShelf').value);
  const facing=parseInt(document.getElementById('fFacing').value)||1;const stock=parseInt(document.getElementById('fStock').value)||0;
  const lines=parseInt(document.getElementById('fLines').value)||1;const price=parseFloat(document.getElementById('fPrice').value)||0;
  const barcode=document.getElementById('fBarcode').value.trim();const alshaya=document.getElementById('fAlshaya').value.trim();
  const notchRaw=document.getElementById('fNotch').value.trim();const expiry=document.getElementById('fExpiry').value;
  const expiryQty=parseInt(document.getElementById('fExpiryQty').value)||0;const remarks=document.getElementById('fRemarks').value.trim();
  const id=document.getElementById('eId').value;const ex={expiry,expiryQty,remarks};
  if(id){
    S.stockOverrides[id]=stock;setExtra(id,ex);if(_pendingImg)S.prodImgs[id]=_pendingImg;
    const pp=PLANOGRAM.find(x=>x.id===id);if(pp)Object.assign(pp,{name,rack,shelf,facing,lines,price,barcode,alshaya});
    const ci=S.customProds.findIndex(x=>x.id===id);if(ci>=0)S.customProds[ci]={...PLANOGRAM.find(x=>x.id===id)};
    saveS();
  }else{
    const newId=uid();const np={id:newId,name,rack,shelf,facing,lines,price,barcode,alshaya,notch:notchRaw,shelfType:'',stock};
    PLANOGRAM.push(np);S.customProds.push(np);S.stockOverrides[newId]=stock;setExtra(newId,ex);if(_pendingImg)S.prodImgs[newId]=_pendingImg;saveS();
  }
  closeModal();renderRackTabs();renderRackVisual();if(document.getElementById('screen-summary').classList.contains('active'))renderSummary();
}

// SUMMARY
function renderSummary(){
  const all=PLANOGRAM;const total=all.length;
  const low=all.filter(p=>{const v=getStock(p.id);return v>0&&v<5;}).length;
  const out=all.filter(p=>getStock(p.id)===0).length;
  const exp=all.filter(p=>isNearExpiry(p.id)).length;
  document.getElementById('statGrid').innerHTML=`
    <div class="stat-card"><div class="sic" style="background:#EEF2FF">📦</div><div><div class="sv">${total}</div><div class="sl">Total SKUs</div></div></div>
    <div class="stat-card"><div class="sic" style="background:var(--amber-bg)">⚠️</div><div><div class="sv">${low}</div><div class="sl">Low Stock</div></div></div>
    <div class="stat-card"><div class="sic" style="background:var(--red-bg)">🚫</div><div><div class="sv">${out}</div><div class="sl">Out of Stock</div></div></div>
    <div class="stat-card"><div class="sic" style="background:var(--red-bg)">🗓</div><div><div class="sv" style="color:var(--red)">${exp}</div><div class="sl">Near Expiry</div></div></div>`;
  const nearExp=all.filter(p=>isNearExpiry(p.id));
  const nb=document.getElementById('nearExpBanner');
  if(nearExp.length){let h=`<div class="exp-banner" style="border-radius:10px;margin-bottom:12px;border:none"><div class="exp-banner-title">🚨 Near Expiry (${nearExp.length})</div><div class="exp-grid">`;nearExp.forEach(p=>{const ex=getExtra(p.id);const d=daysUntilExpiry(ex.expiry);h+=`<div class="exp-card"><div class="exp-card-name">${esc(p.name)}</div><div class="exp-card-meta">⏰ ${d}d · ${ex.expiry}</div><div class="exp-card-shelf">Shelf ${shelfCode(p.rack,p.shelf)}</div></div>`;});h+='</div></div>';nb.innerHTML=h;}else nb.innerHTML='';
  renderAllList(document.getElementById('searchInp')?.value||'');
}
function renderAllList(q){
  let prods=[...PLANOGRAM];
  if(q)prods=prods.filter(p=>p.name.toLowerCase().includes(q.toLowerCase())||p.barcode?.includes(q)||p.alshaya?.toLowerCase().includes(q.toLowerCase()));
  prods.sort((a,b)=>{const ae=isNearExpiry(a.id)?0:1;const be=isNearExpiry(b.id)?0:1;if(ae!==be)return ae-be;return a.rack-b.rack||a.shelf-b.shelf;});
  const el=document.getElementById('allList');
  if(!prods.length){el.innerHTML='<div style="text-align:center;padding:36px;color:var(--muted)">No products found.</div>';return;}
  el.innerHTML=prods.map(p=>{
    const v=getStock(p.id);const st=stockStatus(v);const sec=sectionFor(p.rack);const ne=isNearExpiry(p.id);const ex=getExtra(p.id);const days=daysUntilExpiry(ex.expiry);const img=getImgSrc(p.id);const col=prodColor(p.id);
    return `<div class="all-card${ne?' ne':''}" style="border-left-color:${ne?'var(--red)':sec.color};cursor:pointer" onclick="showProdDetail('${p.id}')">
      <div style="width:32px;height:40px;border-radius:5px;flex-shrink:0;overflow:hidden;border:1px solid var(--border)">
        ${img?`<img src="${img}" style="width:100%;height:100%;object-fit:cover">`:`<div style="width:100%;height:100%;background:${col}"></div>`}
      </div>
      <div style="flex:1;min-width:0">
        <div style="font-size:11px;font-weight:700;margin-bottom:3px;line-height:1.3">${esc(p.name)}</div>
        <div class="pr-tags" style="margin-top:2px">
          <span class="ptag" style="background:${sec.bg};color:${sec.color};font-weight:700">${shelfCode(p.rack,p.shelf)}</span>
          <span class="ptag pt-f">F:${p.facing}</span>
          ${ne?`<span class="ptag pt-e">⚠️ ${days}d</span>`:''}
          ${p.barcode?`<span class="ptag" style="background:#F8F8F8;color:#999">${esc(p.barcode.slice(0,12))}</span>`:''}
        </div>
        ${ex.remarks?`<div class="remarks-lbl">${esc(ex.remarks.slice(0,55))}${ex.remarks.length>55?'…':''}</div>`:''}
      </div>
      <div style="display:flex;flex-direction:column;align-items:flex-end;gap:4px;flex-shrink:0">
        <span class="chip ${ne?'c-exp':st.chip}">${ne?'EXP':st.label}</span>
        <div class="stock-ctrl">
          <button class="sbtn" onclick="event.stopPropagation();adjStockAll('${p.id}',-1)">−</button>
          <span class="snum">${v}</span>
          <button class="sbtn" onclick="event.stopPropagation();adjStockAll('${p.id}',1)">+</button>
        </div>
      </div>
    </div>`;
  }).join('');
}
function adjStockAll(id,d){setStock(id,getStock(id)+d);renderSummary();renderRackTabs();}
function filterAll(v){renderAllList(v);}

function switchTab(tab){
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  document.querySelectorAll('.nb').forEach(b=>b.classList.remove('active'));
  document.getElementById('screen-'+tab).classList.add('active');
  const nb=document.getElementById('nav-'+tab);if(nb)nb.classList.add('active');
  document.getElementById('topAddBtn').style.display='';
  if(tab==='summary')renderSummary();
}

loadS();
renderRackTabs();
renderRackVisual();
renderSummary();

</script>
</body>
</html>
