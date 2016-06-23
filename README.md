# PR-workflow-tracking-for-DQM-GUI

Note that for the moment this is just a test!!! It will be either this or JIRA
Jira probably has better state machine support, but github is extremely simple

The workflow itself is documented in https://twiki.cern.ch/twiki/bin/view/CMS/DQMOnlineProcedures

For the moment I keep track of the different statuses of each GUI PR in a private text file.
This works, fine, the overhead is absolutely minimal and it allows me to remember the status of every PR in the blink of an eye.
It also allows me to follow up on the final merging: I can see immediatly for which PRs I have requested a merge and for which of those the merge has actually happened.

Text files are fine, but difficult to share. So the idea would be to create an issue for each GUI PR and track the status in this issue.<br>
The title of the issue would be (the way it's done now in my test file):<br>
PRxxx / <subsystem name> / first name of requester / Online/Offline : Title of the PR<br>
Example:<br>
PR336 / L1T / Esmaeel / Online: shift_l1t_layout is updated<br>
PR345 / BeamPixel / Mauro / Online: Changed histogram name accordingly to DQM app<br>
PR346 / ECAL / Mike / Online: Add noise correlation+difference plots<br>

The different statuses can then be encoded using the typical labels
