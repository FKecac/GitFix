# GitLab & CodeGrade Guides & Problem Fixes

## Submission Steps (CodeGrade)

- [Choose a Git Hoster](Choose%20git%20hoster.md): How to select the UTwente GitLab.
- [Add the Deploy Key](Milestone%20%231%20Deploy%20Key.md): Instructions for setting up a deploy key for CodeGrade.

## FAQ

<details>
<summary>How do I connect the UTwente GitLab to CodeGrade?</summary>
Follow the steps to set up a deploy key in your GitLab repository and link it to CodeGrade.
</details>

<details>
<summary>Why is my deploy key not working?</summary>
Ensure that the deploy key is properly added with the correct permissions and that the repository is accessible.
</details>

<details>
<summary>I linked my repository to CodeGrade, but it doesn't detect any changes.</summary>
<ul>
  <li>Did you commit and push changes <b>after</b> linking them? This is required.</li>
  <li>
    <details>
      <summary>Are your commits pushed to the branch marked as the <em>default</em> branch in your GitLab repository?</summary>
      <ul>
        <li>
          CodeGrade can only see commits to you default branch.
        </li>
        <li>
          This is not dependent on you branch name. Check on the GitLab website what branch is marked as <em>"default"</em>.
        </li>
        <li>
          If all of this does not work try adding "?branch=YOUR_BRANCH_NAME" to the end of the CodeGrade webhook URL. Replace YOU_BRANCH_NAME with the name of the branch that you want CodeGrade to listen to.
        </li>
      </ul>
    </details>
  </li>
</ul>
</details>
