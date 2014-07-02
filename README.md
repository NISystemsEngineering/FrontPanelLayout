#NISETemplateRepo
================
###This repository serves as a template for future repositories. It includes a sample readme, style guidelines, gitignore, vipb, and directory structure.
================
####*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*
================

###Goals:
**What** should be accomplished by the project.
 
###Background:
**Why** does this project exist? What need or needs does this fill? What experience justifies the need for this project?
 
###Overview:
High level description of **how** it should be accomplished. How does this match the goals of the project, and how does it fulfil the needs outlined. Provide a high level set of specific requirements.
 
###Repository Overview:
Identify the organization of any branches. In general, branches should follow the pattern outlined in the next section. This should include indications of which version each branch is currently on.
 
###Test Process:
Describe what tests exist, and which must pass. In general, all tests must pass. If needed, define what passing means for the tests (if the code does not run in a test framework, for example). All submissions should result in code that passes the expected tests.
 
###Build Process:
Describe how to build the code, and what the expected build artifacts are. This is critical, as all submissions should result in code that builds. If applicable, describe a test plan for the generated build artifact (required if the result is an executable, not required if the result is a source API).
 
###Contribution Workflow:
*For a more complete workflow, view [this set-up guide](https://decibel.ni.com/content/docs/DOC-37416) and [this workflow guide](https://decibel.ni.com/content/docs/DOC-37417).*

1. Fork this repository into your account.
2. Create a branch for your change.
3. Make changes, periodically pulling and merging any updates from the central repository.
4. Push your changes up to your branch in your copy of the repository.
5. Send a pull request to the owner of this primary repository. Follow the contribution guidelines.
 
###Contribution Guidelines:
- Limit the scope of your change as much as possible. Smaller changes are easier to process. Any major changes should be discussed beforehand with the managers of the repository to ensure that it fits within the goals and vision of the project.
- Explain the reason for your change with as much detail as possible. If it is a bugfix, link it to an issue in the issues tracker. If it is an enhancement, consider making an issue in the issue tracker to discuss the enhancement before making it. This ensures that the enhancement will provide value to other users.
- Run through the style guidelines and any available VI analyzer tests to ensure compliance with the general style of the project. Don't go crazy trying to make the code perfect. Do make sure there are no glaring issues.
- Before committing a change, be sure to rebase or merge your code off of the most up-to-date source in the master. This reduces the risk of merge conflicts and makes it that much easier to merge your pull request and that much more likely that the change will be accepted.
- Ensure that all builds are successful with your change in place, after rebasing.
- Ensure that all tests pass with your change in place, after rebasing.
