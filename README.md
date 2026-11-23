# Photo Print Layout & Grid Studio 
[Try Online](https://dnpathirana.github.io/photo-print-studio/index.html)

A browser-based photo print layout and batch grid studio built to arrange, crop, annotate, and export print-ready sheets at selectable DPI resolutions. All image processing runs locally on the client side in the user's browser—no photos are uploaded to or stored on a server.

## Key Features

- **Standard & Custom Print Sheet Sizes:** Supports `4×6"`, `5×7"`, `8×10"`, `8.5×11" (Letter)`, `A4`, and custom inch dimensions in portrait or landscape orientation, with configurable outer margins, inner gutters, and scissor trim guides.
- **Single & Multi-Photo Grid Templates:** Supports `1-Up`, `2-Up`, `4-Up` (such as four `2" × 3"` mini prints on a `4×6"` sheet), `6-Up`, `8-Up`, `9-Up`, and custom `Rows × Columns` grids with live sub-print dimensions.
- **Batch Multi-Page Auto-Layout:** Automatically paginates uploaded photos across multiple sheets using preset batch layouts (such as `4-Up Batch` or `12-Up Batch`), plus sheet navigation (`[` / `]`), add, duplicate, and delete controls.
- **Interactive Crop, Pan, Zoom & DPI Inspector:** Drag photos directly into slots, pan inside any frame, adjust zoom and 90° rotation, and monitor live effective print DPI warnings per slot.
- **Preview Zoom & Pan:** Inspect sheet layouts with toolbar zoom controls (`-`, `100%`, `+`, `Fit`), trackpad/wheel zoom, and a pan hand tool (`Spacebar + Drag` or toggle button).
- **Draggable Text Overlays:** Add custom captions or dates with font size, color, bold, and drop-shadow options, then drag them freely across a sheet.
- **Multi-DPI Export & Printing:** Export single sheets or multi-sheet batches as **JPEG**, **PNG**, **PDF**, or **ZIP** bundles at selectable DPI presets (`150 DPI`, `300 DPI`, `600 DPI`, or custom `72–1200 DPI`) with JPEG quality control, or send directly to your system print dialog.

## Privacy & Client-Side Architecture

- **100% Local Processing:** Source photos are read into browser memory and rendered onto HTML5 `<canvas>` elements locally. Images are not transmitted to an external server by the layout engine.
- **Hosting:** Because the app is static HTML/CSS/JavaScript, it can be opened directly from disk or hosted on static site hosts such as GitHub Pages.

## Usage Notes & Performance Tips

- **Batch Size:** Browser memory usage depends on source image resolution and available system RAM. For smooth performance with high-resolution camera or phone photos, work in moderate batches and export multi-page PDFs or ZIP archives in manageable page counts.
- **Print Sizing:** Use `300 DPI` (or `600 DPI` for fine detail/text) when preparing files for photo labs or home photo printers, and verify your online print lab's exact bleed and safe-zone guidelines before ordering.

