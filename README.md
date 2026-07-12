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

### 2. Email capture — DONE, one click left
The form now submits via **FormSubmit** (free, no account) to haralas@icloud.com.
The very first submission triggers a one-time **activation email** to that inbox —
click the link in it once, and every signup after that arrives as an email
(subject: "One Honest Dollar — waitlist signup"). Until you click it, submissions are held.

## Credits
- 3D robot: [RobotExpressive](https://github.com/mrdoob/three.js/tree/dev/examples/models/gltf/RobotExpressive) by Tomás Laulhé, CC0/MIT via three.js examples.
- Three.js (MIT), AOS (MIT), Inter font (OFL).
