# Sender Blocker
*created by: ccs.uoguelph*
*modified by : Cloud-Temple Grand Ouest*

[this zimlet](https://www.zimbra.org/extend/items/view/sender-blocker) was no longer kept up to date.
**It is now fully compatible with zimbra 8.x and +. **

# What is it ?  

SenderBlocker allows Zimbra users to block or allow incoming mails from given adresses and/or domains.
The zimlet acts as a shortcut to the account Black/WhiteList, therefore revolves around Zimbra's blacklisting function.

# To make use of this zimlet 

* Select one or more messages.
* Right-click to open the context menu.
* Select the option to either allow or block the sender(s) or sender's domain(s).

The sender(s) email address will be added to the corresponding list (You may
need to refresh the browser in order for the changes to show up in the
Preferences panel).

# How to retrieve the list of blacklisted/whitelised senders

Via the CLI for now:

      zmprov ga user@example.com amavisBlacklistSender
      zmprov ga user@example.com amavisWhitelistSender
