# Privacy Cookbook for Business Processes #

## As resource for IPEN ##


## (Internet Privacy Engineering Network) ##

*– draft – V0.0003 – TO BE DISCUSSED -*

Nightly build – 16.10.2014

Begun by Markus Alexander Grete 
– PLEASE participate and add your content!!!

Company Mail address: <Markus.Grete@gretEDV.de>
University Mail address: <grete@l3s.de>

<span id="_Toc401233205" class="anchor"></span>Motivation

If you are in Business Process Modelling (BPM), you need to care about
the privacy topics.\
Let’s start with the basics.

<span id="_Toc401233206" class="anchor"></span>The 7 basic principles of
privacy

1.  Proactive not Reactive; Preventative not Remedial
2.  Privacy as default setting
3.  Privacy embedded into design
4.  Full functionality – Positive-Sum not Zero-Sum
5.  End-to-End Security – Full Lifecycle Protection
6.  Visibility and Transparency – Keep it Open
7.  Respect for User Privacy – Keep it User-Centric

<span id="_Toc401233207" class="anchor"></span>Basic concepts of privacy

* the right to be forgotten
* the minimum acquisition of data
* the processing by consent
* anonymity
* purpose-specification
* […] help me to continue!

The OWASP project is doing expert surveys to evaluate the Top 10 Privacy
Risks as to international security experts. Thanks to FS and his project
for providing the information\
Reminder: *This has to be updated regularly using the link on
“Literature”*

<span id="_Toc401233208" class="anchor"></span>Top 10 Privacy Risks (by
OWASP / FS)

This list is an expert-based rating of the current top 10 IT privacy
risks.

P1 Web Application Vulnerabilities

P2 Operator-side Data Leakage

P3 Insufficient Data Breach Response

P4 Insufficient Deletion of personal data

P5 Non-transparent Policies, Terms and Conditions

P6 Collection of data not required for the user-consented purpose

P7 Sharing of data with third party

P8 Outdated personal data

P9 Missing or Insufficient Session Expiration

P10 Insecure Data Transfer

<span id="_Toc401233209" class="anchor"></span>Intro

By now, this “scrapbook” is mainly motivation and literature references.
Not much content.\
The hope is that we find the way from the motivational part and through
the existing literature and websites to provide content as soon as we
have a strong idea about how it should look like. Furthermore we will
provide content collected on universities and from real-world projects.

As we consider privacy in IT systems, we have to deal with the basic
principles of privacy. As to (3.) we have to embed privacy into design.
As to (2) by default. That means that we have to consider privacy from
the first step on.

Very often in software development in Year 2014 the software development
process begins with an analysis of what is needed, an analysis of the
Business Process (BP) the software has to support.

So we are starting top-down here.

<span id="_Ref400195950" class="anchor"><span id="_Toc401233210"
class="anchor"></span></span>Basic real-world problems making privacy
more difficult

(Reasons for the need to preserve data)

-   Requirements of completeness for audits

-   Requirements for preparation against legal trails

-   […] help me to continue!

<span id="_Toc401233211" class="anchor"></span>The real world outside

You can introduce privacy into business process modelling once at each
project, or – if you are a consultant – once at each customer. And you
can install a separate privacy guiding process in addition to the casual
data protection guidelines or compliance guidelines almost every bigger
company has. If you enter a fresh startup, you should try to install a
privacy guiding process as data protection guideline, combining
everything.

But to be honest, to me this is the boring part of the work and should
be automated via standardized documentation (cookbooks) and tools.
That’s why I suppose we need a cookbook for that.

The interesting part is to analyze the existing (sometimes older and
“established”) business processes and data dictionaries, the business
requirements and the current legal prerequisites. Moreover you have to
look at the Databases and flat files, the Queues and Enterprise Service
Buses and whether all of them are covered in the BP documentation. And –
not for last – the Online- and Offline applications and their BP
coverage.

Consider: If a business process (BP) is running untouched for more than
5 years, it will most probably not be up to date in all respects. And
each time you pick up a BP you have to ask all the experts and sometimes
use a lot of time to get all things done.

<span id="_Toc401233212" class="anchor"></span>Borderlines

<span id="_Toc401233213" class="anchor"></span>Topic borderline

In this cookbook we do not want to care much about the engineering or
solely cryptographic perspective of privacy within applications. That
will be topic of another cookbook. Nevertheless we will take every hint
we get and assimilate it as good as we can.

<span id="_Toc401233214" class="anchor"></span>Cost and security
borderline

I don’t know why, but I learned that companies usually do not want to
show that they care about security or privacy, and want to keep their
privacy enforcing projects secret. They do not even want the company
name on any scientific slide about the “next generation” things we
installed.

The only thing I can estimate about that is that a company’s customer
would think: “Hey, they have to improve their privacy ruleset, there
must be something wrong about it!”. The opposite is correct.
[Kaizen](http://en.wikipedia.org/wiki/Kaizen) rules.

But – therefore – I cannot supply customer’s project documentation and
can only start from now on to tell the customers that everything we do
could but needn’t lead to a passage in the cookbook. If you have
something you could pseudonymize[^1] and supply, you’re welcome.

<span id="_Toc401233215" class="anchor"></span>Main document

- STARTING -

<span id="_Toc401233216" class="anchor"></span>Lifecycles

<span id="_Toc401233217" class="anchor"></span>Customer Lifecycle

If the data of a customer is no longer needed, it can and should be
deleted. If a separate part of customer data is no longer needed, it
should be disposed.

<span id="_Toc401233218" class="anchor"></span>Business Process
Lifecycle

If a Business Process is finished, the data which was collected for this
business process only should be deleted. The speed of this removal
depends mostly on “Basic real-world problems making privacy more
difficult”.

<span id="_Toc401233219" class="anchor"></span>Data retention in common

[…] help me to continue!

<span id="_Toc401233220" class="anchor"></span>Ideas

Installation of “next generation” access control mechanism as Attribute
Based Access Control.

Installation of “Power to the person described by the data” (sometimes
“more power to the user”, which would only sound correct in systems
where the user is entering the data on his own).

<span id="_Toc401233221" class="anchor"></span>Toolsets

If you can support tables etc. which can be used with e.g. Open Office
or similar, please support.

If you are from a software vendor for BPM, please support.

<span id="_Ref401217903" class="anchor"><span id="_Ref401225049"
class="anchor"><span id="_Toc401233222"
class="anchor"></span></span></span>Literature

Danger: The comment “Useable here for\*” in the tables below is very
from my point of view and towards what I think on my own. Please feel
free to get me informed, when I am wrong from your point of view.

  Title                     Attribute Based Access Control
  ------------------------- ----------------------------------------------------------------------------
  Information supplied by   MG
  Useable here for\*        Restricting rights with state-of-the-art Access Systems
  Download-Page             <http://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.sp.800-162.pdf>
  Further Information       For further information: Prof. Ravi Sandhu
  Added                     16.10.2014

  Title                     Android Application Secure Design/Secure Coding Guidebook
  ------------------------- -----------------------------------------------------------
  Information supplied by   JSSEC.ORG / via FD
  Useable here for\*        Heading towards Round-Trip engineering privacy
  Download-Page             <http://www.jssec.org/English>
  Further Information       Seems to [MAG] as a technical and technological Guidebook
  Added                     04.10.2014

  Title                     Enable secure product delivery
  ------------------------- ------------------------------------------------------------------------
  Information supplied by   FD
  Useable here for\*        Thinking about basic processes as already established to secure coding
  Download-Page             <http://www8.hp.com/h20195/v2/GetPDF.aspx/4AA5-3485ENW.pdf>
  Further Information       
  Added                     04.10.2014

  Title                     Engineering privacy requirements
  ------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Information supplied by   JMdA
  Useable here for\*        More for the engineering cookbook
  Download-Page             The document is available in IEEE Xplore Digital Library at <http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=6890523> 
  Further Information       Martin, Y.S., Del Álamo, J.M., Yelmo, J.C., Privacy Requirements Engineering: Valuable Lessons from Another Realm, In 1st International Workshop on Evolving Security and Privacy Requirements Engineering - ESPRE2014, pp. 19-24, Karlskrona (Sweden), 25 Aug 2014. doi: 10.1109/ESPRE.2014.6890523
  Added                     04.10.2014

  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Title                     Linking security with Economics
  ------------------------- ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Information supplied by   SJE

  Useable here for\*        Finding the business and economic value of privacy

  Download-Page             <https://ec.europa.eu/digital-agenda/sites/digital-agenda/files/Stephan.pdf>

  Further Information       SJE supplied more links which seem not very important for this document because they are more technological related. Just picked one which could help to understand his point of view:
                            
                            <http://blog.privacytrust.eu/public/Slides/au_conf670306_engberg_en.pdf>
                            

  Added                     04.10.2014

  Title                     Model-driven security

  Information supplied by   UL

  Useable here for\*        Evaluation of Model driven security

  Download-Page             http://en.wikipedia.org/wiki/Model-driven\_security

  Further Information       

  Added                     16.10.2014
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  Title                     New Digital Security Models
  ------------------------- ---------------------------------------------------------------------------
  Information supplied by   SJE
  Useable here for\*        Telco / ITK privacy issues
  Download-Page             <http://blog.privacytrust.eu/public/Reports/NewDigitalSecurityModels.pdf>
  Further Information       
  Added                     04.10.2014

  Title                     OWASP Top 10 Privacy Risks Project
  ------------------------- ----------------------------------------------------------------------------------------------
  Information supplied by   FS
  Useable here for\*        Addition of information
  Download-Page             <https://www.owasp.org/index.php/OWASP_Top_10_Privacy_Risks_Project>
  Further Information       Will provide us with information about the Top 10 Privacy Risks according to expert surveys.
  Added                     16.10.2014

  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Title                     Privacy Engineering – A dataflow and ontological approach
  ------------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Information supplied by   FS

  Useable here for\*        “it is about applying a structured approach to classification and modelling at data, storage, process, user, and environmental level, illustrated with a few use-cases
                            
                            It has a proposed (or "sample") vocabulary/taxonomy with the aim of engendering PbD from requirements gathering through to end-of-life, and a means to communicate in the organisation, engineering and legal teams. So its not a "cookbook" in my mind, and is one approach to PbD in the engineering lifecycle. As an example of the depth that data modelling for privacy can go to it is good, I think, but it may not be suitable for all organisations.” as to UXOC
                            
                            “I’ve got a copy of the book – have read the initial chapters.  I really like the modelling approach he takes – which encourages drilling down from high level data flows that anyone can understand, to the technical levels where privacy controls can actually get built in.” as to RB
                            

  Download-Page             <http://www.privacyengineeringbook.net> (only overview, Amazon book)

  Further Information       Book by Ian Oliver

  Added                     16.10.2014
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  Title                     “Salt” spelled: NaCl
  ------------------------- ----------------------------------------------------------------------------------------------------------------------
  Information supplied by   CvL
  Useable here for\*        More for the engineering cookbook – About a network comm. library
  Download-Page             <http://cdn.media.ccc.de/congress/2013/workshops/30c3-WS-en-YBTI_OS-Bernstein_Lange_Schwabe-NaCl_and_TweetNaCl.webm>
  Further Information       <http://cdn.media.ccc.de/congress/2013/workshops/30c3-WS-en-YBTI_OS-Jon_Solworth-Ethos_Operating_System.webm>
  Added                     04.10.2014

<span id="_Toc401233223" class="anchor"></span>Companies and Projects

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Homepage**                               **Suggested by**   **Info**
  ------------------------------------------ ------------------ --------------------------------------------------------------------------------------------------------------------
  <http://governor.co.uk>                    [MAG]              \<\<\< PLEASE SUPPLY INFORMATION \>\>\>

  <http://objectsecurity.com/en-home.html>   [MAG]              \<\<\< PLEASE SUPPLY INFORMATION \>\>\>

  <http://pripareproject.eu/>                [CJ]               “PReparing Industry to Privacy-by-design by supporting its Application in Research”
                                                                
                                                                Seems a good attempt. Interested ones should read.
                                                                
                                                                <http://pripareproject.eu/wp-content/uploads/2014/06/PRIPARE-Position-Paper-v1-WP1.pdf>
                                                                

  <https://cryptech.is/>                     [EJ]               They are doing crypto stuff for secured communication. Seem to have some guidelines for HW-design and -evaluation.
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<span id="_Toc401233224" class="anchor"></span>Persons

If you want **your Name added**, just send me an email from the email
account I have to add.\
If you want **your Name deleted** because you do not it in a book which
is not 100% flavored as you like, or you do not want the information in
display, please send me an email.

**But please understand: We cannot keep the discussion going on without
knowing who has which special knowledge or opinion. Just as community we
can correlate all the information.**

  ------------------------------------------------------------------------------------------------------------------
  **Name**   **“Real” Name**          **Task for IPEN**
  ---------- ------------------------ ------------------------------------------------------------------------------
  [AB]       Aral Balkan              =\> Engineers cookbook
                                      
                                      Nice project
                                      

  [CJ]       Christophe Jouvray       Supplies project information

  [CvL]      Carlo von Lynx           Supplies Info about end-to-end encryption, is IPEN lead for mobile solutions

  [EJ]       Erik JOSEFSSON           Supplies company Information

  [FD]       Frank Dawson             Supplies literature

  [FS]       Florian Stahl            Supplies information. OWASP might supply “counter-measures” (?)

  [JMdA]     José M. del Álamo        Supplies research documentation

  [MAG]      Markus Alexander Grete   Cook at the the Privacy Cookbook for Business Process

  [MON]      Mike O'Neill             =\> Engineers cookbook

  [RB]       Richard Beaumont         Supplies information, see governor.co.uk for company information

  [SJE]      Stephan J. Engberg       Supplies slides and PDF

  UL         Ulrich Lang              Supplies information about MD-Security

  UXOC       Ultan X. O’Carroll       Data protection of Ireland, Supplies information and knowledge
  ------------------------------------------------------------------------------------------------------------------

<span id="_Toc401233225" class="anchor"></span>Glossary

  ---------------------------------------------------------------------------------------------------------------
  **Short**   **Element**                      **Abstract**
  ----------- -------------------------------- ------------------------------------------------------------------
  ABAC        Attribute Based Access Control   Idea: Prof. Ravi Sandhu
                                               
                                               @see “Literature” above / „Attribute Based Access Control“
                                               
  Anon...     Anonymising intermediary                                         


  BDSG        Bundesdatenschutzgesetz          German federal law for data protection

  BP          Business Process                 Please refer to: <http://en.wikipedia.org/wiki/Business_process>

  BPM         Business Process Modelling       Constructing BP’s

  PbD         Privacy by Design                Please refer to:
                                               
                                               <http://en.wikipedia.org/wiki/Privacy_by_Design>
                                               
  ---------------------------------------------------------------------------------------------------------------

[^1]: Sorry, in Germany we must make a difference between anonymized and
    pseudonymized as to “BDSG” law.
