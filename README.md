# cloudflare-realip

## Overview
This repository provides shell scripts and utilities for handling real IP addresses when operating behind Cloudflare. When using Cloudflare’s proxy service, the actual client IP can be masked, which may impact logging, analytics, and security configurations. The scripts here help retrieve and manage the genuine client IP, ensuring your systems work seamlessly with Cloudflare.

## Features
- **Extract Real IP**: Automatically fetch the original client IP from Cloudflare headers.
- **Simple Shell Scripts**: Lightweight and easily customizable scripts for quick integration.
- **Cloudflare Compatibility**: Designed to work with standard Cloudflare proxy setups.
