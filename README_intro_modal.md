Overview modal added to `index.html` by the assistant.

How it works:
- Header button: `#intro-btn` - opens the overview modal.
- Modal overlay: `#intro-overlay` with `.modal-overlay` `.modal-box` reuse.
- Dismiss option: `#intro-dismiss` - checking "Don't show again" saves `localStorage.setItem('a8_intro_dismissed','1')`.
- First visit: modal opens automatically unless dismissed.

To show manually in console:
```js
showIntroModal();
```
