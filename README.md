# Google Meet Tab
Unofficial Google Meet add-on for Thunderbird, it adds a button that opens a Google Meet tab in Thunderbird.
The [home page](https://addons.mozilla.org/thunderbird/addon/thundermeet/) of the extension contains some pictures and reviews.

#### Installing 
A new Google Meet icon should appear in the top-right corner of Thunderbird. Click to open.

#### Installing from sources
Download the repository, zip it, rename it to Google-Meet-Tab.xpi and choose install addon from file in Thunderbird.

In linux the xpi file can be created with the following commands
* `git clone https://github.com/feranick/Thunderbird-Google-Meet-Tab`
* `cd ./Thunderbird-Google-Meet-Tab`
* `VERSION=$(cat ./manifest.json | jq --raw-output '.version')`
* `zip -r "../Google-Meet-Tab-${VERSION}-tb.xpi" *`
