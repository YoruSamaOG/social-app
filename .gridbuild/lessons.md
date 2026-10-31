# Lessons

- The test devices run this app against Bluesky's local test network (`dev-env`), already signed in as alice.test. Don't sign out, and don't change the hosting provider.
- Alice's profile has an image post with alt text ("Golden hour at the bay") and a two-post thread. Settings > Accessibility holds "Display larger alt text badges".
- Drive the devices with `agent-device`: `agent-device --platform ios --udid <device> open xyz.blueskyweb.app`, then `agent-device --platform ios --udid <device> snapshot -i` and `agent-device --platform ios --udid <device> press @e3`. On Android use `--platform android --serial <device>`.
- The app can take up to 20 seconds after opening to show the feed.
