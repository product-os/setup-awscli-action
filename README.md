# Setup AWS CLI Action

This action installs [AWS CLI version 2](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html) in your GitHub Actions workflow.

## Usage

```yaml
uses: product-os/setup-awscli-action@main
with:
  # AWS CLI release to install (see https://raw.githubusercontent.com/aws/aws-cli/v2/CHANGELOG.rst)
  # Default: '2.15.43'
  version: '2.15.43'

  # Skip using the tool cache and always re-download
  # Default: 'false'
  skip-cache: 'false'
```

## Resources

- <https://docs.aws.amazon.com/cli/latest/userguide/getting-started-version.html>

## Contributing

Please open an issue or submit a pull request with any features, fixes, or changes.
