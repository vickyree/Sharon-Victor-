# Sharon weds Victor — Wedding Appreciation Website

A responsive, static website for wedding information, appreciation, contribution transparency and shareable updates.

## Included
- Couple portraits in `assets/`
- Wedding date marked “To be confirmed”
- Venue: Kebirigo Main Altar
- Contributor names and amounts from the supplied list
- Progress display using the supplied reported total (KES 111,200)
- Searchable donor list, appreciation message, scripture and WhatsApp share link
- No M-Changa URL, Paybill or account details are included

## Contribution list

The contributors are displayed together in the same order as the supplied original list, including Lydia (Mama SDAB Mokaya) and the KES 2,000 amount as originally posted. The reported total remains KES 111,200 and the estimated budget remains KES 320,000.

## Update the website
Edit `data.json`:
- `wedding_date` when the date is confirmed
- `venue` if it changes
- `reported_total` when the treasurer confirms an updated total
- `donors` to add or correct contributions
- `announcements` to publish updates

## Publish with GitHub Pages
1. Extract this ZIP.
2. Upload the contents (not the enclosing folder) to the root of your existing GitHub repository.
3. In GitHub, open **Settings → Pages** and select **GitHub Actions** as the deployment source if your repository has a Pages workflow configured. Otherwise use the standard Pages deployment option for a static site.
4. Open the deployed Pages URL after deployment completes.

This is a static website. It does not automatically send SMS/WhatsApp reminders or sync payments. Use the Share button to create a WhatsApp-ready update. Get permission before publishing contributors' names, amounts or the treasurer's contact.
