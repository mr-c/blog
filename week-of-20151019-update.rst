.. post:: 2015-10-26
   :tags: weekly-update
   :author: me
   :location: Cluj

****************************************
Weekly report for the week of 2015-10-19
****************************************

Hello! Here is the first weekly update on what I've been doing for the CWL
covering the week of 2015-10-19, and a couple days before.

Summary: settling in and getting ready for the Festival of Genomics Workshop on
November 3rd.

Thursday 2015-10-15
-------------------

- Announcement of SBG Gift on Twitter & this blog. Tagged the wrong vet med
  school in my tweet; whoops!
- Reviewed `BD2K hackathon funding opportunity
  <http://bd2kcc.org/files/hackathons.pdf>`_, decided to skip it for the
  November CWL codefest; will reconsider for future workshops that have the
  required diversity plan.
- Renewed my membership at `Cluj Cowork <http://clujcowork.ro/>`_, where I do
  my work.

Friday 2015-10-16
-----------------

- Figured out how to use the UC Davis library to view paywalled articles when
  one is not on their network.
- Short work day due to travel logistics.

Monday 2015-10-19
-----------------

- `Announced free tickets to CWL Workshop at the Festival of Genomics
  <https://groups.google.com/d/msg/common-workflow-language/hAMs0nu2k_o/h3eXXbwkDQAJ>`_
- Researched how the CWL website is built; summary: `schema_salad
  <https://github.com/common-workflow-language/schema_salad>`_ builds the raw
  HTML out of the `README.rst
  <https://github.com/common-workflow-language/common-workflow-language/blob/master/README.md>`_
  and `cwl-avro.yml 
  <https://github.com/common-workflow-language/common-workflow-language/blob/master/draft-3/cwl-avro.yml>`_
  files via a workflow specified in CWL. The process is initiated by a script
  that runs on the Arvados CI server. It is good that we are using our own
  tools ("eating our dogfood"); I will document this more as I move the automated
  testing and building of the website from Arvados's servers to ones run by the
  project. Eventually we will want to `migrate to an existing documentation
  system <https://github.com/common-workflow-language/schema_salad/issues/4>`_
  instead of building our own. Big thanks to Peter Amstutz for all his work
  maintaining and building the CWL website & standard!
- `Noted that CWL job documents could and should include a reference to the
  workflow that they are intended for
  <https://github.com/common-workflow-language/common-workflow-language/issues/148>`_.
- Purchased train ticket to the Festival of Genomics.
- Started the ball rolling on `a meeting at the Broad Institute on November
  13th
  <https://groups.google.com/d/msg/ga4gh-dwg-containers-workflows/55TTWIFTk6M/584NcQaVDQAJ>`_.
- Reported bug with ablog feeds: https://github.com/rtfd/readthedocs.org/issues/1771#issuecomment-149336887
- Opened a couple tracking issues, one for `creating/joining a US foundation to
  own the CWL assets
  <https://github.com/common-workflow-language/common-workflow-language/issues/147>`_
  and another `to create a governenace plan
  <https://github.com/common-workflow-language/common-workflow-language/issues/146>`_
- Reviewed and `gave feedback <https://github.com/ctb/titus-blog/pull/9>`_ on
  draft blog commenting policy for C. Titus Brown's blog. It has since been
  published: http://ivory.idyll.org/blog/2015-site-policies.html

Tuesday 2015-10-20
------------------

- Reviewed the available Code of Conduct templates and adapted one for CWL use.
  This `Code of Conduct draft
  <https://github.com/mr-c/common-workflow-language/tree/CoC>`_ I sent for
  review by the leadership team. Initially I went with the Django version, but
  it was too unwieldy for a group our size. I received good feedback and will
  send out a revision next week.
- Got flights to visit TACC & Broad Institute sorted
- Noticed that we weren't tagging the cwltool PyPI releases on the GitHub repo;
  `wrote-up issue
  <https://github.com/common-workflow-language/schema_salad/issues/2>`_.
- Found and `fixed
  <https://github.com/common-workflow-language/schema_salad/pull/3>`_ a
  problem that prevented the installation of the SALAD from the GitHub repo (as
  opposed to using PyPI).

Wednesday 2015-10-21
--------------------

- Individual membership in GA4GH approved, spent time trying to understand its
  structure and how to interact with them. Sent feedback to GA4GH about issues
  with the signup process (password validation & broken links).
- promoted `workshop <https://twitter.com/biocrusoe/status/656789421421961216>`_
  & `codefest <https://twitter.com/biocrusoe/status/656791781510676480>`_ on
  Twitter.
- followed up on blog feed issue: https://github.com/rtfd/readthedocs.org/issues/1771#issuecomment-149875488
- Put in request for video camera & microphone for the CWL codefest
- Caught up on CWL and other email backlog
- Reviewed NIH BD2K funding opportunities

Thursday 2015-10-22
-------------------

- Copyedited FoG workshop materials
- initial meeting with local tech nonprofit
- reviewed `mistral`, a workflow engine reported by `Roman Valls Guimerà
  <https://github.com/brainstorm>`_. Made a quick entry on the `wiki
  <https://github.com/common-workflow-language/common-workflow-language/wiki/Existing-Workflow-systems#mistral>`_
  for it.
- Responded to `an error with our documentation
  <https://github.com/common-workflow-language/common-workflow-language/issues/149>`_.
  Fixed it; thanks to `Sehrish Kanwal <https://github.com/skanwal>`_ for
  reporting it!
- Made CWL Build Bot user on PyPI complete with GPG signing key. `Asked Peter
  Amstutz to make it the owner of CWL packages
  <https://github.com/common-workflow-language/cwltool/issues/4>`_.

Friday 2015-10-23
-----------------

- NSF funding opportunities review
- More back and forth on the blog feed issue; finally `it got fixed
  <https://github.com/abakan/ablog/issues/54#issuecomment-150762739>`_!
- Update on my application for the Stripe Open Source Retreat 2016: I was not
  selected for further review.

Saturday 2015-10-24
-------------------

- Polished my notes from the week into this blogpost.

To do
-----

- Get `Andrey Kartashov's recently contributed workflows
  <https://github.com/common-workflow-language/schema_salad/issues/4>`_
  running for myself.
- Familiarize myself with vagrant to setup Jenkins CI server to test CWL
  conformance
- Refresh my backstory of the CWL slides for the Festival of Genomics workshop.
- Sketch out more technical slides for TACC/Agave presentation the week after.
- Work with Hervé Ménager to organize a CWL related workshop/codefest in Paris
  during the Spring.
- Start the sustainability review.
- Start an ontological comparison between the semantics of CWL tool and
  workflow descriptions and `the other known efforts
  <https://github.com/common-workflow-language/common-workflow-language/wiki/Existing-Workflow-systems>`_.
- Follow up on Code of Conduct
- Follow up with the Software Freedom Conservancy and NumFOCUS.

