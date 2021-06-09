# UNSUPPORTED PAGES

- https://github.com/citation-file-format/citation-file-format/commit/16192bf05e99bcb35d5c3e085047807b5720fafc (COMMIT - PROBABLY DON'T WANT TO SUPPORT IN DOWNSTREAM CLIENTS)
Context is only commit w/ diff or something, not "the software"

--------------------

# COMMIT PAGE

e.g.:
- https://github.com/citation-file-format/citation-file-format/tree/16192bf05e99bcb35d5c3e085047807b5720fafc (REPO AT COMMIT (!=TAG))
- https://github.com/citation-file-format/citation-file-format (TIP COMMIT OF DEFAULT BRANCH AT COMMIT != TAG)
- https://github.com/citation-file-format/citation-file-format/tree/lint-schema (TIP COMMIT OF OTHER BRANCH at COMMIT != TAG)



Cite this software:

Druskat, S. My Software. 2021-01-14. GitHub. url: https://github.com/sdruskat/mysoftware/aszgöohaölshgljsfhg363as9df6709as678b4a7fd65gs67d5fg4a8 [Accessed: 2021-06-09]

## Where does DOWNSTREAM CLIENTS get their info from for rendering?

- From CFF: authors, title
- From GitHub: url (`commit` you're looking at, always the tree URL (second one above)), "publication date" = commit date, date last accessed: `today`)

--------------------

# RELEASE / TAG PAGE

e.g.:
- https://github.com/citation-file-format/citation-file-format/releases/tag/1.1.0 (RELEASE)
- https://github.com/citation-file-format/citation-file-format/tree/v0.9-RC1 (REPO AT TAG)
- https://github.com/citation-file-format/citation-file-format (TIP COMMIT OF DEFAULT BRANCH AT COMMIT = TAG)
- https://github.com/citation-file-format/citation-file-format/tree/lint-schema (TIP COMMIT OF OTHER BRANCH AT COMMIT = TAG)



Cite this software:

Druskat, S. My Software (Version 1.2.0). 2021-01-05. GitHub. doi: https://doi.org/version.doi.1.2.0. url: https://github.com/citation-file-format/citation-file-format/releases/tag/1.1.0 [Accessed: 2021-06-09]

## Where does DOWNSTREAM CLIENTS get their info from for rendering?

- From CFF: authors, title, doi (based on the latest release)
- From GitHub: url (e.g., release or tag you're looking at), version (== tag), date-released (of tag), date last accessed: `today`
