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
* reduce needless friction in accepting contributions

This policy change stops needlessly requiring CLAs of contributors. Projects and individual committers can still require CLAs where they see a need.

* projects, through their PMCs, could still require CLAs of their contributors.
* individual committers can still require CLAs in their determining their individual comfort with committing a contribution. (Attempted contributions always require committer action to actually become part of Apereo software; committers can and should gate that action on all sorts of things, including comfort with the provenance of the contribution).

# Background and resources

## Terms defined

Committer: Privileged project participant, typically with write access to the canonical codebase and voting rights. Committership is a big deal. Typically committership is earned through virtuous contribution and is granted through vote of existing committers.

Contributor: Anyone who contributes a contribution that is included in the open source product. (See also: [Apache 2 license][] definition of "Contributor".)

Contribution: Anything intentionally submitted for inclusion in the open souce product. (See also: [Apache 2 license][] definition of "Contribution".)

## Why do we care?

Requiring CLAs of contributors adds

* friction to committers, in their having to check for CLA compliance, nag for this.
* friction to contributors, in their having to understand, print, sign, scan or fax, and follow up on their CLA submission.

but does not add value, since the [Apache 2 license][] already specifies that contributions intentionally submitted for inclusion in the work may be distributed under the Apache 2 license.

## What does Apache do?

Apache's policy is the proposed policy rather than the status quo policy.

* Apache requires ICLAs of individual committers.
* Apache does not (universally, at a Foundation level) require CLAs of contributors.

See also [analysis](http://apetro.ghost.io/apache-contributors-no-cla/).

## Working examples

| Scenario  | Status quo | Proposed policy |
|---|---|---|
| **Minor documentation contribution:**<br> A deployer discovers an error in [the wiki deployment documentation][UPM43 Building and Deploying uPortal] and directly edits the wiki.  | They are in violation of [the current policy][licensing stance for uPortal manual 3.2 and later] if they do not have a CLA on file. |  As there is no need to file a CLA for  contributions under the proposed policy, direct edits are consistant with the proposed policy. Committers (and others) can monitor wiki updates for inapproriate edits. |
| **Minor code contribution:**<br> A developer discovers a bug in the uPortal codebase and submits the fix via a Git pull request or an email to the project list. | A committer contacts them requesting they submit a CLA before the change can be accepted; the developer decides it is not worth the hassel and the contribution is not accepted. <br>OR<br> A committer inserts the fix into the project knowing there is no CLA on file, a violation of the current policy. | As there is no need to file a CLA for minor contributions under the proposed policy, a committer can readily add the code to the project. |
| **Major code contribution:**<br> A developer creates a new code module and submits it via a Git pull request. | A committer contacts them requesting they submit a CLA before the contribution can be accepted; the contributor decides it is not worth the hassel and the contribution is not accepted. <br>OR<br> A committer adds the code into the project knowing there is n CLA on file, a violation of the current policy. | A committer judges the contribution as significant and contacts them requesting they submit a CLA before the change can be accepted; the contributor decides it is not worth the hassel; the committer can make an evaluation as to whether or not to still accept the code. |

## Resources for learning more

* [Blog post explaining that Apache does not require CLAs of contributors](http://apetro.ghost.io/apache-contributors-no-cla/)
* [Apereo licensing discussion list topic](https://groups.google.com/a/apereo.org/d/topic/licensing-discuss/c1puG3RKZcA/discussion)

[Apache 2 license]: http://www.apache.org/licenses/LICENSE-2.0

[licensing stance for uPortal manual 3.2 and later]: https://wiki.jasig.org/display/UPC/Documentation+Licensing
[UPM43 Building and Deploying uPortal]: https://wiki.jasig.org/display/UPM43/Building+and+Deploying+uPortal
