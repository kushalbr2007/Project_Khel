PROJECT KHEL - NO SERVER NEEDED
================================
Put this folder on any free web host (it gives you an https link, which also makes the phone microphone work).

EASIEST: Netlify Drop
 1. Go to https://app.netlify.com/drop  (free, sign up with Google/email)
 2. Drag this whole "khel-web" folder onto the page.
 3. You get a link like https://something.netlify.app
 Student phones open:   https://something.netlify.app
 Teacher opens:         https://something.netlify.app/teacher.html

(Alternative: GitHub Pages, Cloudflare Pages - any static host works.)

CLASS FLOW
 1. Teacher opens the teacher link. A 4-digit class code appears.
 2. Child opens the student link, types the class code, sees their 4-character ID.
 3. Teacher types the child's ID and taps Link child.
 4. When a child says a letter, the recording plays on the teacher screen: tap Correct or Wrong.

NOTES
 - Needs internet on both devices (any network; they do NOT need to be on the same Wi-Fi).
 - Messages and recordings go directly device-to-device (WebRTC). Only the connection handshake uses the free PeerJS cloud.
 - Allow the microphone when the phone asks.
 - If a school network blocks WebRTC, switch the phone to mobile data.
 - Teacher page must stay open during class.
