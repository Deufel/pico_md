# Personal fork of pico css, not intended to knock your socks off.
NOTE: I only use CSS so I stripped this down to only include the CSS
NOTE: This is currently being butilt to take advantage of the new CSS features more so then ensure compatibility with older browsers.

# Change Log (to do)
- fluid font size
- fluid container width
- Custom Scrollbar (webkit only)
- Custom Button (svg support)
  ```html
  <!-- Regular button (works exactly as before) -->
  <button>Click me</button>

  <!-- Button with left icon -->
  <button>
      <svg><!-- your icon --></svg>
      <span>Click me</span>
  </button>

  <!-- Button with right icon -->
  <button>
      <span>Click me</span>
      <svg><!-- your icon --></svg>
  </button>
  ```

# to Do
- [ ] betternative support for color themes
- [ ] better support for popover API (in progress)
- [ ] better support for anchor API (in progress)
