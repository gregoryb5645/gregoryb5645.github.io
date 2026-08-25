VITRACELL — EXACT GODADDY WEBSITE INSTALLATION
================================================

IMPORTANT
---------
Your GoDaddy account currently shows "Websites + Marketing Basic." That product
cannot import this complete custom website. For an exact reproduction, add a
Linux Web Hosting plan with cPanel. Do not cancel your current website and do
not change DNS until the new hosting plan is active and the uploaded site has
been tested.

WHAT IS IN THE ZIP
------------------
index.html       Complete VitraCell webpage
styles.css       Exact styling and mobile behavior
assets/          Site imagery and logo
favicon.svg      Browser icon
og.png           Social-sharing image
robots.txt       Search-engine instructions
sitemap.xml      Search-engine sitemap

STEP 1 — BUY THE CORRECT GODADDY PRODUCT
----------------------------------------
1. Sign in to GoDaddy in your normal browser.
2. Open Products or All Products and Services.
3. Add a Linux Web Hosting plan that includes cPanel and SSL.
4. A basic single-site plan is sufficient for this static VitraCell website.
5. Keep "Websites + Marketing Basic" active for now.

STEP 2 — SET UP THE HOSTING ACCOUNT
-----------------------------------
1. Return to My Products.
2. Under Web Hosting, select Set Up or Manage.
3. Choose the existing domain vitracell.io when GoDaddy asks which domain to use.
4. Complete the cPanel setup prompts.
5. Wait until the hosting dashboard and cPanel are available.

STEP 3 — BACK UP THE CURRENT SITE
---------------------------------
1. Open the current Websites + Marketing editor.
2. Use its site-history or backup option if available.
3. Do not cancel or delete that product yet.

STEP 4 — UPLOAD THE ZIP
-----------------------
1. In the new Web Hosting dashboard, select cPanel Admin.
2. Open File Manager.
3. Open the document root for vitracell.io. On a primary cPanel domain this is
   usually public_html. Use the document root shown by cPanel if it differs.
4. If public_html contains a default index.html or placeholder page, rename it
   to index-backup.html. Do not delete email or system folders.
5. Select Upload and upload VitraCell-GoDaddy-Static-Site.zip.
6. Return to File Manager, select the ZIP, and choose Extract.
7. If extraction creates a folder named VitraCell-GoDaddy-Static-Site, open it,
   select all contents, and move them directly into the domain document root.
8. Confirm that index.html, styles.css, favicon.svg, og.png, robots.txt,
   sitemap.xml, and the assets folder are all directly in the document root.

STEP 5 — TEST BEFORE SWITCHING DNS
---------------------------------
1. Use cPanel's temporary URL or Preview Website option if it is available.
2. If no preview is provided, contact GoDaddy support and ask them to confirm
   that vitracell.io is attached to the correct cPanel document root.
3. Test the page on desktop and mobile.
4. Click Technology, Development, Partnerships, and Company in the navigation.
5. Click a collaboration button and confirm it opens a new email addressed to
   Gregory.Moore@VitraCell.io.
6. Confirm that all four images load.

STEP 6 — CONNECT VITRACELL.IO
-----------------------------
1. In GoDaddy, open Domains, select vitracell.io, and open DNS.
2. In cPanel or the hosting dashboard, locate the exact IP address and DNS
   values assigned to the hosting account.
3. Change only the website records requested by GoDaddy hosting—normally the
   A record for @ and the CNAME for www.
4. Do not change or delete MX, SPF, DKIM, DMARC, TXT, autodiscover, or other
   email-related records. Those records keep your email working.
5. Save the changes. DNS updates may take several hours and can occasionally
   take up to 48 hours worldwide.

STEP 7 — ENABLE HTTPS
---------------------
1. In the hosting dashboard, verify that SSL is enabled for both vitracell.io
   and www.vitracell.io.
2. Open https://vitracell.io in a private/incognito browser window.
3. Confirm that the browser shows a secure connection and no certificate error.
4. Confirm that http://vitracell.io redirects to https://vitracell.io.

STEP 8 — FINAL CHECK AND CLEANUP
-------------------------------
1. Test the live site on a phone and a desktop computer.
2. Verify the images, navigation, email links, spelling, and footer.
3. Reconfirm that company email still sends and receives normally.
4. Keep the old Websites + Marketing product for several days as a fallback.
5. After the new site has been stable, you may cancel Websites + Marketing
   Basic if it is no longer needed. Keep the domain registration and cPanel
   hosting active.

IF YOU NEED GODADDY SUPPORT
---------------------------
Say: "I have a static HTML/CSS website ZIP. I need Linux Web Hosting with cPanel,
I need vitracell.io attached to its document root, and I need to preserve all
existing email DNS records. Please help me preview the uploaded site before I
change the web A and www CNAME records."

ROLLBACK
--------
If the new site does not work, restore the previous website A and www CNAME
records from your DNS history or the values you recorded before the switch.
Do not change email records during rollback.
