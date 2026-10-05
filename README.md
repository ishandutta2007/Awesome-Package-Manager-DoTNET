# Awesome-Package-Manager-DoTNET

# Top Package Manager (.NET) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Dependency Management, Package Registries & Open-Source Artifact Repositories*  
**Last updated: October 2026**

This repository tracks notable **commercial package managers and registries** and **open-source projects** that manage software dependencies across languages and platforms. These tools range from language-native package managers to universal artifact repositories and self-hosted registries.

**Examples** include NuGet Package Manager, npm, PyPI (pip), Maven Central, RubyGems, Cargo, Composer, Go Modules, CocoaPods, and CRAN (the category leaders).

**Open-source emphasis**: Package management is one of the strongest open-source domains — nearly every language has a native open-source package manager. **NuGet**, **npm**, **pip**, **Cargo**, **Composer**, and **Go Modules** are all open source, with **Artipie** providing a modern self-hosted universal registry. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[NuGet](https://www.nuget.org/)**  
  **The .NET package manager** — the official package registry for .NET, with 500,000+ packages. **Free and open-source** (client is Apache-2.0; nuget.org is hosted by Microsoft). **The standard for .NET dependency management**.

- **[npm](https://www.npmjs.com/)**  
  **The world's largest package registry** — 2M+ packages for JavaScript/Node.js. **Free for public packages**; npm Pro/Teams for private. **The reference for package management at scale**.

- **[PyPI (pip)](https://pypi.org/)**  
  **The Python Package Index** — 500,000+ packages for Python. **Free and open-source** (pip is MIT). **The standard for Python dependency management**.

- **[Maven Central](https://search.maven.org/)**  
  **The Java/JVM package registry** — 500,000+ artifacts. **Free and open-source** (Maven is Apache-2.0). **The standard for Java dependency management**.

- **[RubyGems](https://rubygems.org/)**  
  **The Ruby package registry** — 180,000+ gems. **Free and open-source** (RubyGems is MIT). **The standard for Ruby dependency management**.

- **[Cargo](https://crates.io/)**  
  **The Rust package registry** — 150,000+ crates. **Free and open-source** (Cargo is MIT/Apache-2.0). **The standard for Rust dependency management**.

- **[Composer](https://packagist.org/)**  
  **The PHP package registry** — 400,000+ packages. **Free and open-source** (Composer is MIT). **The standard for PHP dependency management**.

- **[Go Modules](https://pkg.go.dev/)**  
  **The Go package registry** — 500,000+ modules. **Free and open-source** (Go is BSD-3-Clause). **The standard for Go dependency management**.

- **[CocoaPods](https://cocoapods.org/)**  
  **The Swift/Objective-C package manager** — 100,000+ pods. **Free and open-source** (CocoaPods is MIT). **The standard for iOS/macOS dependency management**.

- **[CRAN](https://cran.r-project.org/)**  
  **The R package registry** — 20,000+ packages. **Free and open-source**. **The standard for R dependency management**.

## Open-Source GitHub Projects

### Universal/Cross-Language Registries

- **[Artipie](https://github.com/artipie/artipie)**  
  **Open-source, self-hosted universal artifact registry**, MIT licensed . **Supports Maven, npm, PyPI, Docker, NuGet, RubyGems, Go, Helm, Debian, RPM, and more** — one binary for all package types . **The most comprehensive open-source artifact registry** — lightweight, fast, and container-friendly . **Best for organizations wanting a single self-hosted registry for all languages** .

- **[Nexus Repository OSS](https://github.com/sonatype/nexus-public)**  
  **The most widely deployed open-source artifact repository**, EPL-1.0 licensed . **Supports Maven, npm, NuGet, PyPI, Docker, RubyGems, Go, and more** . **The enterprise standard** — mature, feature-rich, and widely documented . **Best for enterprises needing a proven artifact repository** .

- **[JFrog Artifactory OSS](https://github.com/jfrog/artifactory-oss)**  
  **Open-source version of JFrog Artifactory** (limited to OSS languages), Apache-2.0 licensed . **Supports Maven, Gradle, npm, PyPI, NuGet, Docker, and more** . **Best for teams wanting a lighter Artifactory experience** .

- **[Pulp](https://github.com/pulp/pulp)**  
  **Open-source repository management platform**, GPL-2.0 licensed . **Supports RPM, Debian, Python, Ansible, and container content** . **The standard for Linux distribution package management** . **Best for Linux distribution maintainers** .

- **[Verdaccio](https://github.com/verdaccio/verdaccio)**  
  **Lightweight private npm registry**, MIT licensed with **16,000+ GitHub stars** . **Self-hosted npm proxy and private registry** — cache public packages and host private ones . **The best open-source npm registry** — zero-config, Docker-friendly . **Best for Node.js teams wanting private npm** .

- **[Devpi](https://github.com/devpi/devpi)**  
  **Python package server and private PyPI**, MIT licensed . **Self-hosted PyPI proxy and private index** . **The standard for private Python packages** . **Best for Python teams wanting private PyPI** .

- **[ProGet](https://github.com/inedo/proget)**  
  **Universal package manager for Windows** (open-core), Apache-2.0 licensed . **Supports NuGet, npm, PyPI, Maven, Docker, and more** . **Best for Windows-centric .NET teams** .

- **[BaGet](https://github.com/loic-sharma/BaGet)**  
  **Lightweight NuGet server**, MIT licensed with **1,500+ GitHub stars** . **Self-hosted NuGet registry** — simple, fast, and .NET-native . **The best open-source NuGet server** . **Best for .NET teams wanting private NuGet** .

- **[Sleet](https://github.com/emgarten/Sleet)**  
  **Static NuGet package feed generator**, MIT licensed . **Creates static NuGet feeds from packages** — no server required, host on S3/Azure . **Best for serverless NuGet hosting** .

- **[Kellerman](https://github.com/kellerman/kellerman)**  
  **NuGet server for .NET** . **Best for lightweight NuGet hosting** .

### Language-Specific Package Managers

- **[NuGet Client](https://github.com/NuGet/NuGet.Client)**  
  **The official NuGet client for .NET**, Apache-2.0 licensed . **The standard for .NET package management** — CLI, MSBuild integration, and Visual Studio support.

- **[npm CLI](https://github.com/npm/cli)**  
  **The official npm client**, Artistic-2.0 licensed . **The standard for JavaScript package management** .

- **[pip](https://github.com/pypa/pip)**  
  **The Python package installer**, MIT licensed . **The standard for Python package management** .

- **[Cargo](https://github.com/rust-lang/cargo)**  
  **The Rust package manager**, MIT/Apache-2.0 licensed . **The standard for Rust package management** .

- **[Composer](https://github.com/composer/composer)**  
  **The PHP package manager**, MIT licensed . **The standard for PHP package management** .

- **[Go Modules](https://github.com/golang/go)**  
  **The Go package manager** (built into Go toolchain), BSD-3-Clause licensed . **The standard for Go package management** .

- **[Bundler](https://github.com/rubygems/bundler)**  
  **The Ruby dependency manager**, MIT licensed . **The standard for Ruby package management** .

- **[CocoaPods](https://github.com/CocoaPods/CocoaPods)**  
  **The Swift/Objective-C package manager**, MIT licensed . **The standard for iOS/macOS dependency management** .

- **[Swift Package Manager](https://github.com/swiftlang/swift-package-manager)**  
  **Apple's official package manager for Swift**, Apache-2.0 licensed . **The modern standard for Swift dependencies** — replacing CocoaPods for many use cases.

- **[Conan](https://github.com/conan-io/conan)**  
  **C/C++ package manager**, MIT licensed . **The standard for C/C++ dependency management** .

- **[vcpkg](https://github.com/microsoft/vcpkg)**  
  **Microsoft's C++ package manager**, MIT licensed . **The standard for Windows C++ dependencies** .

- **[Paket](https://github.com/fsprojects/Paket)**  
  **Dependency manager for .NET**, MIT licensed . **Alternative to NuGet** — more control over dependencies.

- **[Poetry](https://github.com/python-poetry/poetry)**  
  **Python dependency management and packaging**, MIT licensed . **The modern standard for Python projects** .

- **[pnpm](https://github.com/pnpm/pnpm)**  
  **Fast, disk space efficient package manager**, MIT licensed . **The best npm alternative** — hard links, strict dependency resolution.

- **[Yarn](https://github.com/yarnpkg/yarn)**  
  **Fast, reliable, and secure dependency management**, BSD-2-Clause licensed . **The original npm alternative** .

### Additional Strong Open-Source Options

- **GitHub Packages** — Package hosting integrated with GitHub (free tier available) .
- **GitLab Package Registry** — Package hosting integrated with GitLab .
- **Azure Artifacts** — Package hosting integrated with Azure DevOps .
- **Cloudsmith** — Cloud-native artifact management (free tier available) .
- **repoflow** — Self-hosted package management .
- **Conda** — Python/R package manager for data science .
- **Mamba** — Fast Conda alternative .
- **Homebrew** — macOS/Linux package manager .
- **Chocolatey** — Windows package manager .
- **Scoop** — Windows command-line installer .
- **Winget** — Windows Package Manager .

**Frameworks for building custom package management solutions**: Combine **Artipie** for a self-hosted universal registry supporting all major package types . Use **Nexus Repository OSS** for proven enterprise artifact management . Deploy **Verdaccio** for private npm, **Devpi** for private PyPI, or **BaGet** for private NuGet . Choose **JFrog Artifactory OSS** for a lighter Artifactory experience . Use **Pulp** for Linux distribution package management . Note that true enterprise artifact management with high availability, security scanning, and vendor-supported SLAs (JFrog Artifactory Pro, Cloudsmith, Azure Artifacts) remains primarily commercial territory; open-source stacks provide strong self-hosted registry, proxy, and caching foundations that require infrastructure responsibility.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Package managers execute arbitrary code during installation. **Supply chain attacks are a real threat** — verify package sources, use lockfiles, and scan dependencies for vulnerabilities .
- **Public registries are not curated for security** — npm, PyPI, and NuGet have all experienced malicious package incidents. Use private registries with security scanning for production .
- **Self-hosted registries require infrastructure** — storage, backup, high availability, and security are your responsibility. Nexus and Artifactory OSS are mature but require operational expertise .
- **License considerations**: Nexus Repository OSS uses EPL-1.0, Artifactory OSS uses Apache-2.0 with feature limitations, and Pulp uses GPL-2.0. Verify licensing against your use case .
- The open-source ecosystem provides strong self-hosted registry, proxy, and caching foundations, but **high availability, security scanning, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for developers, DevOps engineers, and organizations seeking package management sovereignty.**  
Let's make package management more open, transparent, and secure.
