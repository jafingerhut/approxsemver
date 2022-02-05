# ApproxSemantic Versioning 1.0.0

Summary

Given a version number MAJOR.MINOR.PATCH, increment the:

+ MAJOR version when you want to publicize that you have added cool new features you like, and want to draw attention to.
+ MINOR version when you add more minor features that are not quite so cool as a major version increase, or when it has been a while since the last time you released a version that did.
+ PATCH version when you make small bug fixes.

Additional labels for pre-release and build metadata are available as
extensions to the MAJOR.MINOR.PATCH format.

I mean, sure, [semantic versioning](https://semver.org) _sounds_ good
when you read about it, and of course we think it would be great if
other people's code that we depended upon did this, but let's not go
overboard when it comes to version numbers for our project, right?

We are all adults here.  Let's just codify what we are planning to do
anyway.

A project SHOULD pay lip service to semantic versioning, especially if
that is what your users like to hear.

A project MAY bump up the major version number when making backwards
compatible changes, but ...  come on!  I only made a little tiny
backwards-compatible change to this one little API call in the corner
that I don't know how many users of my project actually care about.
It would look embarrasing if I violated common software development
practice of bumping up the MAJOR version number for a little change
like that, when I didn't even include any major new features.  Our
sales/marketing team would never let us do that, anyway, so why get
into a long protracted argument with them that we will lose, anyway?

A project MAY publish backwards-incompatible changes made in release
notes for new versions, regardless of how big or small they might be.
But of course the more minor they are, the more likely they will be in
footnotes, or only in an additional sentence or two of the API docs.
Who has time to keep track of all of these things from release to
release?

A project MUST bump up the major version number when marketing or
sales teams asks for it, even if the new enhancements are completely
backwards compatible.  The cool thing is that this practice is
actually completely compatible with the Semantic Versioning, so we can
defend this by demanding that any Semantic Versioning lawyer tell us
exactly which part of it we are violating.  That should keep them
spinning their wheels for a while.

Now being 100% serious: I am _not_ claiming that everyone should use
semantic versioning for their projects.  I am fervently hoping that if
someone _claims_ to use semantic versioning, that they follow it
strictly to the letter.  If you do not want to follow it strictly to
the letter, then do not claim that you use it.
