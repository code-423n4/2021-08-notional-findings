# [Sponsorname] Contest

Unless otherwise discussed, this repo will be made public after contest completion, sponsor review, judging, and two-week issue mitigation window.

---

## Contest findings are submitted to this repo

Typically most findings come in **on the last day of the contest**, so don't be alarmed at all if there's nothing here but crickets until the end of the contest.

As a sponsor, you have four critical tasks in the contest process:

1. Handle duplicate issues.
2. Weigh in on severity.
3. Respond to issues.
4. Share your mitigation of findings.

Let's walk through each of these.

## Handle duplicates

Because the wardens are submitting issues without seeing each others' submissions, there will always be findings that are clear duplicates. Other findings may use different language which ultimately describes the same issue but from different angles. Use your best judgement in identifying duplicates, and don't hesitate to reach out (in your private contest channel) to ask C4 for advice.

1. Determine the best and most thorough description of the finding among the set of duplicates. (At least a portion of the content of the most useful description will be used in the audit report.)
2. Close the other duplicate issues and label them with `duplicate`
3. Mention the primary issue # when closing the issue so that duplicate issues get linked.

## Weigh in on severity 

Judges have the ultimate discretion in determining severity of issues as well as whether/how issues are considered duplicates. However, sponsor input is a significant criteria.

If you disagree with a finding's severity, **leave the original severity label set by the warden and add the label** `disagree with severity` along with comment indicating your opinion for the judges to review. It is possible for issues to be considered `0 (Non-critical)`.

Feel free to use the `question` label to anything you would like additional C4 input on.

## Respond to issues

Label each finding as one of these:

- `sponsor confirmed`, meaning: "Yes, this is a problem and we intend to fix it.")
- `sponsor disputed`, meaning either: "We either not duplicate this issue" or "We disagree that this is an issue at all."
- `sponsor acknowledged`, meaning: "Yes, technically the issue is correct, but we are not going to resolve it for xyz reasons."

Note that it isn't necessary to dispute a finding in order to suggest it should be considered of lower or higher severity.

Add any necessary comments explaining your rationale for your evaluation of the issue. Note that when the repo is public after all issues are mitigated, wardens will read these comments.

## Share your mitigation of findings

For each non-duplicate finding which you have confirmed, you will want to mitigate the issue before the contest report is made public.

As part of that process, we ask that you create a pull request in your original repo for each finding and link to the PR in the issue the PR resolves. This will allow for complete transparency in showing the work of mitigating the issues found in the contest. Rather than closing the issue, mark it as `resolved` with that label.
