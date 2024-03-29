The project management principles and policies outlined in this document
are intended to maintain transparency in our relationships with the
government while minimizing administrative overhead. As such, we have
taken a simplified approach to project management with three phases.
More complex projects will require additional project management steps
in each phase.

-   Project Approval
    -   Project initiation
    -   Project plan (more detailed plans required for more complex
        projects)
    -   Project approval
-   Project Execution
    -   Carry out project tasks according to the principles and policies
        outlined in the document titled Reproducible Research.
    -   Project monitoring (requirements vary by level of complexity)
-   Project Closeout
    -   Publication
    -   Project archival

## Project Approval

After project initiation and completion of the project plan, all project
documents will be routed to the appropriate individuals listed in the
table below for notification and/or approval using the communications
tab in [AMP](https://abcs-amp.cancer.gov). ABCS and government approvals
must be documented in AMP prior to project execution.

<table>
<thead>
<tr class="header">
<th style="text-align: left;">Level</th>
<th style="text-align: left;">Team Lead</th>
<th style="text-align: left;">ABCS Rep</th>
<th style="text-align: left;">Govt Rep(s)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">&lt; 80 hrs</td>
<td style="text-align: left;">Approve</td>
<td style="text-align: left;">Notify</td>
<td style="text-align: left;">Notify</td>
</tr>
<tr class="even">
<td style="text-align: left;">&lt; 200 hrs</td>
<td style="text-align: left;">Approve</td>
<td style="text-align: left;">Approve</td>
<td style="text-align: left;">Notify</td>
</tr>
<tr class="odd">
<td style="text-align: left;">≥ 200 hrs</td>
<td style="text-align: left;">Approve</td>
<td style="text-align: left;">Approve</td>
<td style="text-align: left;">Approve</td>
</tr>
</tbody>
</table>

### Project Initiation

Projects are officially initiated when a request is submitted via the
[ABCS project request
form](https://ncifrederick.cancer.gov/bids/abcs/project-request/).
Information required includes but is not limited to the PI requesting
the project and a description of the work to be completed.

Once a project request is completed an ABCS representative will triage
the request and assign a lead analyst and other analysts as needed. The
lead analyst is then responsible for providing the following additional
information prior to project approval:

-   Estimated level of effort (LOE) category:
    -   &lt; 80 hours
    -   &lt; 200 hours
    -   ≥ 200 hours
-   GitHub repository link
-   Methods summary (not required for projects requiring &lt;80 hours)
-   Project plan (not required for projects requiring &lt;200 hours)

### Project Planning

For simple projects requiring less than 80 hours of effort, the project
scope and aims outlined in the description should correlate with the
stated level of effort. Additional follow up and justification may be
required prior to approval.

#### Methods Summary

Projects with an estimated LOE greater than 80 hours require a one to
two paragraph description of the planed methods to be used for the
project prior to approval. This will be included in the project metadata
in AMP and should include the following information:

-   Proposed methods to meet project aims described in the project
    description.
-   Analysts expected to contribute to the project.

#### Project Plan

Projects with an estimated LOE greater than 200 hours (approximately 0.1
FTEs over the course of a year) require a signed project plan prior to
commencement of work. This should follow the standard template and be
uploaded to [AMP](https://abcs-amp.cancer.gov) for consideration and
approval (links for the template in:
[Rmarkdown](https://raw.githubusercontent.com/abcsFrederick/Principles-and-Policies/main/templates/Project-Plan.Rmd)
and
[Word](https://raw.githubusercontent.com/abcsFrederick/Principles-and-Policies/main/templates/Project-Plan.docx)).

## Project Execution

Once all requisite approvals have been granted, work on the project may
begin. The project should employ reproducible research best practices as
outlined
[here](https://raw.githubusercontent.com/abcsFrederick/Principles-and-Policies/main/Reproducible-Research.md).
This includes but is not limited to the following:

-   Code is versioned and regular commits are pushed to GitHub.
-   Communications are logged in [AMP](https://abcs-amp.cancer.gov/).
-   All other research objects are stored in
    [AMP](https://abcs-amp.cancer.gov/), with the exception data sets
    larger than 2 Gb.

Changes in scope should be brought to the attention of an ABCS
representative and documented in [AMP](https://abcs-amp.cancer.gov/).

### Project Monitoring

The following project metrics and metadata should be kept up to date in
[AMP](https://abcs-amp.cancer.gov/):

-   Project status
-   Project notes (1-2 sentence, scientific/technical update)
-   Current issues (e.g. changes in scope, changes in estimated level of
    effort, risks that are threatening the project)
-   Approximate hours spent on the project (*working with Tyler on hours
    tracking*)
-   Approximate percent complete (one of four categories):
    -   &lt; 25%

    -   25 - 75%

    -   75 - 95%

    -   95%

Differences between planned LOE and actual LOE should be noted as soon
as possible to allow time to secure any additional approvals necessary
without impacting the project. Once the actual LOE has exceeded the
planned LOE, work should stop until the requisite approvals have been
granted.

Monthly reports will be run on the evening of the 10th day of each month
and shared with government Contracting Officer Representatives (CORs)
and subject matter experts as designated by each COR.

## Project Closeout

When projects are completed or canceled, the following actions should be
taken:

-   Project data should be archived in AMP (&lt;2 Gb file size) or HPC
    DME (≥2 Gb).
-   GitHub repository actions:
    -   Ensure any DOIs, publication references, and/or links to
        archived data are included in the README.
    -   Ensure the public/private status of the repository is correct.
    -   Analysis repositories and unsupported software repositories
        should be archived (see GitHub repository settings &gt;
        Options &gt; Danger Zone).
-   Submit a [new project
    request](https://ncifrederick.cancer.gov/bids/abcs/project-request/)
    for all completed software projects that will require ongoing
    maintenance and support. The level of effort for maintenance should
    reflect the expected number of hours required for maintenance each
    year.
-   Project metadata should be reviewed and updated appropriately in
    [AMP](https://abcs-amp.cancer.gov/).
