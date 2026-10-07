# Konfigurasi maksimal untuk perangkat

Struktur Folder

`Manufacture/Model/Type.json`

Struktur JSON 
```json
{
  "showPttScreen" : false,
  "screenPttToggle" : false,
  "setFullScreen" : false,
  "textMarquee" : false,
  "internalPTT" : "yes",
  "pttButton" : 132,
  "hwPttToggle" : false,
  "pttButton2" : 132,
  "hwPttToggle2" : false,
  "pttButton3" : 132,
  "hwPttToggle3" : false,
  "pttBukaAplikasi" : true,
  "autoScreenOnAlways" : "yes",
  "autoHideHeader" : true,
  "gps_tracker" : true,

  "micGain" : 1,
  "micType" : 7,
  "notifVolume" : 30,
  "incomingVolume" : 95,
  "bitrate" : "32000",
  "mic_quality" : "AUDIO",
  "mic_enhancer" : true,

  "audio_enhancer_rx" : true,
  "rx_noise_suppression" : true,

  "isNoiseSuppressor" : true,
  "isNoiseSuppressorSW" : true,

  "callsignOnly" : false,

  "useHeatMapBG" : false,
  "records_incoming_voice" : false,

  "white_noise" : false,

  "prevButton" : 10,
  "nextButton" : 23,
  "font_scale" : "1.6",
  "UseDigitFont": true,
  "autorun" : true,
  "useTLS" : true,
  "checkNetworkQuality" : true,
  "textTovoiceMode" : false,
  "pttCaraka" : "None/Orange/Green",
  "tema" : "Analogo",
  "font_scale" : "1.1",
  "hideChannelInfo" : "no"
}
```
## mic_quality

- AUDIO
- VOICE

## micGain

-10 s/d 10

## bitrate

- 8000
- 12000
- 16000
- 24000
- 28000
- 32000
- 48000

## micType

0. Default
1. Mic
2. Uplink
3. Downlink
4. Call
5. Camcorder
6. Recognition
7. Communication
8. Submix
9. Unprocessed
10. Karaoke

## notifVolume & incomingVolume
1 s/d 100
