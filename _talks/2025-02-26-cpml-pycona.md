---
title: "A CPMpy-based Python Library for Constraint Acquisition - PyConA"
collection: talks
type: "Presentation"
permalink: /talks/2025-02-26-cpml-pycona
venue: "CPML 2025"
excerpt_separator: <!--more-->
date: 2025-02-26
location: "Philadelphia, USA"
---

Constraint Programming (CP) has been successfully used to model and solve complex combinatorial problems. However, modeling is often not trivial and requires expertise, which is a bottleneck to wider adoption. As a result, the field of Constraint Acquisition (CA) has evolved with the aim to (semi-) automate the modeling process by combining CP and Machine Learning. Passive CA acquires constraints using a set of pre-existing examples of solutions and non-solutions, while in (inter)active CA, the system is interacting with the user, e.g., asking whether a (partial) solution satisfies their (unspecified) constraints or not. Despite recent advancements in CA, a key limitation is the lack of a generic, easily accessible tool for practitioners and researchers to utilize these CA systems. In this work, we present PyConA, an open-source Python library for CA, which is based on the powerful CPMpy modeling library. PyConA currently includes only interactive CA methods, with the intention to also be extended to include passive CA systems. PyConA covers the state-of-the-art in interactive CA, including a variety of different algorithms, methods, and types of queries. 

[Demo](https://dimostsouros.github.io/files/Tutorial-Demo.ipynb)

[paper](https://dimostsouros.github.io/files/CPML_AAAI25_Pycona.pdf)

[repo](https://github.com/CPMpy/PyConA)

