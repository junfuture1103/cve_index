# Junhak Lee(Juntheworld) : Public Vulnerability Index

Public vulnerability disclosures reported by **Junhak Lee** (`juntheworld` / `junfuture1103`).

**24 unique public advisories:** 4 CVEs and 20 GitHub Security Advisories.

Last verified: **2026-10-21**

> CVE rows include their GitHub Advisory Database aliases when available. Those aliases refer to the same vulnerabilities and are not counted again.

## CVEs

| ID | Target | Brief description | Public links |
|---|---|---|---|
| CVE-2026-82478 | NASA Trick | Stack buffer overflow in the JSON Variable Server request parser. | [CVE record](https://www.cve.org/CVERecord?id=CVE-2026-82478) · [GitHub alias: GHSA-fq2p-334f-fcrf](https://github.com/advisories/GHSA-fq2p-334f-fcrf) |
| CVE-2026-82479 | NASA cFS / SBN | Buffer overflow caused by validating an SBN TCP message size after the receive operation. | [CVE record](https://www.cve.org/CVERecord?id=CVE-2026-82479) · [GitHub alias: GHSA-6cv3-j4mc-jf2r](https://github.com/advisories/GHSA-6cv3-j4mc-jf2r) |
| CVE-2026-82480 | NASA cFS / cFE | Integer underflow in the Software Bus user-data length calculation. | [CVE record](https://www.cve.org/CVERecord?id=CVE-2026-82480) · [GitHub alias: GHSA-h35r-6hg6-mcg3](https://github.com/advisories/GHSA-h35r-6hg6-mcg3) |
| CVE-2026-105164 | NASA cFS / cFE | Out-of-bounds read in File Services input filename parsing. | [CVE record](https://www.cve.org/CVERecord?id=CVE-2026-105164) · [GitHub alias: GHSA-v57f-4hqc-phxq](https://github.com/advisories/GHSA-v57f-4hqc-phxq) · [VulDB](https://vuldb.com/vuln/413396) |

## GitHub Security Advisories

### NASA-AMMOS/AIT-Core

| ID | Brief description | Public link |
|---|---|---|
| GHSA-93gm-4cqq-j774 | Path traversal through telemetry-dictionary CSV handling. | [Advisory](https://github.com/NASA-AMMOS/AIT-Core/security/advisories/GHSA-93gm-4cqq-j774) |
| GHSA-rgwv-x7h5-f7j3 | An unauthenticated OpenMCT WebSocket `unsubscribe` request can crash the connection handler. | [Advisory](https://github.com/NASA-AMMOS/AIT-Core/security/advisories/GHSA-rgwv-x7h5-f7j3) |

### NASA-AMMOS/AIT-DSN

| ID | Brief description | Public link |
|---|---|---|
| GHSA-9mm7-x883-w33x | CFDP destination path traversal can write transferred files outside the intended directory. | [Advisory](https://github.com/NASA-AMMOS/AIT-DSN/security/advisories/GHSA-9mm7-x883-w33x) |

### NASA-AMMOS/BSL

| ID | Brief description | Public link |
|---|---|---|
| GHSA-5w4g-59g2-p7f5 | ASB security-parameter type confusion can trigger an assertion failure or uninitialized-pointer use. | [Advisory](https://github.com/NASA-AMMOS/BSL/security/advisories/GHSA-5w4g-59g2-p7f5) |
| GHSA-9xjx-rm9v-636m | A short wrapped-key parameter causes an integer underflow in BPSEC key unwrapping. | [Advisory](https://github.com/NASA-AMMOS/BSL/security/advisories/GHSA-9xjx-rm9v-636m) |

### NASA-JPL/ION-DTN

| ID | Brief description | Public link |
|---|---|---|
| GHSA-28pm-53wh-vwgp | Production cryptography uses a fixed, publicly known AES-GCM IV and content-encryption key. | [Advisory](https://github.com/nasa-jpl/ION-DTN/security/advisories/GHSA-28pm-53wh-vwgp) |
| GHSA-4438-9mff-3ppf | Signed truncation of a BPv7 payload length can produce an invalid negative memory-move size. | [Advisory](https://github.com/nasa-jpl/ION-DTN/security/advisories/GHSA-4438-9mff-3ppf) |
| GHSA-5w69-g2h4-crr4 | A non-null-terminated file-transfer command string causes a heap out-of-bounds read. | [Advisory](https://github.com/nasa-jpl/ION-DTN/security/advisories/GHSA-5w69-g2h4-crr4) |
| GHSA-74r8-6qvf-vj4f | A negative BPSEC security-context value index can cause an out-of-bounds read and indirect call. | [Advisory](https://github.com/nasa-jpl/ION-DTN/security/advisories/GHSA-74r8-6qvf-vj4f) |
| GHSA-8gm8-v334-hmxh | A non-null-terminated file-transfer filename causes a heap out-of-bounds read. | [Advisory](https://github.com/nasa-jpl/ION-DTN/security/advisories/GHSA-8gm8-v334-hmxh) |
| GHSA-cv5f-frw6-xj36 | Missing length validation before reading the LTP extension-count byte causes an out-of-bounds read. | [Advisory](https://github.com/nasa-jpl/ION-DTN/security/advisories/GHSA-cv5f-frw6-xj36) |
| GHSA-f93p-7w63-4p5p | Multiple missing bounds checks in the IPND beacon deserializer allow out-of-bounds memory access. | [Advisory](https://github.com/nasa-jpl/ION-DTN/security/advisories/GHSA-f93p-7w63-4p5p) |
| GHSA-fh7m-mf49-m786 | An unbounded destination entity-ID length causes an out-of-bounds write in the CFDP Proxy Put Request parser. | [Advisory](https://github.com/nasa-jpl/ION-DTN/security/advisories/GHSA-fh7m-mf49-m786) |
| GHSA-fj72-4276-r26x | Malformed CFDP PDUs delivered over Bundle Protocol can trigger a heap buffer overflow. | [Advisory](https://github.com/nasa-jpl/ION-DTN/security/advisories/GHSA-fj72-4276-r26x) |
| GHSA-gc93-87v8-hpfx | Repeated BPv7 extension-block instances can overflow fixed stack state used by the parser. | [Advisory](https://github.com/nasa-jpl/ION-DTN/security/advisories/GHSA-gc93-87v8-hpfx) |

### Yamcs

| ID | Brief description | Public link |
|---|---|---|
| GHSA-8h6m-c7cf-4x35 | Runtime algorithm override source is exposed without the required `ReadAlgorithm` authorization. | [Advisory](https://github.com/yamcs/yamcs/security/advisories/GHSA-8h6m-c7cf-4x35) |
| GHSA-ch9q-x62h-pg3g | User-controlled keys and missing checks allow authorization bypasses in `yamcs-web`. | [Advisory](https://github.com/yamcs/yamcs/security/advisories/GHSA-ch9q-x62h-pg3g) |
| GHSA-wqq5-5w4p-m569 | Template arguments can inject YAML structure that is persisted and reinterpreted on instance restart. | [Advisory](https://github.com/yamcs/yamcs/security/advisories/GHSA-wqq5-5w4p-m569) |
| GHSA-8m48-7crw-xpxm | OpenID Connect back-channel logout accepts unsigned logout tokens. | [Advisory](https://github.com/yamcs/yamcs/security/advisories/GHSA-8m48-7crw-xpxm) |
| GHSA-6c5v-fxc6-8qgq | The browser login endpoint bypasses the authentication rate limit. | [Advisory](https://github.com/yamcs/yamcs/security/advisories/GHSA-6c5v-fxc6-8qgq) |

## Scope

This index contains only advisories that were publicly accessible when last verified. Accepted reports that remain private drafts are intentionally excluded.
