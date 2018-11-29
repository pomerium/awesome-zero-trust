# Awesome Zero trust

Zero trust is a security model and framework originally described by [John Kindervag in 2010](http://www.virtualstarmedia.com/downloads/Forrester_zero_trust_DNA.pdf). Around that time, as a result of the [Operation Aurora](https://en.wikipedia.org/wiki/Operation_Aurora) breach, Google also began developing BeyondCorp which shared similar ideas. 

## Summary

### Why? 

Zero trust improves on [perimeter](https://www.redbooks.ibm.com/redpapers/pdfs/redp4397.pdf) [security](https://en.wikipedia.org/wiki/Perimeter_Security)'s shortcomings, namely:

- Insider threat is not properly addressed; 28% of breaches are [by internal actors](http://www.documentwereld.nl/files/2018/Verizon-DBIR_2018-Main_report.pdf). 
- Impenetrable fortress in theory; multiple entry points (like VPNs), lots of firewall rules in practice.
- The perimeter's scope has expanded. Enterprises today support heterogeneous mix of cloud, on-premise, cloud, and multi-cloud environments. 

### Principles

- Do not trust the network. Network location does not impart trust.
- There are always internal and external threats. Act like you are already breached, because your probably are. 
- Every device, user, and application communication should be authenticated, authorized, and encrypted. 
- Policy should be dynamic, and built from multiple sources.

## Resources

### Books

- [Zero Trust Networks](http://shop.oreilly.com/product/0636920052265.do) by Gilman and Barth
### Papers

- Forrester [Build Security Into Your Network’s DNA: The Zero Trust Network Architecture](http://www.virtualstarmedia.com/downloads/Forrester_zero_trust_DNA.pdf)
- Google BeyondCorp 1  [An overview: “A New Approach to Enterprise Security”](https://research.google.com/pubs/pub43231.html)
- Google BeyondCorp 2  [How Google did it: “Design to Deployment at Google”](https://research.google.com/pubs/pub44860.html)
- Google BeyondCorp 3  [Google’s front-end infrastructure: “The Access Proxy”](https://research.google.com/pubs/pub45728.html) 
- Google BeyondCorp 4  [Migrating to BeyondCorp: Maintaining Productivity While Improving Security](https://research.google.com/pubs/pub46134.html) 
- Google BeyondCorp 5  [The human element: “The User Experience”](https://research.google.com/pubs/pub46366.html) 
- Google BeyondCorp 6 [Secure your endpoints: "Building a Healthy Fleet"](https://ai.google/research/pubs/pub47356)

#### Posts

- Google [Securing your business and securing your fleet the BeyondCorp way](https://cloud.google.com/blog/products/identity-security/securing-your-business-and-securing-your-fleet-the-beyondcorp-way)
- Google [Preparing for a BeyondCorp world: Understanding your device inventory](https://cloud.google.com/blog/products/identity-security/preparing-beyondcorp-world-understanding-your-device-inventory)
- Google [How BeyondCorp can help businesses be more productive](https://www.blog.google/products/google-cloud/how-beyondcorp-can-help-businesses-be-more-productive/)
- Google [How to use BeyondCorp to ditch your VPN, improve security and go to the cloud](https://www.blog.google/products/google-cloud/how-use-beyondcorp-ditch-your-vpn-improve-security-and-go-cloud/)
- Cloudflare [Introducing Cloudflare Access: Like BeyondCorp, But You Don’t Have To Be A Google Employee To Use It](https://blog.cloudflare.com/introducing-cloudflare-access/)
- Duo [BeyondCorp For The Rest Of Us](https://duo.com/blog/beyondcorp-for-the-rest-of-us)
- Microsoft [Building Zero Trust networks with Microsoft 365](https://cloudblogs.microsoft.com/microsoftsecure/2018/06/14/building-zero-trust-networks-with-microsoft-365/)
- Wall Street Journal [Google Moves Its Corporate Applications to the Internet](https://blogs.wsj.com/cio/2015/05/11/google-moves-its-corporate-applications-to-the-internet/)

### Videos

- [USENIX Enigma 2016 - NSA TAO Chief on Disrupting Nation State Hackers](https://youtu.be/bDJb8WOJYdA?list=PLKb9-P1fRHxhSmCy5OaYZ5spcY8v3Pbaf)
- [What, Why, and How of Zero Trust Networking](https://youtu.be/eDVHIfVSdIo?list=PLKb9-P1fRHxhSmCy5OaYZ5spcY8v3Pbaf) by Armon Dadgar, Hashicorp 
- [O'Reilly Security 2017 NYC Beyondcorp: Beyond Fortress Security](https://youtu.be/oAvDASLehpY?list=PLKb9-P1fRHxhSmCy5OaYZ5spcY8v3Pbaf) by Neal Muller, Google
- [Be Ready for BeyondCorp: enterprise identity, perimeters and your application](https://youtu.be/5UiWAlwok1s?list=PLKb9-P1fRHxhSmCy5OaYZ5spcY8v3Pbaf) by Jason Kent

