---
layout: homepage
---

## About Me

I am joining the [Department of Computer Science and Engineering at Korea University](https://cs.korea.edu/en_cs/index.do) as an Assistant Professor in Fall 2026. Until that, I am spending my gap year as a Lead AI Research Scientist at [EverEx](https://everex.kr/), leading the AI team together with [Byung-Hoon Kim](https://egyptdj.notion.site/NAIPL-f6283de309a04223b1c04793f5a10ce1). Before joining EverEx, I did my Ph.D. at [KAIST](https://www.kaist.ac.kr/en/) where I was advised by [Jong Chul Ye](https://bispl.weebly.com/professor.html). During my Ph.D., I also spent my time as a research intern at [NVIDIA Research](https://www.nvidia.com/en-us/research/), [Google Research](https://research.google/), and [Los Alamos National Laboratory](https://www.lanl.gov/). I pioneered and advanced some of the most widely acknowledged works on diffusion model-based inverse problem solvers. I'm interested broadly in the intersection of generative models, imaging, multimodality, and their applications to real-world problems.

I am looking for highly motivated researchers to work with me at [EverEx](https://everex.kr/) for pushing the boundaries of understanding and generation of videos. If you are interested, send me an email with your CV attached.

I also hold office hours weekly on Friday. From research collaborations to informal coffee chat and mentorships, please sign up [here](https://calendly.com/hyungjin-chg/30min)

## News

<ul id="news-list">
  <li><b>[2025.10]</b> A paper (<a href="https://arxiv.org/abs/2504.01689">InvFusion</a>) is accepted to NeurIPS 2025.</li>
  <li><b>[2025.06]</b> 3 papers (<a href="https://arxiv.org/abs/2503.12024">SteerX</a>, <a href="https://arxiv.org/abs/2503.15855">VideoRFSplat</a>, <a href="https://arxiv.org/abs/2411.06869">CapeLLM</a>) are accepted to ICCV 2025.</li>
  <li><b>[2025.03]</b> A paper (<a href="https://arxiv.org/abs/2411.15265">FreeMCG</a>) is accepted to CVPR 2025.</li>
  <li><b>[2025.02]</b> <a href="https://arxiv.org/abs/2406.08070">CFG++</a> is awarded Silver prize in 31st Samsung Humantech Paper Award.</li>
  <li><b>[2025.01]</b> Two papers (<a href="https://arxiv.org/abs/2406.08070">CFG++</a>,<a href="https://arxiv.org/abs/2311.15658">TReg</a>) are accepted to ICLR 2025.</li>
  <div id="more-news" style="display: none;">
    <li><b>[2024.11]</b> Defended my Ph.D. thesis! (Title: Practical approximations of posterior sampling in diffusion model-based inverse problems)</li>
    <li><b>[2024.08]</b> I joined <a href="https://everex.kr/">EverEx</a> as a research scientist.</li>
    <li><b>[2024.07]</b> A paper (<a href="https://arxiv.org/abs/2310.01110">P2L</a>) is accepted to ICML 2024.</li>
    <li><b>[2024.06]</b> A paper (<a href="https://arxiv.org/abs/2407.10641">DDIP</a>) is accepted to ECCV 2024.</li>
    <li><b>[2024.02]</b> <a href="https://arxiv.org/abs/2407.10641">DDIP</a> is awarded Gold prize in 30th Samsung Humantech Paper Award.</li>
    <li><b>[2024.01]</b> A paper (<a href="https://arxiv.org/abs/2303.05754">DDS</a>) is accepted to ICLR 2024.</li>
    <li><b>[2023.11]</b> I joined <a href="https://www.nvidia.com/en-us/research/">NVIDIA Research</a> as an intern (Host: <a href="https://sites.ps.uci.edu/pritchard/">Mike Pritchard</a>).</li>
    <li><b>[2023.07]</b> A paper (<a href="https://arxiv.org/abs/2303.08440">TPDM</a>) is accepted to ICCV 2023.</li>
    <li><b>[2023.03]</b> I joined <a href="https://research.google/">Google Research</a> as an intern (Host: <a href="https://mdelbra.github.io/">Mauricio Delbracio</a>).</li>
    <li><b>[2023.03]</b> Two papers (<a href="https://arxiv.org/abs/2211.10656">BlindDPS</a>,<a href="https://arxiv.org/abs/2211.10655">DiffusionMBIR</a>) are accepted to CVPR 2023.</li>
    <li><b>[2023.02]</b> <a href="https://arxiv.org/abs/2209.14687">DPS</a> is awarded Gold prize in 29th Samsung Humantech Paper Award.</li>
    <li><b>[2023.01]</b> A paper (<a href="https://arxiv.org/abs/2209.14687">DPS</a>) is accepted to ICLR 2023 as spotlight.</li>
    <li><b>[2022.09]</b> Two papers (<a href="https://arxiv.org/abs/2206.00941">MCG</a>,<a href="https://arxiv.org/abs/2207.11192">Blur diffusion</a>) are accepted to NeurIPS 2022 / NeurIPS 2022 SBM workshop.</li>
    <li><b>[2022.03]</b> A paper (<a href="https://arxiv.org/abs/2112.05146">CCDF</a>) is accepted to CVPR 2022.</li>
    <li><b>[2021.03]</b> <a href="https://www.nature.com/articles/s42256-020-00289-5">Our paper</a> is selected as a cover of Nature Machine Intelligence.</li>
  </div>
</ul>

<button id="toggle-news" onclick="toggleNews()">Show More</button>

{% include_relative _includes/publications.md %}
<!-- {% include_relative _includes/services.md %} -->

<style>
  /* News 리스트 스타일 */
  #news-list {
    font-family: "Roboto", "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 1rem;
    line-height: 1.6;
    padding-left: 15px;
  }
  #news-list li {
    margin-bottom: 5px;
  }

  /* 버튼 스타일 */
  #toggle-news {
    background-color: #444; /* 다크 그레이 */
    color: white;
    font-family: "Roboto", "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 0.9rem;
    border: none;
    padding: 8px 14px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease-in-out;
  }
  
  #toggle-news:hover {
    background-color: #222; /* 더 어두운 회색 */
  }
</style>

<script>
  function toggleNews() {
    var moreNews = document.getElementById("more-news");
    var button = document.getElementById("toggle-news");

    if (moreNews.style.display === "none") {
      moreNews.style.display = "block";
      button.innerText = "Show Less";
    } else {
      moreNews.style.display = "none";
      button.innerText = "Show More";
    }
  }
</script>
