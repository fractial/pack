# Pack

A template for automated data- & resource-pack publishing.

## Usage

1. Commit and push the latest version of your repository
   ```bash
   git add .
   git commit -m "<message>"
   git push origin main
   ```

1. Create a new tag with the desired version and push it to your repository
   ```bash
   git tag v1.0.0
   git push origin v1.0.0
   ```
   This will automatically create a new release including all files inside a `release.zip`.
   If you want to use a custom name for the release-candidate specify it inside the `pack.mcmeta` under `.pack.name`.

<!-- b299250 -->
