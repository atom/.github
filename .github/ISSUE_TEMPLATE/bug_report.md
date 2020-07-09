---
name: Bug report
about: Create a report to help us improve

---

<!--

Have you read Atom's Code of Conduct? By filing an Issue, you are expected to comply with it, including treating everyone with respect: https://github.com/atom/.github/blob/master/CODE_OF_CONDUCT.md

Do you want to ask a question? Are you looking for support? The Atom message board is the best place for getting support: https://discuss.atom.io

-->

### Prerequisites

* [X] Put an X between the brackets on this line if you have done all of the following:
    * Reproduced the problem in Safe Mode: <https://flight-manual.atom.io/hacking-atom/sections/debugging/#using-safe-mode>
    * Followed all applicable steps in the debugging guide: <https://flight-manual.atom.io/hacking-atom/sections/debugging/>
    * Checked the FAQs on the message board for common solutions: <https://discuss.atom.io/c/faq>
    * Checked that your issue isn't already filed: <https://github.com/issues?utf8=✓&q=is%3Aissue+user%3Aatom>
    * Checked that there is not already an Atom package that provides the described functionality: <https://atom.io/packages>

### Description

Crash Behavior:
A folder have been oppened for some times,
even if the folder is empty.

Crash Possible Initial Trigger:
It seems that crash began after I installed Git Bash
(I also had recently installed Github Desktop)

Attempted Steps:
Tried Safe Mode
Tried Clearing Window State
Tried Deleting the folder I was attempting to work which contained .git folder
Tried Disabling the 'github', 'open-on-github', and 'git-diff' packages
Tried a Clean Install after careful Uninstall
Tried Disabling all Packages (after reinstallation)
Tried Clearing Window State Again with all packages disabled
Tried Safe Mode Again with all packages disabled
Tried Disabling GPU Acceleration
Also got a runtime performance report just in case.

### Steps to Reproduce

1. Open Atom any way you want. (Click on the icon, as Admin, or from the command line)
2. Open a folder, even an empty one or one that only contain text files.
3. Wait a few minutes.

**Expected behavior:**

Atom code editor keeps on functionning normally.

**Actual behavior:**

Atom code editor crashes

**Reproduces how often:**

100%

### Versions

Atom: 1.48.0
Electron: 5.0.13
Chrome: 73.0.3683.121
Node: 12.0.0

Windows Edition: Windows 10 Education

### Additional Information

I'l like to include the error log but I'm not sure how to join a file on here.
