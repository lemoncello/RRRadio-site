---
title: RRRadio
---

# RRRadio

**RRRadio** is a free internet radio app: discover thousands of stations from around the
world and keep listening even when your connection gets bumpy.

## Features

- **Discover** thousands of stations via the Radio Browser community directory.
- **Favorites** to keep your stations one tap away.
- **Background playback** with automatic reconnection — the "modo subte" keeps the stream
  alive when the network drops.
- **Now playing** metadata straight from the station.
- **Traffic meter** to see how much data your listening uses.
- **Free**: no account, no ads, no personal data collection.

## Availability

Coming to **Google Play**.

## Privacy

RRRadio does not collect, store or transmit any personal data. Read the full
[Privacy Policy](PRIVACY_POLICY/).

## Contact

Questions, feedback or a station that doesn't work? Send us a message — we read everything.

<form id="contact-form">
  <p>
    <label for="c-email">Your email (so we can reply)</label><br/>
    <input id="c-email" type="email" style="width: 95%" placeholder="you@example.com"/>
  </p>
  <p>
    <label for="c-subject">Subject</label><br/>
    <input id="c-subject" type="text" style="width: 95%" placeholder="Question about RRRadio"/>
  </p>
  <p>
    <label for="c-message">Message</label><br/>
    <textarea id="c-message" rows="6" style="width: 95%" placeholder="Tell us something…"></textarea>
  </p>
  <p>
    <button type="submit">Send message</button>
  </p>
</form>

<script>
document.getElementById('contact-form').addEventListener('submit', function (e) {
  e.preventDefault();
  var email = document.getElementById('c-email').value.trim();
  var subject = document.getElementById('c-subject').value.trim() || 'RRRadio contact';
  var message = document.getElementById('c-message').value.trim();
  if (!message) { alert('Please write a message first.'); return; }
  var body = message + (email ? '\n\n—\nReply to: ' + email : '');
  window.location.href = 'mailto:mguadagnini@gmail.com'
    + '?subject=' + encodeURIComponent(subject)
    + '&body=' + encodeURIComponent(body);
});
</script>

You can also write directly to <mguadagnini@gmail.com>.
