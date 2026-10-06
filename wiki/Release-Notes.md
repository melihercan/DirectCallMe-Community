# Release notes

What changes from one version of DirectCallMe to the next. Versions are the build date, as shown in
**Settings > About** - for example 26.09.30 is 30 September 2026.

## Unreleased

Fixed or added, and not yet in a public release. They come with the next version in the stores.

### New

- **The call starts when they open your invitation.** Their reply now comes back to your device by
  itself wherever it can reach it - on the same Wi-Fi, and on many mobile networks - so there is
  nothing for them to send back. Where it cannot, they see the reply to send you as before.
- **Remember people, and call them again in one tap.** After comparing the code, tap **Codes
  match**: the next call with that person is recognised as the same device, with no comparing.
  They appear under **Call again** on the home screen; **Call** makes a new invitation and opens the
  share sheet. If someone uses a remembered name from a different device, the call warns you.
- **Calls on the same Wi-Fi, with no invitation.** While you are inviting, devices on your network
  see the call under **Join a call → Calls on this Wi-Fi**. They tap **Join**, you accept, and the
  call starts. You can switch it off for a call on the invitation screen.
- **Invitations say what to do.** The shared file is named *Tap to join Anna's call* (a reply, *Tap
  to connect to Bob*), and a copied message starts with the link to tap.
- **iPhone and iPad: the invitation shows who is calling.** Tapping an invitation in WhatsApp or
  Files used to open a grey page with only the file's name and size. It now shows *Call invitation
  from Anna* and how to join: tap the share button, then **DirectCallMe**.
- **A message travels with the shared file** - *Anna is calling you on DirectCallMe. Tap the file to
  join the call.* - in mail and the apps that show text sent with a file. WhatsApp on Android sends
  the file alone.
- **When a reply has to go back by hand, the share sheet opens with it**, and it now stays valid for
  about fifteen minutes instead of five.
- **Documentation and help** in Settings, under About, opens this wiki.
- **A back arrow** beside the Settings title, so the way back is at the top of the page rather than
  only the **Done** button at the bottom.

### Fixed

- **Opening your own invitation answered it.** Tapping an invitation you had sent - still in the
  chat you sent it to - made the app try to join your own call. It now says *This is your own
  invitation* and leaves you where you were.
- **"Camera and microphone are in use" after closing the app (Android).** A call that was still
  being set up when the app was closed from the recent apps could keep its notification, and the
  app running, for a long time afterwards. The camera and microphone were not in use, but the
  notification said they were. Closing the app now ends the call, and a call that ends always
  releases the camera and microphone.
- **Invitations now expire after an hour.** An invitation opened more than an hour after it was
  made says *This invitation has expired*, instead of being answered when nobody is waiting, and a
  caller who has had no reply for an hour stops waiting. Start a new call to try again.
- **"The invitation is damaged" when pasting a whole message.** Copying the entire invitation or
  reply message and using **Paste invitation** or **Paste reply** - as the message itself suggests -
  failed for about half of all invitations. The app now reads the code wherever the message ends.
  Tapping the link was never affected.
- **The other side's hang-up could take up to half a minute to show.** On a Mac in particular, the
  call could stay on screen for 16 to 27 seconds after the other person had hung up. Hanging up now
  tells the other device before the connection closes, so its call ends at once.
- **The call's buttons after closing the chat.** Swiping the chat down could leave a strip across the
  bottom of the call screen that covered Hang up, the microphone and the camera. A chat swiped down
  now closes completely.

- **iPad: the camera stopped when another app was on screen.** With DirectCallMe in Split View, Slide
  Over, Stage Manager or a window next to another app, the other person saw no video and your own
  picture was empty. The camera now keeps running.
- **"No public address could be learned" on a call within the same network.** Answering a call from
  a device on the same Wi-Fi could show this warning although nothing was wrong. It no longer does.
- **The Back button on the invitation and join screens** now cancels the call being set up, the same
  as the **Cancel** button, instead of only leaving the screen. On the purchase screen it does the
  same as **Not now**.
- **The name field on large screens.** On a tablet or a large window the name you type grew with the
  screen but its label stayed small; the label and any message under the field now grow with it,
  within limits.
