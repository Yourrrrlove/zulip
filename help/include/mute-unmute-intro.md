Zulip lets you mute topics and channels to avoid receiving notifications for messages
you are not interested in. Muting a channel effectively mutes all topics in
that channel. You can also manually **mute** a topic in an unmuted channel, or
**unmute** a topic in a muted channel.

Muting has the following effects:

- Messages in muted topics do not generate notifications (including [alert
  word](/help/dm-mention-alert-notifications#alert-words) notifications), unless
  you are [mentioned](/help/mention-a-user-or-group).
- Messages in muted topics do not appear in the [**Combined
  feed**](/help/combined-feed) view or the mobile **Inbox** view.
- Muted topics appear in the [**Recent conversations**](/help/recent-conversations)
  view only if the **Include muted** filter is enabled.
- Unread messages in muted topics do not contribute to channel unread counts.
- Muted topics and channels are grayed out in the left sidebar of the desktop/web
  app, and in the mobile app.
- In the desktop/web app, muted topics are sorted to the bottom of their channel,
  and muted channels are sorted to the bottom of their channel section.

You can search muted messages using the `is:muted` [search
filter](/help/search-for-messages#search-by-message-status), or exclude them
from search results with `-is:muted`.

!!! warn ""

    **Note**: Some parts of the Zulip experience may start to degrade
    if you receive more than a few hundred muted messages a day.
