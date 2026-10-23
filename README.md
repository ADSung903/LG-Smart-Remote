# LG Smart Remote

Family prototype for LG webOS TV (initial target UM731CPWA). Not affiliated with LG.

This code has **not been built or tested** on iPhone or LG TV. Features: manual TV IP, WebSocket pairing, volume, channel, directional pad, Back, Home and input-list request. Some endpoints and permissions may vary by firmware.

Install Node.js, run `npm install`, then `npx expo start`. A standalone iOS build requires signing and may use Expo EAS Build without a personal Mac. TV and iPhone must share a trusted Wi-Fi network.

Security: Uses local unencrypted `ws://` on port 3000; never expose the TV to the internet. TV IP and client key remain on the phone.
