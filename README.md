# ⏰ TimeVerse

A responsive world clock and alarm web application built using **HTML**, **Bootstrap**, and **JavaScript**.  
TimeVerse displays real-time clocks of multiple countries and lets users set local alarms directly in their browser.

> 💡 The name *TimeVerse* is inspired by my favorite YouTube channel, **ComicVerse**.

---

## 🌍 Features

- 🌐 Live time display of global cities (New York, London, Tokyo, India, Sydney, Dubai)
- ⏰ Alarm setting functionality based on the user's local time
- 🔔 Alarm sound notification
- 🧭 Clean and responsive UI using Bootstrap 5
- 🎨 Gradient color scheme with smooth hover effects

---

## 📱 Responsiveness

This project uses Bootstrap's grid system (`col-12`, `col-sm-6`, `col-md-4`) and utility classes to ensure mobile-friendliness.  
It automatically adjusts layout and component sizes for desktops, tablets, and mobile devices.

---

## 💻 Technologies Used

- HTML5
- Bootstrap 5
- JavaScript (Vanilla)
- SVG Icons from [Bootstrap Icons](https://icons.getbootstrap.com/)
- Alarm audio from [Google Sound Library](https://actions.google.com/sounds/v1/alarms/alarm_clock.ogg)

---

## 🧠 JavaScript Functions Explained

### `updateClocks()`
Updates the current time for each listed timezone using:
```js
new Date().toLocaleTimeString('en-US', { timeZone: zone.timeZone })