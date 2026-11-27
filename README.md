# Reboot Camp 2026 RSVP pages

Two thank-you pages linked from the buttons in the Reboot Camp 2026 guest invitation emails.

| Page | What it's for | Live link |
|---|---|---|
| `yes/` | Guests who click "Yes, I'll be there" | https://demiladeakintan.github.io/rbc-rsvp/yes/ |
| `no/` | Guests who click "No, I can't make it" | https://demiladeakintan.github.io/rbc-rsvp/no/ |

## What's in here

- `yes/index.html` and `no/index.html`: the two pages
- `assets/css/styles.css`: shared styles, including the brand colours at the top
- `assets/fonts/`: Expose and Quilon
- `assets/images/`: the poster, schedule, background, logos, browser icons and `share.jpg` (the link preview image)
- `assets/reboot-camp-2026.ics`: the calendar file behind "Add to Apple or Outlook calendar"

## Making changes

- **Wording:** edit the text in `yes/index.html` or `no/index.html`.
- **Colours:** change the values at the top of `assets/css/styles.css`.
- **Poster:** replace `assets/images/poster.jpg` with a new file of the same name.

GitHub Pages republishes the site a minute or two after each change. Don't rename the `yes` or `no` folders once the emails have gone out, because the links in the emails point to them.
