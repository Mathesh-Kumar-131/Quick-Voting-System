# Quick-Voting-System-
QuickVote: Simple HTML, CSS, and JavaScript Polling System with Candidate Selection and Dynamic Updates
<h3  ><a href=https://votingsys.netlify.app/ >Quick Access web App system (click)</a></h3> 



This repository contains the code for a simple web-based voting system, named QuickVote, implemented using HTML, CSS, and JavaScript. The system allows users to create polls with up to three candidates, cast votes, and view real-time vote counts. The application leverages sessionStorage for data persistence, enabling users to navigate between pages without losing poll and vote information. The code includes intuitive UI updates, dynamic content population, and a straightforward user experience. To use QuickVote, simply save your poll details, vote for candidates, and track the ongoing voting process effortlessly.

<h3> Initialization and Data Retrieval:</h3>
Declare variables (c1_votes, c2_votes, c3_votes, poll_name, cand_1, cand_2, cand_3) for voting counts and candidate information.
Check sessionStorage for stored values of poll details, candidate names, and vote counts.
Populate corresponding UI elements with retrieved or default values.
<h3> User Interface Updates:</h3>
Update elements with specific classes (e.g., .poll-name, #cn-1, .c1-nme) with retrieved or default values.
<h3> Voting Functionality:</h3>
Attach event listeners to buttons (.btn-1, .btn-2, .btn-3) for voting candidates 1, 2, and 3.
Increment corresponding vote count on button click.
Display user alert with the voted candidate and store updated vote count in sessionStorage.
<h3> Poll Creation and Navigation:</h3>
Capture input values for poll name and candidate names on .save-btn click event.
Store input values in sessionStorage for data persistence.
Redirect user to another page (index.html) using window.location.href.
Usage:

<h2> Clone the repository.</h2>
Open index.html in your browser.
Create a poll, vote for candidates, and track real-time vote counts.
Feel free to contribute or report issues!
