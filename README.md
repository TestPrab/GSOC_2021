# GSOC_2021

All the work done during Google Summer of Code 2021, in BRL CAD organization for the [Project Topic](https://github.com/opencax/GSoC/issues/41).
<br>
During the period of the project, I was responsible for the following tasks:

1. Updating the BCFXML library to support version 3.0 of the bcf xsds.
2. Implementing BCF API Version 3.0 .
3. Creating a Test Server to test the implementation of the BCF API.

The [BCFXML library](/bcf/v3/bcfxml.py) is a library that provides a set of functions to read and write BCF files.

The [BCF API](/bcf/v3/bcfapi.py) is a set of functions that allow to read and write BCF files.

The [Test Server](/foundationserver/bcfserver) is a server that allows to test the implementation of the BCF API.

ALL The Above Codes are Merged in [IfcOpenShell Repository](https://github.com/IfcOpenShell/IfcOpenShell)

Here are the list of all the sucessfully merged pull requests:

- All The PRs merged in the [IfcOpenShell Repository](https://github.com/IfcOpenShell/IfcOpenShell/pulls?q=is%3Apr+is%3Aclose+author%3ATestPrab+is%3Amerged)

Challenges Faced:<br>
The initial phase of GSOC was the only challenging phase where I had to struggle how to setup the repository and how to work on it, what is what and how to do it. I had to learn how to work on a repository and how to do a pull requests. Once this was done, I was able to work on the repository and was able to create proper the pull requests.

Todo List:<br>

- Implementing Document and extension XSD for the bcfxml.py library.
- Implementing Odata filtering for the client side of bcfapi.py.

The Mentors Assigned to the project are:

- [Dion Moult](https://github.com/Moult)
- [Yorik van Havre](https://github.com/yorikvanhavre)
