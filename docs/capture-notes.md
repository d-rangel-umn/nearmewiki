# Capture notes

The four PNGs were captured on September 20, 2026, from the actual profile widget using Flutter 3.41.1 and its widget-test renderer. They use a separate synthetic fixture and contain no business photos, logos, or artwork.

| Capture | Viewport | State |
| --- | --- | --- |
| Desktop overview | 1100 × 900 | Initial profile view |
| Desktop catalog | 1100 × 900 | Scrolled catalog with Sketchbook expanded |
| Mobile overview | 400 × 800 | Initial profile view |
| Mobile catalog | 400 × 800 | Scrolled catalog with Sketchbook expanded |

Juniper Workshop, its address, offerings, narrative, opening status, and travel estimates are fictional presentation data. Contact links use `example.com` and a fictional phone number. No real business output was used as the source of these profiles.

The capture harness reuses the actual UI widget and theme. It loads local text and icon fonts, disables runtime font fetching, injects fixture data, waits for rendering, and captures the profile before and after scrolling and expanding an item. Contact callbacks are inert during capture.

The captures were generated and then checked against the saved images in a second test run. Their filenames, hashes, viewport sizes, and action paths are recorded in [the capture manifest](../capture-manifest.json).

These component captures do not verify a running backend, live map tiles, search, Discover, location permissions, research jobs, or publication behavior. They are a bounded illustration of the responsive profile experience.
