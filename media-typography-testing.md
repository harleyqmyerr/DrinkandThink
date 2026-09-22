Media and Typography Testing Notes

Responsive widths
[yes ] Checked approximately 320 px wide.
[yes ] Checked approximately 768 px wide.
[yes ] Checked wide desktop layout.
Result: Image remains within its container, text remains readable, and no horizontal scrolling occurs.

200 percent zoom
[yes ] Checked browser zoom at 200%.
Result: Navigation, buttons, headings, and image content remain usable without overlap.

Slow-network behavior
[yes ] Simulated Slow 3G or inspected with network throttling.
Result: The image area retains its space while loading. Responsive image markup allows the browser to request an appropriate file size.

Image dimensions and file size
[ yes] Confirmed image width and height attributes match the source image ratio.
[ yes] Confirmed 640w, 960w, and 1440w variants exist.
[yes ] Recorded each file size.

Accessibility
[yes ] Confirmed alt text matches the image’s purpose.
[yes ] Confirmed decorative elements are not announced to screen readers.
[yes ] Confirmed keyboard focus remains visible and usable.

Layout-shift risk
[yes ] Confirmed the image region reserves space before loading.
[yes ] Confirmed any map or external embed has a defined region size and a fallback link.
