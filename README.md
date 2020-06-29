# Meta Hub Main repo
Main repo for the Code for NL "Meta Hub" [Community Project](https://www.codefor.nl/communityprojects).

## The Idea

Meta Hub is a Marketplace for Code for NL community members to find community projects. We create tools for community projects to create a profile, so they can be found.

Meta Hub is also a Marketplace for Code for NL community projects to find community members. We create tools for community members to create a profile, so they can be found.

## Design Principles

1. micro-application: we create micro-applications that are compattible
2. open standards: we use open standards as much as possible
3. user owned data: you may put your data files on github, or on your own website (and we will only cache it (temporarily) for optimization)

## Subsystems

![Meta Hub Remote File Architecture](https://github.com/codefornl/meta-hub-main/blob/master/metahub_archi.png)

### Community Member Profiles

Adding your community member profile to the meta hub database can be done in multiple ways, to enable self-ownership of your data.

The primary way to do this is to publish a file called codefornl.json in one of your Github repositories (we suggest your personal github.io repository hosting your personal website). These files will be indexed automatically every 10 minutes. You need to add a field to this file called "resume", with the value being the URL to your [jsonresume formatted resume](https://jsonresume.org/).

![Code for NL Meta Hub file](https://github.com/codefornl/meta-hub-main/blob/master/metahub_c4nlfile.png)

Another way is to upload your jsonresume file to the Meta Hub DB at [URL].

![Community Member Profile](https://github.com/codefornl/meta-hub-main/blob/master/metahub_member.png)

### Browse Community Members

![Browse Community Members](https://github.com/codefornl/meta-hub-main/blob/master/metahub_member_browse.png)

### Community Members Search

![Search Community Members](https://github.com/codefornl/meta-hub-main/blob/master/metahub_member_search.png)

### Community Project Profiles

### Browse Community Projects

### Community Projects Search

## How we work
We will be using the [Standard for Public Code](https://standard.publiccode.net/) in cobination with the [Shape Up Methodology](https://basecamp.com/shapeup).
