---
layout: narrative
title: "Graphql: A Query Language for your API"
author: Michael Angerman
editor: Michael Angerman
rights: Public Domain
source: Arcadian Group
publication-date: 2017
toc:
- Title Page
- Chapter I
- References
---

---

## Note

For many years developers have been using Rest APIs with JSON as an interface to allow
front end developers and back end developers to communicate with each other programmatically.
Recently, a new programming paradigm has been introduced by Facebook called Graphql.  I will
attempt in this post to highlight was this is significant.

---

<a id="title-page" />

<p class="centered large">Graphql</p>
<p class="centered medium">A new style Query Language to talk to APIs</p>

---

## CHAPTER I

For the past number of years I have been designing and building large scale API systems that use REST api endpoints.  Tools like Swagger are helpful for managing and automatically documenting the actual REST schemas that can then be generated for the different language implementations.

Recently, Facebook introduced the concept of Graphql which is now starting to gain some traction.  It "changes the game" so to speak in how we think about and build out APIs to back end services.  Now instead of designing many different endpoints for different types of data, we are able to incorporate our complete data model into one schema that we can then query against very similar to an SQL query.  We now have a defined Query Language that uses JSON requests to get at the data which is then returned in JSON as well.

I am in the process of working in the Golang, Javascript and Ruby implementations to build out initial test data schemas.  In addition, I have been working with Github and their Early Access Program to build applications that use their new pre Alpha Graphql model of the Github data.

---

## References

[Graphql Github](https://developer.github.com/early-access/graphql/)  
[Graphql Go](https://github.com/neelance/graphql-go)  
[Graphql Viewer](http://graphql.org/swapi-graphql/)  
