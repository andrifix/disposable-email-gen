# Disposable Email Domain List Generator

Generates a Go file containing a slice of known disposable email domains fetched from [disposable.github.io](https://disposable.github.io/disposable-email-domains/).

## Installation

There are two ways to install:

**1. Download from Releases:**

Pre-compiled binaries are available on the [**GitHub Releases**](https://github.com/andrifix/disposable-email-gen/releases) page. 

**2. Build from Source:**

```bash
go install github.com/andirifx/disposable-email-gen@latest
```

## Usage

```bash
# Generate domains.go in current directory (package main)
disposable-gen

# Generate pkg/blocklist/domains.go (package blocklist)
disposable-gen pkg/blocklist/domains.go blocklist

# Generate internal/data/domains.go (package main)
disposable-gen internal/data
```
