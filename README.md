# OpiArto — privacy policy

The privacy policy for the OpiArto study planner, published at
**https://auroracamsolutions.github.io/opiarto-privacy/**

That URL is what the Google Play listing points at, and Play requires it to
stay reachable for as long as the app is published. The repository holds
nothing but the page: no app source, no keys.

**It is public as of 6 September 2026, and the page is live again.**

Keep it that way. GitHub Pages does not serve a private repository on a free
plan, and when this repository was made private on 29 August it *unpublished*
the site rather than pausing it: the URL began returning 404 and the Pages
configuration was gone from the API, so restoring it meant making the
repository public **and** switching Pages back on. Play checks this URL, and an
app whose privacy policy 404s is an app whose listing is in trouble — so making
this repository private again is not a small or reversible thing to do.

The policy's central claim — that nothing the student types leaves the device —
is checkable against the app itself: it contains no networking code. The
`INTERNET` permission *is* declared, held and unused, so that a later release
can ask whether it must be updated; the page says so, and says that the
student's work is not what such a check would send. If that ever changes, this
page changes first.

Edit `index.html`, commit, and GitHub Pages republishes it.
