# Episode Mr. Robot
- onion routing / Tor
    - does not suppord JS
        Imagine having to use the default HTML form / no framework :P 
- rudy attack
   1. The R.U.D.Y. tool crawls the victim’s application looking for a form field.
   1. Once a form is found, the tool creates an HTTP POST request to mimic a legitimate form submission. This POST request contains a header* which alerts the server that a very lengthy piece of content is about to be submitted.
   1. The tool then drags out the process of submitting the form data by breaking it down into packets as small as 1 byte each, sending these packets to the server at randomized intervals of around 10 seconds each.
   1. Repeat until dead :D

- rootkit? root access ? if yes == danger
    -> from [umbrella.cisco](https://umbrella.cisco.com/trends-threats/cyber-threat-categories-and-definitions#level-2-threat-types) :A rootkit is a collection of computer software, typically malicious, designed to enable access to a computer or areas of its software that would not otherwise be allowed (for example, to an unauthorized user) and often masks its existence or the existence of other software.  
- can you chmod / lmao??  too lazy to test it sorrry :P 
- single point of failure
- parrametrable password breaker => pretty cool 

cd => a token of time, or good practice ?

# Cyber-security NIST
National intiture of standards and technologies
a lot of documents, they cover many fields
## SP-800.53 Rev. 5
[link](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf)
CHAPTER 3 : THE CONTROLS
It inclues best practices for acesing any ressource. 
NOT a manual on how to do it ; it's a series of questions you must ask 
in terms of security, and it's yourx
## SP-800.72 Rev. 3
[link](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-172r3.ipd.pdf)
Control unclassified informations
It's a standard you must respect if you want to work with a government agency (US now, Canada soon)
Takes a shit ton of time to assess if you meet requirements (600+ points to check)

# Trust
Important to note, the key concept in cybersecurity is **TRUST**. As boring as it is, 
in the context of any interraction, you need to assume an arbitrary entity is trustworthy, 
or the interraction won't achieve anything. 

In an IRL interraction (face to face), you usually assume that your interlocutor's information 
is trustworthy, otherwise, you would simply ignore it. The same in the *cyberspace* (what a shit term).

Now the model behind the trust system might be complex and abstract, but it should always stand
true. 

