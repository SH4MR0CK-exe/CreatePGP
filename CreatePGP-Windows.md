<h1>Create PGP key pair in Windows</h1>

GnuPG is a complete and free implementation of the OpenPGP standard as defined by RFC4880. Read more here:
https://www.gnupg.org/index.html

Download the Windows installer here (W10 and 11 x64 compatible at time of writing):
https://gpg4win.org/download.html

<ol>
  <li>Install GnuPGwin with defaults, or customize, I don't give a shit.</li>
  <li>Once finished, run from Start Menu or "C:\Program Files (x86)\Gpg4win\bin\kleopatra.exe"</li>
  <li>Select "File" and "New OpenPGP Key Pair..." </li></br>
  ![alt text](https://github.com/SH4MR0CK-exe/Privacy/blob/main/pictures/pgp_sop1.jpg)</br>
  <li>Check "Protect the generated key with a passphrase" (unless you're an idiot) > expand "Advanced options" > change encryption standard to rsa 4096</li>
  <li>(Optional) Set name and email (if you don't care about privacy) and alter or remove the cert expiration date.</li></br>
  ![alt text](https://github.com/SH4MR0CK-exe/Privacy/blob/main/pictures/pgp_sop2.jpg)</br>
  <li>Select "OK" and wait for your computer to do some maths n' shit.</li>
  <li>Righ click the newly generated cert > Select "Export" to get a copy of your <i>public</i> key > Share with recipients you whish to decrypt your messages.</li></br>
  ![alt text](https://github.com/SH4MR0CK-exe/Privacy/blob/main/pictures/pgp_sop3.jpg)</br>
  
</ol>
