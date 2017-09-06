---
title: Installation
description: 
position: 3
publish: true
slug: installation
---

# Set Up Your System

## Step 1: Install Node.js

To run {{ site.ns-sk }}, you need to have Node.js installed on your machine. To check whether Node.js is installed on your development machine, you should open a terminal or command prompt and run the `node --version` command. If you get an error, head to [https://nodejs.org/](https://nodejs.org/en/) and download and install the latest [Node.js LTS](https://github.com/nodejs/LTS#lts-schedule) version. We recommend using [Node.js 6.x](https://nodejs.org/dist/latest-v6.x/).

## Step 2: Install the {{ site.ns-cli }}

To run {{ site.ns-sk }}, you need to have {{ site.ns-cli }} version 3.1.3 or greater installed on your machine. To install the latest version of {{ site.ns-cli }} from npm, you should open a terminal or command prompt and run the following command:

<pre class="add-copy-button"><code class="language-terminal">npm install -g nativescript</code></pre>

## Step 3: Install iOS and Android Requirements for Local Builds

> If you plan on using only the Cloud build functionality, you should disregard this step.

When you build with {{ site.ns }}, you are building truly native iOS and Android apps and as such, you need to set up each platform you intend to build for on your development machine.

* [Set up a Windows machine](/start/ns-setup-win)
* [Set up a macOS machine](/start/ns-setup-os-x)
* [Set up a Linux machine](/start/ns-setup-linux)

## Step 4: Download and Install Sidekick

1. Download the installation file appropriate for your operating system:
	* [Windows 64-bit](https://www.nativescript.org/nativescript-sidekick/download-windows-latest)
	* [macOS 64-bit](https://www.nativescript.org/nativescript-sidekick/download-macos-latest)
	* [Linux 64-bit](https://www.nativescript.org/nativescript-sidekick/download-linux-latest)
2. Run the downloaded installable and complete the installation.