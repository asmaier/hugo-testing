# Hugo GitHub Issue #6241

Details: <https://github.com/gohugoio/hugo/issues/6241>

Description: Shorter fingerprinting

## Instructions

Clone this branch of the repository and build the site.

```bash
git clone --single-branch -b hugo-github-issue-6241 https://github.com/jmooring/hugo-testing hugo-github-issue-6241
cd hugo-github-issue-6241
npm ci
rm -rf resources/ public && hugo --templateMetrics --templateMetricsHints 
```
