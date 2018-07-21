# Backups of my node-red flow

## google-home-notifier

### Feature

- Supports Google Cloud Text-To-Speech
 - Hi-Fi speech quality.
 - Supports to change voice.
 - Supports to change rate/pitch of speech.
- Supports volume level of notification.
- Supports audio url.
- Synchronize successive notification request.
- Requrires customized google-home-notifier: https://github.com/tinoue/google-home-notifier

### Installation

See [google-home-notifier/README.md](./google-home-notifier/README.md)

## talk-line-message

### Feature

- Talks line message by using goole-home-notifier.
- Supports audio message.

### Installation

- Import talk-line-message into node-red.
- Import google-home-notifier.json above.

### Installation

- Install node-red plug-in - node-red-contrib-credentials and node-red-contrib-hostip.
- Import [talk-line-message.json](./talk-line-message/talk-line-message.json) into node-red.
- Create /home/pi/.node-red/line_users.json. See [sample file](./talk-line-message/line_users.json.sample).

## License

MIT
