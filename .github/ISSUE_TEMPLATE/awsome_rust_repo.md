name: "Awesome Rust Repo"
description: "Request for adding your missing Rust repo."
title: "[Awesome Rust Repos] "
labels: ["rust-repo-add"]
assignees: ["samirparhi-dev"]

body:
  - type: markdown
      attributes:
      value: |
          ### Request for your Favorite Repo 🧪
          Please fill out the following details to add your favorite Rust repository.

  - type: input
      id: name
      attributes:
      label: "Name"
      placeholder: "Please provide the short name of the repo (Example: rust)"
      validations:
      required: true

  - type: textarea
      id: repo_description
      attributes:
      label: "Repo Description"
      description: "Provide a brief description of the repository."
      placeholder: "(Example: Empowering everyone to build reliable and efficient software.)"
      validations:
      required: true

  - type: input
      id: git_url
      attributes:
      label: "Git URL"
      description: "Git URL for the repo 🌎"
      placeholder: "Example: git://github.com/rust-lang/rust.git"
      validations:
      required: true

  - type: input
      id: repo_license
      attributes:
      label: "License"
      description: "License info of the repository 📄"
      placeholder: "Example: Apache, MIT"
      validations:
      required: true

  - type: input
      id: url
      attributes:
      label: "URL"
      description: "URL of the tool's website or the Git repository 🤗"
      placeholder: "Example: https://github.com/rust-lang/rust"
      validations:
      required: true

  - type: dropdown
      id: use_case
      attributes:
      label: "Use Case"
      description: "Select the primary use case for the repo 🪄"
      options:
          - "AI/ML"
          - "System Programming"
          - "Crypto/Decentralization"
          - "Gaming/Entertainment"
          - "Others"
      validations:
      required: true