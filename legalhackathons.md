---
layout: default
permalink: /legalhackathons/
---

# Fall 2013 Legal Hackathon 

On October 5, 2013, DC Legal Hackers hosted their first DC Legal Hackathon at [Fastcase](www.fastcase.com). 

<img src="http://24.media.tumblr.com/573ef5b8b1e9a76305d2d8a9cbad478d/tumblr_muexg6SkcN1s13242o5_1280.jpg" alt="Drawing" style="width: 600px;"/>  

### The Setup 

Prior to DC Legal Hackers first ever Legal Hackathon, the group reached out to the local legal, tech, and open government communities to gather for an Issue Spotting Happy Hour where the group [identified problems and pain points](https://github.com/dclegalhackers/ideas/blob/master/ideas.md) that existed within their (law or tech) work and brainstormed ways to solve them. Jameson Dempsey and Rebecca Williams, DC Legal Hacker co-organizers, met up with the Legal Services Corporation staff to further discuss the access to justice technical issue identied at the meetup. Problems in hand, the DC Legal Hackers gathered to hack on real legal and tech issues they faced every day.  

<img src="http://31.media.tumblr.com/5fa89fa8be5e50b90d0d036c2f7946a6/tumblr_muexg6SkcN1s13242o1_1280.jpg" alt="Drawing" style="width: 600px;"/>  

The [Legal Hackathon](https://github.com/dclegalhackers/dclegalhackathon/) started at 9 am with bagels, meeting, and greeting. [Participants](https://github.com/dclegalhackers/dclegalhackathon/blob/master/Participants.md) included familiar faces from the [Issue Spotting happy hour](http://www.meetup.com/DCLegalHackers/events/131895222/), the Hypothes.is and Open Gov Foundation [Legal Annotation Roundtable](https://github.com/opengovfoundation/Open-Government-Annotation-Gathering), and [Code for DC](www.codefordc.org), as well as first time #LegalHackers, including: DC's Open Government Director and fresh faces from the local tech and law community. The [Agenda](https://github.com/dclegalhackers/dclegalhackathon/blob/master/Agenda.md) began with a [GitHub 101](https://github.com/dclegalhackers/dclegalhackathon/blob/master/GitHub101.md) session for non-techies hosted by DC Legal Hackers co-organizer, and idea-man behind this hackathon, Ben Balter. For more information on how to start with GitHub, check out our [sign up guide](https://github.com/dclegalhackers/dclegalhackathon/blob/master/GitHub101.md), or [Ben's presentation](http://ben.balter.com/open-sourcing-government/#/git), his [GitHub glossary](https://help.github.com/articles/github-glossary) (created the day before at the annotation roundtable), [tryGit](http://try.github.io/levels/1/challenges/1) with Code School or if all else fails, [ask Ben](https://github.com/benbalter/feedback) himself.

<blockquote class="twitter-tweet"><p><a href="https://twitter.com/search?q=%23LegalHack&amp;src=hash">#LegalHack</a> New to GitHub? Here are some resources that may help: <a href="https://t.co/pD65QueR1e">https://t.co/pD65QueR1e</a>, <a href="http://t.co/PqnCj46HEO">http://t.co/PqnCj46HEO</a>, <a href="http://t.co/yZ5d13hUQ8">http://t.co/yZ5d13hUQ8</a></p>&mdash; Ben Balter (@BenBalter) <a href="https://twitter.com/BenBalter/statuses/386489991247175681">October 5, 2013</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>  

After the GitHub 101 introduction for non-techies, the tables were turned, with a Legal Access 101 presentation for techies, featuring Jessie Posilkin and Glenn Rawdon from Legal Services Corporation who explained the overarching access to justice issue, as well as Legal Services Corporation's specific mapping problem. As it stood, the LSC website search tool only offered the ability to search on the basis of state and county. Because counties can be very large, and sometimes the LSC service areas are not drawn on a county basis, the search function is not as helpful as it can be (and in some cases leads to confusing results). See [Massachusetts](http://grants.lsc.gov/about-grants/where-we-fund/massachusetts) as an example. LSC was looking to improve their search tool so it would be able to take a zip code as input and return the nearby locations in the assigned service area. LSC's Access to Justice project was chosen beforehand as a project to feature at the hackathon because it was a specific problem with technical and non-technical components. 

In addition to [LSC's Mapping Project](https://github.com/LegalServicesCorporation/LSC-Mapping/blob/master/README.md), and the building of the [DC Legal Hackers' website](www.github.com/dclegalhackers/dclegalhackers.github.io), the following projects were hacked on: [DC Procurement Scraping](https://github.com/vzvenyach/dc-contracts), [US Glossary Annotation project](https://github.com/unitedstates/glossary), [new DC Code Parsing](https://github.com/openlawdc/dc-decoded), [Legal Cititaton Linker in Markdown](https://github.com/adelevie/citation-linker), [Stackedit fork for legislative drafting](https://github.com/opengovfoundation/stackedit). See more information about how those projects turned out below.

### Projects #LegalHack-ed On 

#### [LSC Mapping](https://github.com/LegalServicesCorporation/LSC-Mapping/blob/master/README.md)  
<img src="https://pbs.twimg.com/media/BV1000XIQAADHvo.jpg" alt="Drawing" style="width: 600px;"/>

During the hackathon LSC, and hackers, including Tom Macwright, converted service area shapefiles to open/web-friendly geoJSON and plotted service centers, to create new and helpful ways for low-income individuals to search for their appropriate LSC location. LSC signed up for their first GitHub account during the hackathon: 

<blockquote class="twitter-tweet"><p>YES! <a href="https://twitter.com/LSCtweets">@LSCtweets</a> is now on Github. <a href="http://t.co/BYhl2KlCzL">http://t.co/BYhl2KlCzL</a> with a project up and everything. <a href="https://twitter.com/search?q=%23LegalHack&amp;src=hash">#LegalHack</a></p>&mdash; Jessie Posilkin (@jposi) <a href="https://twitter.com/jposi/statuses/386509591413927936">October 5, 2013</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>  

<iframe width="600" height="515" src="http://www.youtube.com/embed/R3D5ncONdhI" frameborder="0" allowfullscreen></iframe>  
_Tom Macwright explains the shapefile conversion._

#### [DC Procurement Scraping](https://github.com/vzvenyach/dc-contracts)  

David Zvenyach, chief counsel for the DC Council, worked on a Python scraper for DC’s contracts, gathering procurement data, improving their search-ability (including lawyer information), and most importantly creating permalinks for contract information that left the site after the contract was completed. This project practically makes it easier to search DC contract information for potential legal issues and provides additional accountability and transparency to the financial proceedings of DC.

#### [US Glossary Annotation project](https://github.com/unitedstates/glossary)  

Eric Mill, along with Lindsay Young, Erroll Grannum, and Keith Leonard (of Fastcase) worked on a glossary the Unite States project on GitHub. A tool where lawyers and non-techies alike can through Prose.io define legal terms and then have those definitions turned into data and applied to synced apps. 

<iframe width="600" height="515" src="http://www.youtube.com/embed/SlmDEDNV7d0" frameborder="0" allowfullscreen></iframe> 
_Eric Mill explains his United States Glossary #LegalHack._ 

#### [*New* DC Code Parsing](https://github.com/openlawdc/dc-decoded)  

In addition to assisting Legal Services Corporation on their map quest, Tom Macwright sought assistance on updating [DCCode.org](www.dccode.org) by creating a new parser for the newest code edition. To read more about the DC Code project, see Tom's eureka [moment](http://macwright.org/2013/02/20/you-cannot-have-the-code.html) and Robert Richard's [fantastic timeline](http://legalinformatics.wordpress.com/2013/04/05/freeing-the-dc-code/) of how the code was freed. 

#### [Stackedit fork for legislative drafting](https://github.com/opengovfoundation/stackedit)  

<img src="http://31.media.tumblr.com/ba91e8583bb4d59f827660421ffe3f68/tumblr_muexg6SkcN1s13242o3_1280.jpg" alt="Drawing" style="width: 600px;"/>

Open Gov Foundation forked StackEdit to devise a Markdown-based format for legal drafting.

### Success!

After the hacking, the gang went out for celebratory drink. Not a first hackathon! Lastly, check out the great round ups from our co-conspirators, [Open Gov Foundation](http://opengovfoundation.tumblr.com/post/63569079653/dc-legal-hackers-inaugural-hackathon-october-5), and US Glossary Annotator, [Eric Mill](https://www.konklone.com/post/legal-hacking-in-dc), as well.


#### [Legal Cititaton Linker in Markdown](https://github.com/adelevie/citation-linker)  

<img src="http://25.media.tumblr.com/f918ce2393ca3562499c1efff6b8bb2f/tumblr_muexg6SkcN1s13242o2_1280.jpg" alt="Drawing" style="width: 600px;"/>  

<blockquote class="twitter-tweet"><p>Automagically add links to legal citations within markdown text: <a href="https://t.co/K2dd9KRNnB">https://t.co/K2dd9KRNnB</a> Supports USC, CFR, and DC Code (so far) <a href="https://twitter.com/search?q=%23LegalHack&amp;src=hash">#LegalHack</a></p>&mdash; Alan deLevie (@adelevie) <a href="https://twitter.com/adelevie/statuses/386598438999044096">October 5, 2013</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>  

DC Legal Hacker co-organizer, Ruby programer, and 3L, Alan deLevie, wrote a tool to autolink legal citations, using Eric Mill's unitedstates/citation parser as a foundation.  
