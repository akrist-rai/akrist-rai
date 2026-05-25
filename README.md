
<div align="center">


<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=akrist-rai&color=00D9FF&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/akrist-rai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akrist-rai-b510593b1/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akrist-rai)

<br/>

![AI](https://img.shields.io/badge/🧠_Deep_Learning-0A192F?style=flat-square)
![Systems](https://img.shields.io/badge/⚙️_Systems_Programming-102230?style=flat-square)
![Web](https://img.shields.io/badge/🌐_Full--Stack_Web-0F3460?style=flat-square)
![Security](https://img.shields.io/badge/🔐_Web_Application_Security-533483?style=flat-square)
![Crypto](https://img.shields.io/badge/🔑_Applied_Cryptography-1a1a2e?style=flat-square)

</div>

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

### 🔐 Security & Cryptography

#### 🛠 Tooling

<p align="center">
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-004A7C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white" />
  <img src="https://img.shields.io/badge/John_the_Ripper-000000?style=for-the-badge" />
</p>

---

#### 💥 Web Application Attacks

<p align="center">
  <img src="https://img.shields.io/badge/XSS-Reflected_•_Stored_•_DOM_•_Blind-E74C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/SQL_Injection-In--band_•_Blind_•_Error--based-C0392B?style=flat-square" />
  <img src="https://img.shields.io/badge/CSRF-Token_Bypass_•_SameSite_Abuse-8E44AD?style=flat-square" />
  <img src="https://img.shields.io/badge/SSRF-Internal_Network_Pivot-2980B9?style=flat-square" />
  <img src="https://img.shields.io/badge/CORS-Misconfiguration_Exploitation-16A085?style=flat-square" />
  <img src="https://img.shields.io/badge/Clickjacking-Frame_Injection-F39C12?style=flat-square" />
  <img src="https://img.shields.io/badge/HTTP_Request_Smuggling-CL.TE_•_TE.CL-E67E22?style=flat-square" />
  <img src="https://img.shields.io/badge/Prototype_Pollution-Client_•_Server_Side-9B59B6?style=flat-square" />
  <img src="https://img.shields.io/badge/DOM_Clobbering-Global_Namespace_Hijack-1ABC9C?style=flat-square" />
  <img src="https://img.shields.io/badge/CSP_Bypass-Nonce_•_Hash_•_strict--dynamic-D35400?style=flat-square" />
  <img src="https://img.shields.io/badge/Web_Cache_Poisoning-Header_•_Param_Injection-7F8C8D?style=flat-square" />
  <img src="https://img.shields.io/badge/Insecure_Deserialization-Gadget_Chains-E74C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/SSTI-Jinja2_•_Twig_•_Freemarker-2ECC71?style=flat-square" />
  <img src="https://img.shields.io/badge/XXE-External_Entity_Injection-3498DB?style=flat-square" />
  <img src="https://img.shields.io/badge/Command_Injection-OS_Command_Execution-C0392B?style=flat-square" />
  <img src="https://img.shields.io/badge/Path_Traversal-Directory_Climbing-27AE60?style=flat-square" />
  <img src="https://img.shields.io/badge/IDOR-Object_Reference_Abuse-F1C40F?style=flat-square" />
  <img src="https://img.shields.io/badge/JWT_Attacks-alg:none_•_Secret_Brute--force-8E44AD?style=flat-square" />
  <img src="https://img.shields.io/badge/OAuth_Vulnerabilities-State_•_Redirect_URI_Abuse-E67E22?style=flat-square" />
  <img src="https://img.shields.io/badge/Race_Conditions-TOCTOU_•_Limit_Bypass-1ABC9C?style=flat-square" />
  <img src="https://img.shields.io/badge/Open_Redirect-URL_Param_Exploitation-E74C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/MIME_Sniffing-Content--Type_Exploitation-95A5A6?style=flat-square" />
  <img src="https://img.shields.io/badge/Session_Hijacking-Cookie_Theft_•_Fixation-2C3E50?style=flat-square" />
  <img src="https://img.shields.io/badge/Business_Logic_Flaws-Workflow_Abuse-16A085?style=flat-square" />
  <img src="https://img.shields.io/badge/Authentication_Bypass-Credential_•_MFA_Abuse-8E44AD?style=flat-square" />
  <img src="https://img.shields.io/badge/File_Upload-Extension_•_Content--Type_Bypass-D35400?style=flat-square" />
  <img src="https://img.shields.io/badge/WebSocket_Security-Message_Hijacking-3498DB?style=flat-square" />
  <img src="https://img.shields.io/badge/Recon_&_Enumeration-Bug_Bounty_Methodology-2ECC71?style=flat-square" />
</p>

---

#### 🔑 Applied Cryptography


<p align="center">
  <img src="https://img.shields.io/badge/Modular_Arithmetic-Number_Theory_•_Euler_•_Fermat-0A192F?style=flat-square" />
  <img src="https://img.shields.io/badge/Galois_Fields-GF(2⁸)_•_Polynomial_Arithmetic-102230?style=flat-square" />
  <img src="https://img.shields.io/badge/Discrete_Logarithm_Problem-DLP_•_Cyclic_Groups-0F3460?style=flat-square" />
  <img src="https://img.shields.io/badge/Integer_Factorization-RSA_Hardness_Assumption-1a1a2e?style=flat-square" />
  <img src="https://img.shields.io/badge/Extended_Euclidean_Algorithm-Modular_Inverse_•_GCD-16213E?style=flat-square" />
  <img src="https://img.shields.io/badge/One--Time_Pad-Perfect_Secrecy_•_XOR_Cipher-1ABC9C?style=flat-square" />
  <img src="https://img.shields.io/badge/LFSR-Linear_Feedback_Shift_Register_•_Berlekamp--Massey-16A085?style=flat-square" />
  <img src="https://img.shields.io/badge/Stream_Ciphers-RC4_•_A5/1_•_Trivium_•_ChaCha20-148F77?style=flat-square" />
  <img src="https://img.shields.io/badge/PRNG-Cryptographically_Secure_Randomness-0E6655?style=flat-square" />
  <img src="https://img.shields.io/badge/DES-Feistel_Network_•_56--bit_•_16_Rounds-E74C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/3DES-EDE_Mode_•_112--bit_Effective_Key-C0392B?style=flat-square" />
  <img src="https://img.shields.io/badge/AES_(Rijndael)-SubBytes_•_ShiftRows_•_MixColumns_•_Key_Schedule-922B21?style=flat-square" />
  <img src="https://img.shields.io/badge/ECB_Mode-Electronic_Codebook_(Insecure)-7F8C8D?style=flat-square" />
  <img src="https://img.shields.io/badge/CBC_Mode-Cipher_Block_Chaining_•_IV_Reuse_Attacks-2980B9?style=flat-square" />
  <img src="https://img.shields.io/badge/CTR_Mode-Counter_•_Nonce_•_Parallelizable-1F618D?style=flat-square" />
  <img src="https://img.shields.io/badge/OFB_•_CFB-Output_&_Cipher_Feedback_Modes-154360?style=flat-square" />
  <img src="https://img.shields.io/badge/GCM-Authenticated_Encryption_•_AEAD_•_GHASH-117A65?style=flat-square" />
  <img src="https://img.shields.io/badge/RSA-Key_Generation_•_PKCS%231_•_OAEP_•_PSS-8E44AD?style=flat-square" />
  <img src="https://img.shields.io/badge/Diffie--Hellman_Key_Exchange-DHKE_•_Ephemeral_•_Forward_Secrecy-7D3C98?style=flat-square" />
  <img src="https://img.shields.io/badge/Elgamal-DLP--based_Encryption_•_Probabilistic-6C3483?style=flat-square" />
  <img src="https://img.shields.io/badge/Elliptic_Curve_Cryptography-Point_Addition_•_Scalar_Multiplication_•_ECDLP-5B2C6F?style=flat-square" />
  <img src="https://img.shields.io/badge/ECDH-Elliptic_Curve_Diffie--Hellman_•_NIST_Curves-4A235A?style=flat-square" />
  <img src="https://img.shields.io/badge/Hash_Functions-MD5_•_SHA--1_•_SHA--256_•_SHA--3_•_Merkle--Damgård-E67E22?style=flat-square" />
  <img src="https://img.shields.io/badge/Collision_Resistance-Birthday_Paradox_•_Preimage_Resistance-D35400?style=flat-square" />
  <img src="https://img.shields.io/badge/MAC-HMAC_•_CMAC_•_Poly1305_•_Length_Extension_Attack-BA4A00?style=flat-square" />
  <img src="https://img.shields.io/badge/Digital_Signatures-RSA--PSS_•_DSA_•_ECDSA_•_Unforgeability-A04000?style=flat-square" />
  <img src="https://img.shields.io/badge/PKI-X.509_Certificates_•_CA_•_Chain_of_Trust-2ECC71?style=flat-square" />
  <img src="https://img.shields.io/badge/Key_Establishment-Station--to--Station_•_Authenticated_DH-27AE60?style=flat-square" />
  <img src="https://img.shields.io/badge/TLS/SSL-Handshake_•_Record_Protocol_•_Certificate_Verification-1E8449?style=flat-square" />
  <img src="https://img.shields.io/badge/Classical_Ciphers-Caesar_•_Affine_•_Vigenère_•_Substitution-2C3E50?style=flat-square" />
  <img src="https://img.shields.io/badge/Cryptanalysis-Frequency_Analysis_•_Brute--force_•_Meet--in--the--Middle-34495E?style=flat-square" />
  <img src="https://img.shields.io/badge/Enigma_Machine-Rotor_Cipher_•_Kerckhoffs's_Principle-273746?style=flat-square" />
</p>

---

