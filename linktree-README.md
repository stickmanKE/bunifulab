# stickmanKE · Personal Links Page

A clean, animated personal link-in-bio page hosted on Vercel.

🔗 **Live:** [stickmanke.vercel.app](https://stickmanke.vercel.app)

## Adding New Projects

Open `index.html` and copy this block inside the `.links-section` div:

```html
<a href="YOUR_LINK" target="_blank" rel="noopener" class="link-card teal">
  <div class="card-icon teal-bg">
    <!-- paste an SVG icon here -->
  </div>
  <div class="card-body">
    <div class="card-title">Project Name</div>
    <div class="card-desc">Short description of the project</div>
  </div>
  <span class="card-tag tag-live">Live</span>
  <div class="card-arrow">
    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
      <line x1="5" y1="12" x2="19" y2="12"/><polyline points="12 5 19 12 12 19"/>
    </svg>
  </div>
</a>
```

### Color themes available:
- `teal` — green/teal accent
- `gold` — warm gold accent  
- `blue` — deep blue accent
- `ink` — neutral dark accent

### Tag options:
- `tag-live` — green "Live" badge
- `tag-open` — blue "Open Source" badge
- `tag-soon` — amber "Coming Soon" badge

## Deployment

Push to GitHub then import to [Vercel](https://vercel.com) — deploys automatically on every push.
