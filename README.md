# deps
use [pnpm](https://pnpm.io/) as a package manager.

# setup
`pnpm install`

# development
open 2 terminal windows. 

run `pnpm run dev` to host the website locally, and `pnpm run css` to watch for tailwind changes and rebuild the css output file accordingly.

# conventions
### commits:
- messages should be all lowercase except for acronyms.
- messages should start with a verb. i.e "migrate images to new CDN host".

### branches:
- names are all lower case, always.
- smaller names are better.
- don't put your name in the branch name like "caio-branch".

### issues
- be verbose and explain the issue/feature request to the best of your understanding.

### PRs
- explain what you did.
- mention issues which the PR closes when applicable.
- rebase is preferable over merge.
- delete branch after rebasing/merging

### the code
- always format.
- no meat proxies (use clankers responsibly).
