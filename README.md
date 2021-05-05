# About

CI template for .Net application.

Template will consist of 3 jobs:
1. **Build**
   - Checkout
   - Restore
   - Build
   - Setup Sonar
   - Run Tests
   - Finish Sonar analysis
2. **Nuget** (disabled by default)
   - Create nuget package
   - Publish to Github (if configured)
   - Publish to Nuget (if configured)
3. **Docker** (disabled by default)
   - Create Docker image
   - Publish to Github (if configured) using SemVer tags
   - Publish to Docker Hub (if configured) using SemVer tags
