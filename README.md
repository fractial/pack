# Pack

A template for automated data- & resource-pack publishing.

## Usage

1. Commit and push the newest version to your repository
   ```bash
   git add .
   git commit -m "<message>"
   git push origin main
   ```

1. Create a tag with the desired version and push it to your repository
   ```bash
   git tag v1.0.0
   git push origin v1.0.0
   ```
   This wil automatically create a new release including all files inside a `release.zip`

<!-- b299250 -->
