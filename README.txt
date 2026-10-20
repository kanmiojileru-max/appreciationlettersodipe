CCC IJESHATEDO PARISH IV — APPRECIATION LETTER ON LETTERHEAD

This package contains a Vercel-ready static website. The appreciation letter uses the green-and-gold CCC Ijeshatedo letterhead style, with the existing header logo and matching footer. The separate logo/stamp artwork previously attached as a logo is not placed in the header; the blue conventional stamp is embedded directly in the HTML at the bottom of the letter so it does not depend on a separate stamp image path.

Contents: index.html and assets/letterhead-header.jpg + assets/letterhead-footer.jpg.

DEPLOY / UPDATE ON VERCEL
1. Extract this ZIP.
2. In the GitHub repository connected to Vercel, replace index.html and the assets folder with the versions from this package. Upload both letterhead-header.jpg and letterhead-footer.jpg inside assets.
3. Commit the changes. Vercel should automatically redeploy.
4. Open the live site and check the envelope, letterhead, stamp, and Print / Save as PDF.

Recipient details are in the JavaScript object near the end of index.html: const recipient = { name: 'Evang. Tokunbo', role: 'Chairman, CCC Ijeshatedo Parish IV in Diaspora' }. Change only these values to personalize a copy for another recipient.

The phrase “With sincere appreciation and Christian regards” has been removed. The extra attached logo is not added separately.

DEPLOYMENT FIX: The letterhead header and footer are embedded directly into index.html as data images, as is the stamp. This avoids missing assets due to incorrect folder paths on Vercel. Upload index.html and assets folder as included.
