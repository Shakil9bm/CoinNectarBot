:root {
  --bg:#f6f8fb;
  --card:#ffffff;
  --accent:#0b74ff;
  --muted:#6b7280;
  --danger:#e11d48;
}
*{box-sizing:border-box}
body{
  margin:0;
  font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
  background:var(--bg);
  color:#111827;
}
.container{max-width:760px;margin:20px auto;padding:20px}
header h1{margin:0;font-size:24px}
.sub{color:var(--muted);margin-top:6px}
.status{display:flex;gap:20px;margin-top:18px}
.status>div{
  background:var(--card);
  padding:14px;
  border-radius:10px;
  flex:1;
  box-shadow:0 2px 6px rgba(15,23,42,0.04);
}
.label{color:var(--muted);font-size:13px}
.big{font-weight:700;font-size:20px;margin-top:6px}
.actions{margin-top:18px}
button{cursor:pointer;border:0;padding:12px 16px;border-radius:10px;font-weight:600}
.primary{background:var(--accent);color:#fff;box-shadow:0 6px 18px rgba(11,116,255,0.12)}
.secondary{background:#fff;border:1px solid #e5e7eb;}
.ghost{background:transparent;border:1px dashed #cbd5e1;padding:8px 12px}
.note{color:var(--muted);margin-top:8px}
.withdraw{margin-top:22px;background:var(--card);padding:14px;border-radius:10px}
.form-row{display:flex;flex-direction:column;margin-bottom:10px}
.form-row input{padding:10px;border-radius:8px;border:1px solid #e5e7eb}
.msg{margin-top:8px;color:var(--danger)}
.history{margin-top:18px;background:var(--card);padding:14px;border-radius:10px}
.history ul{list-style:none;padding:0;margin:0}
.history li{padding:8px 0;border-bottom:1px dashed #eef2ff;font-size:14px}
footer{margin-top:14px;color:var(--muted);font-size:12px}
.modal{
  position:fixed;left:0;right:0;top:0;bottom:0;
  display:flex;align-items:center;justify-content:center;
  background:rgba(2,6,23,0.45);
}
.hidden{display:none}
.modal-content{
  background:#fff;
  padding:22px;
  border-radius:12px;
  text-align:center;
  width:320px;
}
.timer{font-size:32px;font-weight:700;margin:12px 0}
