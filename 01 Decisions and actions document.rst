
This document is a list of decisions/recommendations and actions taken when
applying GDPR.

Approach
--------

First - some points about my approach to all of this:

* My primary sources have been the GDPR legislation itself, and the UK
  governments guide to it:

  * https://gdpr.eu/tag/gdpr/

    More convenient version here: https://gdpr-info.eu/

  * https://ico.org.uk/for-organisations/in-your-sector/charity/charities-faqs/

  I've read all the relevant sections of these. These documents are not actually
  very long.

* I've also read all the other materials prepared so far, for reference:

  1. Information_Audit_CCiW May2018.docx (from Rebecca)
  2. CCiW Data Protection Policy.docx (derived from EMW as far as I know.) TODO
  3. CCiW Working on your own device policy.docm (WOYD, from EMW)  TODO

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
  times have you actually read them? That's right, zero. Asking people to stop
  what they are doing to read a long doc and tick a box to say they have done so
  is just asking them to lie.

* The one time I actually read a computer use policy was when I had begun
  working for a software development company in Leeds. Due to a planning
  mistake, for the first few weeks I had literally nothing else to do, so I
  actually read the policies. I then attempted to apply them, and found it
  almost impossible to do so, because parts of them were so impractical. Within
  the first day I gave up. I concluded I should do what everyone else was
  doing - ignore the policy, which is what I did from then on.

* The reason we don't lose sleep over all those online lies we've been telling
  is that we correctly understand those checkboxes as "transactional
  interactions", in which, like in many other circumstances, such as when your
  wife asks you if her clothes make her look fat, truthfulness is not expected
  or even desired. Also because of experiences of policy documents like the one
  I recounted.

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

* Many things copied from other people's documents incorporate very outdated
  ideas (e.g. ideas about password rotation).

* Many things that are copied from other people are simply not appropriate for
  our context. For example, larger organisations assume you have "company
  computers", and, perhaps "your own device". For CCiW, none of the computing
  hardware we use is owned by CCiW. Many of the things in the document are
  entirely impractical for us, and would simply never be actioned e.g.:

    39.5 A list (appendix 1) will be kept of locations where data is stored by
    the CCiW. This will include CCiW hardware and devices, third-party servers,
    mobile devices, computers and devices owned by volunteers and/or contractors
    used in accordance with the WOYD policy and physical records.

  Are we actually going to keep a list of the location of every personal device
  of CCiW leaders? And what about online services - in general the nature of
  "cloud" computing is that you don't know the location of the computing device.
  And what would this list actually achieve?

  It is often easier to write things from scratch with a knowledge of CCiW and
  GDPR rather than trying to adapt.

* Role-specific documents are better than policies for everyone. The majority of
  data protection responsibilities fall on the CCiW web master, so the longest
  document is the "CCiW Website security policies", which already existed and
  has been updated.

  We also need specific guidance for the booking secretary.

* We should start with our **existing processes and people**, and see where
  things need tightening. In a very small organisation like ours, the current
  division of labour should be our guide as to who probably has the knowledge to
  know how to write a policy. As web master I should basically be responsible
  for our security and data protection requirements, and I'll work closely with
  Rebecca to produce something for her.

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

* A document that is both human-readable and a machine-readable *executable*
  document is better than just human-readable.

  Since we actually have to implement a lot of our policies in terms of
  software, in some cases I've made the machine readable document be the
  official policy document, and made it part of the CCiW source code.

  These documents will then be read by software and applied as part of our data
  protection or retention processes.

  This has some other advantages - for example, our software can check the
  document for exhaustiveness. So, for example, if I add an extra table or
  column to our database, but without updating the "Data Retention Policy", our
  software will automatically complain that no data retention policy has been
  created for these fields, forcing us to ask those questions.

  An example that already exists is the ``groups.yaml`` file:

  https://gitlab.com/cciw/cciw.co.uk/-/blob/master/config/groups.yaml

* Hyperlinks are awesome! We should include links to other resources, rather
  than copy large parts of them.

* Here are some things we don't need:

  * A "Data Protection Policy" document. It might be useful to have a short one,
    but it is not actually required.

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


For these reasons the "policy documents" I will recommend are massively shorter
than other peoples! This document is the long one.


GDPR notes
----------

Notes I've made while reading the GDPR. You can skim this, refer back to it as
necessary.


- 1.1
  
  - it's about people's data

- 1.2
  
  - it applies to kind of thing CCiW does.

- 1.3
  
  - it applies to CCiW because we are in the EU and activities take place in EU.
    Technically we're not in the EU any more due to Brexit, but we assume the same
    rules will hold.

- 1.4
  
  - we hold "personal data" about people
    
    - leaders + officers
    - campers + parents

    Also "Trustees data" and "Land owners and suppliers" that Darren mentioned - how are these held? QUESTION

  - we have a "filing system" - the CCiW website database. QUESTION - any others?
  - we "process" data, and we are a "data controller"
  - we do not store "genetic data" or "biometric data"
  - we do store "data concerning health"
  - we don't do "cross-border processing"



Decisions and recommendations
-----------------------------

* We'll start from the premise that in CCiW, when it comes to computers,
  everyone is using their own "device". The only system that is easy for us to
  secure is the central CCiW database that is part of the website. We should
  design processes that make the most of this. For the most part people should
  be protected from the need to have sensitive data on their own devices.

* We will minimise the amount of "downloading" of sensitive data that
  can be done on the website.

  * only leaders will be able to download camper data. STATUS DONE (since the beginning)

  * we will train leaders at the point of download with rules about use
    of this data TODO.

* We will not email sensitive data:

  * Status DONE - several years ago we switched from emailing application forms
    and references to instead sending email notifications and allowing them
    to be viewed online.

* Online authentication systems and password rules and login

  We will use * `NIST Special Publication 800-63B
  <https://pages.nist.gov/800-63-3/sp800-63b.html>`_ as a general reference
  standard for securing digital identity. This is a modern, pragmatic set of
  guidelines that are widely used in the industry.

  While the data CCiW holds is sensitive, we are relatively low risk in terms of
  expecting cyber attacks. This is because we hold, relatively speaking, a very
  small amount of data, and the data has no immediate monetisation
  possibilities, making us very unlikely to be specifically targeted.

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

  * TODO - Apply NIST-800-63B  § 5.1.1.2

    * Add https://github.com/ubernostrum/pwned-passwords-django


* TODO - Add privacy notice to website

  https://ico.org.uk/for-organisations/in-your-sector/charity/charities-faqs/

  - One for officers
  - One for campers/parents

  Can be very short, because it mainly says:
  
  - we do not share any data with 3rd parties
  - we collect only the necessary data for providing camp activities, namely:
    
    - contact data for people coming on camp
    - health information so we can look after campers while on camp.
    - criminal records/references/etc. to ensure camper safety

* TODO Register with ICO?

* TODO Create "Appropriate Policy Document"

* TODO Retention Policy

  - write it down as a machine readable document in the CCiW source code
  - implement it in terms of wiping data from CCiW database

* TODO Find out rules for privacy breach, add to relevant manual

* TODO Links for downloadable private data should prompt regarding privacy when
  clicked

* TODO downloaded camper data XLS should contain cover sheet
  with relevant policy regarding use, especially for medical data.

* Review TODO items in website security document

* ACTION DONE: Move source code to GitLab, and correct in source code and other
  documents. This makes it easy for people to see our source code, including
  data retention policy.

* Use of "@cciw.co.uk" email accounts (using a provider like Google or
  Microsoft 365) is NOT recommended. We have to take into account what will
  actually happen:

  * CCiW volunteers will forget to check these accounts - they are *unpaid
    volunteers*, not full time workers, and have to be treated as such.

  * When @cciw.co.uk mail is not replied to:

    * other people trying to contact them will try other email addresses.

    * the volunteer will eventually realise that they can use the email
      providers 'forwarding' feature to forward email to their personal
      address

    And so you end up back where you were, but now with a false sense of
    security and compliance, and, even worse, you will have some processes
    that assume we have secure @cciw.co.uk accounts that we can send
    sensitive data to.

  The few @cciw.co.uk email addresses we have at the moment are simply
  "forwarding addresses" which redirect to personal email accounts, and I
  recommend we continue to do this. We will design processes and practices
  that do not involve sending sensitive data to email as far as possible.

  (DONE: This is already current practice on the website and has been for several
  years. We may need to tighten some things regarding telling leaders what they
  can and can't do with list of camper data etc.)

* TODO QUESTION - in officer application form, what do we need address and
  employee data for? Should we remove them?

* TODO new AWS account for CCIW, instead of my personal one.

  - use for AWS S3 backups
  - recreate AWS SES config using this account
