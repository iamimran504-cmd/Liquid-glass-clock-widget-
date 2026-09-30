# Phone-only build

Is project ko computer ke bina GitHub Actions se APK banaya ja sakta hai.

1. GitHub app ya browser me GitHub account login karo.
2. New repository banao, example: LiquidGlassClockWidget
3. Is ZIP ko extract karke project ke files repository me upload karo.
4. `.github/workflows/build-apk.yml` bhi upload hona chahiye.
5. GitHub repository me **Actions** tab kholo.
6. `Build Liquid Glass Clock APK` workflow select karo.
7. **Run workflow** dabao.
8. Build complete hone ke baad workflow ke bottom me **Artifacts** me
   `LiquidGlassClock-debug` milega.
9. Artifact ZIP download karke uske andar `app-debug.apk` phone me install karo.

Note: Android may show an "install unknown apps" permission when installing
an APK downloaded from GitHub. Only install APKs from your own repository.
