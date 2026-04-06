# muratec

**Muratec ENI** — IT Consulting & Business Automation  
Website: [muratec.pt](https://muratec.pt) | Fallback: [ermin-muratovic.github.io/muratec](https://ermin-muratovic.github.io/muratec)

---

## Deploy

GitHub Pages is configured to serve from the `main` branch root.  
Custom domain: `muratec.pt` (set via `CNAME` file).

## DNS Setup (muratec.pt → GitHub Pages)

Add these records at your domain registrar:

```
A     @     185.199.108.153
A     @     185.199.109.153
A     @     185.199.110.153
A     @     185.199.111.153
CNAME www   ermin-muratovic.github.io
```

Then in GitHub repo Settings → Pages → Custom domain → type `muratec.pt` → Save.  
Enable "Enforce HTTPS" once DNS propagates (~10–30 min).

## Stack

- Pure HTML/CSS/JS — zero dependencies, zero build step
- Google Fonts (Cormorant Garamond, DM Mono, Outfit)
- Ready for Donna AI backend integration

## Entity

Muratec ENI · NIF 332987493 · EU VAT PT332987493  
Avenida Brasília 36, R/C Dto, 2780-207 Oeiras, Portugal
