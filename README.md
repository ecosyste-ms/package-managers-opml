# Package Manager Release Feeds

A curated collection of RSS/Atom feeds tracking releases and updates for package manager clients, registries, and related infrastructure across multiple programming languages and platforms.

## What's Included

This OPML feed collection covers:

- **Package manager clients** (npm, pip, cargo, composer, etc.)
- **Package registries** (PyPI, crates.io, RubyGems.org, etc.)
- **System package managers** (Homebrew, APT, DNF, Nix, etc.)
- **Container tooling** (Docker, Helm, Harbor)
- **Dependency management tools** (Renovate, Dependabot)

## Categories

| Category | Package Managers/Tools |
|----------|------------------------|
| JavaScript/Node.js | npm, pnpm, Yarn, Bun, Verdaccio |
| Python | pip, Poetry, uv, Warehouse (PyPI) |
| Ruby | RubyGems, Bundler, RubyGems.org |
| Rust | Cargo, Crates.io |
| PHP | Composer, Packagist |
| Go | Go modules, Athens |
| Java/JVM | Maven, Gradle |
| .NET | NuGet Client, NuGet.Server |
| Elixir | Hex, Hexpm |
| System Package Managers | Homebrew, APT, DNF, Pacman, Flatpak, Snap, Nix |
| Container & Cloud | Docker, Helm, Harbor |
| Language-Specific | CocoaPods, Swift PM, Pub, CPAN |
| Multi-Language | Conda, Mamba, Spack, asdf, mise |
| Infrastructure | Renovate, Dependabot |

## Usage

### Import into RSS Reader

**Quick Import:** [Download package-manager.opml](https://raw.githubusercontent.com/andrew/package-managers-opml/main/package-manager.opml)

#### Popular RSS Readers

**Feedly**
1. Click "Add Content" → "Import OPML"
2. Upload `package-manager.opml`

**Inoreader**
1. Settings → Import/Export → Import from OPML
2. Upload the file

**NewsBlur**
1. Click your username → Import/Upload → Choose File
2. Upload `package-manager.opml`

**NetNewsWire** (macOS/iOS)
1. File → Import Subscriptions
2. Select `package-manager.opml`

**Thunderbird**
1. Tools → Import → Import from OPML file
2. Browse and select the file

### Manual Subscription

You can also subscribe to individual feeds by copying URLs directly from the OPML file.

## Contributing

Contributions are welcome! To add a new feed:

1. Fork this repository
2. Add the feed to `package-manager.opml` in the appropriate category
3. Ensure the feed includes:
   - `text`: Descriptive name
   - `xmlUrl`: RSS/Atom feed URL
   - `htmlUrl`: Human-readable URL
   - `type="rss"`: Feed type attribute
4. Keep feeds alphabetically sorted within categories
5. Submit a pull request

### Feed Guidelines

- Feeds should be for official releases, not community channels
- Prefer GitHub Releases Atom feeds (`.../releases.atom`) for consistency
- Include both client and registry/infrastructure projects where applicable
- Test the feed URL before submitting

## License

CC0 1.0 Universal. Do whatever you want with this.