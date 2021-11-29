# Contributing to ZilChill

<pre>
  Title: Contributing ZilChill process, initialized
  Author: Bibek Koirala < bibek@redchillies.org >
  Comments-Summary: No comments yet.
  Comments-URI: None yet.
  Status: Active
  Type: Process
  Created: 2020-08-27
  License: BSD-2-Clause
           OPL
</pre>

ZilChill DApp is driven by open source collaborative approach. Currently, RedChillies Labs team is supporting ZilChill as maintainer. And we welcome contributions to ZilChill from all interested parties in many forms. More we contribute, more we grow!

The following is a set of guidelines for contributing to ZilChill which are hosted in the [RedChillies Labs](https://github.com/RedChillies-Core) on Github. Please feel free to propose changes to this document in a pull request as well.

## Before getting started

With peer-to-peer gaming platform, people do not need to depend on centralized entities to play games or to receive game rewards. On top of this, the game result that could be verified by anyone and accessible to everyone would bring true "fair play". Utilizing the high throughput and negligible transaction cost of Zilliqa blockchain, we propose a solution to bring decentralization into gaming platform. Anyone can engaged to host a game by using the RedChillies token and anyone can participate to play the game using ZIL token (will be replaced by stablecoin in future). Results can be verified in smart contracts. And reward claims are distributed from stored Zil and REDC used in each game adding fresh RedChillies token from Reward Wallet. Rewards are distributed to hosts, winning players, developers and governors. As long as there remains majority of honest hosts, players and voters, system remains safe from attackers. We can have a look at [ZilChill Gaming Platform](https://zilchill.com).

## Table of Contents
- [Ways to Contribute](#ways-to-contribute)
- [Can I ask questions by creating issues?](#can-i-ask-questions-by-creating-issues)
- Style-guides(#style-guides)

## Ways to contribute

### Reporting bugs
Bugs are inevitable part of product development and we embrace them openly. If you are a user and find any bugs in the platform, please create an issue in [github repo](https://github.com/RedChillies-Core/PredictionGame/issues). Before creating any issue, please have a look at already existing issues if they are already created. Please try to provide sufficient information and images along with the issue and if possible the steps to replicate the bug. You can also forward the issue in our [Telegram channel](https://t.me/redchilliesREDC). If there is any closed issue and you are facing the same bug again, consider creating a new issue and mentioning the previous issue link in the description.
Note: Please put ``bug`` tag while creating the issue and be as specific you can be.

#### Security bug
If the bug in the platform is related to severe security issues or affects the tokens/coins of other users in the platform, please report us the security issue in our email: [contact@redchillies.org](contact@redchillies.org). We are constantly looking to improve the security of our platform and are happy enough to reward you with a nice bounty.

### Request a feature/enchancement
If you are a user or a developer, you can request a completely new feature or enhancement to already existing features. You can help the maintainers and the community understands your suggestions and possibly that might be the next feature in ZilChill. Please create an issue in RedChillies Labs and put a tag of ``enhancement``. Please be specific and clear about what are you suggesting. Also, provide the motivation behind the enhancement and how would it impact the RedChillies community. 
The suggestions for feature/enhancement can include anyone or combination of the following:
- UI/UX enhancement
- Architecture enhancement
- Security enhancement
- Speed or Storage enhancement
- New functionality
- Others

### Contribute code
You can contribute by adding code to RedChillies Labs. Please open the [issues in github](https://github.com/RedChillies-Core/PredictionGame/issues?q=is%3Aopen+is%3Aissue) and you can start contributing. If the features that you want to develop are not in the issues or if they are not the part of the project's timeline, consider [submitting an enhancement proposal](#request-a-feature/enchancement) first. For creating a contribution:
- Fork the repository from [RedChillies Labs](https://github.com/RedChillies-Core) in which you want to make the changes
- Clone the forked repository in your local machine
- Consider making branches for individual changes in your local machine
- Make changes or add features to the repository
- Fetch the upstream so that your repository is in-sync with the main project
- Push changes to your forked repository in github.
- Open a pull request to the upstream with your changes. Please make sure there are no merge conflicts when you submit the PR. If there are any merge conflicts, fetch the upstream to your local machine and fix the merge conflicts before submitting the pull request.
- Please refer to the [Styleguides](#styleguides) while writing code, commit messages and pull requests. 


### Governance
ZilChill is governed by the community. If you feel that you have a proposal that needs to be decided by the RedChillies community, you can create the proposal and enable voting from our [Governance Portal](https://vote.zilliqa.com/#/redc). You can have a look at previous proposals for the templates of a proposal. Please refer to the following [document](https://docs.snapshot.org/proposals/create) for guiding you to create a proposal. Please use a relevant title for the proposal and ellaborate the proposal to that it can be understood by the voters easily. The options for voting should be clear and specific.
Note: Please discuss about the proposal in our [Telegram Channel](https://t.me/redchilliesREDC).

## Can I ask questions by creating issues?
Please don't create any issues for asking questions. You might get your queries answered faster by contacting us through following medium:
- [Telegram](https://t.me/redchilliesREDC)
- [Email](contact@redchillies.org)

## Styleguides

### Git Commit Messages
- Use present tense in commits
	- Adds reward to the pool ✅
	- Added reward to the pool ❌
- Limit the commit messages to 60 characters or less
- Write a single commit for a single feature change
- Consider adding the following tags in your commit messages based on the changes
	- ``SC:`` : Smart Contract related changes
	- ``Document:`` : Documentation related changes
	- ``API:`` : Changes in API
	- ``Database:`` : Changes in database model
	- ``UI:`` : Changes in frontend

For example: ``git commit -m "SC: Transfers fund to the treasury"``

### Javascript guidelines
- We follow the [Airbnb guidelines](https://github.com/airbnb/javascript) for the applications. Please refer to the following linting configurations:
	- [Enslint]()
	- [Prettirc]()

Note: Please make sure you pass through all the linting configurations before commiting your changes.

### Pull Request guidelines
- Create a pull request by grouping all the commits of the changes
- Make sure you donot include any commit or changes that arenot the part of the pull request
- Please make a single PR for each issue/feature. Minimize the lines of code per PR
- Pick a suitable and specific name within 60 characters
- Describe about the changes made in detail
- Link the issues from the repo linked with the submitted PR
- Consider using the following labels in your PR

| Label | Description |
| ----- | ----------- |
| ``work-in-progress`` | For pull requests that are still being worked on and more changes will be added |
| ``needs-review`` | For pull requests that needs review and approval from the maintainers after completing changes |
| ``under-review`` | While maintainers are reviewing the pull request |
| ``requires-changes`` | For pull requests that needs changes based on the reviews and feedbacks |
| ``needs-testing`` | For pull requests that needs testing to be done |

Release Policy
--------------

The maintainer acts as release manager for each ZilChill release.

Copyright
---------

By contributing to this repository, you agree to license your work under the
BSD-2-Clause OPL license unless specified at the top of the file itself. Any work contributed where you are not the original
author must contain its license header with the original author(s) and source.


