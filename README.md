# Manoj & Hema Wedding Website

A mobile-friendly, single-page wedding invitation made with plain HTML, CSS and JavaScript. It includes a live countdown, event details, family names, map link, photo placeholders, WhatsApp RSVP and original synthesized instrumental-style tones (starts only after the visitor taps Play music).

## 1. Personalise before publishing

1. Open `index.html` in a text editor.
2. Replace `91XXXXXXXXXX` in `RSVP_WHATSAPP_NUMBER` with the host family's WhatsApp number, including country code and without `+`.
   Example format: `919876543210`.
3. Replace the Google Maps search URL with the exact venue pin URL.
4. Add your photographs to the `assets` folder using these exact names:
   - `couple-main.jpg`
   - `gallery-1.jpg`
   - `gallery-2.jpg`
   - `gallery-3.jpg`
5. In `index.html`, replace each `<div class="photo-placeholder">...</div>` block with an image, for example:
   `<img src="assets/couple-main.jpg" alt="Manoj and Hema" style="display:block;width:100%;height:auto">`
   For the three gallery slots, use the matching `gallery-*.jpg` files and add `style="width:100%;height:100%;object-fit:cover"`.

## 2. Preview on your phone or computer

Open `index.html` in a browser. The music begins only after the visitor taps the music button because mobile browsers block autoplay. The RSVP button opens WhatsApp with a pre-filled message.

## 3. Publish free with GitHub Pages

1. Sign in to GitHub and create a new **public** repository, for example `manoj-hema-wedding`.
2. Upload `index.html`, `README.md`, and the `assets` folder with your photos.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then press **Save**.
6. Wait for GitHub Pages to publish. Your website address will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/manoj-hema-wedding/`
7. Open the link on your phone and test the music, RSVP and map before sharing it.

## Important checks

- Confirm the exact venue map pin before sharing.
- Confirm spelling of all family names and event details.
- Test RSVP using a family member's phone.
- Keep the repository public if using the free GitHub Pages plan.
- Do not upload private documents or personal phone numbers other than the RSVP contact you intend guests to use.

## Current invitation details included

- Reception: 25 November 2026, 7:00 PM; dinner 8:00 PM.
- Wedding: 26 November 2026; muhurtham 8:45–9:25 AM.
- Venue: Sri Jagadguru Thontadharya Sidhalingeshwara Samudhaya Bhavana.
- Groom: Ch. Sri. Manoj N; parents Smt. Saraswathi and Sri. Naresh Rao P. Amalkar.
- Bride: Ch. Sou. Hema B N; parents Smt. Chandramma and Sri. Narayan Sindhe.
- Elder blessings: Smt. Savithri Bai and Late Sri. Prakash Rao Amalkar.

Please proofread the details and add the exact map pin and photos before publishing.
