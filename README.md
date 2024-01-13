# Sublet_Boston_Flask

This is an application that stores information on users looking to sublet their apartment for a set period of time of their choosing (example: summer, semester, few weeks, etc). The user interfaces we've created would be for potential subletters and sublessors. It is anonymous on the front end and would show only a subletter/sublessor’s username.

Sublessors can create, update, and delete their postings. They also have the ability to add and update their lease information, as well as view their reviews.

Subletters are be able to scroll and filter through postings based on price, to look at various off-campus options that meet their needs. Potential subletters can contact those posting sublet information through direct messaging. Subletters are also able to create, delete and update their own profile info.

All users are be able to see the apartment’s photos, description, and basic roommate and pricing information. The application would be open to Northeastern students who are both looking to sublet their apartment out and find a place to sublet.

This repo contains a boilerplate setup for spinning up 3 Docker containers:

A MySQL 8 container for obvious reasons
A Python Flask container to implement a REST API
A Local AppSmith Server
