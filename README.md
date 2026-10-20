# imx

Instant Message eXchange

## Roadmap

### `v0.1` Core Messaging

Users send messages through outboxes and receive them through inboxes. Each message is stored once, with independent access for its sender and recipient.

- [`accounts`](/docs/features/users.md)
- [`messages`](/docs/features/messages.md)
- [`inboxes`](/docs/features/inboxes.md)
- [`outboxes`](/docs/features/outboxes.md)

### `v0.2` Conversations

DMs organize private exchanges between two users, while channels let groups of users communicate in shared conversations.

- [`dms`](/docs/features/dms.md)
- [`channels`](/docs/features/channels.md)

### `v0.3` Authentication

Passwords let users prove their identities, while sessions maintain authenticated access across requests.

- [`passwords`](/docs/features/passwords.md)
- [`sessions`](/docs/features/sessions.md)

### `v0.4` Synchronization

Allows users to continue conversations across devices and keeps devices up to date.

- [`realtime`](/docs/features/realtime.md)
- [`devices`](/docs/features/devices.md)
- [`notifications`](/docs/features/notifications.md)

### `v1.0` Stable Messaging

imx provides a documented, reliable Rust library and standalone server, with configurable capabilities and stable public interfaces.

- [`config`](/docs/features/config.md)

### `v1.1` Message Activity

Delivery and read receipts track message status, reactions let users respond, and notifications alert users to new activity.

- [`delivery_receipts`](/docs/features/delivery_receipts.md)
- [`read_receipts`](/docs/features/read_receipts.md)
- [`reactions`](/docs/features/reactions.md)

### `v1.2` Message Management

Users can edit messages, retract them from conversations, and attach files or other media.

- [`editing`](/docs/features/editing.md)
- [`unsend`](/docs/features/unsend.md)
- [`attachments`](/docs/features/attachments.md)

### `v1.3` Social Connections

Contacts organize known users, invitations manage access to conversations, blocks prevent unwanted contact, and presence indicates availability.

- [`contacts`](/docs/features/contacts.md)
- [`invites`](/docs/features/invites.md)
- [`blocks`](/docs/features/blocks.md)
- [`presence`](/docs/features/presence.md)

### `v1.4` Broadcasting

Users publish messages for anyone to view, optionally setting an expiration time. Followers receive notifications when someone they follow broadcasts.

- [`broadcasts`](/docs/features/broadcasts.md)
- [`follows`](/docs/features/follows.md)

### `v1.5` Threads

Users organize replies into threads, allowing multiple discussions to develop within a conversation.

- [`threads`](/docs/features/threads.md)

### `v1.6` Server Administration

Administrators manage users, configure messaging capabilities, and control server operations.

- [`admin`](/docs/features/admin.md)

### `v2.0` Federation

Independently operated imx servers exchange messages, allowing users to communicate across server boundaries.

- [`federation`](/docs/features/federation.md)

### Future

Potential capabilities beyond the initial roadmap:

- End-to-end encryption
- Passkeys and external authentication providers
- Message search
- Voice and video calling
- Moderation tools
- Native desktop applications