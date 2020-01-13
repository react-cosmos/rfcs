# React Cosmos RFCs

> Join `#ideas` on [Slack](https://join-react-cosmos.now.sh/) for bouncing around ideas without formality.

Many changes, including bug fixes and documentation improvements can be
implemented and reviewed via the normal GitHub pull request workflow.

Some changes though are "substantial", and we ask that these be put
through a bit of a design process and produce a consensus among the React Cosmos
core team.

The "RFC" (request for comments) process is intended to provide a
consistent and controlled path for new features to enter the project.

[Active RFC List](https://github.com/react-cosmos/rfcs/pulls)

React Cosmos is still **actively developing** this process, and it will still change as
more features are implemented and the community settles on specific approaches
to feature development.

## When to follow this process

You should consider using this process if you intend to make "substantial"
changes to React Cosmos or its documentation. Some examples that would benefit
from an RFC are:

- A new feature that creates new API surface area, and would
  require a feature flag if introduced.
- The removal of features that already shipped as part of the release
  channel.
- The introduction of new idiomatic usage or conventions, even if they
  do not include code changes to React Cosmos itself.

The RFC process is a great opportunity to get more eyeballs on your proposal
before it becomes a part of a released version of React Cosmos. Quite often, even
proposals that seem "obvious" can be significantly improved once a wider
group of interested people have a chance to weigh in.

The RFC process can also be helpful to encourage discussions about a proposed
feature as it is being designed, and incorporate important constraints into
the design while it's easier to change, before the design has been fully
implemented.

Some changes do not require an RFC:

- Rephrasing, reorganizing or refactoring
- Addition or removal of warnings
- Additions that strictly improve objective, numerical quality
  criteria (speedup, better browser support)
- Additions only likely to be _noticed by_ other implementors-of-React Cosmos,
  invisible to users-of-React Cosmos.

## What the process is

In short, to get a major feature added to React Cosmos, one usually first gets
the RFC merged into the RFC repo as a markdown file. At that point the RFC
is 'active' and may be implemented with the goal of eventual inclusion
into React Cosmos.

- Fork the RFC repo http://github.com/react-cosmos/rfcs
- Copy `0000-template.md` to `text/0000-my-feature.md` (where
  'my-feature' is descriptive. Don't assign an RFC number yet).
- Fill in the RFC. Put care into the details: **RFCs that do not
  present convincing motivation, demonstrate understanding of the
  impact of the design, or are disingenuous about the drawbacks or
  alternatives tend to be poorly-received**.
- Submit a pull request. As a pull request the RFC will receive design
  feedback from the larger community, and the author should be prepared
  to revise it in response.
- Build consensus and integrate feedback. RFCs that have broad support
  are much more likely to make progress than those that don't receive any
  comments.
- Eventually, the team will decide whether the RFC is a candidate
  for inclusion in React Cosmos.
- An RFC may be rejected by the team after public discussion has settled
  and comments have been made summarizing the rationale for rejection. A member of
  the team should then close the RFCs associated pull request.
- An RFC may be accepted and a team member will merge the RFCs associated pull
  request, at which point the RFC will become 'active'.

## The RFC life-cycle

Once an RFC becomes active, then authors may implement it and submit the
feature as a pull request to the React Cosmos repo. Becoming 'active' is not a rubber
stamp, and in particular still does not mean the feature will ultimately
be merged; it does mean that the core team has agreed to it in principle
and are amenable to merging it.

Furthermore, the fact that a given RFC has been accepted and is
'active' implies nothing about what priority is assigned to its
implementation, nor whether anybody is currently working on it.

Modifications to active RFCs can be done in followup PRs. We strive
to write each RFC in a manner that it will reflect the final design of
the feature; but the nature of the process means that we cannot expect
every merged RFC to actually reflect what the end result will be at
the time of the next major release; therefore we try to keep each RFC
document somewhat in sync with the feature as planned, tracking such changes
via followup pull requests to the document.

[react rfc process]: https://github.com/reactjs/rfcs

## Implementing an RFC

The author of an RFC is not obligated to implement it. Of course, the
RFC author (like any other developer) is welcome to post an
implementation for review after the RFC has been accepted.

If you are interested in working on the implementation for an 'active'
RFC, but cannot determine if someone else is already working on it,
feel free to ask (e.g. by leaving a comment on the associated issue).

## Reviewing RFCs

Each week the team will attempt to review some set of open RFC
pull requests.

React Cosmos doesn't employ full-time developers and the RFC process can be delayed in some cases.
We thank you for your patience and for your contributions to React Cosmos.

**React Cosmos's RFC process owes its inspiration to the [React RFC process]**
