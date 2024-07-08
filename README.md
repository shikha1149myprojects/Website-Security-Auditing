# Website Security Auditing

The following are some of the benefits of conducting a security audit on a website: 
1. Assess resistance to common security threats like brute force attacks, DDoS attacks, SQL injections, and cross-site scripting (XSS).
2. Spot vulnerabilities early to stop hackers from taking advantage of them.
3. Use access controls and encryption methods to safeguard data.
4. Verify adherence to relevant laws and industry guidelines.

## Tools used
- Burp Suite Professional

Here, I have conducted security auditing of 2 websites using Burp Suite Professional:
- www.vendasta.com
- www.ourshopee.com

 ### Running Your First Scan with Burp Scanner



#### Overview
- **Burp Scanner**: Automated scanner for detecting vulnerabilities, used in Burp Suite Professional and Enterprise Editions.
- **Phases**: 
  1. **Crawling**: Navigates and maps the site.
  2. **Auditing**: Analyzes site behavior for security issues.



#### Steps to Launch an Automated Vulnerability Scan

1. **Open Scan Launcher**
   - Navigate to the **Dashboard** tab.
   - Select **New scan**.

2. **Enter Target URL**
   - In the **URLs to scan** field, enter `your_url_name`.
   - Ensure other settings remain default.

3. **Configure the Scan**
   - Select **Scan configuration**.
   - Choose **Use a preset scan mode** and select **Lightweight** (max 15 minutes).

4. **Launch the Scan**
   - Click **OK** to start the scan.
   - A new task will appear in the **Dashboard**.

5. **Monitor the Crawl**
   - Go to **Target > Site map** to see real-time updates of the discovered content.

6. **View Identified Issues**
   - Check the **Dashboard** tab for the scan status.
   - After crawling, auditing begins.
   - Select the scan from the **Tasks** list and go to the **Issues** tab to see identified vulnerabilities.
   - Review the **Advisory** tab for details and remediation advice.

You've successfully performed your first scan! 

 ### Port Scan of Web Sever

Web servers can scan their ports for open and listening ports and security devices like firewalls. It can offer details about active services, users who own services, anonymous logins, and authentication needs. Unnecessary open ports can produce an extensive attack surface for malevolent users. The results of port scans can be classified as filtered, closed, or open. This method assists in locating possible weak points and vulnerabilities.

#### Links used:
- https://pentest-tools.com/network-vulnerability-scanning/tcp-port-scanner-online-nmap
- https://hackertarget.com/nmap-online-port-scanner/

 ### Security Auditing of Websites using Online Tools

To perform a website security audit, you need to:
1. Set out your scope and aims.
2. Complete a vulnerability assessment.
3. Run a security scan to verify whether a website is blacklisted and check it for malware, errors, and outdated software.
4. Review your site settings.
5. Check data protection and communication.
6. Assess traffic and user accounts.
7. Document your findings and repeat.

#### Links used:
- https://hackertarget.com/nmap-online-port-scanner/
- https://observatory.mozilla.org/
- https://pentest-tools.com/website-vulnerability-scanning/website-scanner
- https://www.immuniweb.com/websec/
- https://www.ssllabs.com/ssltest/
