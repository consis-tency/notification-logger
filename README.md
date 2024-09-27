# Notification Logger 🔔 [![npm version](https://badge.fury.io/js/notification-logger.svg)](https://badge.fury.io/js/notification-logger)

Effortlessly see your `console.log()` messages as **Desktop Notifications** without opening the console. Simplify development and debugging with just ~50 lines added to your project.

[**Demo**](http://singhharkirat.com/notification-logger) | [**GitHub**](https://github.com/hkirat/notification-logger/)

---

## ⚡ Features

- Desktop notifications for `console.log()` messages.
- Lightweight, only ~50 lines of code.
- Seamless integration with your existing console methods.

---

## 📦 Installation

Install via `npm` or clone the repo:

```bash
npm install notification-logger
```
Or:
```bash
git clone https://github.com/hkirat/notification-logger.git
```

Include `notification-logger.js` or `notification-logger.min.js` and initialize:

```js
logger.init();
```

---

## 🛠️ API Methods

- **`logger.init()`**: Initialize the logger.
- **`logger.log()`**: Log via desktop notification only.
- **`console.log()`**: Log to both desktop notification and console.
- **`logger.destroy()`**: Restore default console behavior.

---

## 🌐 Browser Support

Optimized for the latest versions of **Chrome**, **Firefox**, and **Safari**.

---

## 📝 To-Do

- Add custom icons to notifications.
- Unwrap objects in desktop notifications.

---

## 🎨 Credits

Icons by [Roundicons](http://www.flaticon.com/authors/roundicons).