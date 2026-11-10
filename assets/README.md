# Promotional material

Images for Prune's Google Play listing and this repository. Nothing here is made yet; this is where each piece goes. Check the sizes against Play Console before uploading, as Google changes them from time to time.

| Path | What | Google Play rules |
| --- | --- | --- |
| `icon-512.png` | Store icon | 512 × 512 px, 32-bit PNG, up to 1 MB. Full square: Play rounds the corners and adds the shadow. |
| `icon-rounded.png` | Icon for the top of the main README, as in Reach's | Any size; Reach's is the store icon with rounded corners. |
| `feature-graphic.png` | Banner at the top of the listing | 1024 × 500 px, JPEG or 24-bit PNG with no transparency. Keep text and the main subject away from the edges. |
| `screenshots/phone/` | Phone screenshots | 2 to 8. JPEG or 24-bit PNG with no transparency. Each side between 320 and 3840 px, the long side at most twice the short one. |
| `screenshots/tablet-7/` | 7-inch tablet screenshots | Same rules. Optional; a foldable's inner screen fits here. |
| `screenshots/tablet-10/` | 10-inch tablet screenshots | Same rules. Optional. |

A promo video, if any, goes on YouTube; the listing takes its link.

## Naming

Number screenshots in the order they appear on the listing, with a short description of what they show, as in Reach:

```
screenshots/phone/01-home.png
screenshots/phone/02-categories.png
screenshots/phone/03-duplicates.png
```

When the app changes enough to need new screenshots, replace the files rather than adding versions next to them; git keeps the old ones.
