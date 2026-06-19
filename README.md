<div align="center">


<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=akrist-rai&color=00D9FF&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/akrist-rai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akrist-rai-b510593b1/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akrist-rai)

<br/>

![AI](https://img.shields.io/badge/🧠_Deep_Learning-0A192F?style=flat-square)
![Security](https://img.shields.io/badge/🔐_Web_Application_Security-533483?style=flat-square)
![RE](https://img.shields.io/badge/🔬_Reverse_Engineering-2C3E50?style=flat-square)
![Malware](https://img.shields.io/badge/🦠_Malware_Analysis-8E44AD?style=flat-square)
![Systems](https://img.shields.io/badge/⚙️_Systems_Programming-102230?style=flat-square)
![Crypto](https://img.shields.io/badge/🔑_Applied_Cryptography-1a1a2e?style=flat-square)

</div>

---

## 🔭 Currently Building

> Three things in active motion — security tooling, applied ML, and a gamified learning platform.

### WebScan 🛡️
**Zero-Dependency Security Scanner — Go**

<table>
<tr>
<td width="55%">

> A from-scratch security platform built by studying how tools like Nuclei, Burp, WPScan, and Nikto actually work, then implementing the core techniques with zero external dependencies.

| Module | Capability |
|--------|------------|
| **Core Recon** | Headers, TLS, cookies, CORS, port scan, subdomain enum & takeover |
| **Injection** | SQLi, XSS, SSTI, XXE, command injection, CRLF, LDAP injection |
| **CVE & CMS** | 30+ CVE probes, WordPress/Drupal/Joomla deep scans, default creds |
| **Discovery** | 280-path brute-force, arjun-style param discovery, BFS web crawler |
| **Advanced** | OAST/OOB callbacks, GraphQL security suite, JWT `alg:none` detection |

![Status](https://img.shields.io/badge/🚧_Status-Active_Development-FF6B6B?style=flat-square)
![Stack](https://img.shields.io/badge/Go_1.21_Generics-00ADD8?style=flat-square&logo=go&logoColor=white)
![Scale](https://img.shields.io/badge/~5%2C800%2B_Lines_•_12_Files-2C3E50?style=flat-square)
![Domain](https://img.shields.io/badge/Bug_Bounty_Tooling-E74C3C?style=flat-square)

</td>
<td width="45%" align="center">

```
        WebScan Engine
       ┌─────────────┐
       │   main.go   │
       └──────┬──────┘
   ┌──────┬───┴────┬───────┐
   ▼      ▼        ▼       ▼
checks  inject   recon    cve
  .go     .go     .go     .go
   │      │        │       │
   └──────┴───┬────┴───────┘
              ▼
         report.go
   (JSON / Markdown · CVSS + CWE)
```

</td>
</tr>
</table>

---

### Commute 🚦
**Spatio-Temporal Traffic Flow Prediction — Python, PyTorch**

<table>
<tr>
<td width="55%">

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

**Core architectures**

| Graph & Spatial | Sequential & Temporal | Generative | Security-Adjacent ML |
|:-:|:-:|:-:|:-:|
| GNN · GAT · GCN | Mamba/SSM · LSTM · RNN | GANs · VAEs | Malware Classification |
| Spatio-Temporal | Transformers (MHA · MoE · GQA · RoPE) | RL + VAE | Behavioral Anomaly Detection |
| Flash Attention | DeepSeek Sparse Attention | — | Network Traffic Clustering |

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Hardware--Aware_Training-Memory--Efficient_•_Mixed_Precision-0A192F?style=flat-square" />
  <img src="https://img.shields.io/badge/Applied_ML_for_Security-Static_%26_Behavioral_Feature_Engineering-533483?style=flat-square" />
</p>

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

### 🔐 Security, Reverse Engineering & Cryptography

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
  <img src="https://img.shields.io/badge/Session_Hijacking-Cookie_Theft_•_Fixation-2C3E50?style=flat-square" />
  <img src="https://img.shields.io/badge/Business_Logic_Flaws-Workflow_Abuse-16A085?style=flat-square" />
  <img src="https://img.shields.io/badge/Authentication_Bypass-Credential_•_MFA_Abuse-8E44AD?style=flat-square" />
  <img src="https://img.shields.io/badge/File_Upload-Extension_•_Content--Type_Bypass-D35400?style=flat-square" />
  <img src="https://img.shields.io/badge/Recon_&_Enumeration-Bug_Bounty_Methodology-2ECC71?style=flat-square" />
</p>

---

#### 🔬 Reverse Engineering

<p align="center">
  <img src="https://img.shields.io/badge/x86/x64_Assembly-Instruction_Set_•_Calling_Conventions-2C3E50?style=flat-square" />
  <img src="https://img.shields.io/badge/PE_%26_ELF_Binary_Format-Headers_•_Sections_•_Imports-34495E?style=flat-square" />
  <img src="https://img.shields.io/badge/Static_Analysis-Disassembly_•_String_%26_Import_Analysis-16A085?style=flat-square" />
  <img src="https://img.shields.io/badge/Dynamic_Analysis-Debugger--Driven_Execution_Tracing-27AE60?style=flat-square" />
  <img src="https://img.shields.io/badge/Ghidra-Decompilation_•_Scripting-2980B9?style=flat-square" />
  <img src="https://img.shields.io/badge/GDB-Breakpoints_•_Memory_Inspection_•_Live_Patching-1F618D?style=flat-square" />
  <img src="https://img.shields.io/badge/Unpacking_%26_Patching-Stub_Analysis_•_OEP_Recovery-8E44AD?style=flat-square" />
  <img src="https://img.shields.io/badge/Anti--Debugging_%26_Anti--Disassembly-Evasion_Technique_Recognition-C0392B?style=flat-square" />
  <img src="https://img.shields.io/badge/Control_Flow_Analysis-CFG_Reconstruction_•_Deobfuscation-D35400?style=flat-square" />
  <img src="https://img.shields.io/badge/Relocation_%26_IAT_Resolution-Fixups_•_Import_Table_Repair-7F8C8D?style=flat-square" />
</p>

---

#### 🦠 Malware Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Static_Malware_Analysis-Signature_•_Heuristic_•_IOC_Extraction-E74C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/Dynamic_%26_Behavioral_Analysis-Sandboxed_Detonation-C0392B?style=flat-square" />
  <img src="https://img.shields.io/badge/Memory_Forensics-Volatility_3_•_EPROCESS_•_DKOM_Detection-8E44AD?style=flat-square" />
  <img src="https://img.shields.io/badge/Network_Traffic_Analysis-C2_•_Beaconing_•_Exfiltration_Patterns-2980B9?style=flat-square" />
  <img src="https://img.shields.io/badge/Threat_Intelligence-Pyramid_of_Pain_•_IOC_Provenance-16A085?style=flat-square" />
  <img src="https://img.shields.io/badge/YARA_Rule_Development-Pattern--based_Detection-F39C12?style=flat-square" />
  <img src="https://img.shields.io/badge/Malware_Family_Research-Mirai_•_WannaCry_•_Zeus_•_Stuxnet_•_Emotet-922B21?style=flat-square" />
  <img src="https://img.shields.io/badge/Malware_Family_Research-AsyncRAT_•_Cobalt_Strike_•_RedLine_•_NotPetya--HermeticWiper-7B241C?style=flat-square" />
  <img src="https://img.shields.io/badge/Packer_%26_Crypter_Analysis-Stub_%26_Payload_Separation-1ABC9C?style=flat-square" />
  <img src="https://img.shields.io/badge/Sandbox_Evasion_Detection-VM_%26_Debugger_Fingerprinting-34495E?style=flat-square" />
</p>

---

#### 🧪 Malware Development *(offensive technique research, isolated lab environments)*

<p align="center">
  <img src="https://img.shields.io/badge/Process_Injection-DLL_•_Reflective_•_Process_Hollowing-C0392B?style=flat-square" />
  <img src="https://img.shields.io/badge/Persistence_Mechanisms-Registry_•_Services_•_Scheduled_Tasks-8E44AD?style=flat-square" />
  <img src="https://img.shields.io/badge/Shellcode_Development-Position--Independent_Code-E67E22?style=flat-square" />
  <img src="https://img.shields.io/badge/Anti--Forensics_Concepts-Log_Tampering_•_Timestomping-7F8C8D?style=flat-square" />
  <img src="https://img.shields.io/badge/Rootkit_%26_DKOM_Concepts-Kernel_Object_Manipulation-2C3E50?style=flat-square" />
  <img src="https://img.shields.io/badge/C2_Framework_Design-Beacon_Protocols_•_Encrypted_Channels-16213E?style=flat-square" />
  <img src="https://img.shields.io/badge/Obfuscation_%26_Packing-Custom_Stub_Design-1a1a2e?style=flat-square" />
</p>

---

#### 🧰 Other Skills — DFIR & Tooling

<p align="center">
  <img src="https://img.shields.io/badge/Digital_Forensics_%26_Incident_Response-DFIR_Methodology-27AE60?style=flat-square" />
  <img src="https://img.shields.io/badge/Vulnerability_Research-Binary_%26_Web_Vuln_Discovery-E74C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/Binary_Exploitation-Buffer_Overflows_•_ROP_Chains-C0392B?style=flat-square" />
  <img src="https://img.shields.io/badge/Environment--as--Variable_Methodology-Controlled_Experimental_Design-16A085?style=flat-square" />
  <img src="https://img.shields.io/badge/Toolchain-Ghidra_•_GDB_•_Volatility_3_•_YARA_•_Wireshark_•_QEMU-2C3E50?style=flat-square" />
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
