# GitHub Pages Demo

A simple GitHub Pages site with automated testing.

## Files

- `index.html` - Main page with interactive content
- `test.html` - Test suite to verify functionality
- `.github/workflows/deploy-test.yml` - Automated deployment and testing

## Testing

### Local Testing
Open `test.html` in your browser to run the test suite locally.

### Automated Testing
The GitHub workflow automatically:
1. Deploys the site to GitHub Pages
2. Tests page accessibility
3. Verifies content is correct
4. Confirms both main and test pages work

## Setup Instructions

1. Enable GitHub Pages in repository settings
2. Set source to "GitHub Actions"
3. Push changes to trigger deployment
4. Visit your site at `https://[username].github.io/[repository-name]/`
5. Check test results at `https://[username].github.io/[repository-name]/test.html`

## Status

The workflow will show ✅ if all tests pass or ❌ if there are issues.