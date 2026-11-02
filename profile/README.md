# CipherMap (`Ciphermap Technologies LLC`)

**CipherMap** is a local, zero-egress **12-language post-quantum cryptography (PQC) vulnerability scanner**, **signed CycloneDX 1.6 Cryptographic Bill of Materials (CBOM) & CISA IBOM generator**, **4-Gate `IMM-*` bug-class extinction engine**, and **local `stdio` Model Context Protocol (MCP) AI agent referee**.

- **Website:** [https://www.ciphermap.io](https://www.ciphermap.io)
- **CLI Documentation:** [https://www.ciphermap.io/docs](https://www.ciphermap.io/docs)
- **Technical Comparison:** [https://www.ciphermap.io/compare](https://www.ciphermap.io/compare)
- **Signed Offline CLI Evaluation Pack:** [https://www.ciphermap.io/eval-pack](https://www.ciphermap.io/eval-pack)
- **Machine-Readable LLM Specs:** [`llms.txt`](https://www.ciphermap.io/llms.txt) · [`llms-full.txt`](https://www.ciphermap.io/llms-full.txt)

## Key Capabilities

1. **Zero Source-Code Egress (`--offline --no-telemetry`):** Runs locally on macOS, Linux, and Windows (`arm64` & `x64`) across Go, Python, JavaScript/TypeScript, Java, Kotlin, C#, Rust, C/C++, Ruby, PHP, and Swift—plus compiled `.jar`/`.war`/`.whl` archives, `.jks`/`.p12` keystores, ELF/Mach-O/PE binaries, PKCS#11 HSM calls, and IaC manifests.
2. **Standards-Pinned PQC Discovery (`NIST FIPS 203 / 204 / 205` & `CNSA 2.0`):** Separates finalized `ML-KEM`, `ML-DSA`, and `SLH-DSA` implementations from wire-incompatible NIST Round 3 `kyber768` / `dilithium3` drafts (`PQC-PRE-001..005`).
3. **Deterministic CycloneDX 1.6 CBOM & Provenance:** Generates CycloneDX 1.6 CBOMs (`ciphermap cbom` + `--diff`), SARIF 2.1.0, CISA IBOM & OpenVEX 0.2.0 attestations, sealed with composite `Ed25519 + ML-DSA-65` (`.pqc.sig`) signatures.
4. **Local `stdio` MCP Referee (`ciphermap mcp --workspace .`):** Exposes deterministic verification tools to Claude Code, Cursor, and Windsurf over local `stdio` JSON-RPC 2.0—rejecting unverified AI patches when AST, compiler, or network-denied OS witness gates fail.
