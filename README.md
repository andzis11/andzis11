  
                                              ██▓▒­░⡷⠂ANDZISONE⠐⢾░▒▓██
<p align="center">
  <img src="https://techstack-generator.vercel.app/aws-icon.svg"     alt="AWS"     width="68" height="68" style="margin: 8px;" />
  <img src="https://techstack-generator.vercel.app/cpp-icon.svg"    alt="C++"    width="68" height="68" style="margin: 8px;" />
  <img src="https://techstack-generator.vercel.app/csharp-icon.svg" alt="C#"     width="68" height="68" style="margin: 8px;" />
  <img src="https://techstack-generator.vercel.app/java-icon.svg"   alt="Java"   width="68" height="68" style="margin: 8px;" />
  <img src="https://techstack-generator.vercel.app/github-icon.svg" alt="GitHub" width="68" height="68" style="margin: 8px;" />
</p>

## Security Research

Disclosure terverifikasi dengan credit resmi (GHSA / changelog vendor):

| Target | Advisory / Bukti | Temuan | Status |
|---|---|---|---|
| xevrion/hatchzip | [GHSA-cq63-4gv9-w2gc](https://github.com/xevrion/hatchzip/security/advisories/GHSA-cq63-4gv9-w2gc) | Symlink `.hatchzip-part` mengarahkan ekstraksi menulis di luar output folder (CWE-59) | Fixed 0.1.6 · shared credit |
| xevrion/hatchzip | [GHSA-m6m5-qcjx-55gv](https://github.com/xevrion/hatchzip/security/advisories/GHSA-m6m5-qcjx-55gv) | Progress files yang menyertai arsip membuat resume/restore mengganti file user (CWE-345) | Fixed 0.1.6 · sole reporter |
| shieldfive/crypto | [CHANGELOG](https://github.com/shieldfive/crypto/blob/main/CHANGELOG.md) · [PR #55](https://github.com/shieldfive/crypto/pull/55) | Upload-proof scope: klaim binding proof tidak sesuai cakupan MAC | Credited 2026-09-23 |
| PayPerQ/ppq-enclave-proxy | [GHSA-33j5-hgc8-9mgg](https://github.com/PayPerQ/ppq-enclave-proxy/pull/360) · [PR #360](https://github.com/PayPerQ/ppq-enclave-proxy/pull/360) | Body-parse error membocorkan fragment request (termasuk plaintext EHBP) + unbounded line pump menyebabkan OOM worker | Fixed · credited |

<!---
andzis11/andzis11 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
