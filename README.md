# Evimarko Booking — online booking button for Joomla

A free Joomla 4/5 system plugin that adds a **"Book online"** button to websites of car service businesses: car washes, detailing and paint protection film studios, auto repair and tire shops, window tint.

A customer clicks the button, picks a service, a day and a free time slot in a pop-up window, leaves a name and phone number — and the appointment appears in the studio's [Evimarko](https://evimarko.com/?utm_source=github&utm_medium=referral&utm_campaign=joomla-plugin) calendar right away.

## Download

**[Download plg_system_evimarkobooking.zip (latest release)](https://github.com/evimarko/joomla-booking-button/releases/latest/download/plg_system_evimarkobooking.zip)**

## Features

- Floating "Book online" button on every page (left or right, your text and colour)
- `{evimarkobooking}` or `{evimarkobooking text="Book a wash"}` tag to show a booking button inside articles
- Booking window works on phones and desktops, keyboard accessible, closes with Esc
- No credit link on your site unless you turn it on
- Admin strings in English, Ukrainian, Russian and Bulgarian

## Installation

1. In Joomla administrator: **System → Install → Extensions → Upload Package File**, choose `plg_system_evimarkobooking.zip`.
2. **System → Manage → Plugins**, search "Evimarko", open **System - Evimarko Booking**.
3. Paste your booking page link (`https://evimarko.com/b/your-studio`) from your Evimarko account (**Settings → Booking page**), set the button text and colour, enable the plugin and save.

## Requirements

- Joomla 4.x or 5.x, PHP 7.4+
- An Evimarko account (CRM for car service businesses, 14-day free trial)

## External service

The plugin loads a small script from `evimarko.com` on pages where the button is shown; the booking form opens from `evimarko.com`. What the customer types in the form (name, phone, car, chosen time) is sent to Evimarko and to the studio. [Terms](https://evimarko.com/terms) · [Privacy](https://evimarko.com/privacy)

## Support

Open an issue in this repository or write to support@evimarko.com.

## License

GNU General Public License v2 or later — see [LICENSE.txt](LICENSE.txt).
