npx create-next-app@latest my-next-app --typescript --eslint --tailwind --src-dir --app --import-alias "@/*"

**************

.cursorrules

https://gist.github.com/kleneway/8b1e0e33a21d3bb936b3ded84af314e9
****************
BRD/PRD Prompts for a strong reasoning model & Creating .cursor-tasks.md

https://chatgpt.com/share/67c5ee78-0b94-800d-b467-ceecdbf6ce70

********
Updating cursortasks.md

https://gist.github.com/kleneway/07432638aeaf6210316ebbc32dfbe643 
************
Once all functionality built Use rubric (https://youtu.be/5Lu7k2SShNw?t=748)
create a plan using UX rubric :  https://gist.github.com/kleneway/10b3848d60553e794ada863d3393544e
cherrypick most imp things to build from plan.

OR

'Analyze my existing project, then override all CSS and visual styling to match the uploaded design.md specifications while preserving all functionality and HTML structure'

follow this guidelines : https://github.com/ankitpandey2708/dhbvn-web/blob/main/design.md 
*****************
Cosmetic Changes
************************
DO it in this order. DO it atleast twice

check for any data being stored in the browser. delete after confirming with me. 

check for any data being exposed in the browser . eg : api keys etc.

npm run knip

Delete unused code from files. if entire file need to be deleted , give a single command for multiple such files wrt cmd.

check for code duplication.

Delete unused code from files. if entire file need to be deleted , give a single command for multiple such files wrt cmd.

check for Code refactoring.
************
for linting issues :

npm run build
