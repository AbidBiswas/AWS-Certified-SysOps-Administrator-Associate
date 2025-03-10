$$
\huge \text{\color{orange}{AWS Certified SysOps Administrator-Associate}}
$$

## 🔗 Connect Windows CMD with AWS Instance

To connect your **Windows Command Prompt (CMD)** to an AWS EC2 instance, use the following command:

> **Command:**
> ```
> ssh -i DemoKeyPair.pem ec2-user@3.133.112.164
> ```

### ✅ **Prerequisites**
- **Install OpenSSH** (available by default in Windows 10/11, but verify using `ssh -V` in CMD).
- **Place** `DemoKeyPair.pem` in an accessible directory (e.g., `C:\Users\YourUser\`).
- **Use Git Bash or PowerShell** if CMD doesn't recognize `ssh`.

### ⚡ **Steps to Connect**
1. Open **Command Prompt (CMD)** or **PowerShell**.
2. Navigate to the directory where the `.pem` file is located using:
   ```cmd
   cd C:\Users\YourUser\Downloads
like this we have to edit





