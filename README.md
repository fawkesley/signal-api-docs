# Unofficial Signal API docs

## Retrieve profile for a phone number

`GET /v1/profile/:number`

Variants (needs expanding):

* Retrieve versioned profile: `/v1/profile/:number/:version`
* Retrieve versioned profile and credential: `/v1/profile/:number/:version/:credentialRequest`


## Retrieve my devices

`GET /v1/devices/`


## Remove a device

`DELETE /v1/devices/:deviceID`



* [Singal-Android](https://github.com/signalapp/Signal-Android/blob/2334c26cbb146f6fe189732f7b908d81a141f604/libsignal/service/src/main/java/org/whispersystems/signalservice/internal/push/PushServiceSocket.java#L148)

* [Signal-iOS](https://github.com/signalapp/Signal-iOS/blob/9f3e6e0c53be618a79c55122705e768a981d3fc4/SignalServiceKit/src/TSConstants.h#L25)

* [Signal-Desktop](https://github.com/signalapp/Signal-Desktop/blob/345301b5487b9963d80aab1a8c8f9d5e877d1fad/ts/textsecure/WebAPI.ts#L475)
