
# MCP Servers Setup Guide

This repository contains multiple Model Context Protocol (MCP) servers. Follow the instructions below to set up and run each server.

## General Prerequisites
- Node.js (see `package.json` for version) This is for Brave browser. Install using npx was having issues generally.
- npm or yarn
- API keys or credentials for external services (if required)

---

## Server Setup Instructions

### 1. 
- **Dependencies:**
  ```sh
  npm install
  # or
  yarn install
  ```
- **API Keys:** Add required API keys to `mcp.json` as documented in the code.
 ```sh
  "env": {
        "BRAVE_API_KEY": "<YOUR_BRAVE_API_KEY_HERE>"
    }
  ```

## Notes
- Each server may have its own dependencies and configuration files.
- Refer to each server's folder for more specific instructions or documentation.
- If you add a new server, follow the same pattern as above.
