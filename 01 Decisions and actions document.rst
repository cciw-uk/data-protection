Decisions and actions document
==============================

This document is a list of decisions/recommendations and actions taken when
applying GDPR.

It currently has a lot of ``STATUS:TODO`` items - these will hopefully progress
to ``STATUS:DONE``, and various future tense sentences will change to past tense.

Approach
--------

First - a fairly long section about my approach to all of this:

* My primary sources have been the GDPR legislation itself, and the UK
  governments guide to it:

  * https://gdpr.eu/tag/gdpr/

    More convenient version here: https://gdpr-info.eu/

  * https://ico.org.uk/for-organisations/in-your-sector/charity/charities-faqs/

  * https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/

  I've read the relevant sections of these. ``STATUS:DONE``

* I've also read all the other materials prepared so far, for reference:

  1. Information_Audit_CCiW May2018.docx (from Rebecca) ``STATUS:DONE``
  2. CCiW Data Protection Policy.docx (derived from EMW as far as I know.) ``STATUS:WIP``
  3. CCiW Working on your own device policy.docm (WOYD, from EMW)  ``STATUS:WIP``

  The recommendations I'm making are intended to completely replace 2 and 3
  in terms of policy documents.

* Taking human psychology into account is vital for all of this work, and this
  is something that is increasingly recognised in best practices.

  For example, in the past people failed to do this when creating password
  policies. They produced rules including things like: passwords must be changed
  regularly; passwords must use certain combinations of types of characters;
  passwords must not be written down. (By the way, all of these outdated ideas
  are in the Data Protection Policy from EMW, section 57)

  These sound secure, but actually result in behaviour that is less secure: if
  people can't write passwords down, they choose simple passwords; if they have
  to keep changing passwords, they choose a few simple passwords and just rotate
  them etc., and also share them between different services.

  So, for those in the industry, these things are now known "anti-patterns"
  regarding security. For a modern best practice document from the US, see
  https://pages.nist.gov/800-63-3/sp800-63b.html#-511-memorized-secrets (created
  2017, updated 2020). It specifically says, among other things:

      Verifiers SHOULD NOT impose other composition rules (e.g., requiring
      mixtures of different character types or prohibiting consecutively
      repeated characters) for memorized secrets. Verifiers SHOULD NOT require
      memorized secrets to be changed arbitrarily (e.g., periodically).

  In place of the old rules, other, much more effective process are recommended,
  processes that take into account actual human behaviour. We should be doing
  the same in all our processes - we should be asking "What will people actually
  do?", rather than create long lists of things they are supposed to do, but we
  know they won't.

* In terms of human psychology, first of all: most people would rather drink a
  pint of lava than read a long data protection policy. Of all the hundreds of
  times that you have claimed "I have read the terms and conditions", how many
  times have you actually read them? Asking people to stop what they are doing
  to read a long doc and tick a box to say they have done so is just asking them
  to lie.

* The one time I actually read a computer use policy was when I had begun
  working for a software development company in Leeds. Due to a planning
  mistake, for the first few weeks I had literally nothing else to do, so I
  actually read the policies. I then attempted to apply them, and found it
  almost impossible to do so, because parts of them were so impractical. I
  looked around, and concluded I should do what everyone else was doing - ignore
  the policy. Within a couple of days I abandoned even the attempt of following
  the policy, and that was the last I thought about it.

  We want to avoid having **any** impractical rules in a document, because it
  will mean that people ignore **all** of it.

* The reason we don't lose sleep over all those online lies we've been telling
  is that we correctly understand those checkboxes as "transactional
  interactions", in which, like in many other circumstances, such as when your
  gran asks you whether you like the jumper she knitted you, truthfulness is
  neither expected nor desired. Also because of experiences of policy documents
  like the one I recounted.

  "Yes I've read the document" checkboxes are therefore the **worst** possible
  model of how to do this kind of thing **if you actually want to convey
  information or change behaviour**.

* We must remember that all our "staff" are unpaid volunteers. We have a limited
  budget in terms of time and energy, and, in terms of inconveniencing people
  and requiring them to do things, we also have a limited "patience budget" that
  we should spend wisely.

* So, **as a matter of policy**, we should **avoid long policy documents**. This
  does **not** mean we don't **have** policies, or that we are not complying
  with laws - it means we build our policies into our practices in more
  effective ways.

* Instead, as far as possible we should enact policies, and train people about
  policies, by putting in controls or training in small, digestible amounts,
  **at the point of action**. For example, instead of asking people to read and
  remember a policy regarding camper booking data, we should have a **short**
  (max 3 sentence) prompt that reminds leaders of the policy **at the point they
  download it**. (Better still is a workflow that doesn't require or even allow
  downloading of data, if that is practical.)

* I suspect that many things copied from other people's documents will
  incorporate very outdated ideas (e.g. ideas about password rotation as above).

* I suspect that many things that are copied from other people are simply not
  appropriate for our context. For example, larger organisations assume you have
  "company computers", and, perhaps "your own device". For CCiW, none of the
  computing hardware we use is owned by CCiW. Many of the things in the document
  are entirely impractical for us, and would simply never be actioned e.g.:

      39.5 A list (appendix 1) will be kept of locations where data is stored by
      the CCiW. This will include CCiW hardware and devices, third-party
      servers, mobile devices, computers and devices owned by volunteers and/or
      contractors used in accordance with the WOYD policy and physical records.

  Are we actually going to keep a list of the location of every personal device
  of CCiW leaders? And what about online services - in general the nature of
  "cloud" computing is that you don't know the location of the computing device.
  And what would this list actually achieve?

  Similarly, in my work for my current client, my boss has had a headache
  attempting to adapt computer use policies from "templates", because our
  company is "remote first", where most people work from their own machines, and
  many policies have that as an afterthought.

  I think it is often easier to write things from scratch with a knowledge of
  CCiW and GDPR rather than trying to adapt someone else's policy.

* That said, we should definitely look at "prior art" even if we don't use it,
  and I will get expert help for any points that can't be answered easily from
  looking at the help provided by ICO etc.

* Role-specific documents are better than policies for everyone. The majority of
  data protection responsibilities fall on the CCiW web master, so the longest
  manual is the "CCiW Website security policies", which already existed and has
  been updated.

  We also need specific guidance for the booking secretary and DBS officer.

* We should start with our **existing processes and people**, and see where
  things need tightening. In a very small organisation like ours, the current
  division of labour should be our guide as to who probably has the knowledge to
  to write a policy. As web master I should basically be responsible for our
  security and data protection requirements, and I'll work closely with Rebecca
  and Becky to produce something for them.

  The outdated password rules I mentioned above also highlight the fact that we
  should not be writing rules that we're not qualified to write - we should be
  delegating to the appropriate people.

* Regarding the 4 sets of data Darren identified:

  1. Campers/ parents/ guardians data
  2. Officer Team data inc.  Set up & take down teams
  3. Trustees data
  4. Land owners and suppliers

  Item 3 is the most easily dealt with - I think it almost all be public data
  (it has to be given to Charities Commission, and displayed on their website,
  right?). We clearly have to keep this information anyway. If there are addresses
  we don't need to be keeping, we can just remove from CCiW records - we know each
  other as individuals anyway, so have no problem contacting each when necessary.

  Item 4 is also easy - these are just business contacts that we need
  to keep to do our job.

  Items 1 and 2 are the most difficult - they contain the most sensitive
  information, and are much bigger in terms of volume. Almost all our effort
  will be focused there.

* It is better to have one document than two that have to be kept in sync.

* A document that is both human-readable and a machine-readable **executable**
  document is better than just human-readable.

  Since we actually have to implement a lot of our policies in terms of
  software, in some cases I'm intending to make the machine readable document be
  the official policy document, and make it part of the CCiW source code.

  These documents will then be read by software and applied as part of our data
  protection or retention processes.

  This has some other advantages - for example, our software can check the
  document for exhaustiveness. So, for example, if I add an extra table or
  column to our database, but without updating the "Data Retention Policy", our
  deployment checks will automatically complain that no data retention policy
  has been created for these fields, forcing us to ask those questions.

  An example of something like this that already exists is the ``static_roles.yaml``
  file, which is machine readable, "human readable" (ish - I could improve
  this), plus has comments with extra explanation:

  https://gitlab.com/cciw/cciw.co.uk/-/blob/master/config/static_roles.yaml

  This should be the **only** document for this, to help ensure that we don't
  have a disconnect between what we want our policy to be, and what it actually
  is.

* Hyperlinks are awesome! We should include links to other resources, rather
  than copy large parts of them. For the sake of making this document more
  readable I'll sometimes copy rather than link.

* So, I think the right order is:

  1. Create the "manuals" (as mentioned by Wayne's document), especially
     for webmaster, booking secretary, DBS officer and leaders. This will:

     * start from our existing policies

     * apply rules from GDPR to improve our processes where needed, enacting
       changes as we go, bearing in mind what is actually practical for us.

  2. Extract the overall "policy document" from that.

  I realise this is the opposite order to the work that has been done so far,
  but I don't think that work has been wasted - it's very helpful to see other
  approaches, and the other rules that people have created.

* I think the overall policy document can be very short - it will just be a
  section in the camp manual. The reasons for this are:

  * Our policy on not having long documents that no-one will read.

  * We don't need to repeat or summarise anything that is in the GDPR. A large
    amount of the document adapted from EMW is repetition of the GDPR, which
    actually brings dangers — Chinese whispers — as well as adding a lot of
    extra words.

  * We don't need to mention that we will "comply with the GDPR", or slightly
    more specific things like "we'll store data securely" - just like we don't
    need a policy that says "we won't drive more than 30 mph in a 30 zone", or
    "we won't commit fraud" - we are already legally bound to do those things. A
    policy that says "we will store data securely" will do absolutely nothing to
    either 1) ensure that we do store data securely or 2) protect us from
    litigation if it turns out we didn't store data securely.

    What we need to say is **how** we'll store data securely, and **who** will
    implement these things or be responsible for them.

So the policy documents I will produce should hopefully be very short. In
contrast, this document will be much longer, as I'll document every specific
decision and the reasons for them as I go. So the committee will need to read
this, but after that it can be filed away.

About me
--------

For the sake of future reference, in case this is needed at some point to
demonstrate our due diligence, I thought it might be appropriate to include some
information about me, as the author of this document, especially in terms of my
competence to make decisions regarding security of computer systems.

* Name: Luke Plant

* I am a software developer with over 20 years experience, especially in web
  development, and in a range of sectors (automotive industry, employee at a
  software consultancy that did a lot of work for public bodies, Open Source,
  e-commerce, medical consultancies). I'm currently with `MAT
  <https://www.marketaccesstransformation.com/>`_, a young but fast growing
  medical research consultancy, as their lead backend developer.

* In particular, I'm a core developer of `Django
  <https://www.djangoproject.com/>`_, probably the leading web development
  framework for the `Python <https://www.python.org/>`_ programming language.

  Python is currently ranking 3rd most popular programming language in the
  `TIOBE index <https://www.tiobe.com/tiobe-index/>`_ and Django is used very
  widely, in many large and small websites, including Instagram and many others.

  Despite not being very active in Django itself for some time, I remain one of
  the larger contributors historically (see the `contributors stats
  <https://github.com/django/django/graphs/contributors>`_, I'm `spookylukey
  <https://github.com/spookylukey/>`_, currently in 11th place).

  I contributed several key components of Django's security related code, which
  have helped contribute to Django's very good reputation for security,
  including:

  * its CSRF protection mechanism (Cross Site Request Forgery) - Django didn't
    have any protection out of the box when I started using it.

  * its password reset mechanism - originally Django had a rather insecure one!

  You may also be interested to know that both of these security components
  started out life in the CCiW web site!

* I have been a part of CCiW (and, previously EMW outdoor camps) for a very long
  time, as the child of a leader, a camper, an officer and assistant leader, and
  have a very good idea of how the camps run.


GDPR notes
----------

Notes I've made while reading the GDPR. You can skip or skim this whole section,
refer back to it as necessary.

Chapter 1 - General Provisions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Article 1

  - it's about people's data

- 2

  - it applies to the kind of thing CCiW does.

- 3

  - it applies to CCiW because we are in the EU and activities take place in EU.
    (Technically we're not in the EU any more due to Brexit, but we assume the same
    rules will hold).

- 4

  - we hold "personal data" about people

    - leaders + officers
    - campers + parents

    Also "Trustees data" and "Land owners and suppliers" that Darren mentioned - how are these held? QUESTION

  - we have a "filing system" - the CCiW website database. ``STATUS:QUESTION`` -
    any others?
  - we "process" data, and we are a "data controller"
  - we do not store "genetic data" or "biometric data"
  - we do store "data concerning health"
  - we don't do "cross-border processing"


Chapter 2 - Principles
~~~~~~~~~~~~~~~~~~~~~~

- Article 5 - Principles

  1. Personal data must be

     a. processed lawfully ‘lawfulness, fairness and transparency’

     b. 'purpose limitation' - We may need to explicitly specify purposes of collected data

     c. 'data minimisation' - must be 'adequate' for purposes, but not more.

     d. 'accuracy' - includes keeping up to date, w.r.t. "the purposes for which they
        are processed". So, we don't keep old medical records "up to date", but we
        have a separate record for each year the camper comes, and they update
        them before coming on camp. So we are in compliance here.

     e. 'storage limitation'

        Language implies that where data is anonymised, it ceases to be personal
        data and different rules apply

     f. 'integrity and confidentiality' i.e security

        Includes "accidental loss" and destruction as things we should protect
        against, which has implications for things like encryption (e.g. if you
        encrypt and lose the keys, then you have lost the data).

  2. 'accountability' Need to be able to demonstrate compliance, which means
     documenting our processes.

- Article 6 - Lawfulness of processing

  1. At least one of the following must be satisfied for data processing
     to be lawful.

     a. consent

     b. necessary for contractual obligation

     c. necessary for legal obligation

     d. necessary for protecting vital interests of someone

     e. necessary for public interest or official authority

     f. necessary for "legitimate interest"

  2. Adaptations by EU member states

  3. c. and e. above have basis in other EU/state lawas

  4. If processing for a different purpose than the stated one for collection,
     without 'consent', then to determine if it is "compatible" processing,
     you have to take into account other factors (listed)

     We can avoid some of the complexities of working out exactly what
     this means by limiting the processing of data as much as possible,
     e.g. by basing everything on contractual obligations or consent, and
     making clear exactly what we'll process data for.

- Article 7 - Conditions for consent

  If you are relying on 'consent' as basis, there are lots of extra rules.

  - written declarations have got to be clear and accessible in language

  - you can't require people to give consent for some purpose as a condition
    of a contract in which that purpose is not necessary. e.g. you can't say
    "you can only buy this product if you agree to your details being passed onto
    some other group. Do you agree to your details being passed onto them."

  We can avoid a lot of these complexities by not relying on consent as much as
  possible.

- Article 8 - About consent w.r.t. children

  - For children under 16, we have to get consent from parents instead of the child.

- Article 9 - Special categories

  Prohibition/limitation on processing certain types of personal information, including, relevant
  to us:

  * data concerning health
  * religious or philosophical beliefs

  To process these, you can't rely on the whole list of options in 6.1, you must have:

  a. consent

  b. necessity for certain obligations/rights, including area of employment and safeguarding.

  c. necessary for vital interests.

  d. for non-for-profit bodies, if it relates to members of the body, and

  e. knowledge made public

  f. defence of legal claims, court use

  g. reasons of substantial public interest

  h. various health reasons of individual

  i. public health concerns

  j. archiving purpose in public interest


- Article 10 - Data relating to criminal convictions

  Must be done under control/authority of UK law

- Article 11 - Processing which does not require identification


Chapter 3 - Rights of the data subject
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Article 12

  1. Clearness of language/communication

  2. We can't refuse to grant data subjects their rights, unless
     we can show that we can't identify the subject. This has relevance
     for processes regarding disclosing information in requests for info
     i.e. how we determine if it's really coming from the person claimed.

  3. About delays allowed

  5. Charges, dealing with unreasonable requests

  6. Identification of person asking for information etc.

  7. Use of icons and machine-readable data regarding Art. 13, 14


- Article 13 - Information to be provided where personal data are collected from
  the data subject

  1. When collecting info from people, we need to make clear
     the purposes and lawful basis of our use of that data,
     and who will receive the data.

  2. We must tell people about our retention policy when collecting data, plus
     other info about their rights. ``STATUS:TODO`` quite a few additions to our
     forms are necessary here.

- Article 14 - Information to be provided where personal data have not been
  obtained from the data subject

  This has particular relevance to our collecting of references.

  On the officer application form, in the section about referees name we many
  need to include more information about what information we will obtain from
  the referee, the legal basis, and about their rights concerning this data.
  ``STATUS:TODO``


- Article 15 - Right of access by the data subject

  The data subject has rights to see the personal data about them, and various
  other pieces of info, such as the purposes etc. We can fulfil these
  obligations in most cases by providing them with explanations up front. Some
  things could be fulfilled by an appropriate page on the website that would
  allow a subject to download information about them.

  The biggest concern here is what we do about references. These could easily
  contain things that the referee would not want to be disclosed - if the
  referee provides information about an officer being unsuitable for camp work,
  they may not want that to be shared with the officer, and the knowledge that
  it could be shared might compromise the reliability of the reference. We may
  need specific legal advice on this.


- Article 16 - Right to rectification

- Article 17 - Right to erasure (‘right to be forgotten’)

  1.a. when data is no longer necessary for our purposes, the data subject
  has a right to erasure.

  For our purposes, there are various pieces of data that we made need to keep
  long term, including:

  - list of campers on each camp. In the case of an allegation being made in the future,
    we made need complete lists of campers who actually attended camps, along with
    list of officers.

  - to demonstrate due diligence in our selection of officers, we may need to keep
    references about them and some information about criminal records checks.

  Paragraph 3 also gives further exceptions that may apply to us, specifically
  3.e. “for the establishment, exercise or defence of legal claims.”

  We may need to confirm these things with an expert.

- Article 18 - Right to restriction of processing

  Very little here applies to us since most of our information is obtained
  from the data subject, and our "processing" of the data is very limited
  in nature (mostly "storage").

- Article 19 - Notification obligation regarding rectification or erasure of
  personal data or restriction of processing

  We have to pass on rectification/erasure change to those people who received
  the data, in our case very few people outside CCiW, if any, are given our
  data.

- Article 20 - Right to data portability

  When providing downloadable data to people, we need to use a commonly
  used data format that allows for machine processing.


- Article 21 - Right to object

  Specifically, data subjects can object to processing based on 6.e and 6.f i.e.
  "legitimate interest" or public interest. For us, this means that they can
  object to being put on an advertising mailing list (which we can do based
  on legitimate interest). We need to honour their opt-out request.

  We need to work out how we best implement that, in order to avoid accidentally
  putting them back on in the future.


- Article 22 - Automated individual decision-making, including profiling

  We basically don't do this, apart from a few cases where the exceptions listed
  apply to us. For example, based on birth date we exclude campers from
  attending camp (they are prevented from booking) but that is a necessary part
  of fulfilling our contracts.

- Article 23 - Restrictions

  "Member States" e.g. UK, can reduce the scope of some of the requirements.


Chapter 4 - Controller and processor
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Article 24 - Responsibility of the controller

  As well as being required to implement the technical measures needed for
  compliance, we need to be able to "demonstrate" compliance. For this, being
  able to show our manuals and the web site source code will be helpful.

  It also notes, paragraph 1, the need to "take into account..the risks of
  varying likelihood and severity for the rights and freedoms of natural
  persons". This means we can and should be sensible about the actual kinds of
  risks that CCiW is likely to face.

- Article 25 - Data protection by design and by default

  1. Use of data protection techniques

  2. By default we only use necessary data and don't make it public

  The technical things needed for this are already in place in our website - we
  don't make the database open to all, for example, but on a need to know basis
  using authentication.

  Use of a data retention policy that is automatically checked for exhaustiveness
  will also help us remain compliant - if we add a database column, it will
  immediately force us to ask if we need it, how long we need it for etc.

- Article 26 - Joint controllers

  Doesn't apply to us as far as I can see.


- Article 27 - Representatives of controllers or processors not established in
  the Union

  Doesn't apply to us.

- Article 28 - Processor

  We need to be careful about who we pass on data to. Currently we have very
  limited use of 3rd parties via the website. ``STATUS:QUESTION`` Are there
  other people that we pass data on to?

- Article 29 - Processing under the authority of the controller or processor

- Article 30 - Records of processing activities

  1. We need to maintain a "record of processing activities". This probably
     needs to be a single document. It's possible that our web site data
     retention policy will be able to function as this document, if slightly
     expanded. ``STATUS:TODO``

  5. There are exemptions for some groups, but it probably doesn't apply to us:

     While we are less than 250 employees in the organisation, we do process
     some special category data, and data relating to criminal convictions,
     even if at very low scale.

- Article 31 - Cooperation with the supervisory authority

- Article 32 - Security of processing

  1. b) and c) include the need for ongoing "availability" of data, which has to
     be put alongside other things like encryption in part a). This means we
     have to weigh risks associated with encryption that could cause loss of
     availability (if you lose the encryption keys, the data is gone).

- Article 33 - Notification of a personal data breach to the supervisory authority

  Exactly what constitutes a data breach and when you need to contact ICO seems
  to be one of the most fuzzy subjects, but there is quite a lot of help here:

  - https://ico.org.uk/for-organisations/guide-to-dp/guide-to-the-uk-gdpr/personal-data-breaches/
  - https://ico.org.uk/for-organisations/report-a-breach/personal-data-breach/personal-data-breach-examples/
  - https://ico.org.uk/for-organisations/report-a-breach/personal-data-breach-assessment/

  We will need to add training on this to various manuals. ``STATUS:TODO``

  5. We need to set up a process for documenting data breaches and their
     handling.


- Article 34 - Communication of a personal data breach to the data subject

  - Note that the conditions for reporting to data subjects are different to
    reporting to ICO. It is very likely that data breaches we might suffer will
    fall under the exceptions given.

- Article 35 - Data protection impact assessment

  We need to do these DPIA for the data we hold.

  It is very unlikely that we will need or want to do processing of a type
  that needs an impact assessment as per the description in paragraph 3.

- Article 36 - Prior consultation


- Article 37 - Designation of the data protection officer

  We don't need to do this, and shouldn't - see below.

- Article 38 - Position of the data protection officer

  Not relevant

- Article 39 - Tasks of the data protection officer

  Not relevant

- Article 40 - Codes of conduct

  Largely irrelevant for us at the moment because:

      "There are no approved UK GDPR codes of conduct at the moment, but we are
      actively working with various sector bodies and associations to assist
      them in developing codes of conduct and are keen to talk to others who may
      be considering development of a code."

   https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/codes-of-conduct-detailed-guidance/ico-register-of-uk-gdpr-codes-of-conduct/

   It's unlikely that an approved code of conduct will be established for a
   sector that is appropriate for us, given our small size as an organisation.

- Article 41 - Monitoring of approved codes of conduct

  Not relevant due to the above

- Article 42 - Certification

  Probably not relevant to us - it's very unlikely there will certification
  mechanisms appropriate for us.

- Article 43 - Certification bodies

  Ditto

Chapter 5 - Transfers of personal data to third countries or international organisations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Largely not relevant to us - we don't transfer personal data to other people.

Chapter 6 - Independent supervisory authorities
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Relates to bodies in member states (e.g. ICO in the UK), and their duties

Chapter 7 - Cooperation and consistency
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

How bodies in member states cooperate with EU etc. Not relevant to us


Chapter 8 - Remedies, liability and penalties
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Article 77 - Right to lodge a complaint with a supervisory authority

  Every data subject in the UK has a right to complain to ICO concerning
  violations of GDPR.

- Article 80 - Representation of data subjects

  People can use other (specified) organisations to represent them in these
  things.

- Article 82 - Right to compensation and liability

Chapter 9 - Provisions relating to specific processing situations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Very little of relevance to us here.

Chapter 10 - Delegated acts and implementing acts
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Very little of relevance to us here.

Chapter 11 Final provisions
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Very little of relevance to us here.

Understanding the GDPR
----------------------

Some general points to understand the GDPR:

* While I'm not a fan of every piece of legislation that has come out of the EU,
  the GDPR seems entirely reasonable to me, and not overly burdensome in any
  way. For every obligation there are always the reasonable exceptions and
  caveats that need to be in place, and it explicitly talks about the need for
  balance at various points.

  I say this to point out the fact that it is basically just asking us to do
  what is right with people's data, which means we should have a positive
  attitude towards it, especially as we are already doing what is right - we're
  not selling people's data or being negligent with people's privacy, we're
  collecting only what we need to look after campers properly. We are not the
  bad guys that the GDPR was written for.

  I'm not saying we don't need to pay attention to it, just that we shouldn't
  have an attitude of fear that causes us to actually start getting the balance
  wrong and increasing risk to campers.

* The GDPR requires us to have a "lawful basis" for keeping and using personal
  data. The most commonly talked about one is "consent", probably because that
  is the most visible - you get explicitly asked for your consent. However,
  there `other bases <https://gdpr-info.eu/art-6-gdpr/>`_, several of which are
  often more important to us - specifically "legitimate interest", "protecting
  vital interests", "legal obligation" and "contractual obligation".

  In many cases, we should focusing on these latter ones, because they are more
  relevant to us, and because properly meeting the requirements for "consent" is
  often quite hard. What I'm saying is that we don't need to think "we need
  explicit consent to use every piece of information in every specific way" - we
  usually don't.

  Also, ad-hoc processes that attempt to get consent for something probably
  won't satisfy the GDPR's requirements for true consent. Any use of personal
  information depending on consent has to be carefully designed ahead of time.
  For example, an officer could not just say "Oh I asked the camper and they
  said it was fine to use their email address for this" - this will not qualify
  as consent.

* The GDPR includes the more "positive" sides of data protection as an
  obligation. It's not just about using information wrongly or passing it on to
  the wrong people, it's also about using information correctly and keeping it
  safe so that we can do that.

Decisions and recommendations
-----------------------------

General
~~~~~~~

* We should, as a default attitude, aim to limit the amount of personal data we
  collect to the things that are essential (or very useful) for doing our job
  well in terms of looking after campers and running CCiW. Our default mindset
  should be "don't collect it" rather than "find a justification for
  collecting/keeping it". (I think this already reflects our current attitude
  and practices).

  For example, analytics trackers on websites (such as Google Analytics) have a
  variety of privacy concerns, and, for our usage, such analytics is of very
  limited value. So we don't use these services. (Instead we have some limited
  log-based analytics on our own servers that don't have any privacy concerns -
  much more basic than what Google Analytics provides, but that's fine for us).

* We should start from the premise that in CCiW, when it comes to computers, all
  our volunteers are using their own "device". The only system that is easy for
  us to secure is the central CCiW database that is part of the website. We
  should design processes that make the most of this centrally controllable
  database, and understand that most other devices will not be easily
  controlled. So, for the most part, **CCiW volunteers should be protected from
  the need to have sensitive data on their own devices**.

* For this reason, a large part of the responsibility for understanding and
  implementing GDPR will fall to the web master/web developers.

* Website-related security and data protection policies will, as far as
  possible, be woven into the web developer documentation, which is in the
  source code repository, and not in separate documents. This is because a good
  approach to data protection forms an integral part of how the web developers
  need to build the website software.

* We will minimise the amount of "downloading" of sensitive data that
  can be done on the website.

  * only leaders will be able to download camper data. ``STATUS:DONE`` (since
    the beginning)

  * only leaders will be able to view officer data. ``STATUS:DONE`` (since the
    beginning)

  * we will train leaders at the point of download with rules about use of this
    data ``STATUS:TODO``.

Risks
~~~~~

As noted above, GDPR article 24 specifically says that we must "take into
account...the risks of varying likelihood and severity for the rights and
freedoms of natural persons".

In general, it is helpful to think of "risk" = "likelihood" × "severity (of
consequences)". We'll look at these below:

Likelihood
~~~~~~~~~~

Coming from computer security background, one helpful way to think about
security risks is to list "attack vectors" i.e. methods or places where we are
exposed to attacks.

Some attacks depend on being specifically targeted. I estimate that the
probability here is very low, due to the fact that the information we store is
simply not easily "monetisable" by any attacker:

* The health data we store is extremely limited in nature (allergies, current
  medication etc.), and very low value to any attacker, and (with data retention
  policies applied) very small in volume.

* The criminal record information we store could potentially be attractive to an
  attacker for the purposes of blackmail or something, but what we store is very
  small in volume, and also mostly inaccessible online (``STATUS:TODO`` confirm
  what we do actually store and how).

Our main attack vectors are:

* non-targeted online attacks. These can happen when online attackers scan
  internet sites for known vulnerabilities, trying to gain access.

  Probability: moderate - we can't avoid being targeted like this, and the ease
  with which online attacks can be done (relatively anonymous, or easily
  anonymised) means there are few disincentives.

* phishing attacks: people trying to gain access to CCiW by "social engineering"
  attacks on CCiW volunteers (emails that trick you into giving a password).

  Probability: low - these attacks are usually targeted, and we are unlikely to
  be a target.

* physical attacks i.e. theft of devices owned by CCiW volunteers, leading
  to data falling into other people's hands.

  Probability: very low. The probability of devices being stolen is not
  especially low, but such thefts will almost always be for the hardware, and
  not for the data we store. This is because:

  * Most thieves will want to wipe devices as soon as they can, because of the
    possibility of tracking apps or incriminating data (i.e. it is obvious the
    device was owned by someone else).

  * A targeted physical attack (someone stealing a device for the sake of
    getting at our data) is extremely unlikely - our data has so little value to
    an attacker, the risks of being caught massively outweigh any potential
    profit.

* leaking of camper data to other campers while on camp.

  Probability: moderate - we cannot avoid having this data in close proximity to
  campers in some form. They are unlikely to be very interested in it however.

Severity
~~~~~~~~

Another thing we can borrow from computer terminology the importance of thinking
about "denial of service" vulnerabilities. In computer security terminology,
this is when a fault means that a service or system becomes unavailable,
triggered either accidentally or by the deliberate action of an attacker. In
contrast with other security vulnerabilities, which are usually of the kind "the
system can be made to do something it wasn't supposed to do", this kind is "the
system can become **unable** to do what it **was** supposed to do".

We need to have both in mind when listing and evaluating the risks we face,
which I think include the following, in order of decreasing severity:

* By far the most serious consequences from failing to have safe systems is a
  "denial of service" vulnerability - that we do not have the medical
  information needed, at the time we need it, to look after campers on camp.

  In this situation, we might fail to take into account an allergy or some
  regular medication that is needed, or fail to pass on this information to a
  medical professional in the event of an emergency when we take a camper to
  hospital. The results could be serious health consequences or even loss of
  life.

* Leaking of officer information regarding criminal convictions, or other issues
  that are mentioned on their application form. This has the primary consequence
  of loss of personal reputation, which could have serious consequences for
  their lives.

* Leaking of personal camper data on camp to other campers.

  * This could lead to teasing/bullying in some cases e.g. if there is a
    bed-wetting problem or learning difficulty that is mentioned on a medical
    form.

  * It could lead to some loss of privacy and possibly harassment e.g. a camper
    finds another camper's contact information and uses it to harass them after
    camp.

The risks above, with both likelihood and severity, should help inform our
policies and how we balance different responsibilities.

Another way to think about some of these issues is in terms of "fail safe"
behaviour. To establish what "fail safe" is requires you first to have worked
out what your greatest risks are.

For example, elevators are usually created with fail safe break mechanisms so
that if cables snap, or power fails, the `breaks come on
<https://science.howstuffworks.com/science-vs-myth/everyday-myths/question730.htm>`_.
This may mean that you get stuck in the elevator shaft, but it is assumed that
this will only be an inconvenience, not dangerous. However, if being in the
building is itself dangerous, the "fail safe" itself becomes dangerous - which
is one reason you should never take an elevator in the event of fire or
earthquakes. You have to know what the greatest danger is to know what "safe"
is.

Camper data on camp
~~~~~~~~~~~~~~~~~~~

We need to have camper information, including medical forms, and store these
safely.

I recommend that we should print out all medical forms for use on camp (as we do
currently), with enough copies to ensure that a complete set can easily be taken
with every group of campers who might go in different directions for activities,
plus spares. This can easily be done from the downloaded booking forms (a few
A4 sheets for the whole set).

Once on camp, they should be stored in an officer-only part of the camp site,
and all officers must know this location, be able to get the sheets from there.
They should not be left in camper tents or officer bags overnight - they should
be kept physically with the officers and returned to the safe place when
finished with for the day. Campers should not be told the location.

Instructions for use of these forms will be downloaded and printed out with the
forms (as a cover sheet).

Electronic devices for medical info?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Use of phone or tablets has been suggested as a possibility. Relatively
speaking, electronic devices are extremely vulnerable to a range of physical
attacks/flaws:

* theft - they are much more likely to be stolen by an opportunistic thief,
  compared to a few pieces of paper that we are carrying around.

* power failure due to running out of battery - especially on camp where we
  often have insufficient electric supply for the large number of people who
  want to charge devices.

* accidental breakage - e.g. from water damage or rough treatment on camp.
  (Paper is also easily damaged by water, but it is also much easier to protect
  with simple waterproof envelopes, and many, many times cheaper to bring or
  make extra copies.)

For these reasons, I would strongly recommend against relying on any electronic
devices for access to medical data while on camp - paper is a fantastic
technology - cheap, light, very flexible (quite literally), far more secure
for our purposes, and we should use it (as we have been).

Use of a safe?
~~~~~~~~~~~~~~

The use of a safe for storing documents on camp would introduce a significant
"denial of service" vulnerability - the safe could fail physically, or the
officers needing access may not have keys or may not have remembered unlock
codes. Since medical emergencies can happen at any point, and sometimes time is
of the essence, in my opinion this would introduce an unacceptable risk.

To put it another way, the "fail safe" mode of a safe is wrong for our use case
(see above). Safe designers assume the contents must not be stolen, but you
wouldn't normally need to get at the contents in a big hurry; therefore, it is
best to lock you out in the case of electronic failure. But this is no good for
us - if a leak in the tent causes water to pour over the electronics, the fail
safe mechanism will cause the medical forms to get locked inside, when our
biggest danger is not having access to the medical information.


Data Protection Officer
~~~~~~~~~~~~~~~~~~~~~~~

* Do we need to appoint a DPO (Data Protection Officer)? **NO**

  See `Do we need to appoint a Data Protection Officer
  <https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/accountability-and-governance/data-protection-officers/#ib1>`_

  Under the GDPR, you must appoint a DPO if:

  * you are a public authority or body (except for courts acting in their judicial capacity);
  * your core activities require large scale, regular and systematic monitoring of individuals (for example, online behaviour tracking); or
  * your core activities consist of large scale processing of special categories of data or data relating to criminal convictions and offences.

  The closest we get is point 3 (due to health information and criminal records
  information), but it is certainly not a "core activity" (see `What is a core
  activity
  <https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/accountability-and-governance/data-protection-officers/#ib3>`_)
  and our scale is very low.

* Should we appoint one anyway? **NO**

  We can if we want. However:

      If you decide to voluntarily appoint a DPO you should be aware that the
      same requirements of the position and tasks apply had the appointment been
      mandatory.

  And the bar is not low:

      The DPO must be independent, an expert in data protection, adequately
      resourced, and report to the highest management level.

  In our case, due to the small size of our organisation, we wouldn't be able to
  provide anyone from within CCiW who was either “an expert in data protection”
  or “independent”. Under `Can we assign other tasks to the DPO?
  <https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/accountability-and-governance/data-protection-officers/#ib8>`_:

      The GDPR says that you can assign further tasks and duties, so long as
      they don’t result in a conflict of interests with the DPO’s primary tasks.

      …the DPO shouldn’t be expected to manage competing objectives that could
      result in data protection taking a secondary role to business interests.

  That probably rules out most people already involved in CCiW. We could
  possibly pay someone externally, but most likely don't have the funds.

Use of email
~~~~~~~~~~~~

* We will not email sensitive data:

  * ``STATUS:DONE`` - several years ago we switched from emailing application
    forms and references to instead sending email notifications and allowing
    them to be viewed online.

* We should not use "@cciw.co.uk" email **accounts** (using a provider like
  Google or Microsoft 365). We have to take into account what will actually
  happen:

  * CCiW volunteers will forget to check these accounts - they are *unpaid
    volunteers*, not full time workers, and have to be treated as such, and for
    most of the year they will get very little if any email on these accounts.
    It's not realistic to expect them to check those accounts regularly.

  * When owners of @cciw.co.uk accounts forget to check them, and the mail is
    not replied to promptly:

    * other people trying to contact us will try other personal email addresses
      they know (and may have done that anyway - we can't control what addresses
      other people use to email us, and we tend to know a lot of campers and
      their parents personally).

    * CCiW volunteers will eventually realise that they can use the email
      providers 'forwarding' feature to forward email to their personal address
      to stop themselves forgetting.

  * And so you end up back where you were, but now with a false sense of
    security and compliance, and, even worse, you will have created some
    processes that assumed we have secure @cciw.co.uk accounts that we could
    send sensitive data to.

  The few @cciw.co.uk email addresses we have at the moment are simply
  "forwarding addresses" which redirect to personal email accounts, and I
  recommend we continue to do this. We will design processes and practices that
  do not involve sending sensitive data by email as far as possible.

  (``STATUS:DONE`` This is already current practice on the website and has been
  for several years. We may need to tighten some things regarding telling
  leaders what they can and can't do with lists of camper data etc.)


Online authentication systems and passwords
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* We will use `NIST Special Publication 800-63B
  <https://pages.nist.gov/800-63-3/sp800-63b.html>`_ as a general reference
  standard for securing digital identity. This is a modern, pragmatic set of
  guidelines that are widely used in the industry.

  While the data CCiW holds is sensitive, we are relatively low risk in terms of
  expecting cyber attacks, as noted above.

  Therefore, we have adopted the following minimum levels:

  * General CCiW staff authenticating to the CCiW website: Authenticator
    Assurance Level 1 (see NIST document)

  * Webmaster authentication to systems that give access to the site:
    Authenticator Assurance Level 1 (see NIST document)

  * Campers/bookers: a level equivalent to AAL1, but implemented using a
    password-less system which improves security and user experience, as
    described `here
    <https://lukeplant.me.uk/blog/posts/a-simple-passwordless-email-only-login-system/>`_.

  Most of these have been in place a long time, but some additions have been
  made recently:

  * Apply NIST-800-63B  § 5.1.1.2

    * Require 8 character min and add "compromised passwords" checker
      `pwned-passwords-django
      <https://github.com/ubernostrum/pwned-passwords-django>`_ -
      ``STATUS:DONE`` in `change 583a6d00
      <https://gitlab.com/cciw/cciw.co.uk/-/commit/583a6d00504a05cded071e7e04ea7c79b3bfd40a>`_

    * For existing passwords, which wouldn't normally be affected by the
      validation rules on the 'set password' page, we've added validation of
      passwords on next login, forcing a password change if it doesn't meet the
      new standards. ``STATUS:DONE`` in `change dd4b6c79
      <https://gitlab.com/cciw/cciw.co.uk/-/commit/dd4b6c79b193e5b16ebf435bf6b9dc4d00c5608f>`_

      (We cannot check existing passwords meet criteria, because we don't know
      what they are - as per best practices, we don't store passwords but only
      password hashes. So we can only check on next login).

Data Protection Impact Assessment (DPIA)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

We need to do this in some form for all the data we hold and use.

See https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/data-protection-impact-assessments-dpias/what-is-a-dpia/

For data held in the website database, it might be appropriate to combine this
with the data retention policy - this details every piece of information we
store, and we can at the same time document the need for this information. We
can also have that document be checked for exhaustiveness automatically, as part
of the website software test suite, so that any new fields added to the database
are brought to our attention for checking.

It may help to have a separate document that details the decisions and risk
factors we think for different types of processing, similar to the DPIA
templates on ICO.

We need to also do this as part of documenting processes for DBS officer and
booking secretary.


Data retention etc.
~~~~~~~~~~~~~~~~~~~

* ``STATUS:DONE`` Removed some unneeded data in officer application form
  (employment history)

* ``STATUS:TODO`` Retention Policy

  - write it down as a machine readable document in the CCiW source code
  - implement it in terms of wiping data from CCiW database


https://allaboutuklaw.co.uk/statute-of-limitations/


Data breaches
~~~~~~~~~~~~~

As per GDPR Art. 33 para 5., we need to document all data breaches and
potentially report them to ICO.

It is very likely that the number of such incidences will be very low, and we
will manage this with a Google Docs document that the committee and webmasters
have access to:

https://docs.google.com/document/d/1KFTIin9xxb0aN9lXtKRLk5q6aEw0DXOmCHamNT7s5Sw/  ``STATUS:WIP``

We need to add simple processes to relevant manuals, especially:

* Leaders
* Webmaster
* Booking secretary
* DBS Officer

``STATUS:TODO``


Legal defence considerations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

As much as possible, we don't want to be storing details of criminal records,
due to the privacy concerns.

However, we also need to remember that abuse could happen on camp, and whether
it happens or not we are open to allegations. Such allegations could come out a
long time later.

In such situation, we have a need and right to defend ourselves against
accusations, and this is recognised by the GDPR (see Article 9 item f).

For this reasons, I'm recommending that the following information should be kept
essentially forever, overriding the "right to erasure" and other concerns (in
accordance with the exception made in GDPR Article 17 paragraph 3.e.)

* List of names of all campers on camp, with the name of the parent/guardian.
  The purpose here is to be able to identify a complete list of campers present
  on a camp.

* Records of DBS checks we've made:

  * The records stored in the CCiW website, which actually store no information
    about criminal convictions, just a decision.

  * The separate document that we keep detailing cases where we had to make a
    decision for officers who had criminal convictions - see the section in `02
    Amendments to CCiW handbook.rst <02%20Amendments%20to%20manual.rst>`_



Security tightening and consolidation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* New AWS account for CCiW, instead of my personal one, with documented
  setup procedures  ``STATUS:DONE``

  - use for AWS S3 backups ``STATUS:DONE``
  - recreate AWS SES config (email) using new account ``STATUS:DONE``
  - move everything off Mailgun ``STATUS:DONE``


Uncategorised
~~~~~~~~~~~~~

* ``STATUS:TODO`` - Add privacy notice to website

  https://ico.org.uk/for-organisations/in-your-sector/charity/charities-faqs/

  - One for officers
  - One for campers/parents

  Can be very short, because it mainly says:

  - we do not share any data with 3rd parties
  - we collect only the necessary data for providing camp activities, namely:

    - contact data for people coming on camp
    - health information so we can look after campers while on camp.
    - criminal records/references/etc. to ensure camper safety

* ``STATUS:TODO`` Register with ICO?

* ``STATUS:TODO`` Create "Appropriate Policy Document" (for health and criminal records data)

* ``STATUS:TODO`` Contact Becky about her DBS processes

* ``STATUS:TODO`` Find out rules for privacy breach, add to relevant manuals

* ``STATUS:TODO`` Links for downloadable private data should prompt regarding data
  protection when clicked

* ``STATUS:TODO`` downloaded camper data XLS should contain cover sheet
  with relevant policy regarding use, especially for medical data.

* Review ``STATUS:TODO`` items in website security document

* Move source code to GitLab, and correct in source code and other
  documents. This makes it easy for people to see our source code, including
  data retention policy.  ``STATUS:DONE``

* ``STATUS:TODO`` Decide policy on external storage devices
