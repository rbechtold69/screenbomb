# Screenbomb

The two public pages Apple requires for Screenbomb, an iPhone app. GitHub
Pages serves them from the `gh-pages` branch, which is kept the same as
`main`. Push both at once: `git push origin main main:gh-pages`.

- `index.html`: the support page, https://rbechtold69.github.io/screenbomb/
- `privacy.html`: the privacy policy, https://rbechtold69.github.io/screenbomb/privacy.html

The App Store page links to both, and the app links to the privacy policy,
so these addresses must keep working. The app itself lives in a separate
private repository.

The text follows the App Store page: if the app changes what it does, change
these pages to match.
