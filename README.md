# WIZ CARD-ID PRINT

A standalone browser-based ID card artwork and print utility designed to help prepare front/back artwork for card printing, including workflows with the Evolis Primacy 2 Duplex.

## Features
- Load front and back artwork (PNG, JPG, WebP)
- Preview both sides
- CR80, CR79 (approximate), CR100, and custom dimensions
- Landscape and portrait orientation
- Fit-inside or cover/crop artwork scaling
- Print front, back, or both sides; choose copies and sequence
- Runs locally in the browser; artwork is not uploaded

## Deploy
This is a static site. Import this repository into Vercel and use the default static deployment settings. No build command is required; the output is the repository root.

## Important printing notes
The application uses the browser print dialog and cannot directly control printer-driver features. Select the correct card/media size and duplex settings in the Evolis driver. Browser print scaling and paper-size settings can affect alignment. Test with one card before a production batch. Confirm actual CR79/CR100 dimensions against the media you use.

## Scope
This project is independent from WIZKEY COMMAND HUB, KSUCflow, and KSUC Photo Resizer.
