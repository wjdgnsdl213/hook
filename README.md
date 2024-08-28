# hook
submodule for git_rce:
https://github.com/EQSTSeminar/git_rce

# Attack Scenario
kali(192.168.216.129) --Give remote repository address--> Win(192.168.216.130)

kali(192.168.216.129) <--Git clone && hook script(post-checkout) execution-- Win(192.168.216.130)

# Disclaimer
This repository is not intended to be git clone RCE exploit to CVE-2024-32002. The purpose of this project is to help people learn about this vulnerability, and perhaps test their own applications.
