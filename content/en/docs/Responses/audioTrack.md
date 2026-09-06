---
title: "audioTrack"
linkTitle: "audioTrack"
description: >
  Video file audio tracks.
---

{{< tabpane persistLang=false >}}
{{< tab header="**Example**:" disabled=true />}}
{{< tab header="OpenSubsonic" lang="json">}}
{
  "id": "1",
  "name": "English",
  "languageCode": "eng"
}
{{< /tab >}}
{{< tab header="Subsonic" lang="json" >}}
{
  "id" : "1",
  "name" : "English",
  "languageCode" : "eng"
}
{{< /tab >}}
{{< /tabpane >}}

| Field | Type | Req. | OpenS. | Details |
| ----- | ---- | ---- | ------ | ------- |
| `id` | string | **Yes** | | The ID of a transcoded version of the video file |
| `name` | string | No | | Language Name (e.g. English, French) |
| `languageCode` | string | No | | ISO 639 (2/3) code |
