
# Purpose

The objective is to ultimately have a system to automatically apply any hotfixes that are required so that going to production on Monday morning becomes as smooth as possible.


# Hotfixes

File structure is :
```
<course>/
  |-> hotfix-x/
	  |-> readme.md # (optional)
	  |-> bootstrap # (the fix)
	  |-> test      # (optional: test code to validate change)
    ...
```


# Status

deployed this week for a custom do180/do288, so far it worked.

fully unattended execution has not yet been tested.


# Contribute

Patches are most welcome be they regarding the courses already covered or for new courses.

The structure is meant to be as generic as possible while still abiding by a few conventions in order to automate patch application itself.

# TODO

- [ ] make the fX loop match registered machines

- [ ] investigate rc.local use for hotfix bootstrapping

- [ ] validate do288v3.6 for v3.9


