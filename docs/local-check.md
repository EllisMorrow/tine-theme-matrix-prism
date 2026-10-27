# Local check summary

- Theme: Matrix · Prism 0.1.1
- Manifest SHA-256: `45f74738e5db03e94acea6b3a64a47c6a9cdb1324025cc39952a469acedf1858`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 9.6:1, title 9.6:1, link 4.88:1, tag 4.88:1, code 8.75:1, mark 9.14:1, chosen 9.1:1.
  - Dark: body 17.46:1, title 17.46:1, link 14.88:1, tag 14.88:1, code 15.95:1, mark 14.07:1, chosen 13.78:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
