---
name: Awsome Rust Repo
about: Request for Adding adding your Missing Repo
title: "[Awsome Rust Repos] "
labels: repo-add
assignees: 'samirparhi-dev'
---
body:
  - type: markdown
    attributes:
      value: |
        Request for your Favorite Repo 🧪

  - type: input
    id: name 🖋️
    attributes:
      label: "name"
      placeholder: "Please provide shortname of the Repo (Example: rust)"
    validations:
      required: true

  - type: textarea
    id: repo_description ⿳
    attributes:
      label: "repo_description"
      description: "Description of the Repo "
      placeholder: "(Example: Empowering everyone to build reliable and efficient software.)"
    validations:
      required: true

  - type: input
    id: git_url
    attributes:
      label: "git_url"
      description: "git URL for the repo"🌎
      placeholder: "example:git://github.com/rust-lang/rust.git "
    validations:
      required: true

  - type: input
    id: repo_license
    attributes:
      label: "repo_license"
      description: "License info of the Repo📄"
      placeholder: "Example: "Apache", MIT"
    validations:
      required: true

  - type: input
    id: url
    attributes:
      label: "url"
      description: "URL of the tool if has a website else provide git URL🤗"
      placeholder: "Example: https://github.com/rust-lang/rust"
    validations:
      required: true

  - type: dropdown
    id: use_case
    attributes:
      description: "Why is this Repo Used for 🪄"
      placeholder: "Example : Ai, ML, System Programing"
      label: "use_case"
      options:
        - AI/ML
        - System Programing
        - Crypto/ Decentralization
        - Gaming/Entertainment
        - Others
    validations:
      required: true

