# 👋 Hi, I’m @haroonawanofficial

I’m an advanced cybersecurity expert specializing in inventing new, never-seen-before techniques in cyber and information security.

---

## 🧠 Notable Works (Original & Unprecedented)

### 💻 User Computer Hijacking
- **MIRC DNS Resolver Bug Exploitation**  
  Hijacking user machines via malformed DNS response chaining.

---

### 🧬 Next-Gen Cross Site Scripting (XSS) Techniques

- WebGPU / WebXR / WebTransport API fuzzing  
- Service-Worker cache poisoning vectors  
- `instantiateStreaming()` WebAssembly injection  
- `MutationObserver` race-condition exploitation  
- Cross-protocol chains (`file://` ↔ `http/https://` ↔ `ws://`)  
- Adaptive Header Morphing / `--polymorph` WAF-bypass engine  
- JSON-LD / RDFa / Microdata injection  
- GraphQL schema autodiscovery & variable fuzzing  
- Prototype-pollution–assisted DOM clobbering  
- Unicode RLO & BOM disguise encodings  

---

### 🌐 Advanced Server-Side Request Forgery (SSRF) Techniques

#### 🔁 Meta-Application Request Smuggling Forgery
> Chains backend service calls by smuggling attacker-controlled params through one service into another. Bypasses access controls enforced only at the frontend.

#### 🌀 RARF – Request Alias Resolution Forgery
> Uses DNS rebinding & CNAME tricks to resolve attacker domains into internal hostnames (`*.svc.cluster.local`).

#### 🔓 VREF – Virtual Reference Elevation Forgery
> Access/mutate objects via fuzzed or guessed UUIDs, hashes, or opaque references belonging to other users or admins.

#### 📩 SREF – Stored Request Execution Forgery
> Injects POST/PUT payloads in drafts/configs/webhooks that auto-execute later via background jobs or CRON tasks.

#### 🪞 CLRF – CORS Logic Rebinding Forgery
> Exploits wildcard/weak CORS settings to trigger credential reflection or data leaks from attacker-controlled origins.

#### 🔊 EPRF – Event Propagation Request Forgery
> Injects commands using browser APIs (`postMessage`, `BroadcastChannel`, `SharedWorker`) into trusted app contexts.

#### 🧬 IMRF – Interface Mutation Request Forgery
> Mutates DOM—hidden inputs, CSRF tokens, form actions—via Shadow DOM or inline scripts, auto-submitting forms stealthily.

#### 🔗 UDRF – Universal Dependency Relay Forgery
> Abuses SDKs/backends (e.g., S3 relays, gRPC proxies) to relay malicious input to internal services or file systems.

---

🔐 *Every technique listed here is based on real-world, operational proof-of-concepts built from the ground up.*

📫 Connect or collaborate: [haroon@cyberzeus.pk](mailto:haroon@cyberzeus.pk)

