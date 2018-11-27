---
@title[Intro]

@snap[north headline]
### MacOS disk imaging in the data centers
@snapend

@snap[south byline]
Jake Watkins :dividehex
jwatkins@mozilla.com
@snapend

---
@title[What is BSDP?]

@snap[north headline]
### What is BSDP?
@snapend

@snap[west]
@ul
 - BSDP = Boot Service Discovery Protocol
 - It is an extention to DHCP developed by Apple (ages ago)
 - Allows apple computers to boot over the network similar to PXE booting
 - Utilizes DHCP option 43 "vendor-specific information"
 - And option 60 "vendor class identifier
@ulend
@snapend

---
@title[BSDP exchange]
### BSDP exchange
![Image-Relative](assets/img/BSDP_exchange.PNG)

---
@title[What is BSDPy?]
### What is BSDP@color[#ff0000](y)?


---
@title[Why are we switching to bsdpy?]

List of reasons to switch
<br><br>
#### Why not continue using Apple Server App?
<br>
@fa[arrow-down]

+++?image=assets/img/apple_server_app_store.png
+++?image=assets/img/apple_server_app_store.png
# @color[#ff0000](GOOD JOB, APPLE!)

---
@title[What is Deploystudio]
What is Deploy Studio?

---
@title[How it all ties together]
How it all ties together


---
@title[Recorded Demo]
Demo
<br>
![demo-video](https://player.vimeo.com/video/303137935)

---
@title[Final]

@snap[north]
### Thank you
#### References
@snapend

@snap[west list-content-verbose span-100]
@size[.5em]( - [https://en.wikipedia.org/wiki/Boot_Service_Discovery_Protocol](https://en.wikipedia.org/wiki/Boot_Service_Discovery_Protocol))<br>
- [https://static.afp548.com/mactips/bootpd.html](https://static.afp548.com/mactips/bootpd.html)<br>
- [https://github.com/mozilla-platform-ops/relops-bsdpy](https://github.com/mozilla-platform-ops/relops-bsdpy)<br>
- [https://github.com/mozilla-platform-ops/pydhcplib](https://github.com/mozilla-platform-ops/pydhcplib)<br>
- [https://github.com/bruienne/bsdpy](https://github.com/bruienne/bsdpy)<br>
@snapend

@snap[south-west]
Jake Watkins :dividehex
@snapend

@snap[south-east]
jwatkins@mozilla.com
@snapend

