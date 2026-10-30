# EAGCAP website — starter (Jekyll + GitHub Pages + Pages CMS)

This starter is designed for the GitHub organization `eagcap`, repository `eagcap.github.io`. It is a **working starter**, not a published website. The conference's full official name and placeholder text should be checked before public launch.

## Deploy it (first time)

1. Download the starter ZIP and **unzip** it.
2. Open your existing `eagcap/eagcap.github.io` repository on GitHub. If there is already a README, you can overwrite it with this one.
3. Easiest reliable way to preserve folders: use Git locally (VS Code's terminal is fine):

   ```bash
   git clone https://github.com/eagcap/eagcap.github.io.git
   cd eagcap.github.io
   ```

4. Copy **everything INSIDE** the extracted `eagcap-starter` folder into `eagcap.github.io/` (including the hidden file `.pages.yml`). Do not copy the outer folder itself.
5. Commit and push:

   ```bash
   git add -A
   git commit -m "Set up EAGCAP conference site"
   git push origin main
   ```

   If `git push` requests authentication, use GitHub authentication in VS Code or Git Credential Manager, **not your account password**. If your default branch isn't `main`, use its actual name.

6. In GitHub repository go to **Settings → Pages → Build and deployment**. Select **Deploy from a branch**, choose `main` and `/(root)`, then Save. Wait for the deployment to finish. The eventual address is `https://eagcap.github.io/`.

## Connect Pages CMS

1. Visit `https://app.pagescms.org/`.
2. Sign in with GitHub and authorize/install its GitHub App for **only** the `eagcap.github.io` repository in your `eagcap` organization.
3. Open the repository in Pages CMS. It will read `.pages.yml` in the root.
4. You will see **Announcements**, **Home page settings**, **About**, **Call for Papers**, **Program**, **Venue**, **Contact**, and **Conference editions**.
5. Try adding a *test* announcement and publish it, then inspect your live website. Published posts appear in the News section and on the home page (newest first). To keep a draft, uncheck Publish.
6. To let nontechnical successors edit content, use Pages CMS's invitation feature. They can be collaborators via email even if they have no GitHub account; admin tasks remain with GitHub users.

## Design it yourself

- `assets/css/style.css`: **colors, fonts, spacing, sections, mobile design**. Start with `:root` variables at top.
- `_layouts/default.html`: header, navigation, footer — shared by every page.
- `index.html`: home page layout.
- `_layouts/page.html`, `_layouts/post.html`: internal pages and announcements.
- `_data/home.yml`: words and dates on home page — editable in Pages CMS.
- Individual `.md` files in `about/`, `cfp/`, etc.: page text — editable in Pages CMS.
- `_data/years.yml`: yearly editions — editable in Pages CMS.

Pages CMS is for **editing content**, not drag-and-drop site design. You do the visual design by editing the HTML/CSS. You can prototype a layout in Canva, then implement it in HTML/CSS — Canva does not automatically export Jekyll source.

## Submission form and privacy

- `submission_url` under **Home page settings** is blank by default; no submissions are currently accepted by this starter site.
- When you select a submission system (Tally, CMT, etc.), paste the **tested** form link into this field. It will enable a **Submit a paper** button.
- Submission data and paper PDFs **must not** be stored in this public repository or uploaded via Pages CMS. Pages CMS public media folders are only for assets intended to be seen by visitors (e.g., images or a public conference program PDF).
- Test **both the site and submission form** from mainland China without a VPN, and provide a fallback submission channel in the CFP if necessary.

## Year-by-year handover

- Update year, dates, venue and headline through Pages CMS's Home page settings.
- Add the new edition in Conference editions; keep old years for the archive.
- Announcements automatically accumulate by date. Back up the repository and ensure there are at least two Organization owners before handover.

## Optional local preview

GitHub Pages builds Jekyll automatically. For a local live preview, install Ruby, Bundler, and the Jekyll gem; then `jekyll serve` and open localhost. VS Code's basic Live Server alone won't interpret Liquid/Jekyll templates.
