Tranny
==

Tranny *transcodes* videos.

Pre-reqs
--

* ffmpeg
* ruby >= 1.9

Installation
--

`$ bundle install`

Configure
--

`profiles.yml` - currently just a list of formats to convert to. We only use the **all** profile for now.

Running
--

Put stuff in `/src` to transcode.

`$ bundle exec tranny`

Best run as a cron job.

Caveats
--

This will remove source files. So like don't rely on them stil being there.

Because source files are removed last and because we don't overwrite files you can probably get away with the tool dying and then restarting.
