# MegaLinter Custom Flavor: megalinter-arm64

This custom MegaLinter aims to have an optimized Docker image size.

It is built from official MegaLinter images, but is maintained on [anwarani-ext-ks/megalinter-custom-flavor-arm64](https://github.com/anwarani-ext-ks/megalinter-custom-flavor-arm64) by Drew Waranis

## Embedded linters

- [ACTION_ACTIONLINT](https://megalinter.io/latest/descriptors/action_actionlint/)
- [ACTION_ZIZMOR](https://megalinter.io/latest/descriptors/action_zizmor/)
- [ANSIBLE_ANSIBLE_LINT](https://megalinter.io/latest/descriptors/ansible_ansible_lint/)
- [API_SPECTRAL](https://megalinter.io/latest/descriptors/api_spectral/)
- [ARM_ARM_TTK](https://megalinter.io/latest/descriptors/arm_arm_ttk/)
- [BASH_EXEC](https://megalinter.io/latest/descriptors/bash_exec/)
- [BASH_SHELLCHECK](https://megalinter.io/latest/descriptors/bash_shellcheck/)
- [BASH_SHFMT](https://megalinter.io/latest/descriptors/bash_shfmt/)
- [BICEP_BICEP_LINTER](https://megalinter.io/latest/descriptors/bicep_bicep_linter/)
- [CLOJURE_CLJSTYLE](https://megalinter.io/latest/descriptors/clojure_cljstyle/)
- [CLOJURE_CLJ_KONDO](https://megalinter.io/latest/descriptors/clojure_clj_kondo/)
- [CLOUDFORMATION_CFN_LINT](https://megalinter.io/latest/descriptors/cloudformation_cfn_lint/)
- [COFFEE_COFFEELINT](https://megalinter.io/latest/descriptors/coffee_coffeelint/)
- [COPYPASTE_JSCPD](https://megalinter.io/latest/descriptors/copypaste_jscpd/)
- [CPP_CLANG_FORMAT](https://megalinter.io/latest/descriptors/cpp_clang_format/)
- [CPP_CPPCHECK](https://megalinter.io/latest/descriptors/cpp_cppcheck/)
- [CPP_CPPLINT](https://megalinter.io/latest/descriptors/cpp_cpplint/)
- [CREDENTIALS_SECRETLINT](https://megalinter.io/latest/descriptors/credentials_secretlint/)
- [CSHARP_CSHARPIER](https://megalinter.io/latest/descriptors/csharp_csharpier/)
- [CSHARP_DOTNET_FORMAT](https://megalinter.io/latest/descriptors/csharp_dotnet_format/)
- [CSHARP_ROSLYNATOR](https://megalinter.io/latest/descriptors/csharp_roslynator/)
- [CSS_BIOME](https://megalinter.io/latest/descriptors/css_biome/)
- [CSS_SCSSLINT](https://megalinter.io/latest/descriptors/css_scsslint/)
- [CSS_SCSS_LINT](https://megalinter.io/latest/descriptors/css_scss_lint/)
- [CSS_STYLELINT](https://megalinter.io/latest/descriptors/css_stylelint/)
- [C_CLANG_FORMAT](https://megalinter.io/latest/descriptors/c_clang_format/)
- [C_CPPCHECK](https://megalinter.io/latest/descriptors/c_cppcheck/)
- [C_CPPLINT](https://megalinter.io/latest/descriptors/c_cpplint/)
- [DART_DARTANALYZER](https://megalinter.io/latest/descriptors/dart_dartanalyzer/)
- [DOCKERFILE_DOCKERFILELINT](https://megalinter.io/latest/descriptors/dockerfile_dockerfilelint/)
- [DOCKERFILE_HADOLINT](https://megalinter.io/latest/descriptors/dockerfile_hadolint/)
- [EDITORCONFIG_EDITORCONFIG_CHECKER](https://megalinter.io/latest/descriptors/editorconfig_editorconfig_checker/)
- [ENV_DOTENV_LINTER](https://megalinter.io/latest/descriptors/env_dotenv_linter/)
- [GHERKIN_GHERKIN_LINT](https://megalinter.io/latest/descriptors/gherkin_gherkin_lint/)
- [GIT_GIT_DIFF](https://megalinter.io/latest/descriptors/git_git_diff/)
- [GO_GOLANGCI_LINT](https://megalinter.io/latest/descriptors/go_golangci_lint/)
- [GO_REVIVE](https://megalinter.io/latest/descriptors/go_revive/)
- [GRAPHQL_BIOME](https://megalinter.io/latest/descriptors/graphql_biome/)
- [GRAPHQL_GRAPHQL_SCHEMA_LINTER](https://megalinter.io/latest/descriptors/graphql_graphql_schema_linter/)
- [GROOVY_NPM_GROOVY_LINT](https://megalinter.io/latest/descriptors/groovy_npm_groovy_lint/)
- [HTML_DJLINT](https://megalinter.io/latest/descriptors/html_djlint/)
- [HTML_HTMLHINT](https://megalinter.io/latest/descriptors/html_htmlhint/)
- [JAVASCRIPT_BIOME](https://megalinter.io/latest/descriptors/javascript_biome/)
- [JAVASCRIPT_ES](https://megalinter.io/latest/descriptors/javascript_es/)
- [JAVASCRIPT_PRETTIER](https://megalinter.io/latest/descriptors/javascript_prettier/)
- [JAVASCRIPT_STANDARD](https://megalinter.io/latest/descriptors/javascript_standard/)
- [JAVA_CHECKSTYLE](https://megalinter.io/latest/descriptors/java_checkstyle/)
- [JAVA_PMD](https://megalinter.io/latest/descriptors/java_pmd/)
- [JSON_BIOME](https://megalinter.io/latest/descriptors/json_biome/)
- [JSON_ESLINT_PLUGIN_JSONC](https://megalinter.io/latest/descriptors/json_eslint_plugin_jsonc/)
- [JSON_JSONLINT](https://megalinter.io/latest/descriptors/json_jsonlint/)
- [JSON_NPM_PACKAGE_JSON_LINT](https://megalinter.io/latest/descriptors/json_npm_package_json_lint/)
- [JSON_PRETTIER](https://megalinter.io/latest/descriptors/json_prettier/)
- [JSON_V8R](https://megalinter.io/latest/descriptors/json_v8r/)
- [JSX_BIOME](https://megalinter.io/latest/descriptors/jsx_biome/)
- [JSX_ESLINT](https://megalinter.io/latest/descriptors/jsx_eslint/)
- [KOTLIN_DETEKT](https://megalinter.io/latest/descriptors/kotlin_detekt/)
- [KOTLIN_KTLINT](https://megalinter.io/latest/descriptors/kotlin_ktlint/)
- [KUBERNETES_HELM](https://megalinter.io/latest/descriptors/kubernetes_helm/)
- [KUBERNETES_KUBECONFORM](https://megalinter.io/latest/descriptors/kubernetes_kubeconform/)
- [KUBERNETES_KUBESCAPE](https://megalinter.io/latest/descriptors/kubernetes_kubescape/)
- [KUBERNETES_KUBEVAL](https://megalinter.io/latest/descriptors/kubernetes_kubeval/)
- [LATEX_CHKTEX](https://megalinter.io/latest/descriptors/latex_chktex/)
- [LUA_LUACHECK](https://megalinter.io/latest/descriptors/lua_luacheck/)
- [LUA_SELENE](https://megalinter.io/latest/descriptors/lua_selene/)
- [LUA_STYLUA](https://megalinter.io/latest/descriptors/lua_stylua/)
- [MAKEFILE_CHECKMAKE](https://megalinter.io/latest/descriptors/makefile_checkmake/)
- [MARKDOWN_MARKDOWNLINT](https://megalinter.io/latest/descriptors/markdown_markdownlint/)
- [MARKDOWN_MARKDOWN_LINK_CHECK](https://megalinter.io/latest/descriptors/markdown_markdown_link_check/)
- [MARKDOWN_MARKDOWN_TABLE_FORMATTER](https://megalinter.io/latest/descriptors/markdown_markdown_table_formatter/)
- [MARKDOWN_REMARK_LINT](https://megalinter.io/latest/descriptors/markdown_remark_lint/)
- [MARKDOWN_RUMDL](https://megalinter.io/latest/descriptors/markdown_rumdl/)
- [OPENAPI_SPECTRAL](https://megalinter.io/latest/descriptors/openapi_spectral/)
- [PERL_PERLCRITIC](https://megalinter.io/latest/descriptors/perl_perlcritic/)
- [PHP_BUILTIN](https://megalinter.io/latest/descriptors/php_builtin/)
- [PHP_PHPCS](https://megalinter.io/latest/descriptors/php_phpcs/)
- [PHP_PHPCSFIXER](https://megalinter.io/latest/descriptors/php_phpcsfixer/)
- [PHP_PHPLINT](https://megalinter.io/latest/descriptors/php_phplint/)
- [PHP_PHPSTAN](https://megalinter.io/latest/descriptors/php_phpstan/)
- [PHP_PSALM](https://megalinter.io/latest/descriptors/php_psalm/)
- [POWERSHELL_POWERSHELL](https://megalinter.io/latest/descriptors/powershell_powershell/)
- [POWERSHELL_POWERSHELL_FORMATTER](https://megalinter.io/latest/descriptors/powershell_powershell_formatter/)
- [PROTOBUF_PROTOLINT](https://megalinter.io/latest/descriptors/protobuf_protolint/)
- [PUPPET_PUPPET_LINT](https://megalinter.io/latest/descriptors/puppet_puppet_lint/)
- [PYTHON_BANDIT](https://megalinter.io/latest/descriptors/python_bandit/)
- [PYTHON_BLACK](https://megalinter.io/latest/descriptors/python_black/)
- [PYTHON_FLAKE8](https://megalinter.io/latest/descriptors/python_flake8/)
- [PYTHON_ISORT](https://megalinter.io/latest/descriptors/python_isort/)
- [PYTHON_MYPY](https://megalinter.io/latest/descriptors/python_mypy/)
- [PYTHON_NBQA_MYPY](https://megalinter.io/latest/descriptors/python_nbqa_mypy/)
- [PYTHON_PYLINT](https://megalinter.io/latest/descriptors/python_pylint/)
- [PYTHON_PYRIGHT](https://megalinter.io/latest/descriptors/python_pyright/)
- [PYTHON_RUFF](https://megalinter.io/latest/descriptors/python_ruff/)
- [PYTHON_RUFF_FORMAT](https://megalinter.io/latest/descriptors/python_ruff_format/)
- [RAKU_RAKU](https://megalinter.io/latest/descriptors/raku_raku/)
- [REPOSITORY_BETTERLEAKS](https://megalinter.io/latest/descriptors/repository_betterleaks/)
- [REPOSITORY_CHECKOV](https://megalinter.io/latest/descriptors/repository_checkov/)
- [REPOSITORY_DEVSKIM](https://megalinter.io/latest/descriptors/repository_devskim/)
- [REPOSITORY_DUSTILOCK](https://megalinter.io/latest/descriptors/repository_dustilock/)
- [REPOSITORY_GITLEAKS](https://megalinter.io/latest/descriptors/repository_gitleaks/)
- [REPOSITORY_GIT_DIFF](https://megalinter.io/latest/descriptors/repository_git_diff/)
- [REPOSITORY_GOODCHECK](https://megalinter.io/latest/descriptors/repository_goodcheck/)
- [REPOSITORY_GRYPE](https://megalinter.io/latest/descriptors/repository_grype/)
- [REPOSITORY_KICS](https://megalinter.io/latest/descriptors/repository_kics/)
- [REPOSITORY_KINGFISHER](https://megalinter.io/latest/descriptors/repository_kingfisher/)
- [REPOSITORY_LS_LINT](https://megalinter.io/latest/descriptors/repository_ls_lint/)
- [REPOSITORY_OSV_SCANNER](https://megalinter.io/latest/descriptors/repository_osv_scanner/)
- [REPOSITORY_SECRETLINT](https://megalinter.io/latest/descriptors/repository_secretlint/)
- [REPOSITORY_SEMGREP](https://megalinter.io/latest/descriptors/repository_semgrep/)
- [REPOSITORY_SYFT](https://megalinter.io/latest/descriptors/repository_syft/)
- [REPOSITORY_TRIVY](https://megalinter.io/latest/descriptors/repository_trivy/)
- [REPOSITORY_TRIVY_SBOM](https://megalinter.io/latest/descriptors/repository_trivy_sbom/)
- [REPOSITORY_TRUFFLEHOG](https://megalinter.io/latest/descriptors/repository_trufflehog/)
- [ROBOTFRAMEWORK_ROBOCOP](https://megalinter.io/latest/descriptors/robotframework_robocop/)
- [RST_RSTCHECK](https://megalinter.io/latest/descriptors/rst_rstcheck/)
- [RST_RSTFMT](https://megalinter.io/latest/descriptors/rst_rstfmt/)
- [RST_RST_LINT](https://megalinter.io/latest/descriptors/rst_rst_lint/)
- [RUBY_RUBOCOP](https://megalinter.io/latest/descriptors/ruby_rubocop/)
- [RUST_CLIPPY](https://megalinter.io/latest/descriptors/rust_clippy/)
- [R_LINTR](https://megalinter.io/latest/descriptors/r_lintr/)
- [SALESFORCE_CODE_ANALYZER_APEX](https://megalinter.io/latest/descriptors/salesforce_code_analyzer_apex/)
- [SALESFORCE_CODE_ANALYZER_APEXGURU](https://megalinter.io/latest/descriptors/salesforce_code_analyzer_apexguru/)
- [SALESFORCE_CODE_ANALYZER_AURA](https://megalinter.io/latest/descriptors/salesforce_code_analyzer_aura/)
- [SALESFORCE_CODE_ANALYZER_FLOW](https://megalinter.io/latest/descriptors/salesforce_code_analyzer_flow/)
- [SALESFORCE_CODE_ANALYZER_LWC](https://megalinter.io/latest/descriptors/salesforce_code_analyzer_lwc/)
- [SALESFORCE_LIGHTNING_FLOW_SCANNER](https://megalinter.io/latest/descriptors/salesforce_lightning_flow_scanner/)
- [SALESFORCE_SFDX_SCANNER_APEX](https://megalinter.io/latest/descriptors/salesforce_sfdx_scanner_apex/)
- [SALESFORCE_SFDX_SCANNER_AURA](https://megalinter.io/latest/descriptors/salesforce_sfdx_scanner_aura/)
- [SALESFORCE_SFDX_SCANNER_LWC](https://megalinter.io/latest/descriptors/salesforce_sfdx_scanner_lwc/)
- [SCALA_SCALAFIX](https://megalinter.io/latest/descriptors/scala_scalafix/)
- [SNAKEMAKE_LINT](https://megalinter.io/latest/descriptors/snakemake_lint/)
- [SNAKEMAKE_SNAKEFMT](https://megalinter.io/latest/descriptors/snakemake_snakefmt/)
- [SPELL_CODESPELL](https://megalinter.io/latest/descriptors/spell_codespell/)
- [SPELL_CSPELL](https://megalinter.io/latest/descriptors/spell_cspell/)
- [SPELL_LYCHEE](https://megalinter.io/latest/descriptors/spell_lychee/)
- [SPELL_MISSPELL](https://megalinter.io/latest/descriptors/spell_misspell/)
- [SPELL_PROSELINT](https://megalinter.io/latest/descriptors/spell_proselint/)
- [SPELL_VALE](https://megalinter.io/latest/descriptors/spell_vale/)
- [SQL_SQLFLUFF](https://megalinter.io/latest/descriptors/sql_sqlfluff/)
- [SQL_SQL_LINT](https://megalinter.io/latest/descriptors/sql_sql_lint/)
- [SQL_TSQLLINT](https://megalinter.io/latest/descriptors/sql_tsqllint/)
- [SWIFT_SWIFTLINT](https://megalinter.io/latest/descriptors/swift_swiftlint/)
- [TEKTON_TEKTON_LINT](https://megalinter.io/latest/descriptors/tekton_tekton_lint/)
- [TERRAFORM_CHECKOV](https://megalinter.io/latest/descriptors/terraform_checkov/)
- [TERRAFORM_KICS](https://megalinter.io/latest/descriptors/terraform_kics/)
- [TERRAFORM_TERRAFORM_FMT](https://megalinter.io/latest/descriptors/terraform_terraform_fmt/)
- [TERRAFORM_TERRAGRUNT](https://megalinter.io/latest/descriptors/terraform_terragrunt/)
- [TERRAFORM_TERRASCAN](https://megalinter.io/latest/descriptors/terraform_terrascan/)
- [TERRAFORM_TFLINT](https://megalinter.io/latest/descriptors/terraform_tflint/)
- [TERRAFORM_TOFU_FMT](https://megalinter.io/latest/descriptors/terraform_tofu_fmt/)
- [TERRAFORM_TOFU_VALIDATE](https://megalinter.io/latest/descriptors/terraform_tofu_validate/)
- [TSX_BIOME](https://megalinter.io/latest/descriptors/tsx_biome/)
- [TSX_ESLINT](https://megalinter.io/latest/descriptors/tsx_eslint/)
- [TYPESCRIPT_BIOME](https://megalinter.io/latest/descriptors/typescript_biome/)
- [TYPESCRIPT_ES](https://megalinter.io/latest/descriptors/typescript_es/)
- [TYPESCRIPT_PRETTIER](https://megalinter.io/latest/descriptors/typescript_prettier/)
- [TYPESCRIPT_STANDARD](https://megalinter.io/latest/descriptors/typescript_standard/)
- [VBDOTNET_DOTNET_FORMAT](https://megalinter.io/latest/descriptors/vbdotnet_dotnet_format/)
- [XML_XMLLINT](https://megalinter.io/latest/descriptors/xml_xmllint/)
- [YAML_PRETTIER](https://megalinter.io/latest/descriptors/yaml_prettier/)
- [YAML_V8R](https://megalinter.io/latest/descriptors/yaml_v8r/)
- [YAML_YAMLLINT](https://megalinter.io/latest/descriptors/yaml_yamllint/)

## How to use the custom flavor

Follow [MegaLinter installation guide](https://megalinter.io/latest/install-assisted/), and replace related elements in the workflow.

- **GitHub Action**: On MegaLinter step in `.github/workflows/mega-linter.yml`, define `uses: anwarani-ext-ks/megalinter-custom-flavor-arm64@main`
- **Docker image**: Replace official MegaLinter image with `ghcr.io/anwarani-ext-ks/megalinter-custom-flavor-arm64/megalinter-custom-flavor:latest`

## How the flavor is generated and updated

This custom flavor is automatically kept up to date with MegaLinter releases:

1. **Automatic version sync**: The `check-new-megalinter-version` workflow runs daily, checks for new MegaLinter releases, and automatically creates matching releases in this repository.

2. **Automated builds**: Each release triggers the `megalinter-custom-flavor-builder` workflow, which:
   - Builds a Docker image with only the selected linters
   - Publishes to GitHub Container Registry (ghcr.io)
   - Optionally publishes to Docker Hub (if credentials are configured)

3. **Available image tags**:
   - Release tags (e.g., `v9.0.0`): Built from MegaLinter releases
   - `beta` tag: Built from non-main branch pushes for testing
   - `latest` tag: Points to the most recent release

## Configuration requirements

### Optional: Personal Access Token (use with care)

> **Security warning**: Using a Personal Access Token (PAT) is **not recommended**. Open-source projects have been heavily targeted by supply-chain attacks in recent months, and a leaked or compromised PAT can give attackers broad write access to your repository — better safe than sorry!
> If you do not need fully automatic daily version sync, you can skip the PAT entirely and trigger the `check-new-megalinter-version` workflow manually whenever you want to upgrade.

If you decide automatic daily releases are worth the trade-off, configure a `PAT_TOKEN` secret as a **repository-scoped fine-grained token** with:

- **Repository access**: Only select repositories (select this repository)
- **Repository permissions**:
  - Contents: Read and write
  - Actions: Read and write

Rotate the token regularly.

See the [Custom Flavors documentation](https://megalinter.io/beta/custom-flavors/) for detailed setup instructions.

### Optional: Docker Hub publishing

To publish to Docker Hub in addition to ghcr.io, configure:

- `DOCKERHUB_REPO` variable (e.g., your Docker Hub username)
- `DOCKERHUB_USERNAME` secret
- `DOCKERHUB_PASSWORD` secret

## How to generate the flavor manually

If you need to manually trigger a build:

1. **Create a GitHub release**: Creates a versioned build matching the tag name (e.g., `v9.0.0`)
2. **Push to any branch** (except main): Builds a `beta` tagged image for testing
3. **Manually run the workflow**: Go to Actions > Build & Push MegaLinter Custom Flavor > Run workflow

See [full Custom Flavors documentation](https://megalinter.io/beta/custom-flavors/).

## License

A MegaLinter custom flavor is still MegaLinter: this repository and the Docker image it publishes are covered by the [AGPL-3.0 license](https://github.com/oxsecurity/megalinter/blob/main/LICENSE).

The published image is built from the official MegaLinter image and bundles MegaLinter, whose source is available at [oxsecurity/megalinter](https://github.com/oxsecurity/megalinter).

[![MegaLinter is provided by OX Security](https://raw.githubusercontent.com/oxsecurity/megalinter/main/docs/assets/images/ox-banner.png)](https://www.ox.security/?ref=megalinter)
