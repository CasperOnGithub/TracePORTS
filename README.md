Tired of using CMD / Powershell to check if the common ports are open on a site? Well I am.
Let's check here, oh okay. Port 65,535 is closed, that's awesome.

So I decides to build a quick tool to test them all in seconds, it ain't perfect but it sure as shit works. 

What it does:
- Checks common ports such as. (SSH, HTTP, HTTPS, MySQL, RDP etc.)
- Multithreaded so takes 2 seconds to finish
- Zero extra dependencies (booooring)

Installation & Usage:
- Clone the repo (git clone https://github.com/CasperOnGithub/TracePORTS.git) and then (cd TracePORTS)
- Run against a target, example:

Example 1: python TracePORTS.py example.com

