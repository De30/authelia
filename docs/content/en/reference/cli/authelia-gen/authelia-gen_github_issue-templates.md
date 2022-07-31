---
title: "authelia-gen github issue-templates"
description: "Reference for the authelia-gen github issue-templates command."
lead: ""
date: 2022-07-31T12:55:34+10:00
draft: false
images: []
menu:
  reference:
    parent: "cli-authelia-gen"
weight: 330
toc: true
---

## authelia-gen github issue-templates

Generate GitHub issue templates

```
authelia-gen github issue-templates [flags]
```

### Options

```
  -h, --help   help for issue-templates
```

### Options inherited from parent commands

```
  -C, --cwd string                        Sets the CWD for git commands
      --dir.docs.cli-reference string     The directory to store the markdown in (default "docs/content/en/reference/cli")
      --dir.docs.content string           The directory with the docs content (default "docs/content")
      --dir.locales string                The locales directory in relation to the root (default "internal/server/locales")
  -d, --dir.root string                   The repository root (default "./")
  -X, --exclude strings                   Sets the names of excluded generators
      --file.bug-report string            Sets the path of the bug report issue template file (default ".github/ISSUE_TEMPLATE/bug-report.yml")
      --file.docs.data.languages string   The languages docs data file in relation to the docs data folder (default "docs/data/languages.json")
      --file.feature-request string       Sets the path of the feature request issue template file (default ".github/ISSUE_TEMPLATE/feature-request.yml")
      --file.web-i18n string              The i18n typescript configuration file in relation to the root (default "web/src/i18n/index.ts")
      --versions int                      the maximum number of minor versions to list in output templates (default 5)
```

### SEE ALSO

* [authelia-gen github](authelia-gen_github.md)	 - Generate GitHub files
* [authelia-gen github issue-templates bug-report](authelia-gen_github_issue-templates_bug-report.md)	 - Generate GitHub bug report issue template
* [authelia-gen github issue-templates feature-request](authelia-gen_github_issue-templates_feature-request.md)	 - Generate GitHub feature request issue template

###### Auto generated by spf13/cobra on 31-Jul-2022