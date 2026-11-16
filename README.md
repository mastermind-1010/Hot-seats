# Hot Seats

4 business challenges × 15 minutes. Interactive group problem-solving for mastermind sessions.

Members submit business challenges and upvote them. The top 4 by votes each get a 15-minute hot seat. The host starts each hot seat (which starts the shared timer), and `#present` is a full-screen view for screensharing.

Members don't need an account: each browser is signed in anonymously, which allows one upvote per challenge per person. The host signs in with Google.

## Setup

See the steps in the project's setup notes: create a Firebase project, enable Firestore, Anonymous and Google sign-in, add `mastermind-1010.github.io` as an authorized domain, publish `firestore.rules` with the host's email, and paste the web app config into the top of `index.html`.

## Running a session

- Share the site link with members. They submit and vote from there.
- Click **Host sign-in** and use the host Google account to get the timer, **Start hot seat**, **Finish hot seat**, **Remove** and **Clear finished challenges**.
- Open **Present view** in its own window, click **Full screen**, and screenshare that window.
