# Contribution Guidelines

Before contributing to this repository, please ensure you are adhering to the following general guidelines. Further, if you are submitting a new prompt to the repository, be sure you are also following the prompt-specific guidelines. These checks will ensure that your contributions can be easily integrated into the main repository, without any headache for the owners.

## General Guidelines

The following guidelines should be followed when making any open-source contributions:

- [ ] Contributions should be made via a pull request to the main repository from a personal fork.
- [ ] Pull requests should be accompanied by a descriptive title and detailed explanation.
- [ ] Submit all pull requests to the repository's main branch.
- [ ] Before submitting a pull request, ensure additions/edits are aligned with the overall repo organization.
- [ ] Be sure changes are compatible with the repository's license.
- [ ] In case of conflicts, provide helpful explanations regarding your proposed changes so that they can be approved by repo owners.

## New Prompt Guidelines

To add a new prompt to this repository, a contributor should take the following steps (in their personal fork):

1. Create the new prompt.
   - Copy the file [PROMPT](./attachments/prompt.md) to the appropriate folder.
   - Ensure prompts generate intended results and can be used by other users to replicate those results.
   - <b>Note:</b> If the folder does not exist, create it.
2. Add the prompt to `README.md` using the following markdown template :

    `[x] [Prompt Title](./prompts/folder-name/prompt-title.md)`

3. Submit a pull request on the repository's main branch.
   - If possible, provide some documentation of how you tested your prompt and the kinds of results you received.
   - Be sure to include a detailed title and description.

### New Prompt Checklist:

- [ ] I've confirmed the prompt works well
- [ ] I've added `[x] [Prompt Title](./prompts/folder-name/prompt-title.md)` to the README.md
- [ ] Removed "Act as" from the title on CSV

Please ensure these requirements are met before submitting a pull request.
