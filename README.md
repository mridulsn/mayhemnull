# MayhemNull

A free focus timer that shows where your time went. One page, runs in the browser:
https://mridulsaravanan.com/mayhemnull/

Sign-in (Google, GitHub, Discord) and YouTube search are served by the shared sign-in
server at https://auth.mridulsaravanan.com (the `auth-api` project), with `?app=mayhemnull`.
Data syncs to Firebase (Firestore `users/{uid}`) when signed in.
