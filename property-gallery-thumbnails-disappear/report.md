# Thumbnail Gallery Disappears After Rapid Image Navigation

---

## Bug ID

BUG-001

---

## Environment

* Browser: Chrome Version 136
* OS: Windows 11

---

## Preconditions
- User is viewing a property listing
- Image gallery is loaded correctly
  
---

## Description

The thumbnail gallery on property pages becomes visually broken after rapidly clicking through property images.

The thumbnails progressively move to the left until they completely disappear, leaving an empty blank area where the thumbnails should be displayed.

## Tested Website
https://www.dilletpropiedades.com.ar/

---

## Steps to Reproduce

1. Open a property listing
2. Access the image gallery
3. Rapidly click through the property images multiple times
4. Observe the thumbnail section on the right side

---

## Expected Result

The thumbnails should remain visible and properly aligned regardless of click speed.

---

## Actual Result

The thumbnails shift progressively to the left and eventually disappear completely, leaving an empty blank space.

---

## Severity

Medium

## Priority

Medium

---

## Frequency

Occurs consistently on multiple property listings tested.

## Screenshot

![Bug Screenshot](Bug-screenshot.png)
