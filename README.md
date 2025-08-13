<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Chandan — Data Science & Engineering</title>
  <style>
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,Arial;background:#041022;color:#e6f0fb}
    .wrap{max-width:860px;margin:28px auto;padding:20px}
    .card{background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .hero{display:flex;gap:16px;align-items:center}
    .avatar{width:84px;height:84px;border-radius:12px;overflow:hidden;background:#081226}
    .avatar img{width:100%;height:100%;object-fit:cover}
    h1{margin:0;font-size:22px}
    .muted{color:#9fb0c8;font-size:14px}
    .chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .chip{background:rgba(255,255,255,0.02);padding:8px 10px;border-radius:8px;font-size:13px;color:#dceffd}
    .row{display:flex;gap:12px;align-items:center;margin-top:12px}
    a.link{color:#7be0ff;text-decoration:none;font-weight:600}
    .small{font-size:13px;color:#9fb0c8}
    .gh{margin-top:12px;display:flex;flex-direction:column;gap:8px}
    .pkg{display:flex;gap:12px;align-items:center;padding:10px;border-radius:10px;background:rgba(255,255,255,0.01);border:1px solid rgba(255,255,255,0.02)}
    .pkg .logo{width:56px;height:56px;border-radius:8px;background:#081226;display:flex;align-items:center;justify-content:center;font-weight:700}
    .pkg pre{background:rgba(0,0,0,0.12);padding:8px;border-radius:6px;margin:0;font-size:13px}
  </style>
</head>
<body>
  <div class="wrap">
    <section class="card hero">
      <div class="avatar"><img src="https://avatars.githubusercontent.com/u/0000000?v=4" alt="avatar"></div>
      <div style="flex:1">
        <h1>Namaste — I'm <em>Chandan</em> 👋</h1>
        <div class="muted">Data Science & Engineering — remote sensing, air quality modelling, sensor calibration, time-series analysis, reproducible tooling.</div>

        <p style="margin-top:10px;color:#dfeeff">
          I design and deploy full data pipelines for environmental monitoring — from noisy sensor/satellite ingestion to clean, aligned time-series with validated PM2.5 estimates.  
          Skilled in scalable ETL, spatial analysis, model training (ML/DL/NLP/LLM), and deployment via containerised services.  
          Experienced across research institutes and public sector projects, with a focus on reproducibility, automation, and production-readiness.
        </p>

        <div class="chips">
          <div class="chip">Python</div>
          <div class="chip">C</div>
          <div class="chip">OOP / DSA</div>
          <div class="chip">pandas / xarray / geopandas</div>
          <div class="chip">PyTorch / TensorFlow / Keras</div>
          <div class="chip">scikit-learn</div>
          <div class="chip">Flask / REST API</div>
          <div class="chip">LangChain / RAG</div>
          <div class="chip">rasterio / GDAL / Folium</div>
          <div class="chip">Docker / AWS / MLOps</div>
          <div class="chip">SQLite / MongoDB</div>
          <div class="chip">NetCDF / GRIB</div>
          <div class="chip">CI/CD / GitHub Actions</div>
        </div>

        <div class="row">
          <div class="small">Worked at IIM Bangalore & IIT Bombay in Data Science roles.</div>
        </div>

        <div class="row">
          <a class="link" href="http://ec2-13-235-81-32.ap-south-1.compute.amazonaws.com:8080/" target="_blank">Sensor Live Dashboard — live</a>
        </div>

      </div>
    </section>

    <div style="height:12px"></div>

    <section class="card">
      <div style="display:flex;justify-content:space-between;align-items:center">
        <div>
          <div class="small">Education</div>
          <div>B.Tech — Computer Science & Technology, UEM Kolkata · CGPA 8.8</div>
        </div>
        <div style="text-align:right">
          <div class="small">Contact</div>
          <div class="small">chandankr014@gmail.com · <a class="link" href="https://github.com/chandankr014" target="_blank">github.com/chandankr014</a></div>
        </div>
      </div>

      <div class="gh">
        <img src="https://github-readme-stats.vercel.app/api?username=chandankr014&show_icons=true&theme=dark" alt="github stats" style="width:100%;border-radius:8px;overflow:hidden;border:1px solid rgba(255,255,255,0.03)">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chandankr014&layout=compact&theme=dark" alt="top langs" style="width:100%;border-radius:8px;overflow:hidden;border:1px solid rgba(255,255,255,0.03)">

        <div class="pkg">
          <div class="logo">airpy</div>
          <div style="flex:1">
            <strong>airpy-tool</strong>
            <div class="small" style="margin-top:4px">Open-source Python package for air quality data processing & utilities — published on PyPI.</div>
            <div style="margin-top:8px;display:flex;gap:8px;align-items:center">
              <a class="link" href="https://pypi.org/project/airpy-tool/" target="_blank">PyPI package</a>
              <pre>pip install airpy-tool</pre>
            </div>
          </div>
        </div>

      </div>
    </section>

    <footer style="margin-top:12px;text-align:center;color:#9fb0c8;font-size:13px">
      Profile blends research, engineering, and applied data science. Includes live dashboard & PyPI package.
    </footer>
  </div>
</body>
</html>
