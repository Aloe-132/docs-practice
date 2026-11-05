# Review of the GitHub Repository Guide

## Source and scope

The source is [the Chapter 2 guide](../week2/作业1.md). [before.md](before.md) preserves its title, six steps, and result check without rewriting the sentences. This excerpt contains approximately 181 words, including the title and headings, using a whitespace-based count with Markdown emphasis removed. It meets the 150–250-word source requirement.

[after.md](after.md) revises that excerpt using the six rules in [style-guide.md](style-guide.md).

## Change record

| Change | Before | After | Rule | Reason |
| --- | --- | --- | --- | --- |
| 1 | Signing in appears inside step 1; the excerpt has no starting-point section. | Add **Before you start** with sign-in, desktop browser, English interface, personal account, and a new-repository scope. | R1 | Establish the reader's starting point before the actions. |
| 2 | “Check the box labeled ‘Add a README file.’” | “Set **Add README** to **On** to initialize the repository with a README file.” | R2 | Use a direct action and the control described by current GitHub Docs. |
| 3 | “This file provides basic information about your project…” | Name the “README file” explicitly in step 7. | R3 | Replace an indirect reference with the chosen document term. |
| 4 | “You may also add a short description to explain its purpose.” | “If you want to explain the repository's purpose, enter a short description.” | R4 | Put the condition before the optional action. |
| 5 | Opening the + menu and selecting New repository share one step. | Give opening the menu and selecting New repository separate step numbers. | R5 | Make the sequence easier to track. |
| 6 | The result check is one long sentence. | Use three separate checks for owner/name, visibility, and README content. | R6 | Make each success criterion independently observable. |
| 7 | “Type a suitable name for your repository…” | Give `docs-practice` as the example, with a condition for an existing name. | R4 | Provide a concrete entry and a next action when that name is unavailable. |
| 8 | The procedure does not explicitly select the owner. | Add “Choose your personal account as the owner.” | R1, R5 | Make the personal-account scope an explicit action before entering the repository details. |

## Verification and result check

**Checked on 5 November 2026 by the AI assistant using GitHub's connected tools and official documentation.**

- Repository metadata confirms that `Aloe-132/docs-practice` belongs to the personal account `Aloe-132` and has private visibility.
- Reading the default-branch root file confirms that `README.md` exists and contains text.
- [GitHub Docs — Quickstart for repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories) describes the new-repository menu, repository name, optional description, visibility, **Add README** set to **On**, and **Create repository**.
- The revised document has ordered steps and explicit success criteria.

**Limit:** These checks verify the existing repository and compare the instructions with documentation. They are not a new, end-to-end test in the browser and do not independently verify the rendered **Private** label or README display. No extra repository was created for testing.

**Browser check still to complete:** Have a reader follow the revised guide with an unused repository name in their own account. Record whether the owner/name, **Private** label, and README content match the three result checks. Record any different interface labels.

## Peer feedback

**Status: Pending — no genuine classmate comment has been supplied.**

Ask a classmate to read [after.md](after.md) without an explanation. Ask them to identify one place where the next action is unclear. Record their actual words; do not submit this template as completed feedback.

- Reviewer and date: [To be completed]
- Actual comment: “At step __, I need to know __.”
- Sentence revised in response: [To be completed after the comment]
- Follow-up check and outcome: [To be completed]

## AI disclosure

I used ChatGPT/Codex to help produce my Chapter 2 guide and this revision package. For this homework, it selected an excerpt, drafted the six-rule style guide, revised the instructions, recorded the changes, checked the existing repository through connected GitHub tools, and compared the workflow with GitHub Docs. The assistant also uploaded these files. AI review does not replace an independent browser test or genuine peer feedback; those activities are marked as pending above.

## Before submission

- [x] Preserve a 150–250-word source excerpt.
- [x] Provide six style rules, each with a before/after example.
- [x] Provide a revised guide.
- [x] Explain at least six changes and link them to the rules.
- [x] Include explicit result checks, verification evidence, and an AI disclosure.
- [ ] Add a genuine peer comment and the resulting revision.
- [ ] Complete and record an independent browser test.
