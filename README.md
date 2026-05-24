
<div align="center">



<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=akrist-rai&color=00D9FF&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/akrist-rai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akrist-rai-b510593b1/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akrist-rai)

<br/>

![AI](https://img.shields.io/badge/🧠_Deep_Learning-Expert-0A192F?style=flat-square)
![Systems](https://img.shields.io/badge/⚙️_Systems_Programming-Proficient-102230?style=flat-square)
![Web](https://img.shields.io/badge/🌐_Full--Stack_Web-Proficient-0F3460?style=flat-square)
![Security](https://img.shields.io/badge/🔐_Cryptography_&_Security-Learning-533483?style=flat-square)

</div>

<br/>

---

## 🔭 Currently Building

<table>
<tr>
<td width="55%">

### Commute 🚦
**Spatio-Temporal Traffic Flow Prediction**

> Capturing how cities breathe — predicting traffic by learning both *where* congestion forms (space) and *when* it peaks (time), simultaneously.

| Layer | Tech | What it does |
|-------|------|-------------|
| **Spatial** | Graph Attention Networks | Models road topology & intersection weights |
| **Temporal** | Mamba (SSM) | Long-range sequence dependency across time |
| **Fusion** | Spatio-Temporal GNN | Joint prediction across the full city graph |

![Status](https://img.shields.io/badge/🚧_Status-Active_Development-FF6B6B?style=flat-square)
![Stack](https://img.shields.io/badge/PyTorch_+_PyG-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Domain](https://img.shields.io/badge/Traffic_AI_•_Graph_ML-00D9FF?style=flat-square)

</td>
<td width="45%" align="center">

```
        City Graph
       ┌───────────┐
  Node │  Junction │  ← GAT weights edges
  Feat │  Speed    │    by traffic importance
       └─────┬─────┘
             │  time axis →
       ┌─────▼─────────────┐
  SSM  │ t₀  t₁  t₂  t₃  │  ← Mamba models
  Seq  │ ▓▓  ▓░  ░░  ░▓  │    temporal drift
       └────────────────────┘
             │
       ┌─────▼─────┐
  Out  │  ŷ t+Δ   │  ← predicted flow
       └───────────┘
```

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

### 💻 Languages

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,go,rust,python,java,js,ts,kotlin,lua&perline=10" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C-Systems-00599C?style=flat-square&logo=c" />
  <img src="https://img.shields.io/badge/C++-OOP_&_Embedded-00599C?style=flat-square&logo=cplusplus" />
  <img src="https://img.shields.io/badge/Go-Concurrency_&_Networking-00ADD8?style=flat-square&logo=go" />
  <img src="https://img.shields.io/badge/Rust-Memory_Safety-CE422B?style=flat-square&logo=rust" />
  <img src="https://img.shields.io/badge/Python-AI_&_Scripting-3776AB?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/TypeScript-Type--safe_Web-3178C6?style=flat-square&logo=typescript" />
  <img src="https://img.shields.io/badge/Kotlin-JVM_&_Android-7F52FF?style=flat-square&logo=kotlin" />
  <img src="https://img.shields.io/badge/Lua-Scripting-2C2D72?style=flat-square&logo=lua" />
</p>

---

### 🤖 AI / Machine Learning

<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&perline=10" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/numpy/4DABCF" height="48" title="NumPy"/>
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/pandas/150458" height="48" title="Pandas"/>
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/scikitlearn/F7931E" height="48" title="scikit-learn"/>
</p>

<br/>

<div align="center">

**Architectures I work with**

| Graph & Spatial | Sequential & Temporal | Generative | Training |
|:-:|:-:|:-:|:-:|
| GNN · GAT · GCN | Mamba/SSM · LSTM · RNN | GANs · VAEs | Hardware-Aware |
| Spatio-Temporal | Transformers (MHA · MoE · GQA · RoPE) | RL + VAE | Memory-Efficient |
| Flash Attention | DeepSeek Sparse Attn | — | Mixed Precision |

</div>

---

### 🌐 Web Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,django&perline=10" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/koajs/FFFFFF" height="48" title="Koa.js"/>
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/bun/F9F1E1" height="48" title="Bun"/>
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/socketdotio/FFFFFF" height="48" title="Socket.io"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/WebSocket-Real--time-010101?style=flat-square" />
  <img src="https://img.shields.io/badge/REST_API-Design-005571?style=flat-square" />
  <img src="https://img.shields.io/badge/JWT_•_Sessions-Auth-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Helmet_•_CORS_•_CSP-Security_Headers-red?style=flat-square" />
</p>

---

### 🗄️ Databases & Data Layer

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,supabase&perline=10" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/neon/00E599" height="48" title="Neon"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/Neon_Serverless-00E599?style=flat-square" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
</p>

---

### ☁️ DevOps · Cloud · Systems

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,docker,kubernetes,linux,aws,arch&perline=10" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Systems_Design-Distributed_Arch-2C3E50?style=flat-square" />
  <img src="https://img.shields.io/badge/CI/CD-Pipelines-2088FF?style=flat-square&logo=github-actions" />
  <img src="https://img.shields.io/badge/Containerized_ML-Docker_+_K8s-2496ED?style=flat-square&logo=docker" />
</p>

---

### 🔐 Cryptography & Security

<div align="center">

**Cryptographic Primitives**

<p>
  <img src="https://img.shields.io/badge/RSA-Public_Key-2C3E50?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AES-Symmetric-1ABC9C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DES-Block_Cipher-E74C3C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Diffie--Hellman-Key_Exchange-8E44AD?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ECC-Elliptic_Curve-2980B9?style=for-the-badge" />
</p>

**Offensive & Defensive Tooling**

<p>
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Nmap-004A7C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white" />
  <img src="https://img.shields.io/badge/John_the_Ripper-000000?style=for-the-badge" />
</p>

</div>

---


