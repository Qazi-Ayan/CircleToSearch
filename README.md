cat << 'EOF' > README.md
<div align="center">
  <img src="app/src/main/res/drawable/circletosearch.png" width="160" height="160" alt="Circle To Search">
    <h1>Circle To Search (Minimal Fork)</h1>
      <p>A stripped-down, UI-focused fork of <a href="https://github.com/AKS-Labs/CircleToSearch">AKS-Labs/CircleToSearch</a>.</p>

        <img alt="Last commit" src="https://img.shields.io/github/last-commit/Qazi-Ayan/CircleToSearch?color=c3e7ff&style=flat-square">
          <img alt="Repo size" src="https://img.shields.io/github/repo-size/Qazi-Ayan/CircleToSearch?color=c3e7ff&style=flat-square">
            <br><br>
              <img alt="API 29+" src="https://img.shields.io/badge/Api%2029+-50f270?logo=android&logoColor=black&style=for-the-badge"/>
                <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-a503fc?logo=kotlin&logoColor=white&style=for-the-badge"/>
                  <img alt="Jetpack Compose" src="https://img.shields.io/static/v1?style=for-the-badge&message=Jetpack+Compose&color=4285F4&logo=Jetpack+Compose&logoColor=FFFFFF&label="/>
                  </div>

                  ---

                  ## Why This Fork?

                  The original [CircleToSearch](https://github.com/AKS-Labs/CircleToSearch) packs a lot of extra UI elements—like playful popup messages and a second row of action buttons—on top of the overlay. This fork exists to strip away that visual clutter and keep a cleaner, minimal search pill at the bottom of the screen.

                  ## What's Changed

                  - **Removed popup messages:** Disabled the friendly/playful message bubble that appears on the overlay.
                  - **Removed bottom action row:** Disabled the second row of extra action buttons (`Row 2`) to leave a cleaner bottom bar.
                  - **GitHub Actions Linux build fixes:** Updated the hardcoded Windows NDK path to `linux-x86_64`, skipped rebuilding the prebuilt Rust bindings, and bypassed upstream Android lint errors so the APK compiles on GitHub's Linux runners.

                  ## Current Status

                  > **Work in Progress:** This is an experimental personal fork. Some features are currently broken and have not been fixed yet. If you want a stable, full-featured build, use the [original AKS-Labs repository](https://github.com/AKS-Labs/CircleToSearch).

                  ## Getting the APK

                  1. Open the **Actions** tab in this repository and select the latest green **Build APK** run.
                  2. Scroll down to **Artifacts** and download `release-apk`.
                  3. Extract the zip file, uninstall any existing version of CircleToSearch first (different signing keys will conflict), and install the APK.

                  ## Credits

                  All core functionality and original code belong to **[AKS-Labs/CircleToSearch](https://github.com/AKS-Labs/CircleToSearch)**.
                  EOF
