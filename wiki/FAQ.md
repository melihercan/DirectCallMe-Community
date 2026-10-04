# FAQ

### Can more than two people join a call?

No, and that is deliberate. An invitation holds the keys for one connection, and the first person
to answer it uses it up. Without a server, a group call would mean every device connecting to every other - three
connections for three people, six for four - each carrying its own video, so the upload and battery
use grow with every person. DirectCallMe is made for one-to-one calls and does them well.

### Is it free?

Your first five calls are free. After that, unlimited calls are a **one-time purchase** in the store
you installed from - no subscription and no account. The price is shown in the app.

### I bought it - how do I unlock it on another device?

You don't need to do anything. The purchase belongs to your store account (Google Play, the App
Store, or the Microsoft Store), and DirectCallMe asks the store about it every time it starts, so it
shows **Unlocked** on any of your devices signed in to the same account in the same store.

If it doesn't - no internet when the app started, or the store account not yet signed in - open
DirectCallMe again once it is, or tap **Restore a previous purchase** on the purchase screen, which
asks the store again.

A purchase stays in the store it was made in: one made on Google Play does not unlock DirectCallMe on
an iPhone or on Windows.

### Why do I send an invitation? Other apps just ring.

Other apps ring through their own servers - and through Apple's and Google's notification
services - which know who you are and who you call. DirectCallMe has no server, so the **invitation
is the ring**: a call link you send in any chat you already use. The other person taps it and the
call starts.

On the same Wi-Fi you don't need it: the call shows up in their app under **Calls on this Wi-Fi**.
And for someone you have called before, **Call again** on the first screen makes the invitation and
opens the share sheet in one tap.

### Why does the other person sometimes have to send a reply back?

Their answer normally comes back to your device by itself. Some mobile networks don't let anything
reach a phone directly; then their app shows a reply and opens the share sheet with it, and the call
starts when you tap it. It stays valid for about fifteen minutes.

### It says "The invitation is damaged and cannot be read"

Tap the link in the message instead of pasting it - that always works. If the link can't be tapped,
copy only the line with the link (it starts with `directcallme://`) and paste that. Test versions
before the fix in the [release notes](Release-Notes) sometimes failed to read a whole pasted message;
an updated app reads it either way, so updating from your store fixes it for good.

### Why doesn't DirectCallMe ring the other phone?

Ringing a phone that is not running the app needs a push notification, which always goes through
Apple's or Google's servers. DirectCallMe sends nothing through anyone's servers, so the person you
call opens the app by tapping your invitation.

### Can I call someone who is not on the same kind of device?

Yes. Android, iPhone, iPad, Mac and Windows can all call each other.

### Is it safe to send an invitation over WhatsApp or email?

Yes - it is meant to travel that way. It lets the other device find yours for one call, and only
the first answer is accepted. Don't post invitations publicly. To be sure who you are talking to,
compare the six-character code on the call.

### Does a call use a lot of data?

Video uses about as much as any video call. On mobile data, turn on **Low data** - for one call from
the call screen, or for every call in Settings.

### The app says "Your five free calls are used up."

That is the free trial ending. See *Is it free?* above.
