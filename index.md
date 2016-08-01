---
layout: resume
---

# Ben Krieger

I am a full-stack developer with an ops and analysis background. I enjoy
functional programming and distributed computing. Outside of work, I am an avid
open-source contributor, trombone player, cook, homebrewer, and backpacker.

## Experience

### IT Software Engineer (TRADOC Analysis Center - WSMR)

February 2016 - August 2016

* Orchestrated mass deployment of Red Hat 7
  * Built install server to host package repo and install/configuration scripts
    such as RHEL kickstart
  * Implemented a process of network booting using iPXE
	* Required debugging DHCP handshake with Wireshark and tcpdump to discover
	  why BOOTP settings were being lost
	* Used PHP to automatically generate boot scripts for different OS versions
* Created git server and authentication layer from scratch to transition from
  SVN
  * Wrote secure admin shell for consumer administration in Bash and Python
    around git-shell
  * Ported SVN repo to Git and automated sync with Bash and cron
* Wrote screen scraper to build and maintain up-to-date database related to
  government IT policies
  * Could not use any standard solutions, because neither libcurl nor wget
    support pkcs11 smart card authentication
  * Discovered undocumented SharePoint APIs in order to bypass problems related
    to SP's 5000 item list limit
  * Parsed thousands of PDFs with non-standardized internal representations
    into a flat text database with Node.js scripts
  * Wrote search functionality for the database with Python 3, later ported to
    Bash for portability
* Daily tasks included:
  * 3rd line support of user Linux issues with NFS, Samba, SSH, and other
  * Providing coding support to analysts in R, Python, and SQL
  * Advocating and teaching modern favored workflows to the combat model dev
    team, such as git version control and favoring composition over inheritance
    in Java

### Co-founder/Lead Developer (Paraphin, Inc.)

November 2013 - Present (Projects on hold since July 2015)

* Lead a small team of developers on the following projects:
  * Mapping and data analysis for parking solutions (Android)
  * Meetup competitor plus tools for managing meetings (Full-stack JS)
* Taught junior developers Node.js and Mongo DB
  * Held group work sessions to improve skill, efficiency, and independence
    with these tools 
* Delegated tasks to junior developers, assisted with project management, and
  established timelines for product release
* Designed user interface with emphasis on consumer appeal and smooth
  transition between mobile and desktop viewing
* Gave presentations to university organizations and clubs to develop interest
  and assess consumer needs


### Operations Research Analyst (TRADOC Analysis Center - WSMR)

July 2013 - January 2016

* Developed spreadsheet tools for optimizing budget decisions over 5 year
  horizon
* Advised feature development team for human-in-the-loop combat model by
  providing open source solutions (Javascript)
* Fixed bugs and developed features in combat model and tools (Java)
* Worked on R&D team to implement AI for combat actors (Python/Jython)
* Secret security clearance

## Education

### New Mexico State University

August 2013 - May 2015

Master of Science in Industrial Engineering

GPA: 3.97 / 4

Research projects: Algorithm development

* Meta-heuristic for solving Quadratic Assignment Problem
* Written to efficiently utilize CPU resources in Go
* Employed concurrency-enabled parallelism

### Rensselaer Polytechnic Institute

August 2009 - May 2013

Bachelor of Science in Physics and Mathematics

Minor: Computer Science

GPA: 3.61 / 4 (Cum Laude)

Research projects: Bioinformatics research with the Neural Stem Cell Institute

* Made predictions of genes with undiscovered roles in cerebrum development

Activities:

* Chaplain/Event Planner, Risk Manager, House Manager: Pi Kappa Phi Fraternity
* 3-year Treasurer: Rensselaer Music Association
* Trombonist: Rensselaer Orchestra, Orchestra 2, Low Brass Ensemble

## Code Samples

### Dependency-free Sass build system for Sublime Text

* [https://github.com/blitzrk/sublime_libsass](https://github.com/blitzrk/sublime_libsass)
* Significantly lowers the barrier of entry to trying Sass
* Released build scripts for (cross-) compiling sassc binaries
* Completed feature requests from users

### Project Euler solutions

* Hosted on GitLab privately as not to spoil the fun for others
* Can send git bundle or provide access upon request
* Solved in Elixir and made algorithms concurrent when it seemed like
  parallelism would speed up runs taking over 10 minutes
* Currently solved up to problem 12

## Technologies

* Languages: Python, Java, Go, ES2015 (Javascript), Elixir, Elm, Bash
* Libraries: React, React Router, Redux, Phoenix Framework
* Environment: Vim \|> Tmux \|> Mosh \|> Arch Linux

## References

* **Nemecio Chavez** - Supervisor TRAC-WSMR - nemecio.r.chavez.civ@mail.mil -
  (575) 678-4426
* **Steve Eiserling** - Paraphin Co-founder - seiserling@gmail.com - (575)
  680-6414
* **Damon Baker** - Co-worker/Mentor TRAC-WSMR - damon.d.baker.civ@mail.mil

&nbsp;
