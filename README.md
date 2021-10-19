# Action-gpg

This action sets up a GPG signature for use in actions so you can have verified commits pushed from your actions.


## Requirement

Your runner should provide a valid gpg installation.

## Usage

See [action.yml](action.yml)

Basic:

```yaml
steps:
  - name: Checkout repository
    uses: actions/checkout@v2
    with:
        token: ${{ secrets.GITHUB_TOKEN }}

  - name: Enable GPG
    uses: cresh-io/action-gpg@v1
    with:
        gpg-passphrase: "${{ secrets.CI_GPG_PASSPHRASE }}"
        gpg-sign-key: "${{ secrets.CI_GPG_SIGN_KEY }}"
        git-email: "${{ secrets.CI_USER_EMAIL }}"
        git-username: "${{ secrets.CI_USER_NAME }}"

  # See https://github.com/cresh-io/action-conventional-release
  - name: Create release
    uses: cresh-io/action-conventional-release@v1
    with:
      custom-tag: "${{ github.event.inputs.tags }}"
      github-access-token: "${{ secrets.GITHUB_TOKEN }}"
```

## License
The scripts and documentation in this project are released under the [MIT License](LICENSE)