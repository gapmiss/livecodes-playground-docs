---
created: 2024-03-13
title: Self hosting
updated: 2024-03-14
---

See the [Self-hosting documentation](https://livecodes.io/docs/features/self-hosting) for further up-to-date details.

## Fork, clone and install

Fork the `live-codes/livecodes` [GitHub repo](https://github.com/live-codes/livecodes) and clone it. You may wish to use the included setup to deploy to [GitHub Pages](https://pages.github.com/) (see steps below):

```bash
git clone https://github.com/{your-username}/livecodes
cd livecodes
npm install
```

## Build, serve and deploy

```bash {4}
# build the app to "build" directory
npm build
# or to deploy via username.github.io (see `Build and publish to Github` below)
npx cross-env DOCS_BASE_URL="/playground/docs/" npm run build
# locally serve to http://localhost:8080
npm run serve
# build and deploy to github pages
# (see `Build and publish to Github` below)
npm run deploy
# for development
# w/ code watch, rebuild and live-reload
npm start
```

### Build and publish to Github

If you wish to host the app on Github pages, the base URL of the documentation directory needs to be supplied by the environment variable `DOCS_BASE_URL` during build.

```bash
# e.g. https://{your-username}.github.io/playground/
npx cross-env DOCS_BASE_URL="/playground/docs/" npm run build
```

#### Complete these steps before deploying via `npm run deploy`

1. Under your Github profile, navigate to **Settings** &gt; **Developer settings** &gt; **Fine-grained tokens**.

2. Click **Generate new  token**.

3. Name the token `GH_ACTIONS_REPO_PAT`, choose expiration date and give it a description.

4. Under **Repository access**, select **Only select repositories** and select the appropriate repository.

5. Under **Permissions** &gt; **Repository permissions** &gt; **Actions**, select **Read and write**.

6. Click the **Generate token** button at the bottom of the page.

    > [!warning] NOTICE
    > Your token will be generated. **Make sure to copy your personal access token now** as you will not be able to see it again.

7. Go to `https://github.com/{your-username}/livecodes`

8. Click **Settings** in the menu

9. Click **Environments** in the menu

10. Click **github-pages**

11. Under **Environment secrets**, click **Add secret**

12. Name the secret `GH_ACTIONS_REPO_PAT` and paste your token from step 6.

13. Click **Add secret** button

14. Click **Pages** in the left-side menu

15. Choose the **Source** &gt; **Deploy from a branch**.

16. Select the `gh-pages` branch with `/(root)` folder and click the **Save** button.
17. After some time (~5-30 minutes) the page will refresh with:
    - Your site is live at `https://{your-username}.github.io/livecodes/`
    - Click the **Visit site** button to see the deployed Livecodes instance hosted by Github

---

