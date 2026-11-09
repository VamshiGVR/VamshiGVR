# Install the neon GitHub profile

1. Open https://github.com/VamshiGVR/VamshiGVR . This must be a public repository with the exact same name as your GitHub username.
2. Upload `README.md`, `assets/neon-banner.svg`, and `.github/workflows/snake.yml` preserving their paths. In the GitHub website, **Add file → Upload files** supports folder paths when you drag in the directory; you can also create/edit each file manually.
3. Ensure the README is at repository root, not inside an extra folder.
4. Go to the repository **Actions** tab, enable workflows if requested, select **Generate contribution snake**, and click **Run workflow**.
5. If the action cannot publish, go to **Settings → Actions → General → Workflow permissions** and allow **Read and write permissions**, if available to you. The workflow also requests `contents: write`.
6. Allow the action run to finish, then reload your profile. The snake image references the `output` branch produced by the workflow.
7. Review any external image service availability: typing SVG, icons, activity graph, and stats rely on third-party public endpoints and may sometimes be rate limited or unavailable.
8. Pin only real repositories with documented code and sanitized demo projects. Do not upload proprietary employer source code, secrets, account IDs, or internal policies.

The hero banner is a local SVG, so it works without third-party hosting. Replace the banner file to adjust branding.
