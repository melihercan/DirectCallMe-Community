# Privacy

DirectCallMe was made so that a call is between two people and nobody else. In the app's own words,
under **Settings > Privacy**:

> No account, no server, no call log. Your name and these settings stay on this device. The only
> things outside the two devices that ever see a packet are the STUN servers above, each asked once
> per call for your public address and told nothing else. Turn on LAN-only and not even that is
> sent. Nothing about a call is written to disk; a file you receive is kept only if you save it.

What that means in practice:

- **No account, phone number or contacts.** You choose the name the other person sees.
- **The call is end-to-end encrypted** with the standard WebRTC encryption (DTLS-SRTP). The six
  characters both screens show let you confirm that nobody is in between.
- **Invitations and replies** carry what the two devices need to find each other, including network
  addresses. Send them only to the person you are calling, and don't post them publicly.
- **Nothing is logged or uploaded.** DirectCallMe has no analytics and no crash reporting of its
  own. The app stores may collect their usual crash reports, as they do for any app.
- **Purchases** are handled by the store. DirectCallMe asks the store whether you have unlocked it,
  each time it starts, and keeps nothing about the purchase itself.
