# Networks and connection problems

With no server in between, a call has to find a direct path between two networks. Most home and
office Wi-Fi allows that. Mobile networks are stricter, and two strict networks at once are what
stops a call.

## The network note

While it prepares an invitation or a reply, DirectCallMe checks how your network can be reached and
says so:

| The note says | What it means |
|---|---|
| *Your network gave a public address. Direct calls should connect from here.* | The best case. |
| *Your device has a public address.* | Also fine - often IPv6. |
| *…shares its public address with others (carrier-grade NAT).* | Usual on mobile data. A call connects if the other side is more open, such as home Wi-Fi. |
| *…behind a symmetric NAT.* | Some mobile and corporate networks. Same advice. |
| *Both your network and the caller's are restrictive.* | Shown to the person answering. The call will probably not connect - one of you should switch to Wi-Fi and start again. |
| *No public address could be learned.* | The address servers did not answer, or there is no internet. Only a device on the same network can connect. |
| *LAN-only mode.* | You turned on **LAN only** in Settings: only a device on the same network can connect. |

## When a call will not connect

1. **Put one side on Wi-Fi.** Two phones both on mobile data is the combination most likely to
   fail.
2. **Start again with a fresh invitation.** An invitation is for one call, and a reply is valid for
   about five minutes.
3. **Open the reply on the device that made the invitation**, while it is still waiting on the
   invitation screen.
4. **Check LAN only** is off in Settings on both devices, unless you are on the same network.
5. **Check the STUN servers** in Settings: **Use the defaults** puts them back.

If it still fails, [report it](https://github.com/melihercan/DirectCallMe-Community/issues/new/choose)
with the version from **Settings > About**, both devices, and whether each was on Wi-Fi or mobile
data.

## The call drops or freezes

A weak signal on either side is the usual cause. Turn on **Low data** during the call, or move to
Wi-Fi. If the connection is lost, DirectCallMe tries to recover for a short while before ending the
call.

## Your own servers

The STUN servers in Settings are only asked for your public address, once per call. Any STUN or TURN
address works, and your own is best. A **TURN** server relays the call through itself when no direct
path can be found - the one case where something is in between, and only one you chose.
