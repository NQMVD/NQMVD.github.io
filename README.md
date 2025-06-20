# needs - CLI Tool Landing Page

This is the GitHub Pages landing page for the **needs** CLI tool, hosted at `needs.cli.rs`.

## Overview

The **needs** CLI tool helps developers manage their CLI tool dependencies by:
- Tracking which CLI tools you depend on for your projects
- Installing all needed tools with a single command
- Focusing on modern Rust alternatives to traditional CLI tools

## Custom Domain Setup

The site uses the custom domain `needs.cli.rs` which is:
- Registered through the cli.rs subdomain service
- Configured via the `CNAME` file in this repository
- Points to `NQMVD.github.io` via DNS

## About the needs Tool

The needs CLI tool is designed for developers who want to:
- Use modern Rust CLI tools (ripgrep, fd, bat, etc.) instead of traditional ones
- Keep track of their CLI tool dependencies across projects
- Quickly set up new development environments
- Batch install all their needed tools

### Example Usage

```bash
# Install the needs CLI tool
cargo install needs

# Add tools to your needs list
needs add ripgrep  # Fast text search
needs add fd       # Better find
needs add bat      # Cat with syntax highlighting

# Install all your needed tools
needs install
```

## Development Status

The needs CLI tool is currently in development. This landing page serves as:
- An introduction to the project
- Installation instructions
- Feature overview
- Link to the GitHub repository

## File Structure

```
NQMVD.github.io/
├── index.html          # Landing page
├── CNAME               # Custom domain (needs.cli.rs)
└── README.md           # This file
```

## Domain Troubleshooting

If `needs.cli.rs` isn't working:
1. Check that `CNAME` file contains `needs.cli.rs`
2. Verify the cli.rs subdomain registration is active
3. Allow time for DNS propagation (up to 48 hours)
4. Check GitHub Pages is enabled in repository settings

## Contributing

This is a simple landing page for the needs CLI tool. The main development happens in the [needs repository](https://github.com/NQMVD/needs).

To update the landing page:
1. Edit `index.html` directly
2. Commit and push changes
3. GitHub Pages will automatically deploy