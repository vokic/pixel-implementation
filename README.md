# Pixel Implementation
Marketing-Related Mini Task

# Testing Facebook Pixel – Where and How to Validate

Just a few ways how I would test where and how you would normally validate if the pixel is firing correctly.

**Key indicators of proper firing:**

- Green checkmarks in **Facebook Pixel Helper**
- Successful **network requests** in DevTools
- Matching **conversion data** in Facebook reporting within **24–48 hours**

---

## 1. Facebook Pixel Helper (Chrome Extension)

Use the Chrome extension to visually confirm events are firing.

![Facebook Pixel Helper – Events Detected](https://i.imgur.com/P1SKbLs.png)

---

## 2. Facebook Events Manager

Use Facebook Events Manager to track live activity and event logs.

![Events Manager Screenshot](https://i.imgur.com/dFj2yAY.png)

---

## 3. Test Events Tool

Use the **Test Events** tool inside Events Manager to simulate events in real time and verify:

- Event firing  
- Event parameters  
- Matching custom conversions

---

## 4. Browser Developer Tools

Open **DevTools > Network** tab and filter for requests like:

- `?id=`  
- `tr?id=`  
- `fbevents.js`

Useful for inspecting real-time requests and response status.

---

## 5. Facebook Analytics & Reporting

Review reporting data to validate:

- Conversions tracked  
- Event deduplication  
- Attribution paths

Facebook reporting should show results within **24–48 hours** after the event fires.

---

