# Oasis Website Redesign - Implementation Checklist

Quick reference checklist for implementing the website redesign. See `oasis-website-redesign-prd.md` for full details.

---

## Phase 1: Brand Identity Updates

### Color Replacements
- [ ] Replace `#FFC300` (amber) → `#10B981` (emerald green)
- [ ] Replace `#22d3ee` (cyan) → `#4A90E2` (sky blue)
- [ ] Replace `#a78bfa` (violet) → `#FFFFFF` (white) or keep for accents
- [ ] Update `amber-400` → `emerald-500` in Tailwind classes
- [ ] Update `yellow-400` → `sky-500` in Tailwind classes
- [ ] Update `cyan-400` → `white` in Tailwind classes
- [ ] Update background from `#0b0f14` → `#121820`
- [ ] Update component backgrounds to `#1F2937`

### Typography Updates
- [ ] Replace Inter font import with Poppins
- [ ] Update font-family in body tag
- [ ] Verify font weights: 400, 500, 600, 700

### Gradient Updates
- [ ] Update radial glow backgrounds (emerald + sky blue)
- [ ] Update linear gradients in borders
- [ ] Update conic gradients in decorative elements

### Brand Name Replacements
- [ ] Replace "Archie" → "Oasis" in all user-facing text
- [ ] Update page title
- [ ] Update meta description
- [ ] Update Open Graph tags

---

## Phase 2: Content Updates

### Hero Section
- [ ] Update H1: "Welcome To Your Oasis"
- [ ] Update subtitle with new value proposition
- [ ] Update badge text
- [ ] Update CTA button text (if needed)

### Language Transformation Section
- [ ] Update title
- [ ] Update badge
- [ ] Add mention of meditation soundbaths
- [ ] Update feature descriptions

### Features Section
- [ ] Update Feature 1: Voice-first journaling
- [ ] Add Feature 2: Personalized soundbaths
- [ ] Add Feature 3: Intelligent discovery
- [ ] Update Feature 4: Progress tracking
- [ ] Update icons and colors

### Secondary Preview Section
- [ ] Update title: "A complete wellness companion"
- [ ] Update feature list (4 items)
- [ ] Update mockup image (if available)

### FAQ Section
- [ ] Update existing FAQ answers
- [ ] Add FAQ: "What are personalized soundbaths?"
- [ ] Add FAQ: "What is the Discovery Feed?"
- [ ] Add FAQ: "What are journaling modules?"

### Footer
- [ ] Update copyright text
- [ ] Update links (if domain changes)
- [ ] Verify Terms/Privacy links

---

## Phase 3: Visual Polish

### Images
- [ ] Update mockup images (if new screenshots available)
- [ ] Verify image alt text
- [ ] Check image loading performance

### Accessibility
- [ ] Test color contrast (WCAG AA)
- [ ] Verify text readability
- [ ] Test keyboard navigation
- [ ] Check screen reader compatibility

### Responsive Design
- [ ] Test mobile view (< 640px)
- [ ] Test tablet view (640px - 1024px)
- [ ] Test desktop view (> 1024px)
- [ ] Verify all sections stack properly

### Performance
- [ ] Optimize images
- [ ] Test page load speed
- [ ] Verify font loading
- [ ] Check for render-blocking resources

---

## Phase 4: Technical Updates

### HTML
- [ ] Update `<title>` tag
- [ ] Update meta description
- [ ] Update Open Graph tags
- [ ] Update favicon (if new one available)

### CSS
- [ ] Update all color values
- [ ] Update font-family declarations
- [ ] Update gradient definitions
- [ ] Verify Tailwind config (if using)

### JavaScript
- [ ] Update any brand name references in JS
- [ ] Verify FAQ toggle functionality
- [ ] Test screenshot swap functionality (if keeping)

### Links
- [ ] Verify App Store link
- [ ] Update Terms link (if needed)
- [ ] Update Privacy link (if needed)
- [ ] Test all anchor links

---

## Phase 5: Testing & QA

### Cross-Browser Testing
- [ ] Chrome (latest)
- [ ] Safari (latest)
- [ ] Firefox (latest)
- [ ] Edge (latest)

### Device Testing
- [ ] iPhone (Safari)
- [ ] Android (Chrome)
- [ ] iPad (Safari)
- [ ] Desktop (Chrome/Safari)

### Functionality Testing
- [ ] All links work
- [ ] FAQ accordion works
- [ ] CTA buttons work
- [ ] Navigation works
- [ ] Form submissions (if any)

### Content Review
- [ ] No "Archie" references remain
- [ ] All features accurately described
- [ ] Grammar and spelling correct
- [ ] Consistent tone and voice

---

## Phase 6: Launch

### Pre-Launch
- [ ] Final design review
- [ ] Content review
- [ ] Technical review
- [ ] Stakeholder approval

### Deployment
- [ ] Backup current site
- [ ] Deploy changes
- [ ] Verify DNS/domain
- [ ] Test live site

### Post-Launch
- [ ] Monitor analytics
- [ ] Check for errors
- [ ] Verify all links
- [ ] Test on multiple devices

### Documentation
- [ ] Update any internal docs
- [ ] Document color codes
- [ ] Document font usage
- [ ] Create style guide reference

---

## Quick Reference: Color Codes

```
Emerald Green:  #10B981
Sky Blue:       #4A90E2
White:          #FFFFFF
Dark BG:        #121820
Component BG:   #1F2937
Text Primary:   #F5F5F0
Text Secondary: #9CA3AF
Border:         #374151
```

## Quick Reference: Font

```html
<!-- Import -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">

<!-- Usage -->
font-family: Poppins, ui-sans-serif, system-ui...
```

---

## Notes

- Keep "archie" in technical references (file paths, code comments) for continuity
- Update user-facing content to "Oasis" consistently
- Maintain existing website structure and functionality
- Test thoroughly before launch

---

**Last Updated:** January 2025  
**Status:** Ready for Implementation
