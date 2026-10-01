# Privacy

DirectCallMe was made so that a call is between two people and nobody else. In the app's own words,
under **Settings > Privacy**:

> No account, no server, no call log. Your name and these settings stay on this device, and so do
> the people you chose to remember after comparing the code: a name and a device key each, nothing
> else. The only things outside the two devices that ever see a packet are the STUN servers above,
> asked for your public address while a call is being set up and told nothing else. Turn on
> LAN-only and not even that is sent. Nothing about a call is written to disk; a file you receive
> is kept only if you save it.

What that means in practice:

- **No account, phone number or contacts.** You choose the name the other person sees.
- **The call is end-to-end encrypted** with the standard WebRTC encryption (DTLS-SRTP). The six
  characters both screens show let you confirm that nobody is in between.
- **Remembering people is your choice.** Tap **Codes match** after comparing the code, and the app
  keeps that person's name and their device's public key, on your device only, so the next call
  with them is recognised without comparing again. If someone uses a remembered name from a
  different device, the call says so. Forget anyone from the home screen.
- **Invitations and replies** carry what the two devices need to find each other, including network
  addresses. Send them only to the person you are calling, and don't post them publicly.
- **Nothing is logged or uploaded.** DirectCallMe has no analytics and no crash reporting of its
  own. The app stores may collect their usual crash reports, as they do for any app.
- **Purchases** are handled by the store. DirectCallMe asks the store whether you have unlocked it,
  each time it starts, and keeps nothing about the purchase itself.
