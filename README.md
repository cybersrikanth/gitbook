---
description: Demystifying Web Application Security (For Developers)
---

# Introduction

### Security is everyone's responsibility.

A lot of developers think that security is a complex thing to understand. They think of cyber security professionals as a magician who does some magic to find vulnerabilities in the application.

#### What is security?

Security is not a separate component of the application. But it can be considered as a **state of an application**. \
For example, \
A developer can either write code that is currently **secure** or **vulnerable**. A code can be potentially vulnerable when its **input, output, and side effects** are not well known.

#### What is vulnerability, and where do they come from?

It is easy for a developer to write code that gives the expected output. But it is hard to write a code that gives the expected output all the time.\
For example, \
When a developer constructs a SQL query by concatenating the user inputs, as long as the user input does not contain any characters that could break the query, it will work. But when the user-supplied input contains special characters, the query would break and the code will return unexpected outputs.\
\
These **unexpected outputs are sometimes called vulnerabilities if they impact business or privacy**.

#### Why should developers learn security while there are penetration testers to do security testing?

Developers should be aware of security to make sure the code they are writing is not vulnerable. The **penetration testers cannot find all vulnerabilities**, especially the vulnerabilities that are too complex to detect. Few vulnerabilities can be only discovered by white box penetration testing, which costs a lot of money and time. A penetration tester's job is to make sure there are no common vulnerabilities exist in the application and good security practices are followed.

#### Why do security vulnerabilities increase day by day?

A lot of developers just learn how to code and get output. They are not spending time exploring how it works under the hood. **Developers write vulnerable code when they don't understand how things work "under the hood" (or "behind the scene")**.

#### What should I do to learn web security?

Here are few things one can do to improve knowledge in security.

* Always learn how things work "under the hood"
* "Demystify" concepts that you previously felt like magic.
* Explore common security vulnerabilities (OWASP).
* Read tech blogs/videos.
* Practice.

There are a lot of resources online that can help you learn web security. My favorite one is [PortSwigger Acadamy](https://portswigger.net/web-security). I've also created content on a few topics in which I explain concepts, comparisons, etc. Check next page to demystify web security.



Author: [CyberSrikanth](https://linkedin.com/in/cybersrikanth)
