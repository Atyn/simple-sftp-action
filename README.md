# simple-sftp-action

Simple Action for uploading directories with FTP/SFTP

# Example usage

```yml
jobs:
  - upload:
      - name: Upload build to hosting environment
        uses: Atyn/simple-sftp-action@0.0.2
        with:
          url: sftp://USERNAME:PASSWORD@example.com/remote-directory
          local-directory: build-output
```
