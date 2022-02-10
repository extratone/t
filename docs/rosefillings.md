# Rose Fillings

You can also customise the contents of your message with contextual data. For example, you could mention a user by name in the welcome message, or mention them in a filter!

(Except with {})

Supported fillings:
- [first]: The user's first name.
- [last]: The user's last name.
- [fullname]: The user's full name.
- [username]: The user's username. If they don't have one, mentions the user instead.
- [mention]: Mentions the user with their firstname.
- [id]: The user's ID.
- [chatname]: The chat's name.
- [rules]: Create a button to the chat's rules.
- [preview]: Enables link previews for this message. Useful when using links to Instant View pages.

Example usages:
- Save a filter using the user's name.
-> /filter test [first] triggered this filter.
- Add a rules button to a note.
-> /save info Press the button to read the chat rules! [rules]
- Mention a user in the welcome message
-> /setwelcome Welcome [mention] to [chatname]!