# morvarid-bcheck
This bcheck is designed to detect DOM-based XSS vulnerabilities within panels developed by [Morvarid company](https://ssmorvarid.ir/).

# Running the bcheck 
To run Morvarid-bcheck:
0. `git clone https://github.com/kalhoralireza/morvarid-bcheck.git`
1. Open Burp Suite.
2. Navigate to the `Extensions` panel and select the `BChecks` tab.
3. Click on the "Import" button and navigate to the location where Morvarid-bcheck is downloaded. Select the `morvarid-dom-xss.bcheck` file.
4. Check the checkbox to enable the imported Morvarid-bcheck.
5. You can now scan any target by selecting "Audit checks - BCheck only" from the "Scan configuration" tab within Burp Scanner.
