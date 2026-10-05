---
status: Accepted
ratified_by: 5903b59
---

# conventions — codebase guide

**Loaded when:** writing or reviewing code.

## WDI Engineering Playbook Integration

Proyek ini mengadopsi Single Source of Truth (SSOT) rekayasa terpusat WDI:
- **Konvensi Inti (`03-essential-conventions.md`):** Tiga lapis penegakan `[L1-Tool]`, `[L2-Guard]`, `[L3-Review]`.
- **Backend Go (`stack/go.md`):**
  - Pembungkusan error kontekstual `%w`.
  - Fail-closed secret boot validation dan batas koneksi database terukur.
  - Sanitasi archive decompression melawan Zip Slip & Zip Bomb (`LimitReader`).
- **Frontend React (`stack/react-typescript.md` & `07`):**
  - Skala sentuh minimum 48dp, dialog konfirmasi terkuantifikasi, dan empty states 3-elemen.
