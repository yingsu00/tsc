## Technical Charter (the "Charter") for Presto Project
**a Series of LF Projects, LLC**

---

**Adopted September 16, 2019 / Last amended November 6, 2020**

This charter (the "Charter") sets forth the responsibilities and procedures for technical contribution to, and oversight of, the Presto project, which has been established as Presto Project a Series of LF Projects, LLC (the “Project”).  LF Projects, LLC (“LF Projects”) is a Delaware series limited liability company. All contributors (including committers, maintainers, and other technical positions) and other participants in the Project (collectively, “Collaborators”) must comply with the terms of this Charter. 

### 1. Mission and Scope of the Project

a. The mission of the Project is to develop an open source distributed SQL query engine for running interactive analytic queries against data sources of all sizes. 

b. The scope of the Project includes collaborative development under the Project License (as defined herein) supporting the mission, including documentation, testing, integration and the creation of other artifacts that aid the development, deployment, operation or adoption of the open source project.

### 2. Technical Steering Committee

a. The Technical Steering Committee (the "TSC") will be responsible for all technical oversight of the open source Project. 

b. The TSC will consist of two roles - TSC voting members and Committers. 

c. The TSC voting members are initially the Project’s Committers. At the inception of the project, the Committers of the Project will be as set forth within the "CONTRIBUTING" file within the Project’s code repository. The TSC may choose an alternative approach for determining the voting members of the TSC, and any such alternative approach will be documented in the CONTRIBUTING file.  Any meetings of the Technical Steering Committee are intended to be open to the public, and can be conducted electronically, via teleconference, or in person. 

d. TSC projects generally will involve Contributors and Committers. The TSC may adopt or modify roles so long as the roles are documented in the CONTRIBUTING file. Unless otherwise documented: 

&nbsp;&nbsp;&nbsp;&nbsp;i. Contributors include anyone in the technical community that contributes code, documentation, or other technical artifacts to the Project; 

&nbsp;&nbsp;&nbsp;&nbsp;ii. Committers are Contributors who have earned the ability to modify ("commit") source code, documentation or other technical artifacts in a project’s repository; and

&nbsp;&nbsp;&nbsp;&nbsp;iii. A Contributor may become a Committer by a majority approval of the TSC. A Committer may be removed by a majority approval of the TSC.

&nbsp;&nbsp;&nbsp;&nbsp;iv. A Committer by default is not a voting TSC member. An existing TSC voting member can nominate a Committer to be a TSC voting member, which will require approval from the majority of existing TSC voting members.

e. Participation in the Project through becoming a Contributor and Committer is open to anyone so long as they abide by the terms of this Charter.

f. The TSC may (1) establish work flow procedures for the submission, approval, and closure/archiving of projects, (2) set requirements for the promotion of Contributors to Committer status, as applicable, and (3) amend, adjust, refine and/or eliminate the roles of Contributors, and Committers, and create new roles, and publicly document any TSC roles, as it sees fit.

g. Unless the TSC decides otherwise, committers will operate using the Lazy Consensus method. (NOTE:  https://wiki.eclipse.org/Lazy_Consensus)

h. The TSC may elect a TSC Chair, who will preside over meetings of the TSC and will serve until their resignation or replacement by the TSC. The TSC Chair, or any other TSC member so designated by the TSC, will serve as the primary communication contact between the Project and the Presto Foundation Fund Governing Board of the Linux Foundation ("Governing Board").

i. Responsibilities: The TSC will be responsible for all aspects of oversight relating to the Project, which may include:

&nbsp;&nbsp;&nbsp;&nbsp;i. coordinating the technical direction of the Project;

&nbsp;&nbsp;&nbsp;&nbsp;ii. approving project or system proposals (including, but not limited to, incubation, deprecation, and changes to a sub-project’s scope);

&nbsp;&nbsp;&nbsp;&nbsp;iii. organizing sub-projects and removing sub-projects;

&nbsp;&nbsp;&nbsp;&nbsp;iv. creating sub-committees or working groups to focus on cross-project technical issues and requirements;

&nbsp;&nbsp;&nbsp;&nbsp;v. appointing representatives to work with other open source or open standards communities;

&nbsp;&nbsp;&nbsp;&nbsp;vi. establishing community norms, workflows, issuing releases, and security issue reporting policies;

&nbsp;&nbsp;&nbsp;&nbsp;vii. approving and implementing policies and processes for contributing (to be published in the CONTRIBUTING file) and coordinating with the series manager of the Project (as provided for in the Series Agreement, the "Series Manager") to resolve matters or concerns that may arise as set forth in Section 8 of this Charter;

&nbsp;&nbsp;&nbsp;&nbsp;viii. discussions, seeking consensus, and where necessary, voting on technical matters relating to the code base that affect multiple projects; and

&nbsp;&nbsp;&nbsp;&nbsp;ix. coordinating any marketing, events, or communications regarding the Project.

j. A TSC member may be voted to be removed from the TSC by a two-thirds vote of the entire TSC.

k. A TSC member may resign by submitting their resignation to the TSC [mailing list](mailto:presto-tsc@lists.prestodb.io).

### 3. TSC Voting

a. While the Project aims to operate as a consensus-based community, if any TSC decision requires a vote to move the Project forward, the voting members of the TSC will vote on a one vote per voting member basis.

b. Quorum for TSC meetings requires at least fifty percent of all voting members of the TSC to be present. The TSC may continue to meet if quorum is not met but will be prevented from making any decisions at the meeting.

c. Except as provided in Section 2.j, 8.c. and 9.a, decisions by vote at a meeting requires a majority vote of those in attendance, provided a quorum is met. Decisions made by electronic vote without a meeting requires a lazy consensus of all voting members of the TSC.

d. In the event a vote cannot be resolved by the TSC, any voting member of the TSC may refer the matter to the Governing Board or the Series Manager for assistance in reaching a resolution.

e. The voting members and their terms are listed in the [TSC repo](../README.md#members).

f. TSC members will have term limits set.  For the initial election occurring on October 31, 2021, all TSC voting members are eligible to cast a vote for the incoming TSC.  Going forward, only members whose seats are not up for re-election may vote for the incoming class.

g. If a TSC member resigns, then an election may be held to fulfil the seat vacated.

### 4. Compliance with Policies 

a. This Charter is subject to the Series Agreement for the Project and the Operating Agreement of LF Projects. Contributors will comply with the policies of LF Projects as may be adopted and amended by LF Projects, including, without limitation the policies listed at https://lfprojects.org/policies/.  

b. The TSC may adopt a code of conduct ("CoC") for the Project, which is subject to approval by the Series Manager.  In the event that a Project-specific CoC has not been approved, the LF Projects Code of Conduct listed at [https://lfprojects.org/policies](https://lfprojects.org/policies) will apply for all Collaborators in the Project.

c. When amending or adopting any policy applicable to the Project, LF Projects will publish such policy, as to be amended or adopted, on its web site at least 30 days prior to such policy taking effect; provided, however, that in the case of any amendment of the Trademark Policy or Terms of Use of LF Projects, any such amendment is effective upon publication on LF Project’s web site.

d. All Collaborators must allow open participation from any individual or organization meeting the requirements for contributing under this Charter and any policies adopted for all Collaborators by the TSC, regardless of competitive interests. Put another way, the Project community must not seek to exclude any participant based on any criteria, requirement, or reason other than those that are reasonable and applied on a non-discriminatory basis to all Collaborators in the Project community.

e. The Project will operate in a transparent, open, collaborative, and ethical manner at all times. The output of all Project discussions, proposals, timelines, decisions, and status should be made open and easily visible to all. Any potential violations of this requirement should be reported immediately to the Series Manager.

### 5. Community Assets

a. LF Projects will hold title to all trade or service marks used by the Project ("Project Trademarks"), whether based on common law or registered rights.  Project Trademarks will be transferred and assigned to LF Projects to hold on behalf of the Project. Any use of any Project Trademarks by Collaborators in the Project will be in accordance with the license from LF Projects and inure to the benefit of LF Projects.  

b. The Project will, as permitted and in accordance with such license from LF Projects, develop and own all Project GitHub and social media accounts, and domain name registrations created by the Project community.

c. Under no circumstances will LF Projects be expected or required to undertake any action on behalf of the Project that is inconsistent with the tax-exempt status or purpose, as applicable, of LFP, Inc. or LF Projects, LLC.

### 6. General Rules and Operations. 

a. The Project will:

&nbsp;&nbsp;&nbsp;&nbsp;i. engage in the work of the Project in a professional manner consistent with maintaining a cohesive community, while also maintaining the goodwill and esteem of LF Projects, LFP, Inc. and other partner organizations in the open source community; and

&nbsp;&nbsp;&nbsp;&nbsp;ii. respect the rights of all trademark owners, including any branding and trademark usage guidelines.

### 7. **Related Companies**

a. "Related Company" means any entity which controls or is controlled by a Member or which, together with a Member, is under the common control of a third party, in each case where such control results from ownership, either directly or indirectly, of more than fifty percent of the voting securities or membership interests of the entity in question; 

b. "Related Company Group" are entities that are each a Related Company of a Member.

### 8. Intellectual Property Policy

a. Collaborators acknowledge that the copyright in all new contributions will be retained by the copyright holder as independent works of authorship and that no contributor or copyright holder will be required to assign copyrights to the Project. 

b. Except as described in Section 8.c., all contributions to the Project are subject to the following: 

&nbsp;&nbsp;&nbsp;&nbsp;i. All new inbound code contributions to the Project must be made using the Apache License, Version 2.0, available at [https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0) (the "Project License"). 

&nbsp;&nbsp;&nbsp;&nbsp;ii. All new inbound code contributions must also be accompanied by a Apache Contributor License Agreement ([https://www.apache.org/licenses/contributor-agreements.html#clas](https://www.apache.org/licenses/contributor-agreements.html#clas)) in the source code system that is submitted through a TSC-approved contribution process which will bind the authorized contributor and, if not self-employed, their employer to the applicable license;

&nbsp;&nbsp;&nbsp;&nbsp;iii. All outbound code will be made available under the Project License.

&nbsp;&nbsp;&nbsp;&nbsp;iv. Documentation will be received and made available by the Project under the Creative Commons Attribution 4.0 International License (available at [http://creativecommons.org/licenses/by/4.0/](http://creativecommons.org/licenses/by/4.0/)). 

&nbsp;&nbsp;&nbsp;&nbsp;v. The Project may seek to integrate and contribute back to other open source projects ("Upstream Projects"). In such cases, the Project will conform to all license requirements of the Upstream Projects, including dependencies, leveraged by the Project.  Upstream Project code contributions not stored within the Project’s main code repository will comply with the contribution process and license terms for the applicable Upstream Project.

c. The TSC may approve the use of an alternative license or licenses for inbound or outbound contributions on an exception basis. To request an exception, please describe the contribution, the alternative open source license(s), and the justification for using an alternative open source license for the Project. License exceptions must be approved by a two-thirds vote of the entire TSC. 

d. Contributed files should contain license information, such as SPDX short form identifiers, indicating the open source license or licenses pertaining to the file.

### 9. Amendments

a) This charter may be amended by a two-thirds vote of the entire TSC and is subject to approval by LF Projects.
