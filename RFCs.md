So you want to write an RFC?

Define a problem Discuss in slack

Start an RFC, you can work with this template:

    Title: "RFC: Add a Markdown Spell Checker to all Markdown docs in PR"

    ## Proposal:

    Apply a spell checker to every markdown document that appears in a PR.

    ## Reasoning

    We want to have polished documents, both internally and externally. Having a spellcheck
    happening without any effort on a developers part means that we'll get a second look at
    any documentation improvements on any repo.

    ## Exceptions:

    This won't be perfect, but it is better to get something working than to not have it at all.
    I added the ability to ignore files: so CHANGELOGs which tend to be really jargon heavy will
    be avoided in every repo.

    Other than that, we can continue to build up a global list of words to ignore.

    ## Additional Context:

    You can see our discussion [in slack here](/link/to/slack.com)

Give a week

Resolve the RFC, you can work with this template:

    ## Resolution

    We decided to implement the policy.

    ## Next Steps

    Merge the PR on artsy/artsy-danger

    ## Level of Support

    Overwhelmingly positive feedback.

    ## Exceptions:

    Looks like we don't want it for artsy/auctions or analytics repos.

    ## Additional Context:

    You can see our discussion [in slack here](/link/to/slack.com)

Recommendations for the Level of Support section:

* `Overwhelming positive feedback.`
* `Positive feedback.`
* `Majority Acceptance, with conflicting Feedback.`
* `Acceptance, with Little Feedback.`
* `Unclear Resolution.`
* `RFC Rejected.`
* `RFC Rejected, with Conflicting Feedback.`
