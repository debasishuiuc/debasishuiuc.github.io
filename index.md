---
layout: default
title: Home
---

<section class="hero" style="display: block; background: #f3e6d8;">
    <div style="max-width: 100%;">
    <div style="text-align: center;">
      <h1>Complex Fluids and Biological Systems at the Microscale</h1>
      <div class="subtitle">Applied and Computational Mathematics Group</div>
      <div class="affiliation">
        Department of Mathematics and Statistics<br>
        University of Strathclyde
      </div>
    </div>

    <p>
      We work on problems in applied and computational mathematics, with interests
      in microscale fluid dynamics, active matter, electrohydrodynamics,
      biological flows, and developing novel computational methods for
      complex fluids.
      Many of these problems are motivated by simple physical observations, laboratory
      experiments, and questions arising in soft matter and biological fluid mechanics.  
    </p>

    <p>
      We are always looking for motivated students and post-doctoral researchers to work with, and
      exploring new collaboration opportunities with established research groups. 
      Please feel free to get in touch for any queries.
    </p>

    <div class="links">
      <a href="mailto:debasish.das@strath.ac.uk">✉️ Email</a>
      <a href="{{ '/files/debasishdas.pdf' | relative_url }}">📄 CV</a>
      <a href="https://www.strath.ac.uk/staff/dasdebasishdr/">🏛️ Strathclyde Profile</a>
      <a href="https://scholar.google.com/citations?user=48mN8SQAAAAJ&hl=en">🎓 Google Scholar</a>
      <a href="https://www.linkedin.com/in/debasishdas1/">💼 LinkedIn</a>
      <a href="https://x.com/drdebadas">𝕏 Twitter/X</a>
    </div>
  </div>
</section>

<section class="section-card" style="background: #f3e6d8;">
  <h2>News</h2>
  <ul class="news-list">
    <li><strong>Mar 2026:</strong> The group has received funding from the <a href="https://www.leverhulme.ac.uk/" target="_blank" rel="noopener noreferrer">Leverhulme Trust</a>, which will support an international PhD student and a Postdoctoral Research Associate for a period of three years. Interested candidates are encouraged to email Debasish Das for further information about the project.</li>
    <li><strong>Feb 2026:</strong> Michael has started a new position as a systems engineer at Leonardo in Edinburgh. Congratulations, Michael!</li>
    <li><strong>Jan 2026:</strong> Debasish gave a research talk in the Department of Chemical Engineering at Stanford.</li>
    <li><strong>Oct 2025:</strong> Debasish will be teaching a new course on Asymptotic Methods for the Scottish Mathematical Sciences Training Centre (SMSTC). Interested students enrolled at Scottish universities should register via the <a href="https://smstc.ac.uk/" target="_blank" rel="noopener noreferrer">SMSTC website</a>.</li>
    <li><strong>Jul 2025:</strong> Debasish gave an invited talk at the 9th International Conference on Micro- and Nano Flows (MNF 2025), held in Edinburgh.</li>
    <li><strong>Jul 2025:</strong> The work on cilia was highlighted in <a href="https://www.strath.ac.uk/whystrathclyde/news/2025/lungcilia/" target="_blank" rel="noopener noreferrer">Strathclyde News</a> and received press coverage in the national Indian newspaper <em>The Statesman</em>.</li>
    <li><strong>Jul 2025:</strong> New collaborative work with the Cicuta Lab, Cambridge, on cilia dynamics has been accepted for publication in PNAS.</li>
  </ul>
</section>

<section class="section-card" style="background: #f3e6d8;">
  <div class="video-rotator">
    <div style="height: 430px; display: flex; align-items: center; justify-content: center; border-radius: 12px; overflow: hidden;">
      <video id="rotating-video" controls autoplay muted playsinline preload="metadata"
             style="width: 100%; height: 100%; object-fit: contain;">
        <source src="{{ '/videos/2025_PNAS_1.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    <div id="rotating-caption" class="video-caption" style="margin-top: 10px;">
      Flow above cilia
    </div>
  </div>
</section>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const playlist = [
    {
      src: "{{ '/videos/2025_PNAS_1.mp4' | relative_url }}",
      caption: "Flow above cilia"
    },
    {
      src: "{{ '/videos/2024_PRR.mp4' | relative_url }}",
      caption: "Bacteria hovering"
    },
    {
      src: "{{ '/videos/2024_PRR_2_web.mp4' | relative_url }}",
      caption: "Ellipsoidal cell-body: top view"
    },
    {
      src: "{{ '/videos/2024_PRR_3_web.mp4' | relative_url }}",
      caption: "Ellipsoidal cell-body: side view"
    },
    {
      src: "{{ '/videos/2024_PRR_5_web.mp4' | relative_url }}",
      caption: "Spherical cell-body: top view"
    },
    {
      src: "{{ '/videos/2024_PRR_4_web.mp4' | relative_url }}",
      caption: "Spherical cell-body: side view"
    },
    {
      src: "{{ '/videos/2023_JFM_1.mp4' | relative_url }}",
      caption: "Quincke rotation"
    },
    {
      src: "{{ '/videos/2017_JFM_3_web.mp4' | relative_url }}",
      caption: "Taylor regime: weak electric fields"
    },
    {
      src: "{{ '/videos/2017_JFM_4_web.mp4' | relative_url }}",
      caption: "Quincke regime: strong electric fields"
    },
    {
      src: "{{ '/videos/2019_PRL_1_web.mp4' | relative_url }}",
      caption: "Chiral object translating due to Quincke rotation"
    },
    {
      src: "{{ '/videos/2019_PRL_2_web.mp4' | relative_url }}",
      caption: "Optimum swimming speed at intermediate thickness"
    }
  ];

  const video = document.getElementById("rotating-video");
  const caption = document.getElementById("rotating-caption");
  let current = Math.floor(Math.random() * playlist.length);

  function loadVideo(index) {
    video.src = playlist[index].src;
    caption.textContent = playlist[index].caption;
    video.load();
    video.play().catch(() => {});
  }

  video.addEventListener("ended", function () {
    current = (current + 1) % playlist.length;
    loadVideo(current);
  });

  loadVideo(current);
});
</script>
