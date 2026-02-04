# Google VRP Auto-Download Test

**⚠️ Security Research Only - Authorized Testing ⚠️**

This repository contains test files for Google Vulnerability Reward Program (VRP) security testing.

## Purpose
Test drive-by download vulnerabilities where files download automatically without user interaction.

## Files
- `index.html` - Test page with meta refresh auto-download
- `chrome_test.zip` - Safe test files (ZIP archive)
- `README.md` - This documentation

## Test Description
The HTML page uses `meta http-equiv="refresh"` to automatically redirect to a ZIP file, testing if browsers allow auto-downloads without user consent.

## Safe Content
All files contain only test data:
- Text files with VRP test information
- JSON configuration files
- Safe JavaScript files
- CSV test data

## Testing Instructions
1. Visit the GitHub Pages URL
2. Observe if `chrome_test.zip` downloads automatically
3. Note browser behavior (block/allow/warning)
4. Document findings for VRP reporting

## VRP Reporting
When reporting to Google VRP:
- Include browser name and version
- Note exact behavior observed
- Include console output if available
- Mention security warnings shown

## Disclaimer
This is for authorized security testing only. Do not use for malicious purposes.
