# Task-7-Suspicious-Browser-Extensions
Identification and removal of suspicious or unused browser extensions, including risk assessment, permissions review, and documentation of findings.
# Task 7 - Identify and Remove Suspicious Browser Extensions

## Objective
The goal of this task was to review installed browser extensions, identify suspicious or unused ones, evaluate their permissions, and remove potential security risks. This process improves browser performance, enhances privacy, and reduces the attack surface.

## Steps Taken
1. **Opened the Browser Extension Manager**
   - Chrome: `Menu (⋮) → Extensions → Manage Extensions`
   - Firefox: `Menu (☰) → Add-ons and Themes → Extensions`

2. **Reviewed Installed Extensions**
   - Checked extension names, developers, and installation dates.
   - Verified legitimacy by searching online for reviews and official sources.

3. **Checked Permissions**
   - Looked for unnecessary or excessive permissions (e.g., full access to all sites, clipboard access, file system access).

4. **Identified Suspicious Extension**
   - One extension redirected to a Microsoft Azure 404 page when attempting removal, indicating a dead backend service and possible abandonment.
   - Cleared DNS cache using:
     ```
     ipconfig /flushdns
     ```
   - Cleared browser cache to ensure updated removal process.

5. **Removed the Extension**
   - After clearing caches, successfully removed the broken extension.
   - Restarted the browser to confirm removal.

## Suspicious Extension Found
| Extension Name       | Permissions                          | Reason for Removal                                         |
|----------------------|--------------------------------------|------------------------------------------------------------|
| [Example Extension]  | Full access to all websites, clipboard access | Backend server offline (Azure 404), unused, potential risk |

## Outcome
- Browser performance improved.
- Reduced potential attack vectors.
- Better awareness of browser extension security.

## Security Insights
- Extensions with high-level permissions can collect sensitive data.
- Abandoned extensions pose a security risk due to lack of updates.
- Always install from official sources and review permissions before enabling.

## Screenshots
*(Optional — Add before/after screenshots of your extensions page here)*

## Author
Rattan Tiwari
