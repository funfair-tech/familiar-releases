# familiar-releases

`latest.json` holds the newest familiar release's version and when it was cut.
Each install reads it anonymously to show an "update available" banner in its
admin UI. It is written by `scripts/release` as the last step of a release,
and holds nothing else.
