# AirBike Tracker Privacy Policy

**Effective date: 19 October 2026**

AirBike Tracker is an offline interval timer and workout tracker for air-bike training.
It works without an account, has no analytics and no servers operated by the developer.
Your workouts and results are stored in the app's database **on your device** and never
leave it.

The app ships in two editions:

- the **Google Play edition**, which shows advertising (section 4), and
- the **ad-free edition**, which contains no advertising code at all.

_"The developer" means the individual who publishes AirBike Tracker on Google Play
([contact](#10-contact-and-data-protection-requests))._

## 1. The short version

- **No accounts, no analytics, no tracking** and no developer servers. The developer
  cannot see your workouts, your results, or anything else you do in the app.
- Workout templates, workout history (including the calories, distance, power and heart
  rate values you type in) and settings are stored **only on your device**.
- The app has **no location access, no sensors and no microphone**. All metrics —
  calories, distance, average power, heart rate — are entered by you by hand after a
  workout; every field is optional.
- The **Play edition shows ads** served through Google AdMob; Google's advertising
  service then processes the data described in section 4. The **ad-free edition makes
  no ad requests and no network requests at all**.
- Voice cues are spoken by your device's text-to-speech engine. Nothing is recorded.
- You can delete everything at any time: delete workouts and history in the app, or
  uninstall it.

## 2. Data stored only on your device

The app's local database holds:

- **Workout templates** you create: their names, warm-up/cooldown durations, interval
  blocks (work, rest, rounds), rest between blocks and the get-ready countdown.
- **Workout history**: when you trained, how long it lasted, whether you finished it,
  and the optional metrics you type in afterwards — calories, distance, average power,
  average heart rate and a note.
- **Settings**: distance unit (km/mi), voice-cue options (last-3-seconds countdown,
  halfway announcements) and keep-screen-awake.

None of this is transmitted by the app. Two platform caveats:

- **Android backup:** the app allows Android's automatic device backup. If you use it,
  Android may include your workouts, history and settings in the backup of your Google
  account, or copy them in a direct phone-to-phone transfer. Backup is a device feature
  you control in Android settings; the developer cannot access it.
- **Backup export:** the app's settings offer a backup export (a JSON text containing
  your workouts, history and settings). It goes only where you send it.

## 3. Voice cues, notifications and the timer service

- **Voice cues** (phase announcements, countdown, halfway notices) are synthesised by
  your device's text-to-speech engine. The spoken text is generated from the timer
  state — numbers and phase names only. The app has no microphone access and records
  nothing; which speech engine and voices are used is controlled by your device's
  system settings. Voice cues can be switched off in the app's settings.
- **Notifications** (permission asked on Android 13 and later): one ongoing
  notification while a workout runs, showing progress and letting you control the
  timer.
- **Foreground service** (type media playback) **and wake lock**: they keep the timer
  accurate and the voice cues speaking while the screen is off or the app is in the
  background. Both are active only while a workout is running and stop when you finish
  or discard it.

## 4. Advertising (Play edition only)

The Play edition shows banner ads at the bottom of the workout list and history
screens. Ads are **never shown on the timer screen during a workout**.

Ads are served through **Google AdMob** (Google Play services). When an ad is loaded or
displayed, Google processes data under its own policies — typically the advertising ID
of your device, device and app information (model, operating system, app version,
language) and how you interact with ads (for example views and clicks), for purposes
such as serving and measuring ads, and fraud prevention.

- In the European Economic Area and the United Kingdom, you choose whether ads may be
  personalised before they are first shown, and you can change that choice at any time.
- You can reset your advertising ID or opt out of ad personalisation in Android's
  system settings (Settings › Privacy › Ads).
- Google's disclosures: [Google Privacy Policy](https://policies.google.com/privacy)
  and [How Google uses data when you use our partners' sites or
  apps](https://policies.google.com/technologies/partner-sites).

The developer has no access to the ad-serving decisions or the data Google collects.
The **ad-free edition contains no advertising code** and makes no network requests.

## 5. Permissions overview

| Permission | Why |
|---|---|
| Notifications | The ongoing workout notification with timer controls |
| Foreground service (media playback) | Keeps the timer and voice cues running with the screen off |
| Wake lock | Keeps timing accurate for the whole workout |
| Internet / network state | Play edition only — loading ads (section 4) |

## 6. Data retention and deletion

- **On your device:** data is kept until you delete it. Delete workouts in the
  template editor, and history entries in the history screen. Uninstalling the app
  removes all app data (unless it exists in a backup export you made or in an Android
  backup).
- **At Google (Play edition):** advertising data is handled under Google's policies,
  linked in section 4, and controlled from your device's ad settings. AirBike Tracker
  cannot delete data held by Google.
- The developer keeps no user data, because none is ever sent to the developer.

## 7. Third-party privacy policies

- Google (AdMob, Play services, backups): <https://policies.google.com/privacy>

## 8. Children

AirBike Tracker is a fitness app and is not directed at children under 13. We do not
knowingly collect personal information from children.

## 9. Changes to this policy

If the policy changes, the new version will be published at this URL with a new
effective date. Material changes will additionally be noted in app update notes.

## 10. Contact and data-protection requests

AirBike Tracker stores your data only on your own device, so in almost every case you
can exercise your data rights directly in the app or by uninstalling it. For anything
else, contact:

- Email: <usdevplay@gmail.com>
- Developer: Uroš Slana

Terms of use (training at your own risk, ads):
<https://lobicode.github.io/airbike-privacy/terms/>
