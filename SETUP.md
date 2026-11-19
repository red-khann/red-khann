# Stage 1 setup — red-khann animated README

## 1. Add these files to your profile repository

Download and extract the ZIP. Copy `README.md` and the complete `cards/` folder into the root of your existing `red-khann` repository.

Your repository should look like:

```text
red-khann/
├── README.md
└── cards/
    ├── hero.svg
    ├── stack.svg
    ├── weatherly.svg
    ├── edumetricspro.svg
    ├── risa-interior.svg
    └── footer.svg
```

Commit and push the files to the `main` branch.

## 2. Portrait

The README currently displays your GitHub avatar automatically using:

`https://github.com/red-khann.png`

If you want a different photograph, add it to the repository as `assets/profile.jpg` and replace the avatar image URL in `README.md` with `assets/profile.jpg`.

## 3. Important project links

The project cards currently link to your GitHub profile because the exact repository URLs have not been confirmed. Replace the placeholder links in `README.md` with the real repository URLs when ready.

## 4. Animation compatibility

The custom SVG cards include CSS animations. GitHub may sanitize or limit some SVG animation features in README previews. Check the rendered profile after pushing. If GitHub removes an animation, we can adapt the cards to a GitHub-compatible alternative in the next pass.

## 5. Stage 1 scope

This package contains the visual README and custom SVG cards. It does not yet include a Python generator, contribution-data collector, or GitHub Actions workflow. Those belong to Stage 2.
