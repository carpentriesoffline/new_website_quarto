# Carpentries Offline Website

This website uses Quarto to build using a GitHub Actions workflow: [quarto-publish-example.yml](.github/workflows/quarto-publish-example.yml).

## Local testing and development

Install Quarto following the [Quarto getting started guide](https://quarto.org/docs/get-started/).

```bash
# Linux
sudo apt install ./quarto-1.3.294-linux-amd64.deb
# OSX
brew install quarto
```

Then run:

```bash
quarto preview
```

... to locally preview the site.