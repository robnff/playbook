# Security

Security is no easy topic to talk about. There are many ways to explore vulnerabilities in a web site. To address that we follow [security guidelines](https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project#tab=OWASP_Top_10_for_2013) and use well known and tested tools to reduce risks. Although writing code that is robust and tested against vulnerabilities is essential for secure applications, it's well known that [social engineering](https://en.wikipedia.org/wiki/Social_engineering_(security)) is many times the weakest link in the chain. For that, we enforce tools and practices that tackle this kind of problem.

## 2-factor Authentication
From servers to email, wherever possible we require the use of 2-factor auth. 

## Password Managers
Every password should be generated randomly and managed by a tool. Humans are not good in neither of these tasks. Everyone in the team is required to create and store passwords using [LastPass](https://www.lastpass.com/).

## Encrypting Sensitive Messages
Every once in a while it's necessary to transfer security sensitive information such as passwords to clients. Use GPG to encrypt that kind of information before sending it through insecure channels (a.k.a. any non physical medium). 

 **Linux Users.** We recommended [GPA](https://www.gnupg.org/software/gpa/index.html), a graphical interface for GnuPGP. Follow [this tutorial](https://www.deepdotweb.com/2015/02/17/basic-guide-pgp-linux/) to install and learn the basics.

 **Mac Users.** [PGP tools is easy to install and use](https://gpgtools.org/).