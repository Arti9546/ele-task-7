# ele-task-7
# Task Objective
The objective was to audit the installed browser extensions to identify and remove potentially harmful, suspicious, or unused add-ons, thereby mitigating a significant client-side security risk and reducing the browser's attack surface.

## 🛠 Tool Used
* **Microsoft Edge (Web Browser):** Used to access the extension/add-ons manager.

## ⚙️ Audit Findings and Action Taken

The audit focused on identifying extensions with excessive permissions or an unknown origin.

| Category | Extension Name | Action Taken | Rationale for Action |
| :--- | :--- | :--- | :--- |
| **Suspicious** | **Growman** | **Removed** | Unrecognized extension; likely bundled Adware or Spyware. This type of extension often performs **data harvesting** or **unauthorized ad injection**. |
| **Essential** | **Google Docs Offline** | Kept | Verified as essential for core functionality and sourced from a trusted vendor. |

---

## ⚠️ Security Analysis: Threats from Malicious Extensions

The removal of the suspicious extension directly addresses critical client-side threats:

1.  **Data Harvesting:** Malicious extensions can use broad permissions (e.g., "Read and change all data on websites") to capture and transmit **passwords, credit card numbers, and other PII** entered by the user.
2.  **Adware and Hijacking:** They inject unwanted advertisements into legitimate web pages or redirect the user's search results to malicious sites, compromising browsing integrity and exposing the user to secondary malware. 
3.  **Session Hijacking:** By stealing the user's session cookies, the extension can allow an attacker to hijack an authenticated session without ever needing the account password.

##  Conclusion and Best Practices

The audit successfully eliminated a high-risk security vector. The key takeaway from this task is that users must maintain a strict zero-trust policy toward browser add-ons.

* **Best Practice:** Only install extensions from official stores, verify that their requested **permissions are minimal** and justified by their function, and promptly **remove any unused or unfamiliar extensions** to continuously minimize the attack surface.
