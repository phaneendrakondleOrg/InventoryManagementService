# InventoryManagementService

## Security Updates

### CVE-2022-22965 (Spring4Shell) - Fixed
**Date:** October 2025  
**Severity:** CRITICAL (CVSS 9.8)  
**Status:** ✅ Resolved

The project has been updated to address the critical Spring4Shell remote code execution vulnerability (CVE-2022-22965).

**Changes:**
- Upgraded `spring-boot-starter-web` from `2.5.10` to `2.7.18`
- This upgrade brings Spring Framework from `5.3.16` to `5.3.31`
- The patched version eliminates the remote code execution vulnerability affecting Spring Framework versions < 5.3.18

**Verification:**
- ✅ Build successful with upgraded dependencies
- ✅ No known vulnerabilities in upgraded dependencies (verified via GitHub Advisory Database)
- ✅ All existing tests pass