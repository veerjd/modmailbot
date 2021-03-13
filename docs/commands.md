# 🤖 Commands

## Table of contents
* [Inside a Modmail thread](#inside-a-modmail-thread)
* [Anywhere on the inbox server](#anywhere-on-the-inbox-server)
* [Snippets (canned messages)](#snippets-canned-messages)

## Inside a Modmail thread
These commands can only be used inside a Modmail thread's channel on the inbox server.

### `+reply <text>` / `+r <text>`
Send a reply to the user.

**Example:** `+r How can I help you?`

To reply automatically without using `+reply`, [turn on `alwaysReply` in bot settings](configuration.md).

### `+close`
Close the Modmail thread.

### `+close <time>`
Close the Modmail thread after a timer. Sending a message to the user or receiving a message from the user will cancel scheduled closing.

**Example:** `+close 15m`

### `+close -s` / `+close -s <time>`
Close the Modmail thread without notifying the user that it was closed.

### `+close cancel`
Cancel a timed close.

### `+block`
Block the user from using Modmail.

### `+block <time>`
Block the user from using Modmail for a specified time.

**Example:** `+block 7d`

### `+unblock`
Unblock the user, allowing them to use Modmail again.

### `+suspend`
Suspend the thread.
The thread will act as closed and will not receive any messages until unsuspended via `+unsuspend`.

### `+unsuspend`
Unsuspend the thread. See `+suspend` above.

### `+alert`
Pings you when the thread gets a new reply.

### `+alert cancel`
Cancel the ping set by `+alert`.

### `+edit <number> <new text>`
Edit your own previous reply sent with `+reply`.  
`<number>` is the message number shown in front of staff replies in the thread channel.

### `+delete <number>`
Delete your own previous reply sent with `+reply`.  
`<number>` is the message number shown in front of staff replies in the thread channel.

### `+message <number>`
Shows the DM channel ID, DM message ID, and message link of the specified user reply.
`<number>` is the message number shown in front of staff replies in the thread channel.

## Anywhere on the inbox server
These commands can be used anywhere on the inbox server, even outside Modmail threads.

### `+newthread <userID>`
Open a Modmail thread with a user.

**Example:** `+newthread 106391128718245888`

### `+block <userID>`
Block the specified user from Modmail.

**Example:** `+block 106391128718245888`

### `+block <userID> <time>`
Block the specified user from Modmail for a specified time.

**Example:** `+block 106391128718245888 7d`

### `+unblock <userID>`
Unblock the specified user, allowing them to use Modmail again.

**Example:** `+unblock 106391128718245888`

### `+is_blocked <userID>`
Check if the specified user is blocked.

**Example:** `+is_blocked 106391128718245888`

## Snippets (canned messages)
See the [📋 Snippets](snippets.md) page for more information!
