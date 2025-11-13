# GitHub Connection Test

## Overview
This is a simple Node.js web application imported from GitHub (reiya1011/github-connection). The original repository was minimal (just a test README), so a basic web server has been set up to demonstrate the Replit environment.

## Recent Changes
- **2025-11-13**: Initial Replit setup
  - Created basic Node.js HTTP server
  - Configured to run on port 5000 with host 0.0.0.0
  - Set up workflow for automatic server startup
  - Added cache control headers for proper preview updates

## Project Architecture
- **Language**: Node.js (native HTTP module, no frameworks)
- **Port**: 5000 (frontend web server)
- **Host**: 0.0.0.0 (required for Replit proxy)
- **Structure**:
  - `index.js` - Main HTTP server
  - `package.json` - Node.js configuration
  - `test` - Original test file from GitHub repo
  - `README.md` - Original repository README

## Running the Project
The server starts automatically via the configured workflow. It serves a simple HTML page at the root URL.
