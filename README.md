## amanda-automation-media

Public image host for Amanda's IG auto-publish pipeline.

Meta's Graph API rejects Google Drive `lh3.googleusercontent.com/d/{id}=w2160`
URLs. Instagram's media ingester needs public URLs it can cache. This repo
serves post images via `raw.githubusercontent.com`, which Meta accepts.

Layout:

```
nm-monday/YYYY-MM-DD-slug/{1..N}.png
thirsty-thursday/YYYY-MM-DD-slug/1.png
freebies/YYYY-MM-DD-slug/1.png
```

Written to by the publish scripts in the private `amanda-automation` repo.
