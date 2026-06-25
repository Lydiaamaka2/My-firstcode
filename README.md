
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>5 Fun Facts about Microbiology</title>
  <style>
    :root{
      --gold:#d4af37;
      --green:#1a8a3b;
      --red:#b71c1c;
      --muted:#333;
      --card-bg:#fff8e6;
      --radius:12px;
      --max-w:900px;
      --pad:18px;
      --shadow: 0 6px 18px rgba(0,0,0,0.08);
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }

    body{
      background: linear-gradient(180deg,#fff 0%, #fffdf5 100%);
      color:var(--muted);
      padding:28px;
      display:flex;
      align-items:center;
      justify-content:center;
      min-height:100vh;
    }

    .wrap{
      width:100%;
      max-width:var(--max-w);
      background:var(--card-bg);
      border:4px solid var(--gold);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      padding:24px;
    }

    header{
      display:flex;
      gap:16px;
      align-items:center;
      margin-bottom:18px;
    }

    .title{
      color:var(--gold);
      font-size:1.6rem;
      font-weight:700;
      letter-spacing:0.4px;
    }

    .subtitle{
      color:#6b4b00;
      font-size:0.95rem;
    }

    .definition{
      background:rgba(212,175,55,0.06);
      border-left:6px solid var(--gold);
      padding:14px;
      margin:14px 0;
      border-radius:8px;
    }

    .facts{
      display:grid;
      gap:12px;
      margin-top:8px;
    }

    .fact{
      background:#ffffff;
      border-radius:10px;
      padding:14px;
      display:flex;
      gap:12px;
      align-items:flex-start;
      box-shadow: 0 4px 10px rgba(0,0,0,0.04);
      border:1px solid rgba(0,0,0,0.03);
    }

    .badge{
      min-width:56px;
      height:56px;
      border-radius:10px;
      display:flex;
      align-items:center;
      justify-content:center;
      color:#fff;
      font-weight:700;
      font-size:0.95rem;
      flex-shrink:0;
    }

    .badge.gold{ background:var(--gold); color:#2b1700; }
    .badge.green{ background:var(--green); }
    .badge.red{ background:var(--red); }

    .fact h3{
      margin:0 0 4px 0;
      font-size:1.05rem;
    }

    .fact p{
      margin:0;
      font-size:0.95rem;
      line-height:1.38;
    }

    .legend{
      display:flex;
      gap:8px;
      margin-top:14px;
      align-items:center;
      font-size:0.9rem;
    }

    .legend span{
      display:inline-flex;
      gap:8px;
      align-items:center;
      padding:6px 10px;
      border-radius:8px;
      background:rgba(0,0,0,0.03);
    }

    .note{
      margin-top:12px;
      font-size:0.86rem;
      color:#4b3b00;
    }

    footer{
      margin-top:18px;
      font-size:0.85rem;
      color:#5b4a28;
    }

    @media (max-width:520px){
      .badge{ min-width:48px; height:48px; font-size:0.85rem; }
    }
  </style>
</head>
<body>
  <main class="wrap" role="main" aria-labelledby="page-title">
    <header>
      <div>
        <div class="title" id="page-title">Microbiome & 5 Fun Facts about Microbiology</div>
        <div class="subtitle">Gold accents, green = noteworthy, red = dangers</div>
      </div>
    </header>

    <section class="definition" aria-labelledby="def-title">
      <h2 id="def-title" style="margin:0 0 8px 0; color:var(--gold);">What is the Microbiome?</h2>
      <p style="margin:0; font-size:0.98rem;">
        The microbiome is the collection of all microorganisms — bacteria, viruses, fungi, and their genes — that live on and inside the human body.
        "Normal flora" are the resident microbes that coexist with us in a balanced way. This harmony helps with digestion, trains the immune system, protects against invaders, and even contributes to our mood and metabolism.
      </p>
    </section>

    <section aria-label="Five fun facts" class="facts">
      <article class="fact" aria-labelledby="f1">
        <div class="badge gold" aria-hidden="true">#1</div>
        <div>
          <h3 id="f1">Microbes outnumber our cells (fun stat)</h3>
          <p>There are roughly as many — and possibly more — microbial cells in and on your body than human cells. These tiny residents form ecosystems that influence health, digestion, and even body odor.</p>
        </div>
      </article>

      <article class="fact" aria-labelledby="f2">
        <div class="badge green" aria-hidden="true">Notable</div>
        <div>
          <h3 id="f2">Gut microbes help produce vitamins and break down food</h3>
          <p>Many gut bacteria synthesize essential vitamins (like vitamin K and some B vitamins) and break down complex fibers into short-chain fatty acids that feed colon cells and support overall metabolism.</p>
        </div>
      </article>

      <article class="fact" aria-labelledby="f3">
        <div class="badge green" aria-hidden="true">Notable</div>
        <div>
          <h3 id="f3">Normal flora protect and educate the immune system</h3>
          <p>Resident microbes compete with pathogens for space and resources, produce antimicrobial compounds, and help "train" the immune system to respond appropriately — reducing allergies and infections in many cases.</p>
        </div>
      </article>

      <article class="fact" aria-labelledby="f4">
        <div class="badge red" aria-hidden="true">Danger</div>
        <div>
          <h3 id="f4">Antibiotics and dysbiosis can cause real harm</h3>
          <p>Overuse or misuse of antibiotics can disrupt the microbiome (dysbiosis), enabling harmful organisms like Clostridioides difficile to overgrow, increasing infection risk and contributing to antibiotic resistance.</p>
        </div>
      </article>

      <article class="fact" aria-labelledby="f5">
        <div class="badge green" aria-hidden="true">Notable</div>
        <div>
          <h3 id="f5">The gut–brain axis: microbes can influence mood</h3>
          <p>Microbes produce metabolites and neurotransmitter precursors (like serotonin precursors), and communicate with the nervous and immune systems — illustrating how gut health can affect mood and cognition.</p>
        </div>
      </article>
    </section>

    <div class="legend" aria-hidden="true">
      <span><strong style="color:var(--gold)">Gold</strong> = header/accents</span>
      <span style="display:flex;align-items:center;gap:8px"><span style="width:14px;height:14px;background:var(--green);border-radius:3px;display:inline-block"></span>Green = worthy of note</span>
      <span style="display:flex;align-items:center;gap:8px"><span style="width:14px;height:14px;background:var(--red);border-radius:3px;display:inline-block"></span>Red = danger / caution</span>
    </div>

    <p class="note">Tip: keep a diverse diet and avoid unnecessary antibiotics to help maintain a healthy microbiome.</p>

    <footer>
      Want this saved to a file in your repo or styled differently? I can add images, links to references, or commit this file to Lydiaamaka2/My-firstcode if you want.
    </footer>
  </main>
</body>
</html>
