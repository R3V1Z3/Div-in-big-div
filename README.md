# Div in big div
HTML Experiment for scaling and focusing on a small div within a much larger div.

This experiment is all about scaling and centering a small div to fit the viewport when it's contained in a much larger div. The purpose is to find the optimal way to bring a div to focus in the viewport when it's within a canvas-like div.

Initial outline:
- Create HTML page with an .outer class div and .inner class div.
- SET .outer div to UHD resolution (3,840 x 2,160).
- SET .inner div to 800 x 450 resolution.
- Use flexbox or other optimized method to center .inner div.
- GET window.width and window.height.
- GET .inner div x and y coordinates (top, left).
- Scale the small div to fit the viewport, using that div's margin as a sort of padding.
