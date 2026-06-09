[motor.html](https://github.com/user-attachments/files/28762442/motor.html)
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kala — Motor de Sugerencias</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600&family=Inter:wght@300;400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{--coral:#E86B3A;--cream:#FDF8F5;--cream-dark:#F5EDE6;--text:#2C1810;--text-muted:#8A6A5E;--border:#E8D5CC;--white:#FFFFFF;--green:#22c55e;--amber:#d97706;--blue:#2563eb;--red:#ef4444}
body{font-family:'Inter',sans-serif;background:var(--cream);color:var(--text);min-height:100vh}
header{background:var(--text);color:var(--cream);padding:0 2rem;height:64px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:10}
.header-logo{font-family:'Cormorant Garamond',serif;font-size:1.5rem;font-weight:600}
.header-logo .robot{color:var(--coral)}
.header-logo span{font-size:0.6rem;letter-spacing:3px;text-transform:uppercase;color:rgba(253,248,245,0.5);display:block;font-family:'Inter',sans-serif;font-weight:400;margin-top:-2px}
.back-btn{background:none;border:1px solid rgba(253,248,245,0.3);color:var(--cream);padding:0.4rem 1rem;border-radius:4px;font-size:0.72rem;letter-spacing:1px;text-transform:uppercase;cursor:pointer;font-family:'Inter',sans-serif;text-decoration:none}
.back-btn:hover{border-color:var(--cream)}
main{flex:1;padding:2rem;max-width:900px;margin:0 auto;width:100%}
.intro{margin-bottom:2rem}
.intro h1{font-family:'Cormorant Garamond',serif;font-size:2rem;font-weight:500;margin-bottom:0.4rem}
.intro p{font-size:0.9rem;color:var(--text-muted);line-height:1.5;max-width:600px}
.summary-bar{display:flex;gap:1rem;margin-bottom:2rem;flex-wrap:wrap}
.summary-pill{background:var(--white);border:1px solid var(--border);border-radius:8px;padding:0.8rem 1.2rem;flex:1;min-width:140px}
.summary-num{font-family:'Cormorant Garamond',serif;font-size:1.8rem;font-weight:600}
.summary-label{font-size:0.68rem;letter-spacing:1px;text-transform:uppercase;color:var(--text-muted)}
.section-title{font-family:'Cormorant Garamond',serif;font-size:1.3rem;font-weight:500;margin:2rem 0 1rem;display:flex;align-items:center;gap:0.5rem}
.suggestion{background:var(--white);border:1px solid var(--border);border-radius:10px;padding:1.2rem;margin-bottom:1rem;border-left:4px solid var(--border)}
.suggestion.type-stale{border-left-color:var(--amber)}
.suggestion.type-overstock{border-left-color:var(--coral)}
.suggestion.type-restock{border-left-color:var(--blue)}
.suggestion.type-season{border-left-color:#9333ea}
.sug-head{display:flex;align-items:flex-start;gap:0.9rem;margin-bottom:0.8rem}
.sug-icon{font-size:1.5rem;flex-shrink:0;width:44px;height:44px;display:flex;align-items:center;justify-content:center;background:var(--cream-dark);border-radius:8px}
.sug-body{flex:1;min-width:0}
.sug-product{font-weight:600;font-size:1rem;margin-bottom:0.2rem}
.sug-reason{font-size:0.82rem;color:var(--text-muted);line-height:1.4}
.sug-tag{display:inline-block;font-size:0.62rem;letter-spacing:1px;text-transform:uppercase;font-weight:600;padding:0.2rem 0.6rem;border-radius:20px;margin-bottom:0.5rem}
.tag-stale{background:#fef3c7;color:var(--amber)}
.tag-overstock{background:#fff7ed;color:var(--coral)}
.tag-restock{background:#dbeafe;color:var(--blue)}
.tag-season{background:#f3e8ff;color:#9333ea}
.sug-action{background:var(--cream);border-radius:8px;padding:0.9rem;margin:0.8rem 0;font-size:0.88rem;display:flex;align-items:center;gap:0.6rem}
.sug-action .arrow{color:var(--coral);font-weight:600}
.price-change{font-family:'JetBrains Mono',monospace;font-weight:500}
.price-old{color:var(--text-muted);text-decoration:line-through;margin-right:0.5rem}
.price-new{color:var(--coral);font-weight:600}
.sug-actions{display:flex;gap:0.7rem;flex-wrap:wrap}
.btn-apply{background:var(--coral);color:white;border:none;padding:0.6rem 1.3rem;border-radius:6px;font-size:0.76rem;letter-spacing:1px;text-transform:uppercase;cursor:pointer;font-family:'Inter',sans-serif;font-weight:600;flex:1;min-width:120px;min-height:42px}
.btn-apply:hover{background:#C8512A}
.btn-apply.restock{background:var(--blue)}
.btn-apply.restock:hover{background:#1d4ed8}
.btn-dismiss{background:none;border:1px solid var(--border);padding:0.6rem 1.3rem;border-radius:6px;font-size:0.76rem;letter-spacing:1px;text-transform:uppercase;cursor:pointer;color:var(--text-muted);font-family:'Inter',sans-serif;min-height:42px}
.btn-dismiss:hover{border-color:var(--text-muted);color:var(--text)}
.empty{text-align:center;padding:4rem 2rem;color:var(--text-muted)}
.empty .big{font-size:3rem;display:block;margin-bottom:1rem}
.empty h2{font-family:'Cormorant Garamond',serif;font-size:1.5rem;font-weight:500;color:var(--text);margin-bottom:0.5rem}
.config-note{background:var(--cream-dark);border-radius:8px;padding:1rem 1.2rem;margin-top:2rem;font-size:0.78rem;color:var(--text-muted);line-height:1.5}
.config-note strong{color:var(--text)}
.toast{position:fixed;bottom:2rem;left:50%;transform:translateX(-50%) translateY(20px);background:var(--text);color:var(--cream);padding:0.8rem 1.5rem;border-radius:4px;font-size:0.8rem;letter-spacing:1px;z-index:999;opacity:0;transition:all .3s;pointer-events:none;white-space:nowrap}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0)}
@media(max-width:768px){
  main{padding:1rem}header{padding:0 1rem}.header-logo span{display:none}
  .summary-bar{gap:0.6rem}.summary-pill{min-width:calc(50% - 0.3rem)}
}
</style>
</head>
<body>
<header>
  <div class="header-logo"><span class="robot">🤖</span> Motor <span>Sugerencias inteligentes</span></div>
  <a href="admin.html" class="back-btn">← Volver al panel</a>
</header>
<main>
  <div class="intro">
    <h1>Sugerencias para tu inventario</h1>
    <p>El motor analiza tu stock y tus ventas, y te propone acciones. Vos decidís cuáles aplicar — nada cambia sin tu visto bueno.</p>
  </div>
  <div class="summary-bar" id="summaryBar"></div>
  <div id="suggestionsArea"></div>
  <div class="config-note">
    <strong>¿Cómo funciona?</strong> El motor mira cuántos días hace que no se vende cada producto, cuánto stock queda, su ritmo de ventas y su temporada. Cuanto más uses el botón "Vendí" en el panel, más preciso se vuelve. Por ahora trabaja con reglas simples y seguras, pensadas para un negocio chico.
  </div>
</main>
<div class="toast" id="toast"></div>
<script>
const STORAGE_KEY='kala_products';
const SALES_KEY='kala_sales';
const DISMISS_KEY='kala_dismissed';

// ── UMBRALES (ajustables) ──
const RULES={
  staleDays1:15, staleDiscount1:10,
  staleDays2:30, staleDiscount2:20,
  overstockUnits:10, overstockMaxSales:2, overstockWindow:20,
  restockUnits:3, restockMinSales:3, restockWindow:7
};
const SEASON_ORDER={verano:[12,1,2],otono:[3,4,5],invierno:[6,7,8],primavera:[9,10,11]};

let products=[];
let sales=[];
let dismissed=[];

function load(){
  products=JSON.parse(localStorage.getItem(STORAGE_KEY)||'[]');
  products.forEach(p=>{if(p.stock===undefined)p.stock=10;if(p.season===undefined)p.season='all'});
  sales=JSON.parse(localStorage.getItem(SALES_KEY)||'[]');
  dismissed=JSON.parse(localStorage.getItem(DISMISS_KEY)||'[]');
}
function save(){localStorage.setItem(STORAGE_KEY,JSON.stringify(products))}
function saveDismissed(){localStorage.setItem(DISMISS_KEY,JSON.stringify(dismissed))}
function formatPrice(p){return '$'+Number(p).toLocaleString('es-AR')}
function daysAgo(iso){return Math.floor((Date.now()-new Date(iso).getTime())/(1000*60*60*24))}

function salesFor(pid,windowDays){
  const cutoff=Date.now()-windowDays*24*60*60*1000;
  return sales.filter(s=>s.productId===pid && new Date(s.date).getTime()>=cutoff).reduce((sum,s)=>sum+s.qty,0);
}
function lastSaleDays(pid){
  const ps=sales.filter(s=>s.productId===pid);
  if(!ps.length)return null;
  const latest=ps.reduce((a,b)=>new Date(a.date)>new Date(b.date)?a:b);
  return daysAgo(latest.date);
}

// ── MOTOR: genera sugerencias ──
function generateSuggestions(){
  const out=[];
  const month=new Date().getMonth()+1;
  products.forEach(p=>{
    if(!p.active)return;
    const sid=p.id;
    const lastSale=lastSaleDays(sid);
    const daysSinceCreated=p.createdAt?daysAgo(p.createdAt):999;
    const idleDays=lastSale!==null?lastSale:daysSinceCreated;
    const recentSales=salesFor(sid,RULES.restockWindow);
    const windowSales=salesFor(sid,RULES.overstockWindow);

    // REGLA 1: Stock bajo + alta rotación → reponer (prioridad alta, va primero)
    if(p.stock<=RULES.restockUnits && recentSales>=RULES.restockMinSales){
      out.push({id:sid,type:'restock',icon:'🔥',tag:'Reponé',tagClass:'restock',product:p.name,
        reason:`Vendiste ${recentSales} unidades en los últimos ${RULES.restockWindow} días y solo quedan ${p.stock}. Se está agotando rápido.`,
        actionHtml:`<span class="arrow">→</span> Conseguí más stock pronto. Con esta demanda, hasta podrías subir el precio.`,
        apply:()=>{showToast(`Recordatorio: reponer "${p.name}"`);}});
      return;
    }
    // REGLA 2: Fin de temporada → liquidar
    if(p.season!=='all' && SEASON_ORDER[p.season]){
      const seasonMonths=SEASON_ORDER[p.season];
      const lastMonth=seasonMonths[seasonMonths.length-1];
      if(month===lastMonth && !p.onOffer && p.stock>0){
        const newPrice=Math.round(p.price*0.75/100)*100;
        out.push({id:sid,type:'season',icon:'🍂',tag:'Fin de temporada',tagClass:'season',product:p.name,
          reason:`Es producto de ${p.season} y la temporada está terminando. Quedan ${p.stock} unidades que conviene liquidar antes de que pierdan rotación.`,
          actionHtml:`<span class="arrow">→</span> Liquidación 25%: <span class="price-change"><span class="price-old">${formatPrice(p.price)}</span><span class="price-new">${formatPrice(newPrice)}</span></span>`,
          apply:()=>{p.onOffer=true;p.originalPrice=p.price;p.price=newPrice;save();showToast(`"${p.name}" en liquidación ✓`);}});
        return;
      }
    }
    // REGLA 3: Estancado → descuento progresivo
    if(idleDays>=RULES.staleDays2 && !p.onOffer){
      const newPrice=Math.round(p.price*(1-RULES.staleDiscount2/100)/100)*100;
      out.push({id:sid,type:'stale',icon:'🐌',tag:'Muy estancado',tagClass:'stale',product:p.name,
        reason:`Hace ${idleDays} días que no se vende. Lleva demasiado tiempo quieto, una oferta puede reactivarlo.`,
        actionHtml:`<span class="arrow">→</span> Oferta ${RULES.staleDiscount2}%: <span class="price-change"><span class="price-old">${formatPrice(p.price)}</span><span class="price-new">${formatPrice(newPrice)}</span></span>`,
        apply:()=>{p.onOffer=true;p.originalPrice=p.price;p.price=newPrice;save();showToast(`"${p.name}" en oferta ✓`);}});
      return;
    }
    if(idleDays>=RULES.staleDays1 && !p.onOffer){
      const newPrice=Math.round(p.price*(1-RULES.staleDiscount1/100)/100)*100;
      out.push({id:sid,type:'stale',icon:'⏳',tag:'Estancado',tagClass:'stale',product:p.name,
        reason:`Hace ${idleDays} días que no se vende. Un pequeño empujón puede ayudar a moverlo.`,
        actionHtml:`<span class="arrow">→</span> Oferta ${RULES.staleDiscount1}%: <span class="price-change"><span class="price-old">${formatPrice(p.price)}</span><span class="price-new">${formatPrice(newPrice)}</span></span>`,
        apply:()=>{p.onOffer=true;p.originalPrice=p.price;p.price=newPrice;save();showToast(`"${p.name}" en oferta ✓`);}});
      return;
    }
    // REGLA 4: Sobrestock + baja rotación → ofertar para liberar
    if(p.stock>=RULES.overstockUnits && windowSales<=RULES.overstockMaxSales && !p.onOffer){
      const newPrice=Math.round(p.price*0.85/100)*100;
      out.push({id:sid,type:'overstock',icon:'📦',tag:'Mucho stock',tagClass:'overstock',product:p.name,
        reason:`Tenés ${p.stock} unidades y solo se vendieron ${windowSales} en ${RULES.overstockWindow} días. Hay capital inmovilizado.`,
        actionHtml:`<span class="arrow">→</span> Oferta 15% para liberar: <span class="price-change"><span class="price-old">${formatPrice(p.price)}</span><span class="price-new">${formatPrice(newPrice)}</span></span>`,
        apply:()=>{p.onOffer=true;p.originalPrice=p.price;p.price=newPrice;save();showToast(`"${p.name}" en oferta ✓`);}});
      return;
    }
  });
  // filtrar descartadas
  return out.filter(s=>!dismissed.includes(s.type+'_'+s.id));
}

function render(){
  const suggestions=generateSuggestions();
  // resumen
  const counts={restock:0,stale:0,overstock:0,season:0};
  suggestions.forEach(s=>counts[s.type]++);
  document.getElementById('summaryBar').innerHTML=`
    <div class="summary-pill"><div class="summary-num">${suggestions.length}</div><div class="summary-label">Sugerencias</div></div>
    <div class="summary-pill"><div class="summary-num" style="color:var(--blue)">${counts.restock}</div><div class="summary-label">Reponer</div></div>
    <div class="summary-pill"><div class="summary-num" style="color:var(--amber)">${counts.stale}</div><div class="summary-label">Estancados</div></div>
    <div class="summary-pill"><div class="summary-num" style="color:var(--coral)">${counts.overstock+counts.season}</div><div class="summary-label">Ofertas</div></div>`;
  const area=document.getElementById('suggestionsArea');
  if(!suggestions.length){
    area.innerHTML=`<div class="empty"><span class="big">✨</span><h2>Todo en orden</h2><p>No hay nada que sugerir por ahora. El inventario está balanceado.<br>Volvé después de registrar más ventas en el panel.</p></div>`;
    return;
  }
  area.innerHTML=suggestions.map((s,i)=>`
    <div class="suggestion type-${s.type}">
      <div class="sug-head">
        <div class="sug-icon">${s.icon}</div>
        <div class="sug-body">
          <span class="sug-tag tag-${s.tagClass}">${s.tag}</span>
          <div class="sug-product">${s.product}</div>
          <div class="sug-reason">${s.reason}</div>
        </div>
      </div>
      <div class="sug-action">${s.actionHtml}</div>
      <div class="sug-actions">
        <button class="btn-apply ${s.type==='restock'?'restock':''}" onclick="applySuggestion(${i})">${s.type==='restock'?'Marcar como visto':'Aplicar'}</button>
        <button class="btn-dismiss" onclick="dismissSuggestion(${i})">Descartar</button>
      </div>
    </div>`).join('');
  window._currentSuggestions=suggestions;
}

function applySuggestion(i){
  const s=window._currentSuggestions[i];if(!s)return;
  s.apply();
  // las de reponer no modifican producto, solo se descartan tras marcarlas
  dismissed.push(s.type+'_'+s.id);saveDismissed();
  render();
}
function dismissSuggestion(i){
  const s=window._currentSuggestions[i];if(!s)return;
  dismissed.push(s.type+'_'+s.id);saveDismissed();
  showToast('Sugerencia descartada');
  render();
}
function showToast(msg){
  const t=document.getElementById('toast');t.textContent=msg;t.classList.add('show');
  setTimeout(()=>t.classList.remove('show'),2500);
}
load();render();
</script>
</body>
</html>
