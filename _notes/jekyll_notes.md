# How to Build an Run Jekyll Site Locally

In the project root

```bash
bundle install
bundle exec jekyll serve --watch
```

Use [http://localhost:4000/](http://localhost:4000/) rather than [http://localhost:4000/](http://localhost:4000/) to make icons load correctly

Fix `GitHUB API credentials you provided aren't valid`

Sources

- https://stackoverflow.com/questions/72859595/jekyll-certificate-verify-failed-unable-to-get-local-issuer-certificate-when
- https://github.com/jekyll/github-metadata/blob/main/docs/authentication.md
- http://blog.johannesmp.com/2017/02/13/fixing-jekyll-serve-on-windows/

Create a GitHUB Token

- Open https://github.com/settings/tokens/new
- Select the scope public_repository, and add a description.
- Confirm and save the settings. Copy the token you see on the page.

Add it to Windows as a system variable

`system -> advanced system settings -> environment variables -> System variables -> JEKYLL_GITHUB_TOKEN`
