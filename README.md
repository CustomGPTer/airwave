# Airwave

Airwave is an Android app for live radio and podcasts. It comes with about 1,900 UK stations, sorted by
region and town, and reaches around 50,000 more worldwide. It has no adverts in the app, no accounts and no
paid version.

- Website: https://customgpter.github.io/airwave/
- Latest app file: https://github.com/CustomGPTer/airwave/releases/latest
- Privacy: https://customgpter.github.io/airwave/privacy.html

## Good to know before you start

- **Radio uses mobile data**, about 60 MB an hour at ordinary quality. Data saver and a data counter are in
  Settings.
- **Not every station can be paused and rewound.** Stations that stream as HLS, which includes some BBC
  streams, play normally but cannot be rewound.
- **A few stations will not play**, because they only allow their own app or their own country, or have
  moved. If you know the new link, add it under Settings > My stations.
- **Android Auto hides apps that do not come from Google Play.** In Android Auto's settings tap Version ten
  times, then tick Unknown sources under Developer settings.
- **If the sound stops with the screen off**, set Airwave's battery use to Unrestricted in the phone's
  settings.

## What it does

- UK stations by region, town and county, with Stations near me, and a worldwide list by country
- Filters by category, place, language and sound quality that combine and save as one-tap chips
- Your own stations by stream link or playlist file, several at once, or shared from the browser
- Your own podcasts by name, by feed link, or imported as an OPML list from another app
- Pause and rewind live radio, up to an hour
- Podcasts with a UK chart, downloads, a queue, playback speed and new-episode notices
- Favourites in folders, drag to reorder
- Sleep timer with fade-out, and a radio alarm that falls back to the phone's own alarm sound
- Lock-screen controls, Bluetooth and headset buttons, Android Auto, casting and a home-screen widget
- Equaliser, bass boost and volume levelling; the song that is playing, with a history
- Data saver, a data-use counter, and reconnecting by itself
- A backup file, with an automatic copy kept on the phone
- Light, dark and true-black themes; a grid or a list; a Help page inside the app

## What it cannot do

Airwave is a player. It does not run or re-broadcast any station, and it cannot make a station play that
shuts other apps out. Station details come from an open directory and can be missing or wrong. It is new;
if something does not work on your phone, please open an issue.

## Where the listings come from

Stations come from [Radio Browser](https://www.radio-browser.info/), a free directory kept up by its users.
Podcast search and the UK chart use Apple's public podcast directory. Airwave is not connected with any
station, broadcaster or directory; station names and logos belong to their owners.

## Building

The app is in the `android` folder. See `android/README.md`.

## Licence

© 2026 Jonathan Jackson. Published under the GNU General Public License, version 3 (see `LICENSE`).
