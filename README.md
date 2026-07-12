# One Honest Dollar — presell landing page

Waitlist/presell test page for a €17 digital product ("get from zero to your first dollar online").
Live at **https://haralass.github.io/one-honest-dollar/**.

Single static page: `index.html` + `assets/robot.glb`. No build step.

## Before running traffic — two 5-minute setups

### 1. Visitor analytics (see how many people visited)
The page already includes the [GoatCounter](https://www.goatcounter.com) script (free, no cookies, GDPR-friendly).
To activate it:
1. Sign up at https://www.goatcounter.com/signup with the site code **`onehonestdollar`**.
2. Done — stats appear at https://onehonestdollar.goatcounter.com (visits, referrers, countries, devices).

If the code `onehonestdollar` is taken, pick another and update the `data-goatcounter` URL at the bottom of `index.html`.

### 2. Email capture (actually collect the signups)
The form currently only does `console.log` (see the `TODO` in `index.html`).
Easiest free options:
- **Formspree** (https://formspree.io): create a form, set the form's `action` to the endpoint they give you, add `method="POST"` — done.
- **Buttondown** or **MailerLite** free tier if you want the launch email handled by the same tool.

## Credits
- 3D robot: [RobotExpressive](https://github.com/mrdoob/three.js/tree/dev/examples/models/gltf/RobotExpressive) by Tomás Laulhé, CC0/MIT via three.js examples.
- Three.js (MIT), AOS (MIT), Inter font (OFL).
