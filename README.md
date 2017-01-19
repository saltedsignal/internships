# Salted Signal's Internship Program

Salted Signal's intensive, four week, unpaid internship program could be your chance to acquire hands-on technical skills and experience on cutting edge open source cloud automation and systems engineering technologies that are in high demand in the Australian market.

This opportunity is open to Australian permanent residents and/or citizens who are looking to gain experience in the ICT/cyber-security industry in Melbourne, Australia. Although applicants require no qualifications to apply, the application process itself will require solving a handful of technical problems to demonstrate undergraduate-level knowledge in computer science and thus secure an interview. It is our intention to interview every eligible applicant who successfully meets the requirements of the application process.

Expect to be thrown in the deep end. Sure, you might sink. But if you swim, you could be our next Site Reliability Engineer.
Like being challenged? read on.

## The Task

Your task is to write a program that takes the human-visible text from a static web page (via stdin) and prints a report (to stdout) listing each letter of the alphabet, in lower-case ascending order, followed by the number of times that letter appears in the readable text.

The following snippet illustrates the expected output format:

```
a 4546
b 668
c 1735
....
x 225
y 26
z 11
```

You may solve this problem using Python, Ruby or Perl.
You may also use the command line tools available on a standard Ubuntu or CentOS installation (i.e. shell scripting).
Submissions that require the execution of compiled code will be ignored.
Your program should produce the required output by parsing the input just once (i.e. single pass).
"Human-visible" means text that is displayed to a human when a regular desktop web browser renders the page normally.

An automated system will assess all code submissions against several static pages and will compare the output produced to that of our own implementation. Applicants can ensure their solution meets the stated requirements before submission by parsing http://lapwinglabs.github.io/static/ and checking that their program's output produces an MD5 hash of `29adc47a517df85fa74b9fc6fa653289`.

## Submission Process

Submissions accepted via Github.

1. Comment your code with your name, phone number, email address and postcode.
2. Encrypt your entire program, including comments, using the GPG key below.
3. Fork this repository.
4. Commit your encrypted submission as `submissions/<your-github-username>.<extension>.pgp` to the `master` branch. Be sure to use the extension appropriate for the programming language you have selected.
5. Submit a pull request.

```
-----BEGIN PGP PUBLIC KEY BLOCK-----
Version: GnuPG v2

mQENBFiAWokBCADCs1sxGg02CkqPshIhWMEW+d22N2hArJagLqvUX0nHSI43dNkg
eledYISH2IjFkQbVN2lgvMut8qIe+2JXRUmikYy+5XIWH87dUmGdjKWBgcNLPavo
790fmukPTFnal5Utn0h5xE/oTR9vW9h7649K1914sxe51Zqevd0Wp5SXdltsDivx
NVTy/aZZD69exq54fRGWSVGWNvugNoq6ZWgxiLreINdOJRZOLzeKSHUTDrb7fwAV
yArwnAmOKyJl5RsH4wHcdLLQXYdf6kI4SHVi3gJ+hIcZPPH9GXZY5cVcodOeJVHi
NqJ+wid5OT1hc8v/Y8eGIdRztdgnv4teVdxvABEBAAG0O1NhbHRlZCBTaWduYWwg
SW50ZXJuc2hpcHMgPGludGVybnNoaXBzQHNhbHRlZHNpZ25hbC5jb20uYXU+iQE4
BBMBAgAiBQJYgFqJAhsDBgsJCAcDAgYVCAIJCgsEFgIDAQIeAQIXgAAKCRDw0Mt7
1WgPh/NIB/9K8yawJ2cXU30fGmetAU21KRqEV7hmPKYj3+1T+6JCTEXCBA1WPW3t
5IjuWEGKjBoYJX3jEGC1yeX0MC3HnikHIqoT1ZZTBC7M8p46rjrZ+xwa3fmDuhFs
vovDrV22BDEvy0sXZ4XZb6RGqmjkP6TUVFYudBUDQw6yIy34hwt4E3nMdgQEFQW9
d+jTqxDWjUa/ykap0RTwBjf6HUroyfDLCDuJEFumFDxKunD6+GOj0n3SUUyO6XpS
HQ/Gli9qnLhpFVrDENV6uV3/Bf5uWynl+omAmjbJ0NMAqSH32qZWv5zQI9RQuGi4
h4LiOixkV4mJuyFJeu1kF5XZ31HafC2cuQENBFiAWokBCADPQJ8yHJoTYu87C+Xn
C1yE/Ry8G6LtecJ0erHRaw08TEsGDUyhD5iQ+3rcV64wfPNbOTXjbRwIaxlScac5
phXHBMgwlCFFNj1c/jjl6wQrOyG2XYU4IgHsnoLPhqdlYdKz5pTVQ+HtmUSEyLbo
ggsEDadLGoNZl6mVc3cUGIgVe6xSmtv+/buJfUV5d3BtVZsL4Ed9Me9Znsm+MaDM
UmXs2TyntldGRoTuzE+fTry6LSknbubbbG/l77IdHtTrgerBq38So1UGFkNg+jNz
SpTIXpi4XKWMxZccPdX7TV1lWB6bovV7jx1HdhULFRTRtVTTMlKN7xhMv6/7giIs
reOzABEBAAGJAR8EGAECAAkFAliAWokCGwwACgkQ8NDLe9VoD4cgOQgAhkYKKYx8
uUbD2O2gKI19o0ZO5NXC5ocdqtBhqBBqjrZZ+/HUszWPgYooeGhDNncNUMn8KNB/
u3VHp7ekwb2+soUw17ZBTJPfEbQGTIqnBXcezsihThedQ/ZRqCsEXMEeda6avU2i
ETsMBGv2ueD1HvOJo3PnGMcVLcR1QS65HnMc9bGzbDRPmfQuqUNURMLofFDl3Cpf
t6blRK/9lfNxmpnHG9w8xFh67m2GexhyLQWsNBwUd7xSUPBO5rmwyF2ot2VEFs/n
qqbSqkGQS2Uw+F7gS54SALOAdatN7qHakqAxexHx+2tJCwv8Tc2Evg/i+V7XidJd
kTyDwB0itRQrog==
=/933
-----END PGP PUBLIC KEY BLOCK-----
``` 

One final note. If you miss a requirement, no matter how small, you might not be contacted.


# LICENSE

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
