Copyright 2016 the author or authors

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.

-----

Supporting resources for Apereo board consideration of relaxing requiring ICLAs from contributors.

# The change under consideration

## Status quo

> The Apereo Foundation requires that all project contributors complete a Contributor License Agreement (CLA).

([source](https://www.apereo.org/licensing/agreements)).

## Proposed policy change

> Before a given individual is granted committer status (roughly, write access), the Apereo Foundation requires that the individual first submit an Individual Contributor License Agreement (ICLA).

### Nuances

In general, this policy change is intended to 

* bring Apereo in line with how the Apache Foundation requires ICLAs of its committers but does not universally require CLAs of contributors.
* reduce friction in accepting contributions

This policy change stops universally requiring CLAs of contributors. Projects and individual committers can still require CLAs where they see a need.

* projects, through their PMCs, could still require CLAs of their contributors.
* individual committers can still require CLAs in their determining their individual comfort with committing a contribution. (Attempted contributions always require committer action to actually become part of Apereo software; committers can and should gate that action on all sorts of things, including comfort with the provenance of the contribution).

# Background and resources

## Terms defined

Committer: Privileged project participant, typically with write access to the canonical codebase and voting rights. Committership is a big deal. Typically committership is earned through virtuous contribution and is granted through vote of existing committers.

Contributor: Anyone who contributes a contribution that is included in the open source product. (See also: [Apache 2 license][] definition of "Contributor".)

Contribution: Anything intentionally submitted for inclusion in the open source product. (See also: [Apache 2 license][] definition of "Contribution".)

## Why do we care?

Requiring CLAs of contributors adds

* friction to committers, in their having to check for CLA compliance, nag for this.
* friction to contributors, in their having to understand, print, sign, scan or fax, and follow up on their CLA submission.

but adds little value, since the [Apache 2 license][] already specifies that contributions intentionally submitted for inclusion in the work may be distributed under the Apache 2 license.

## What does Apache do?

Apache's policy is the proposed policy rather than the status quo policy.

* Apache requires ICLAs of individual committers.
* Apache does not (universally, at a Foundation level) require CLAs of contributors.

See also [analysis](http://apetro.ghost.io/apache-contributors-no-cla/).

## Working examples

| Scenario  | Under the status quo | Under the proposed policy |
|---|---|---|
| **Minor documentation contribution:**<br> A deployer discovers an error in [the wiki deployment documentation][UPM43 Building and Deploying uPortal] and directly edits the wiki.  | They are in **violation of [the current policy][licensing stance for uPortal manual 3.2 and later]** if they do not have an ICLA on file. |  The [uPortal manual is a Work licensed under Apache2][licensing stance for uPortal manual 3.2 and later].  Editing a wiki page is an intentional Contribution to the Work. The Apache2 license states that intentional Contributions to Apache2-licensed Works are Contributed for redistribution under Apache2. No further CLA is required and no project resources need be expended checking for CLA compliance. **No worries.** |
| **Minor code contribution:**<br> A developer discovers a bug in the uPortal codebase and submits the fix via a GitHub pull request, an email to the project list, or an issue tracker entry (JIRA). | A committer contacts them requesting they submit an ICLA before the change can be accepted; the developer decides it is not worth the hassle and **the contribution is discarded**. <br>OR<br> A committer inserts the fix into the project knowing there is no ICLA on file, a **violation of the current policy**. | The developer has clearly communicated the intention to Contribute the fix as a Contribution to the Apache2-licensed Work. Apache2 provides that such Contributions may be incorporated into the Work and redistributed under Apache2. A committer accepts the Contribution. No further CLA is required and no project resources need be expended securing CLA compliance. **No worries.** |
| **Major code contribution:**<br> A developer creates a new code module and submits it via a GitHub pull request. | A committer contacts them requesting they submit an ICLA before the contribution can be accepted; the contributor decides it is not worth the hassle and **the contribution is discarded**. <br>OR<br> A committer adds the code into the project knowing there is no ICLA on file, a **violation of the current policy**. | The pull request clearly communicates the developer's intention to Contribute the new code module for inclusion in the Apache2-licensed Work. A committer honors this intention and accepts the contribution per the terms of the Apache2 license. **No worries.** <br>OR<br>Seeing the significance of the Contribution a committer asks the Contributor to offer a supporting ICLA for improved project comfort with the contribution; the contributor decides it is not worth the hassle; **the Contribution is discarded**. |

## Resources for learning more

* [Blog post explaining that Apache does not require CLAs of contributors](http://apetro.ghost.io/apache-contributors-no-cla/)
* [Apereo licensing discussion list topic](https://groups.google.com/a/apereo.org/d/topic/licensing-discuss/c1puG3RKZcA/discussion)
* the `supporting_resources` folder alongside this `README.md`

[Apache 2 license]: http://www.apache.org/licenses/LICENSE-2.0

[licensing stance for uPortal manual 3.2 and later]: https://wiki.jasig.org/display/UPC/Documentation+Licensing
[UPM43 Building and Deploying uPortal]: https://wiki.jasig.org/display/UPM43/Building+and+Deploying+uPortal
