# CrabVault beta 0.9.9

## General improvements

- Applies camera-image EXIF orientation before Vision OCR so rotated phone
  photos are recognized in their intended reading direction.
- Adds Australian identity, government-card, state, and banking terms to the
  Vision recognition vocabulary.
- Normalizes common OCR substitutions in document labels before assigning
  otherwise-correct values to database fields.

## Bug fixes

- Passport fields accept the common short `Expiry` label.
