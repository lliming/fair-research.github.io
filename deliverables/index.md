---
layout: default
title: FAIR Research Data - NIH DCPPC Deliverables
---

# NIH DCPPC Deliverables

Work supporting the [NIH Data Commons Pilot Phase Consortium](https://www.nihdatacommons.us).

*  [2M.1.FULLSTACKS: TopMed Workflow(s) registered on Public Site](rna-seq-pipeline.md):
   A demo describes the implementation of TOPMed RNAseq analysis
   pipeline that uses BDBags and MINID within a Galaxy based
   [Globus Genomics (GG)](http://globusgenomics.org) platform to
   support FAIR research. We have implemented specific tools within GG that
   automate the use of Minids representing input databags and generate
   output BDBags along with provenance and performance metric that can
   be used to validate reproducibility.
*  [4M.3.FULLSTACKS: Pilot Users Onboarded](globus-auth.html) : A
   description of
   [Globus Auth](https://docs.globus.org/api/auth/developer-guide/)
   and how to join the Globus Group used for authorization to data
   managed by Team Argon.
*  [4M.4.FULLSTACKS: Cross-stack Compute](cross-stack-4m.html) : A
   quickstart tutorial that walks through a quick submission of 5
   downsampled TOPMed CRAM input files using a TOPMed Alignment workflow
   in CWL. It uses a portal to index and search the input datasets and
   submits to a WES (Workflow Execution Service - GA4GH) service deployed
   as a shim-layer on the Galaxy based Globus Genomics platform.

[back](./)


