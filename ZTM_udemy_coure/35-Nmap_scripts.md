
# Nmap scripts: 
  > to detect different system vulnerability
#### [*] location: "/usr/share/nmap/scripts"

### Examples:

 >  **nmap**  -sC <target> default script,, no breaking things,safe.

 >  **nmap** --script auth <ip_address> - "can i login","is login weak or miscnfigured", "Are default or empty passwords allowed?".

 >  **nmap** --script malware <ip_address> -F(fast) - wheather the system is infected or not.

 >  **nmap** --script banner.. - a server introducing itself.

 >  **nmap** --script exploit.. - exploit some vulnerablity

## N.B:

  > **=> nmap --script-help <name_of_scipt>: to get help..**

  > **=> ftp <ip_address>: to connect to a system through port 21...**
