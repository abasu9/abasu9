<div align="center">

<!-- Animated Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=220&section=header&text=Abhishek%20Basu&fontSize=50&fontColor=58A6FF&animation=fadeIn&fontAlignY=35&desc=ML%20Engineer%20%7C%20NLP%20Researcher%20%7C%20LLM%20Systems&descSize=18&descAlignY=55&descColor=8B949E"/>

<!-- Typing SVG -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=1200&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=70&lines=Building+intelligent+systems+that+understand+%26+reason;From+inference+optimization+to+grounded+generation" alt="Typing SVG" /></a>

<br/>

<b><code>MS CS (Thesis Track) @ University of Illinois Chicago</code></b>

<br/><br/>

<!-- Social Badges -->
<a href="https://www.linkedin.com/in/abhishek-basu-2001/"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
<a href="mailto:abasu9@uic.edu"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>&nbsp;
<a href="https://orcid.org/0009-0003-5205-4457"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"/></a>&nbsp;
<a href="https://github.com/abasu9"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=abasu9&label=Profile%20Views&color=58A6FF&style=for-the-badge" alt="Profile Views"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🧠 About Me

```yaml
name: Abhishek Basu
location: Chicago, IL
education: M.S. Computer Science (Thesis Track) @ UIC
thesis: Multimodal Summarization, Grounded Generation & Hallucination Reduction
status: Graduating May 2026
```

- 🔬 **Thesis Research** — Multimodal summarization with grounded generation and hallucination reduction in domain-specific NLP
- 📄 **Lead Author** — [CHQ-Summ](https://arxiv.org/abs/2512.23637): Dataset & Benchmark for Consumer Healthcare Question Summarization *(submitted to Nature Scientific Data)*
- ⚡ **Current obsessions** — Speculative decoding, LLM inference optimization, ethical RAG systems
- 🏆 **MIT Frontiers GenAI Hackathon Finalist** (Top 5) — with Google DeepMind & Breakthrough Ventures
- 🌱 **Previously** — AI Intern @ Carpl.ai/RSNA · SDE I @ BYJU'S (1M+ daily users) · Data Scientist @ Extech Digital

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🏗️ Featured Projects

<table>
<tr>
<td width="50%" valign="top">
<h3>🩺 <a href="https://github.com/abasu9/CHQ-Summ-A-Dataset-for-Consumer-Healthcare-Question-Summarization">CHQ-Summ</a></h3>
<p><sub>🏷️ Lead Author — Submitted to Nature Scientific Data</sub></p>
<p>1,507 consumer health questions with expert-annotated summaries. Benchmarked <b>6 LLMs × 4 prompting strategies × 3 shot settings</b> (72 configs) across 7 evaluation metrics.</p>
<p><sub><b>ROUGE-L 49% · BERTScore 92%</b></sub></p>
<p><code>Python</code> <code>PyTorch</code> <code>HuggingFace</code> <code>AWS</code></p>
</td>
<td width="50%" valign="top">
<h3>🔒 <a href="https://github.com/yawbtng/Frontiers-Hack">Friday — AI Meeting Assistant</a></h3>
<p><sub>🏷️ MIT Frontiers GenAI Hackathon — Top 5 Finalist</sub></p>
<p>Privacy-first, local-first meeting assistant with live transcription via Whisper, real-time audio streaming, synchronized mic + system capture, and editable export workflows.</p>
<p><sub><b>No cloud upload of raw audio by default</b></sub></p>
<p><code>Rust</code> <code>Tauri</code> <code>Next.js</code> <code>FastAPI</code> <code>SQLite</code> <code>Whisper</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>🧬 <a href="https://github.com/abasu9/Ethical_RAG">Ethical RAG</a></h3>
<p><sub>🏷️ Trustworthy Medical Information Retrieval</sub></p>
<p>Hybrid retrieval (BM25 + dense embeddings) with <b>trustworthiness scoring</b>, self-consistency validation, and confidence-based refusal for clinical text generation.</p>
<p><sub><b>AUC ~0.89 · 2,500+ PubMed passages</b></sub></p>
<p><code>Python</code> <code>HuggingFace</code> <code>ChromaDB</code> <code>AWS</code></p>
</td>
<td width="50%" valign="top">
<h3>💡 <a href="https://github.com/abasu9/CoT-RAG-Explainable-Reasoning-Search">CoT-RAG</a></h3>
<p><sub>🏷️ Explainable Reasoning Search</sub></p>
<p>RAG system that <b>exposes its chain-of-thought reasoning</b> for every answer — making retrieval-augmented generation transparent, auditable, and interpretable.</p>
<p><sub><b>Full reasoning trace visibility</b></sub></p>
<p><code>Python</code> <code>LangChain</code> <code>ChromaDB</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>⚡ Speculative Decoding</h3>
<p><sub>🏷️ LLM Inference Optimization</sub></p>
<p>Integrated parallel forward prediction for LLaMA-3.1 and Gemma models, enabling draft-then-verify inference to slash reasoning-step latency in agentic planning loops.</p>
<p><sub><b>&gt;40% latency reduction · GSM8K accuracy preserved</b></sub></p>
<p><code>PyTorch</code> <code>CUDA</code> <code>TensorRT</code></p>
</td>
<td width="50%" valign="top">
<h3>🏀 <a href="https://github.com/abasu9/ClutchCast">ClutchCast</a></h3>
<p><sub>🏷️ AI Sports Commentary Engine</sub></p>
<p>AI-powered sports moment detection &amp; commentary generation — identifying clutch plays in real-time and generating narrative-driven play-by-play commentary.</p>
<p><sub><b>Real-time detection &amp; generation</b></sub></p>
<p><code>TypeScript</code> <code>Next.js</code> <code>AI/ML</code></p>
</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 💻 Tech Stack

<div align="center">

<h3>🔤 Languages</h3>
<p>
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python"/>
<img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++"/>
<img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
<img src="https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white" alt="Rust"/>
<img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
</p>

<h3>🤖 ML / NLP / GenAI</h3>
<p>
<img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch"/>
<img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white" alt="TensorFlow"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="HuggingFace"/>
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA"/>
<img src="https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="TensorRT"/>
</p>

<h3>☁️ Cloud / Infra / Backend</h3>
<p>
<img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS"/>
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi" alt="FastAPI"/>
<img src="https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
<img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/>
</p>

<h3>🗄️ Databases / Retrieval</h3>
<p>
<img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
<img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
<img src="https://img.shields.io/badge/ChromaDB-FF6F61?style=for-the-badge&logo=databricks&logoColor=white" alt="ChromaDB"/>
</p>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 💼 Experience

<table>
<tr>
<td>🤖</td>
<td><b>AI Intern</b></td>
<td>Carpl.ai / RSNA</td>
<td>Multimodal medical-image retrieval with vision-language models · ~28% relevance improvement</td>
</tr>
<tr>
<td>🔬</td>
<td><b>Graduate RA</b></td>
<td>UIC</td>
<td>LLM inference pipelines in PyTorch &amp; TensorRT · Distributed evaluation on AWS (EC2, Inferentia)</td>
</tr>
<tr>
<td>⚙️</td>
<td><b>SDE I</b></td>
<td>BYJU'S</td>
<td>Backend compute workflows serving 1M+ daily users · 35% latency reduction</td>
</tr>
<tr>
<td>📊</td>
<td><b>Data Scientist</b></td>
<td>Extech Digital</td>
<td>10+ ML models to production with zero rollback · ~30% revenue uplift</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📊 GitHub Analytics

<div align="center">

<a href="https://github.com/abasu9">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=abasu9&theme=github_dark_dimmed&hide_border=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&ring_color=58A6FF" alt="GitHub Stats"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abasu9&theme=github_dark_dimmed&hide_border=true&include_all_commits=true&count_private=true&layout=compact&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Top Languages"/>
</a>

<br/>

<img width="70%" src="https://nirzak-streak-stats.vercel.app/?user=abasu9&theme=dark&hide_border=true&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=FF6E40&currStreakLabel=58A6FF&sideLabels=58A6FF&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" alt="GitHub Streak"/>

<br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=abasu9&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FF6E40&area=true&area_color=58A6FF&hide_border=true" alt="Contribution Graph"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=abasu9&theme=darkhub&no-frame=true&no-bg=true&margin-w=10&margin-h=10&column=7" alt="Trophies"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📜 Publications & Achievements

<table>
<tr>
<td>📝</td>
<td><b>Basu, A., et al.</b> "CHQ-Summ: A Dataset and Benchmark for Consumer Healthcare Question Summarization." <em>Submitted to Nature Scientific Data, 2025.</em></td>
</tr>
<tr>
<td>🥇</td>
<td><b>Finalist, Top 5</b> — MIT Frontiers GenAI Hackathon <em>(Google DeepMind × Breakthrough Ventures)</em></td>
</tr>
<tr>
<td>☁️</td>
<td><b>Oracle Cloud Infrastructure</b> — Generative AI Professional (2025)</td>
</tr>
<tr>
<td>☁️</td>
<td><b>Oracle Cloud Infrastructure</b> — AI Foundations Associate (2025)</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=400&size=16&duration=4000&pause=2000&color=8B949E&center=true&vCenter=true&repeat=true&width=500&height=30&lines=%22The+best+way+to+understand+intelligence+is+to+build+it.%22" alt="Quote" /></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=120&section=footer"/>

</div>
