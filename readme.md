<h1>
How to put an HTML website online (on the Internet) 
</h1>
<a href="https://www.youtube.com/watch?v=p1QU3kLFPdg"> Youtube Link</a>

<h2>
How forthrightfilms.com connects to your site
</h2>
<ul>
<li> Client is on a browser </li>
<li> Talks with Github with has a Web Server (a computer w/ some software on it)</li>
<li> During a request, a browser contains the IP Address of your site and hands it to Webserver </li>
<li> Using IP address for requests is hard to remember, so the Domain Registrar (e.g., NameCheap, GoDaddy) can map Domain name (e.g., forthrightfilms.com) to a specific IP address. This mapping is calld a <strong> Domain Name System (DNS) Record</strong>. </li>
</ul>

<h3>
DNS Info
</h3>

<ul>
<li><strong>Type</strong>: E.g.,Type A-Record (stands for "Address Record") are the simplest DNS record. They link Domain Name to IP Address.</li>
<li><strong>TTL</strong>: How long record updates take to take effect across the internet. Short TTL = Faster to updated, Long TTL = more efficient but changes take longer. We chose 5 min which is 300 seconds</li>
<li> <strong> Host</strong>: For subdomain. Helpful for sub-website on your site. To leave blank on namecheap, put @</li>
<li> <strong> Value </strong>: IP Address. Can be found via DNS Lookup Tool: <a href="https://mxtoolbox.com/DNSLookup.aspx"> MxToolbox</a>. We can use the website Github Pages gives us for free and link our Domain to those addresses. So, input something like: manoloc0.github.io and add a DNS record for each.</li>
<strong>CNAME</strong>: Github pages also recommends to add a www subname record with a CNAME record. This links two domain names without knowing their IP addresses. For this project, I put https://manoloc0.github.io in the value of the CNAME.
</ul>

<strong> Https</strong>: Once your site has a certificate issued by the Name Registrar, make sure to enable HTTPS on Github pages to encrypt all data in packets.


