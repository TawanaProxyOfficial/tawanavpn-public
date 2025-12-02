# Publication and Sanitization Checklist — Tawanavpn (v1.0)
# چک‌لیست انتشار و سانیتایز — Tawanavpn (v1.0)

این چک‌لیست دوزبانه است و برای آماده‌سازی اسناد، ریپوها و متادیتای انتشار در Figshare/Zenodo/ORCID استفاده می‌شود. هر بار قبل از انتشار عمومی، همهٔ موارد را مرور کنید. هیچ جزئیات فنی یا عملیاتی نباید افزوده شود.

## A. Document review | بازبینی سند
- [ ] Language consistency (Persian/English) checked; headings and notes aligned.
- [ ] Sanitized content confirmed: no domains, IPs, configs, bypass steps, or operational tips.
- [ ] Version, date, and license (CC BY 4.0) are present and correct.
- [ ] PDF exports generated from Markdown where needed for upload.

## B. Repository hygiene | بهداشت ریپو
- [ ] Only non-sensitive files are included; operational files remain private.
- [ ] File names and paths are clear for public sharing (e.g., roadmap, checklist, metadata, license).
- [ ] README is bilingual, up to date, and references the sanitized scope.
- [ ] Git history reviewed for sensitive traces; rewrite or remove if necessary.

## C. Metadata for Figshare/Zenodo | متادیتا برای فیگ‌شِر/زنودو
- [ ] Title, authors, description, keywords, and license match `figshare_metadata.json`.
- [ ] Resource type set to "Documentation" (or equivalent) and license set to CC BY 4.0.
- [ ] DOI requested/linked after upload; DOI added to public summaries and ORCID profile.

## D. Release & communication | انتشار و ارتباطات
- [ ] Public links shared only after sanitization is confirmed.
- [ ] Weekly review cadence defined; updates remain non-operational.
- [ ] Use trusted, secure channels for coordination and any credential handling.
