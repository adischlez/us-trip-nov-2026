# November 2026 business-trip dashboard / דשבורד נסיעת העבודה

Hebrew RTL dashboard for Adi's Tel Aviv → Austin → Tampa → Tel Aviv business trip.

## Live pages

- Dashboard: https://adischlez.github.io/us-trip-nov-2026/
- Machine-readable feed for a bot: https://adischlez.github.io/us-trip-nov-2026/itinerary.json
- Raw JSON fallback: https://raw.githubusercontent.com/adischlez/us-trip-nov-2026/main/itinerary.json

A bot should poll `itinerary.json` (Pages URL first, raw GitHub URL if Pages is still publishing). `lastUpdated` is an ISO-8601 timestamp. Flight and hotel times use local offset at that airport or hotel.

כל הזמנים במסמך הם שעון מקומי בשדה או במלון.
