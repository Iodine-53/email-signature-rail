# Icon hosting map — email signature #5 ("Rail")

All icons are hosted remotely so the signature works with absolute URLs in any inbox.
Contact/brand icons: **catbox.moe** (free, no account, direct permanent links).
Social icons: Emmanuel's existing **ibb.co** uploads.

| Icon type | File | Hosted URL |
|-----------|------|------------|
| monogram badge (JB) | `slices/e5_monogram.png` | https://files.catbox.moe/b5s05k.png |
| phone | `slices/e5_ic_phone.png` | https://files.catbox.moe/1baydh.png |
| mail | `slices/e5_ic_mail.png` | https://files.catbox.moe/6r720g.png |
| web | `slices/e5_ic_web.png` | https://files.catbox.moe/h46wyf.png |
| pin | `slices/e5_ic_pin.png` | https://files.catbox.moe/jr41y2.png |
| facebook | `slices/e5_soc_fb_navy.png` | https://files.catbox.moe/2mxcut.png |
| instagram | `slices/e5_soc_ig_navy.png` | https://files.catbox.moe/yp4ney.png |
| x | (ibb, kept per Emmanuel — renders well) | https://i.ibb.co/Wps5QjDH/icon-x.png |
| linkedin | `slices/e5_soc_li_navy.png` | https://files.catbox.moe/ax5e3x.png |

Social note (2026-09-23): Emmanuel found the colorful ibb icons render badly except X — fb/ig/li were rebuilt as white glyphs on navy rounded-square badges from the downloaded icon alpha (artwork lives in the alpha channel, RGB is all white; ring removed via scipy connected components), matching the rail design.

Upload method (catbox): `curl -F "reqtype=fileupload" -F "fileToUpload=@file.png" https://catbox.moe/user/api.php`
Note: catbox uploads occasionally time out on the first attempt from this server — retry individually.
