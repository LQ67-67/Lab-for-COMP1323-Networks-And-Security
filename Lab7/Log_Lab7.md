# 1. Namp Scan
### 🍎 Mac OS Command Line Guide

**1. Setup Environment (Run only once)**
```bash
# Install Docker and Nmap (requires Homebrew to be installed first)
brew install --cask docker
brew install nmap
```

**2. Start the Target Machine (Juice Shop)**
*Open the first Terminal window, run this command, and leave the window open:*
```bash
docker run --rm -p 3000:3000 bkimminich/juice-shop
```

**3. And then using web browser to get [http://localhost:3000]**

**4. Run Nmap Scan (Activity 1)**
*Open a **second (new)** Terminal window, run this command, and take a screenshot:*
```bash
nmap -sV localhost
```

**5. Clean Up (After finishing the lab)**
*Run this command in the second terminal to shut down the background target machine:*
```bash
docker stop $(docker ps -a -q)
```

---

### Windows OS Command Line Guide

**1. Setup Environment (Run only once)**
*   Downloading Docker: [https://www.docker.com/products/docker-desktop/]
*   Downloading Namp: [https://nmap.org/download.html]

**2. Start the Target Machine (Juice Shop)**
*Open the first PowerShell or CMD window, run this command, and leave the window open:*
```powershell
docker run --rm -p 3000:3000 bkimminich/juice-shop
```

**3. And then using web browser to get [http://localhost:3000]**

**4. Run Nmap Scan (Activity 1)**
*Open the **second (new)** PowerShell or CMD window, run this command, and take a screenshot:*
```powershell
nmap -sV localhost
```
*(Note: If `localhost` gives an error, try replacing it with `nmap -sV 127.0.0.1`)*

**5. Clean Up (After finishing the lab)**
*Shut down the background target machine:*
```powershell
docker stop $(docker ps -q)
```

---

# 2. How to use OWASP ZAP 
### Step 1: Download and Install
*   Downloading ZAP: `[https://www.zaproxy.org/download/]`

### Step 2: Start ZAP
1. Simply select **"No, I do not want to persist this session at this moment in time"** and click **Start**.

### Step 3: Run the Automated Scan
*(Make sure ur Docker Juice Shop target is still running in the background!)*
1. On the main Welcome screen in ZAP, click the big **"Automated Scan"** button.
2. In the **"URL to attack"** box, type in our target address: `http://localhost:3000`
3. Click the **"Attack"** button.

### Step 4: Get Screenshots
ZAP will now act like a hacker, crawling through your Juice Shop site and testing for vulnerabilities. Wait a minute or two for it to finish.

**📸 Screenshot 1 (For Activity 1): The Alerts List**
1. Click on the **"Alerts"** tab
2. **Take a screenshot** of this entire ZAP window showing the list of alerts.

**📸 Screenshot 2 (For Activity 2): The Vulnerability Details**
1. In that same "Alerts" list on the left, click on a specific vulnerability with an orange or yellow flag (For example: **"Content Security Policy (CSP) Header Not Set"**).
2. Click the little arrow next to it to expand it, and click on the specific URL link that appears underneath it.
3. **Take a screenshot**
