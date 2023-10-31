---
layout: page
title: Author Information
description: Instructions for paper submission.
invisible: false
published: true
priority: 8
---

## Guidance for Demo Preparation

A new type of submission, Demos, is available to RSS 2023 contributors similar to the practice in related communities (e.g., CVPR).

**Type of Submission:** These submissions should demonstrate systems that are innovative given the state-of-the-art of robotics research across any of the [subject areas]({{ site.baseurl }}/information/cfp/#subject-areas) of RSS 2023. Open-source and open-access systems or interactive systems that are accessible by the community are especially encouraged. Demos can relate to hardware or software contributions or their integration. They can also relate to critical system components and useful tools for the community. Examples of such submissions can correspond to demonstrations of:

- useful new mechanisms or software packages for the robotics community,
- large-scale deployments of robotics technology that have not been achieved before,
- mature, production-ready industrial systems of note and lessons from their operation,
- new datasets and benchmarks that will advance robotics research,
- novel applications of robotics technology with important societal impact.

**What to Submit?** Each submitted demo will include a paper describing the system (see format and length recommendations below) and demonstrations of the system itself, which can be accessed by reviewers via the supplementary material (e.g., executable software, multimedia showing the operation of robotic hardware, demonstrations of the achieved scalability, etc.), or via a website that is accessible at the time of the review period.

**Single-blind:** Demo submissions are allowed (but not required) to be single-blind in contrast to science and systems papers, which must be double-blind. Demo submissions are understood to be demonstrating unique systems that will obviously reveal the authors or their affiliations. Demos are not opportunities to bypass the double-blind requirement of regular submissions. The reviewers will be asked to evaluate whether a submission was appropriately submitted under the Demo category.

**Demo Title:** The authors of Demo submissions are encouraged to start the title of the submission with the characters "DEMO:" to communicate to the reviewers that these submissions are allowed to be single-blind.

**Key Questions:** A demo paper submitted to accompany a demonstration should outline the design of the system and provide sufficient details to allow the evaluation of its validity, quality, and relevance to RSS. A demo paper can do this by addressing the following subset of questions:

- What problem does the proposed system address?
- Why is the system important and what is its impact?
- What is the novelty in the approach/technology on which this system is based?
- Who is the target audience?
- How does the system work?
- How does it compare with existing systems?
- How is the system licensed?
- Are there any additional concerns about the proposed system (e.g., ethical or environmental concerns)? 

**Review and Camera-ready:** The review process for demos will take place in parallel with the review of regular RSS paper submissions and will be handled by the same Program Committee.  The proposed system needs to be ready at Camera-Ready time.  Additional improvements are allowed but should not diverge significantly from the description in the submitted paper.

**Conference Demonstration:** Papers describing accepted demonstrations will be published as part of the RSS conference proceedings (under the designation of "Demo Track"). Authors of accepted demos will be encouraged to demonstrate to the attendees of the RSS event their system (if possible), (e.g., an interactive demonstration of a software at the conference, live demonstration of robotic hardware brought at the conference, or via videoconferencing demonstrating a remote robot's abilities). The authors are encouraged to describe at the time of the submission how the RSS live audience will experience the demonstrated system.

**Note:** _Commercial sales and marketing activities are not appropriate for submissions in the RSS Demo Track and should be arranged instead via the RSS Sponsorship program._

## Paper and Demo Format

A template for paper and demo submissions is available in [LaTeX]({{ site.baseurl }}/docs/paper-template-latex.tar.gz) and [Word]({{ site.baseurl }}/docs/paper-template-word.zip). Do not modify the formatting provided in the templates. Any change to font sizes, page dimensions, line spacing, etc. may delay publication. Please do not include any additional markings such as _Draft or To appear in…_ on the pages. Make sure your paper does not contain page numbers.

We only accept a PDF format for the main submission file. Delays in the production of proceedings are usually caused by PDF file submissions that do not embed all fonts.

Before submitting your PDF file, please open it in Acrobat Reader. In the File menu under Document Properties, you will find information on the fonts used by your document. The PDF file must only contain Type-1 fonts (and Embedded True Type fonts if prepared under Word). On Linux, you may also use [pdffonts](https://www.xpdfreader.com/pdffonts-man.html). Below are instructions to embed PDF fonts for various typesetting systems:

- [Overleaf](https://www.overleaf.com/learn/latex/Questions/My_submission_was_rejected_by_the_journal_because_%22Font_XYZ_is_not_embedded%22._What_can_I_do%3F)
- [Acrobat](https://www.printivity.com/insights/2020/09/13/how-to-embed-fonts-in-pdfs/)
- [dvips](https://www.karlrupp.net/2016/01/embed-all-fonts-in-pdfs-latex-pdflatex/)
- [Miktex](http://www.boekenenproefschriften.nl/proefschriften/sites/default/files/EmbedLaTeXfonts.pdf)

## Paper and Demo Length

RSS 2023 has no page length requirements on paper or demo submissions. Paper lengths have been typically around 8 pages in the past, and we expect that most submitted papers will have a similar length. The expectation for demo papers submissions is that they can be even shorter than that if the focus is on the supplementary material or an online website that allows the reviewers to experience the demonstrated system.

The main PDF should contain a concise and lucid presentation of the merits of the paper, including a discussion of its contributions, prior work, and a description of key technical ideas and methods used. The paper should be self-contained and include all the material necessary for an expert to verify the central claims in the paper.

Additional supplemental text, such as appendices, data listings, or expanded proofs, should be included as supplementary material (see below). Reviewers will review supplemental material at their discretion for regular papers. For demos, the reviewers will be guided to prioritize the supplemental material if the system is primarily available through the corresponding file.

Authors should anticipate that their papers may be rejected if the key technical result is not concisely presented. Reviewers may perceive a paper as too long if it is verbose, repetitive, or belabors obvious points. A paper that is 15 pages long is not necessarily going to be rejected, but the authors must make a compelling case to that the length is essential to the key ideas in the paper. Moreover, the aesthetics of a paper also make the case for conciseness, since too much whitespace and poorly cropped figures are detrimental to the "feel" of a high-quality paper. Conversely, reviewers may perceive a paper as too short if it omits important details.

**Note:** _RSS was inspired to make this decision following other conferences, such as SIGGRAPH and FOCS. Researchers have wasted untold hours massaging formatting rules, figure sizes, and trimming paragraphs to fit page limits. Although the nominal reason for page limits in the electronic era is an upper bound on reviewers' effort since they are expected to review "all the material" in the submission, it is inevitable that reviewers do not review material uniformly and will skim over text that is uninteresting or too dense; hence, page length is a poor proxy for reviewer effort. We will trust that authors will recognize that respecting reviewers' time is a necessary condition to get published._

## Double-Blind Submission for Papers

RSS 2023 continues the tradition of double-blind reviews for regular science and systems papers. Authors should not list their names on the title page, and reasonable anonymity should be maintained in the paper. Authors are asked to take particular care when referencing their own work — careless use of self-citations can easily violate the requirements for double blind reviewing and this will result in papers being rejected.

The following general principles should be applied in science and systems submissions:

- Authors' names and affiliations should not be cited in the title or text of the submission.
- Acknowledgments to people or funding agencies should not appear in the submission.
- Citing of web links to the authors or author's institute should be avoided.

In self-citing authors previous work, avoid expressions such as "In the authors earlier work…", rather use alternative expressions such as "In previous work…" or "In related work…", in a manner that does not distinguish their own work from the work of others. Authors should otherwise cite work, including their own, as required for the completeness of the submission.

In presentation of experimental work, avoid logos in pictures, or overt references to an individual laboratory. Use expressions such as "The experimental equipment…" rather than "The University of XYZ's Robby the Robot…". Otherwise, authors should include photographs, graphics and other presentation material as in the normal manner for a paper submission.

**Note:** _Demo submissions are allowed (but not required) to be single-blind in contrast to science and systems papers, which must be double-blind._ 

## Supplementary Materials for Papers and Demos

Authors may submit supplementary material such as a video or an expanded version of a proof. Especially in the context of demos, they are encouraged to provide supplementary material that allow the reviewers to experience and evaluate the demo. The deadline for supplementary material is a few days after the paper and demo description submission deadline (Feb. 8 vs. Feb. 3, 2023).

Note that reviewers of regular papers are not required to view this material and include it in their assessment of the paper. Lastly, if authors feel they must link to additional supplementary material, they are cautioned to ensure that their identities are not revealed for regular papers.

## Multiple Submissions of Papers and Demos

Submissions that are identical (or substantially similar) to versions that have been previously published, or accepted for publication, or that have been submitted in parallel to other conferences are not appropriate for RSS and violate our dual submission policy.

Exceptions to this rule are the following:

1. Submission is permitted of a short version of a paper that has been submitted to a journal, but has not yet been published in that journal. Authors must declare such dual-submissions via email to the program chair. It is the authors' responsibility to make sure that the journal in question allows dual concurrent submissions to conferences.
2. Submission is permitted for papers presented or to be presented at conferences or workshops that do not have published proceedings, or with only abstracts published.
3. It is acceptable to submit to RSS work that has been made available as a technical report (or similar, e.g. in arXiv) without citing it.

None of the above should be construed as overriding the requirements of other publishing venues. In addition, keep in mind that author anonymity to RSS reviewers might be compromised for authors availing themselves of exceptions 2 and 3.

## Plagiarism in Papers and Demos

RSS is intolerant of plagiarism. Submitted papers are expected to contain original work executed by the authors with adequate, proper, and scholarly citations to the work of others. It is the job of the authors to clearly identify both their own contribution(s) and published results / techniques on which they depend or build. RSS reviewers are charged to ensure these standards are met. In cases of alleged plagiarism, the program chair will be guided by Section 8.2.4 Allegations of Misconduct as laid out by the IEEE in this [document]({{ site.baseurl }}/docs/opsmanual.pdf).

## Policy on the Use of Large Language Models

We are following the example of [ICML](https://icml.cc/Conferences/2023/llm-policy) and adopt the following policy:

Papers that include text generated from a large-scale language model (LLM), such as ChatGPT, are prohibited unless the produced text is presented as a part of the paper's experimental analysis. Note the following clarification on the above statement:

- The policy prohibits text produced entirely by LLMs (i.e., "generated").  This does not prohibit authors from using LLMs for editing or polishing author-written text.
- The policy is largely predicated on the principle of being conservative with respect to guarding against potential issues of using LLMs, including plagiarism.
- This policy may evolve in future conferences as society understands LLMs and their impacts on scientific publishing better.

We plan to investigate any potential violation of the LLM policy when a submission is brought to our attention with a significant concern about a potential violation. Any submission flagged for the potential violation of this LLM policy will go through the same process as any other submission flagged for plagiarism.

## Uploading Files for Paper and Demo Submissions

Paper submission and review will occur in the Conference Management Toolkit (CMT) system at the following link: [https://cmt3.research.microsoft.com/RSS2023/](https://cmt3.research.microsoft.com/RSS2023/)

- **Logging into the system:** If you already have a CMT account, use those credentials to login. If you do not, sign up as a new user.
- **Conflict domains:** When you login for the first time, CMT will prompt you to enter your conflict domains. Please finish this step before you start the submission process.
- **Paper/Demo submission:** Make sure your role is "Author". Enter title, abstract, and authors. Select your primary and secondary [subject areas]({{ site.baseurl }}/information/cfp/#subject-areas). Your main submission file may now be uploaded. Papers and demo descriptions must be in the accepted conference style format and must be submitted as a PDF. Papers and demos may be edited, updated and replaced up to the full paper and demo description submission deadline.
- **Demo title:** The authors of Demo submissions are encouraged to start the title of the submission with the characters "DEMO:" to communicate to the reviewers that these are submissions that are allowed to be single-blind.
- **Paper ID:** After clicking the Submit link, your paper or demo submission will be assigned an ID. To make sure your PDF submission is reviewer-friendly, enter this ID at the end of your title as instructed in the paper template.
- **Supplementary material:** Authors may submit supplementary material, such as a video or an expanded version of a proof (100MB max, accepted formats: zip). Please note that the link to upload supplementary material becomes active only after the paper submission is complete. The deadline for the submission of supplementary material is a few days after the paper/demo description deadline.