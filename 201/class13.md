# 🗒️ Class 13: Local Storage

Covering local storage is important because it is our first experience with creating a web application/site that does not refresh the browser state on refresh.

- Why would a developer use local storage for a web application?
  > A developer would use lcoal storage when they want to store somehting but not necessarily on a server-side. Local storage allows for web application to close and reopen without restarting all over again.

- What information should not be stored in local storage?
  > Any sensitive information

- Local storage can store what type of data? How would you convert it to that type before storing?
  > local storage can only store strings in the different keys. If we want objects to work, we would have to use `JSON.stringify()` and `JSON.parse` as a workaround.
