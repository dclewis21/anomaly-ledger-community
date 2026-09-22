# Enable categories + Giscus (manual)

Discussions are **on**. GraphQL cannot create/rename categories with current tokens — do this in the GitHub UI:

1. https://github.com/dclewis21/anomaly-ledger-community/discussions → ⚙️ Manage categories  
2. Add: **Case threads**, **Sightings**, **Places tips**, **Case debates**, **Site feedback**  
3. Install Giscus App via https://giscus.app → select this repo → mapping **pathname** → category **Case threads** → theme **transparent_dark**  
4. Paste repo id `R_kgDOUl8Abw` and the Case threads category id into site env:
   - `PUBLIC_GISCUS_REPO_ID`
   - `PUBLIC_GISCUS_CATEGORY_ID`

Site SETUP.md (private `anomaly-ledger`) has the full CoS checklist.
