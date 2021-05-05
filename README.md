# .github

CI template that should contain most common steps for .Net application.

Steps:
1. Checkout 
2. Restore
3. Build
4. Sonar Begin - optional
5. Run tests
6. Sonar End - optional
7. Add git tag
8. Publish Nugets - optional
9. Build Docker image - optional
10. Publish and tag Docker image using SemVer- optional
