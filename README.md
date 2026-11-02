# arc-platforms.github.io

Arc's join page: https://arc-platforms.github.io/j#<invite>, the link in Arc Command's "Add device" QR code.

The invite is everything after #, which browsers never send to a server. The page reads it in the browser, shows "Open in Arc",
and sends it nowhere. It loads nothing from any other site.

.well-known/assetlinks.json (which lets Android open these links straight in Arc) is added once Arc's release signing key exists.
The page's source and tests live in the Arc repository, deploy/join-page/.
