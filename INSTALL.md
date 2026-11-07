# BDA GitHub Overview — installation (not published)

This kit is for the **personal GitHub account** `BrothersDigitalAgency` (not a GitHub organization).

1. Sign in to the BDA GitHub account.
2. Open https://github.com/BrothersDigitalAgency/BrothersDigitalAgency
3. Replace the existing root `README.md` with the kit's `README.md`.
4. Upload the entire `assets/` directory, preserving the filenames and paths exactly.
5. Commit, then open https://github.com/BrothersDigitalAgency and hard-refresh.

The README uses PNG assets for reliable GitHub rendering. Corresponding SVG source artwork is included to make later edits easier.

Important: the profile's contribution graph and GitHub navigation cannot be removed/repositioned via README. The custom content only displays when GitHub recognizes the public, same-username profile repository. If the new README appears correctly inside the repository but not on the account Overview, that is a **profile-display issue**, not an image/design issue.

### File map
- README.md — must be at repository root
- assets/01-bda-hero.png — editorial header
- assets/02-bda-disciplines.png — the three BDA disciplines
- assets/03-project-aura.png — personal build graphic
- assets/04-project-autopro.png — personal build graphic
- assets/05-bda-contact.png — contact banner

The matching .svg artwork files are optional to upload (but recommended for editability).

### Brand provenance
Colors and direction follow BDA's official website repository:
`https://github.com/mouadbusni/brothers-digital` (`site-source/styles.css`, `public/assets/brand-mark.svg`).
BDA monogram artwork in this kit is a simplified vector trace from the official project mark, not a new logo concept.

No account changes have been performed. The kit is only a draft until you publish it.

### Upload using GitHub in the browser
Open the repository, select `README.md` → pencil icon → replace with the kit's README contents → **Commit changes**. Then use **Add file → Upload files** and upload the five `.png` images to `assets/` (upload SVG source files there as optional extras). The relative file paths in the README must not change.

### Upload using git (alternative)
```bash
git clone https://github.com/BrothersDigitalAgency/BrothersDigitalAgency.git
cd BrothersDigitalAgency
# Copy the kit's README.md and assets/ into this folder.
git add README.md assets/
git commit -m "Redesign BDA GitHub profile"
git push origin main
```

Use the BDA account's credentials/permissions to push. Do not overwrite other repository files.
