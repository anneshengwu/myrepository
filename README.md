<!--
  <<< Author notes: Header of the course >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses Creative Commons Attribution 4.0 International.
-->

<img src=https://repository-images.githubusercontent.com/149791379/3578a500-586d-11ea-9ac3-39087235fe44 width=300 align=right>

# Reviewing pull requests

_See how collaboration works on GitHub and start building great things, together._

<!--
  <<< Author notes: Start of the course >>>
  Include start button, a note about actions minutes,
  and tell the learner why they should take the course.
  Each step should be wrapped in <details>/<summary>, with an `id` set.
  The start <details> should have `open` as well.
  Do not use quotes on the <details> tag attributes.
-->

<details id=0 open>
<summary><strong>:golf: Start</strong></summary>

**To start this course: [<img width="150" alt="Use this template" src="https://user-images.githubusercontent.com/1221423/148581131-555c0fb8-5361-4450-a760-75fa6219a2fc.png">](https://github.com/githublearn/reviewing-pull-requests/generate)**

> We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).<br>
> After you make your own repository, wait about 20 seconds and refresh. I will go to the next step.

All great projects start with collaboration. Pull requests are the foundation of teamwork on GitHub — and pull request reviews give you the ability to work together and discuss changes specific to a pull request by commenting, requesting changes, or approving.

- **Who is this for**: Developers, new GitHub users, users new to Git, students, managers, teams.
- **What you'll learn**: When and how to request a review; how to perform a review for someone else's pull request.
- **What you'll build**: We'll be reviewing a pull request for a simple game.
- **Prerequisites**: We assume you are familiar with creating branches, commits, and pull requests from [Introduction to GitHub](https://github.com/githublearn/introduction-to-github).
- **How long**: This course is 5 steps and takes less than 30 minutes.

</details>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

<details id=1>
<summary><strong>:monocle_face: Step 1: Assign yourself as a reviewer</strong></summary>

### :wave: Welcome to "Reviewing pull requests"!

**What is a _pull request review_**: Reviewing a pull request is an opportunity to examine another contributor's changes. It's an awesome opportunity to learn more about how the project works and how others solve problems.

The best way to get a review is to ask for one. On GitHub, you can ask someone to review a pull request by assigning them as a reviewer. If you are not ready for review, consider [creating a draft pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) instead.

### :keyboard: Activity: Assign yourself as a reviewer

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. We made a pull request for you from the `add-game` branch, so open that pull request.
1. Under **Reviewers** on the right side of the screen, add yourself.
1. Wait about 20 seconds then refresh this page for the next step.

</details>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the first step.
  Define terms and link to docs.github.com.
  Historic note: this step combines the commend, approve, and needs changes steps from the previous version.
-->

<details id=2>
<summary><strong>:white_check_mark: Step 2: Leave a review</strong></summary>

### :tada: You did assigned yourself as a reviewer!

Pull request reviews ensure quality and maintain momentum of changes to your project.

#### When reviewing a pull request:

1. Review the _title_ and _body_ of the pull request to understand the intended change.
1. Review the [diff](https://docs.github.com/en/get-started/quickstart/github-glossary#diff), the comparison of the proposed code, in the context of the whole project.
1. For most things, try out the proposed change. Check if the actual change matches the intention. Find the [contributing guide](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors) to find out how to review the changes.

#### In your review comments:

- Identify potential issues, risks, and limitations.
- Suggest changes and improvements.
- Share awareness of upcoming changes with individuals and teams.
- Ask questions to verify shared understanding.
- Prioritize the most important feedback.
- Be concise _and_ provide meaningful detail.
- Treat the pull request author with empathy.

When an approval or request for changes is not yet needed, consider using **comments**. An **approval** lets the author know you believe the pull request is safe to merge. **Request changes** lets the author know you believe the pull request is not ready to merge.

### :keyboard: Activity: Leave a review

1. On the pull request, click **Files changed**.
1. Click **Review changes**.
1. Add a comment with your initial thoughts on the pull request.
1. Select _comment_, _approve_, or _request changes_: any option will work.
1. Click **Submit review**.
1. Wait about 20 seconds then refresh this page for the next step.

</details>

<!--
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the first step.
  Define terms and link to docs.github.com.
-->

<details id=3>
<summary><strong>:information_desk_person: Step 3: Suggest changes</strong></summary>

### Nice work reviewing that pull request :sparkles:

Now that you have explored the different ways you can review a pull request it is time to learn how to use _suggest changes_.

**What is _suggest changes_**: This feature enables you to recommend a change to a pull request that the author can commit with the push of a button.

### :keyboard: Activity: Suggest changes

1. On the pull request, click **Files changed**.
1. Hover your cursor next to the line numbers on the left side of the page.
1. Click the blue plus icon.
1. After the commment form appears, click the **Insert a suggestion** button.
1. Edit the suggestion.
1. Click **Add a single comment**.
1. Wait about 20 seconds then refresh this page for the next step.

</details>

<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the first step.
  Define terms and link to docs.github.com.
-->

<details id=4>
<summary><strong>:leaves: Step 4: Apply suggested changes</strong></summary>

### Nicely done suggesting changes! :sparkles:

Now lets see how easy it is to [apply your suggestion](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/incorporating-feedback-in-your-pull-request)!

### :keyboard: Activity: Apply suggested changes

1. Click **Commit suggestion**.
1. Enter a commit message.
1. Click **Commit changes**.
1. Wait about 20 seconds then refresh this page for the next step.

</details>

<!--
  <<< Author notes: Step 5 >>>
  Start this step by acknowledging the first step.
  Define terms and link to docs.github.com.
-->

<details id=5>
<summary><strong>:shipit: Step 5: Merge your pull request</strong></summary>

### :heart: Almost there!

You can now [merge](https://docs.github.com/en/get-started/quickstart/github-glossary#merge) your pull request!

### :keyboard: Activity: Merge your pull request

1. Click **Merge pull request**.
1. Delete the branch `add-game` (optional).
1. Wait about 20 seconds then refresh this page for the next step.

</details>

<!--
  <<< Author notes: Finish >>>
  Review what we learned, ask for feedback, provide next steps.
-->

<details id=X>
<summary><strong>:checkered_flag: Finish</strong></summary>

### Congratulations friend, you've completed this course!

<img src=https://octodex.github.com/images/hula_loop_octodex03.gif alt=celebrate width=300 align=right>

As you continue working on GitHub, remember that high quality reviews improve your projects. If you are new to a repository, inquire about what review practices they have so you can hit the ground running.

Here's a recap of all the tasks you've accomplished in your repository:

- You learned how to assign pull requests for review.
- You left a review on a pull request.
- You suggested changes to a pull request.
- You applied suggested changes to a pull request.

### What's next?

- Try adding a [`CODEOWNERS`](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners) file to your project to automatically assign reviewers to pull requests.
- We'd love to hear what you thought of this course [in our community forum](https://github.community/c/education/github-learning-lab/34).
- [Take another GitHub Learn Course](https://github.com/githublearn).
- [Read the GitHub Getting Started docs](https://docs.github.com/en/get-started).
- To find projects to contribute to, check out [GitHub Explore](https://github.com/explore).

</details>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our community forum](https://github.community/c/education/github-learning-lab/34) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2022 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [CC-BY-4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode)
