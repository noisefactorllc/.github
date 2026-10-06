# Contributing to Noise Factor projects

Thanks for your interest in contributing. This policy covers every public
repository in the [noisefactorllc](https://github.com/noisefactorllc)
organization. Some repositories also have their own CONTRIBUTING.md with build
and test steps; follow those too.

## Code of conduct

Everyone who takes part in our projects follows our
[Code of Conduct](CODE_OF_CONDUCT.md). If something happens that makes you
uncomfortable, please tell us at team@noisefactor.io.

## How to contribute

**Report bugs.** Bug reports are always welcome. Tell us what you did, what you
expected, what happened instead, and the version, OS, browser or host
application you used.

**Fix an issue labelled `help wanted`.** These are the issues where we'd love
outside help. Leave a comment on the issue before you start, so two people
don't end up working on the same fix.

**Propose a feature.** Open an issue and describe the problem you want to
solve. We'll talk it through with you and agree on a scope together. Once
we've settled it, we'll write the scope into the issue and label it
`help wanted`, and it's ready for a pull request.

Please check with us before working on anything else. Pull requests that
aren't tied to a `help wanted` issue, including new features, refactors and
dependency bumps, will usually be closed so that our review time goes to the
work we've planned together. If you're not sure whether something fits, open
an issue and ask.

## Issue labels

| Label | Meaning |
|-------|---------|
| `help wanted` | Ready for a contribution. Pull requests should target one of these. |
| `good first issue` | A smaller `help wanted` issue, good for a first contribution. |
| `bug` | A confirmed defect. |

Maintainers apply these labels after triage.

## Pull requests

A good pull request:

1. Links the `help wanted` issue it resolves (for example, `Fixes #123`).
2. Keeps to that issue, so it's easy to review.
3. Passes the repository's existing tests and checks.
4. For a bug fix, adds a test that fails before the fix and passes after it,
   where the repository has a test suite.

By opening a pull request, you confirm that you have the right to submit the
work and that it is licensed under the repository's license.

## Using LLMs and coding agents

You're welcome to use LLMs and coding agents to help with your contribution.
Because generated changes can look right without being right, we ask for a
bit more with these.

**Let us know.** Mention in the pull request description that you used an
LLM, and which tool and model.

**Stick to tracked bugs.** LLM-assisted pull requests should fix an open issue
labelled both `bug` and `help wanted`. For features and other changes, please
start a discussion in an issue first.

**A human is the author.** Every issue and pull request must be opened from
the personal GitHub account of the person responsible for it, not from a bot
or agent account. That person is its author: they have reviewed every line
before submitting, and they answer review questions themselves. If you'd like
an agent to open issues or pull requests on your behalf, arrange it with us
first at team@noisefactor.io.

**Show your work.** New pull requests open with a template that has these
four sections ready to fill in. Paste in or attach output from real runs:

1. **Reproduce.** The steps that show the bug on the default branch, the
   commit SHA, your environment (OS, runtime or browser, GPU or host
   application where relevant), and the failing output. For a visual bug,
   add a screenshot or recording.
2. **Root cause.** What's wrong, where (`file:line`), and why it causes the
   behavior.
3. **Fix.** What you changed and how it addresses the root cause.
4. **Verify.** The same steps on your branch, showing the bug is gone; the
   new test failing on the default branch and passing on yours; and the full
   test suite result. For a visual bug, add an after screenshot or recording.

If a pull request is missing something, we'll point it out and you can update
it.

## Security issues

Please don't report security vulnerabilities in public issues. Email
team@noisefactor.io instead.
