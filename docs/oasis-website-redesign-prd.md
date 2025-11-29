# Oasis Website Redesign PRD

**Version:** 1.0  
**Date:** January 2025  
**Status:** Draft  
**Owner:** Product Team

---

## Executive Summary

This PRD outlines the redesign of the Archie website to align with the Oasis rebrand, reflecting the app's evolution from a voice journaling tool to a comprehensive wellness platform featuring personalized meditation soundbaths, intelligent discovery feeds, and multi-step journaling modules.

**Key Objectives:**
- Rebrand all website content from "Archie" to "Oasis"
- Update visual design system to match Oasis brand colors (emerald green, sky blue, white)
- Refresh content to highlight new features (meditation generation, discovery feed, modules)
- Maintain existing website structure while modernizing the visual presentation
- Ensure consistency with mobile app design system

---

## 1. Background & Context

### 1.1 Current State
- **Old Brand:** Archie - "AI Voice Journal"
- **Old Tagline:** "Speak. Reflect. Grow."
- **Old Color Scheme:** Amber/yellow (#FFC300), cyan (#22d3ee), violet (#a78bfa)
- **Old Focus:** Voice-first journaling with language transformation

### 1.2 New State
- **New Brand:** Oasis - "Your safe space to reflect, grow, and clear your mind"
- **New Tagline:** "Welcome To Your Oasis" / "Your safe space to reflect, grow, and clear your mind"
- **New Color Scheme:** Emerald green (#10B981), sky blue (#4A90E2), white (#FFFFFF)
- **New Focus:** Comprehensive wellness platform with:
  - Voice-first journaling with AI reframing
  - Personalized meditation soundbaths
  - Intelligent discovery feed with weekly themes
  - Multi-step journaling modules
  - Progress tracking across 14 life categories

### 1.3 Rebrand Rationale
The rebrand from "Archie" to "Oasis" reflects:
- **Expanded Value Proposition:** Beyond journaling to holistic wellness
- **Emotional Positioning:** "Oasis" conveys safety, peace, and renewal
- **Visual Identity:** Green (growth), blue (clarity), white (purity) align with wellness themes
- **Feature Evolution:** Meditation generation and discovery feed require broader positioning

---

## 2. Brand Identity Changes

### 2.1 Brand Name & Messaging

**Old:**
- Name: "Archie"
- Tagline: "Speak. Reflect. Grow."
- Value Prop: "Capture thoughts hands‑free, organize insights automatically, and revisit your journey with clarity."

**New:**
- Name: "Oasis"
- Tagline: "Welcome To Your Oasis" / "Your safe space to reflect, grow, and clear your mind"
- Value Prop: "A voice-powered journaling and meditation app that empowers you to become the creator of your own reality through AI-guided reframing and personalized soundbaths."

### 2.2 Color Palette Migration

**Old Colors (Archie):**
```css
Primary Accent: #FFC300 (Amber/Yellow)
Secondary Accent: #22d3ee (Cyan)
Tertiary Accent: #a78bfa (Violet)
Background: #0b0f14 (Dark Navy)
```

**New Colors (Oasis):**
```css
Primary Accent: #10B981 (Emerald Green - growth and renewal)
Secondary Accent: #4A90E2 (Sky Blue - water and clarity)
Tertiary Accent: #FFFFFF (Pure White - light and purity)
Background: #121820 (Dark Charcoal)
Component Background: #1F2937 (Lighter Gray)
Border: #374151 (Component borders)
Text Primary: #F5F5F0 (Light Cream)
Text Secondary: #9CA3AF (Medium Gray)
```

**Gradient Updates:**
- Old: `from-amber-400 via-yellow-400 to-cyan-400`
- New: `from-emerald-500 via-sky-500 to-white` (representing Oasis: plants, water, light)

### 2.3 Typography Migration

**Old:**
- Font Family: Inter
- Weights: 400, 500, 600

**New:**
- Font Family: Poppins
- Weights: 400 (Regular), 500 (Medium), 600 (SemiBold), 700 (Bold)
- Google Fonts URL: `https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap`

---

## 3. Design System Updates

### 3.1 Visual Elements

#### Radial Glow Backgrounds
**Old:**
- Amber/yellow glow: `rgba(255,214,0,0.12)`
- Cyan glow: `rgba(56,189,248,0.12)`

**New:**
- Emerald green glow: `rgba(16,185,129,0.12)` (growth)
- Sky blue glow: `rgba(74,144,226,0.12)` (clarity)
- White glow: `rgba(255,255,255,0.08)` (purity)

#### Gradient Borders
**Old:**
- `linear-gradient(140deg, rgba(253,224,71,0.55), rgba(14,165,233,0.4), rgba(168,85,247,0.35))`

**New:**
- `linear-gradient(140deg, rgba(16,185,129,0.55), rgba(74,144,226,0.4), rgba(255,255,255,0.35))`

#### Conic Gradients
**Old:**
- `conic-gradient(at_20%_10%,#fde047_0deg,#22d3ee_120deg,#a78bfa_240deg,#fde047_360deg)`

**New:**
- `conic-gradient(at_20%_10%,#10B981_0deg,#4A90E2_120deg,#FFFFFF_240deg,#10B981_360deg)`

### 3.2 Component Updates

#### Badge/Pill Components
- Update accent colors from amber/cyan/violet to emerald/sky/white
- Maintain same structure and spacing

#### Feature Cards
- Update icon colors to match Oasis palette
- Update gradient borders to new color scheme

#### CTA Buttons
- Primary: Emerald green (#10B981) with dark text (#121820)
- Secondary: Sky blue (#4A90E2) with white text
- Maintain rounded-2xl styling

---

## 4. Content Updates

### 4.1 Hero Section

**Old:**
```html
<h1>Speak. Reflect. Grow.</h1>
<p>Capture thoughts hands‑free, organize insights automatically, and revisit your journey with clarity.</p>
```

**New:**
```html
<h1>Welcome To Your Oasis</h1>
<p>Your safe space to reflect, grow, and clear your mind. Voice-powered journaling meets personalized meditation soundbaths.</p>
```

**Badge Update:**
- Old: "Voice-first journaling"
- New: "Voice-first journaling • Personalized soundbaths • AI-guided growth"

### 4.2 Language Transformation Section

**Old:**
- Title: "Your words literally rewire your brain"
- Focus: Neuroplasticity and language transformation
- Badge: "Neuroplasticity powered"

**New:**
- Title: "Transform limiting thoughts into empowering beliefs"
- Focus: AI-guided reframing + meditation for holistic transformation
- Badge: "AI-powered transformation"
- Add mention of meditation soundbaths as part of the transformation journey

### 4.3 Features Section

**Old Features:**
1. Hands‑free capture
2. Structured memory
3. Progress over time

**New Features (Updated):**
1. **Voice-first journaling**
   - Icon: microphone (Phosphor icon)
   - Description: "Tap to speak. Your thoughts are transcribed and organized instantly with AI-powered insights."

2. **Personalized soundbaths**
   - Icon: flower-lotus (Phosphor icon)
   - Description: "Generate personalized meditation soundbaths from your journal entries. AI creates scripts tailored to your journey."

3. **Intelligent discovery**
   - Icon: brain (Phosphor icon)
   - Description: "Discover personalized prompts, quotes, and guided modules across 14 life categories. Weekly themes guide your exploration."

4. **Progress tracking**
   - Icon: chart-line (Phosphor icon)
   - Description: "Track your transformation journey with insights, achievements, and patterns across relationships, work, growth, and more."

### 4.4 Secondary Preview Section

**Old:**
- Title: "A focused canvas for your thoughts"
- Features: Private by default, Smart topic clustering, One‑tap prompts

**New:**
- Title: "A complete wellness companion"
- Features:
  - **Private by default** - Your thoughts stay yours
  - **14 life categories** - Explore relationships, work, growth, health, and more
  - **Guided modules** - Multi-step journaling experiences with meditation rewards
  - **Weekly themes** - Personalized exploration paths

### 4.5 FAQ Section Updates

**Update Existing FAQs:**

1. **Privacy Question** - Keep same, update brand name
2. **Language Transformation** - Update to mention meditation soundbaths
3. **Premium Features** - Update to reflect new premium features:
   - Old: "Advanced AI insights, language transformation suggestions, unlimited storage"
   - New: "Personalized meditation soundbaths (3/month), advanced AI insights, unlimited journal entries, premium modules"

**Add New FAQs:**

4. **What are personalized soundbaths?**
   - Answer: "After completing journaling modules, Oasis analyzes your entries and generates personalized meditation scripts. ElevenLabs Music API creates professional soundbaths with AI narration and ambient music tailored to your transformation journey."

5. **What is the Discovery Feed?**
   - Answer: "The Discovery Feed is an intelligent content system that surfaces personalized prompts, quotes, lessons, and modules. It tracks your exploration across 14 life categories and suggests weekly themes to guide your growth."

6. **What are journaling modules?**
   - Answer: "Modules are multi-step guided journaling experiences (5-15 minutes) that help you explore specific topics like gratitude, stress management, or self-compassion. Complete modules unlock personalized meditation soundbaths."

---

## 5. Technical Requirements

### 5.1 HTML/CSS Updates

#### Color Replacements
```css
/* Old → New */
#FFC300 → #10B981 (emerald green)
#22d3ee → #4A90E2 (sky blue)
#a78bfa → #FFFFFF (white, or keep violet for accents if needed)
amber-400 → emerald-500
yellow-400 → sky-500
cyan-400 → white
violet-400 → emerald-500 (or keep for variety)
```

#### Font Updates
```html
<!-- Old -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap" rel="stylesheet">

<!-- New -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
```

```css
/* Old */
font-family: Inter, ui-sans-serif, system-ui...

/* New */
font-family: Poppins, ui-sans-serif, system-ui...
```

### 5.2 Brand Name Replacements

**Global Find & Replace:**
- "Archie" → "Oasis" (in all user-facing text)
- "archie" → "oasis" (in URLs, IDs, classes if needed)
- Keep "archie" in technical references (file paths, code comments) for continuity

### 5.3 App Store Links

**Current:**
- iOS: `https://apps.apple.com/us/app/archie-1-ai-voice-journal/id6747934094`

**Note:** Update when Oasis app is published to App Store. For now, keep existing link or add note about rebrand.

### 5.4 Image Assets

**Mockup Images:**
- Update mockup images to reflect Oasis UI (if available)
- Or keep existing mockups with note that UI has been updated
- Ensure mockups show:
  - New color scheme (emerald green, sky blue)
  - Discovery feed interface
  - Meditation player
  - Module screens

### 5.5 SEO & Meta Tags

**Update Meta Tags:**
```html
<!-- Old -->
<title>Archie — AI Voice Journal</title>
<meta name="description" content="Speak. Reflect. Grow. Voice-first journaling with AI-powered language transformation.">

<!-- New -->
<title>Oasis — Voice Journaling & Personalized Meditation</title>
<meta name="description" content="Your safe space to reflect, grow, and clear your mind. Voice-powered journaling meets personalized meditation soundbaths.">
```

**Open Graph Tags:**
- Update og:title, og:description, og:image to reflect Oasis branding

---

## 6. Implementation Plan

### 6.1 Phase 1: Brand Identity (Priority: High)
**Timeline:** 1-2 days

- [ ] Replace all "Archie" → "Oasis" in HTML content
- [ ] Update color palette throughout CSS
- [ ] Update font family from Inter to Poppins
- [ ] Update gradient definitions
- [ ] Update radial glow backgrounds

**Files to Update:**
- `index.html` (main HTML file)
- Inline CSS styles
- Tailwind config (if using custom Tailwind)

### 6.2 Phase 2: Content Refresh (Priority: High)
**Timeline:** 1-2 days

- [ ] Update hero section copy
- [ ] Update feature descriptions
- [ ] Update language transformation section
- [ ] Add new feature highlights (soundbaths, discovery feed, modules)
- [ ] Update FAQ section
- [ ] Update footer links and text

### 6.3 Phase 3: Visual Polish (Priority: Medium)
**Timeline:** 1 day

- [ ] Update mockup images (if new screenshots available)
- [ ] Adjust gradient intensities for better contrast
- [ ] Test color accessibility (WCAG AA compliance)
- [ ] Verify typography hierarchy
- [ ] Test responsive design across breakpoints

### 6.4 Phase 4: Testing & QA (Priority: High)
**Timeline:** 1 day

- [ ] Cross-browser testing (Chrome, Safari, Firefox, Edge)
- [ ] Mobile responsiveness testing
- [ ] Color contrast validation
- [ ] Link validation (App Store, Terms, Privacy)
- [ ] SEO meta tag verification
- [ ] Performance testing (page load speed)

### 6.5 Phase 5: Launch (Priority: High)
**Timeline:** 0.5 day

- [ ] Deploy to production
- [ ] Verify DNS/domain routing
- [ ] Test all CTAs and links
- [ ] Monitor analytics for errors
- [ ] Announce rebrand (if applicable)

---

## 7. Design Specifications

### 7.1 Color Usage Guidelines

**Primary Accent (Emerald Green #10B981):**
- Primary CTAs
- Active states
- Key highlights
- Success indicators

**Secondary Accent (Sky Blue #4A90E2):**
- Secondary buttons
- Informational icons
- Links
- Progress indicators

**Tertiary Accent (White #FFFFFF):**
- Text on dark backgrounds
- Accent highlights
- Gradient endpoints

**Background Hierarchy:**
- `#121820` - Main page background
- `#1F2937` - Card/component backgrounds
- `#0C0C11` - Layered components

### 7.2 Typography Scale

**Headings:**
- H1 (Hero): 48-64px, Poppins Medium/Bold
- H2 (Section): 36-48px, Poppins Medium
- H3 (Subsection): 24-32px, Poppins Medium
- H4 (Card Title): 18-20px, Poppins Medium

**Body:**
- Large Body: 18px, Poppins Regular
- Body: 16px, Poppins Regular
- Small: 14px, Poppins Regular
- Caption: 12px, Poppins Regular

**Weights:**
- Regular (400) - Body text
- Medium (500) - Headings, emphasis
- SemiBold (600) - Strong emphasis
- Bold (700) - Display text

### 7.3 Spacing System

Maintain existing spacing:
- Section padding: `py-12 lg:py-16` or `py-12 lg:py-20`
- Container padding: `px-4 sm:px-6 lg:px-8`
- Card padding: `p-6`
- Gap between elements: `gap-3`, `gap-6`, `gap-10`

### 7.4 Component Specifications

**Buttons:**
- Primary: `bg-[#10B981] text-[#121820] rounded-2xl px-5 py-3`
- Secondary: `bg-white/10 hover:bg-white/15 text-white rounded-full px-4 py-2`

**Cards:**
- Background: `bg-[#0b0f14]` → `bg-[#121820]`
- Border: `ring-1 ring-white/10`
- Padding: `p-6`
- Border radius: `rounded-2xl`

**Badges:**
- Background: `bg-white/5 ring-1 ring-white/10`
- Padding: `px-3 py-1.5`
- Border radius: `rounded-full`
- Dot indicator: `h-2 w-2 rounded-full` with accent colors

---

## 8. Content Matrix

### 8.1 Section-by-Section Content Updates

| Section | Old Content | New Content | Status |
|---------|------------|-------------|--------|
| **Hero** | "Speak. Reflect. Grow." | "Welcome To Your Oasis" | Update |
| **Hero Subtitle** | "Capture thoughts hands‑free..." | "Your safe space to reflect, grow, and clear your mind..." | Update |
| **Language Section** | "Your words literally rewire your brain" | "Transform limiting thoughts into empowering beliefs" | Update |
| **Features** | 3 features (capture, memory, progress) | 4 features (journaling, soundbaths, discovery, progress) | Update |
| **Secondary Preview** | "A focused canvas for your thoughts" | "A complete wellness companion" | Update |
| **FAQ** | 6 questions | 8 questions (add soundbaths, discovery, modules) | Update |

### 8.2 New Content to Add

**Meditation Soundbaths:**
- "Generate personalized meditation soundbaths from your journal entries"
- "AI creates scripts tailored to your transformation journey"
- "Professional mixing with narration and ambient music"

**Discovery Feed:**
- "Intelligent content delivery across 14 life categories"
- "Weekly themes guide your exploration"
- "Personalized prompts, quotes, and modules"

**Modules:**
- "Multi-step guided journaling experiences"
- "5-15 minute sessions on gratitude, stress, growth, and more"
- "Complete modules to unlock personalized meditations"

---

## 9. Success Metrics

### 9.1 Brand Consistency
- [ ] 100% of "Archie" references replaced with "Oasis"
- [ ] All colors match Oasis design system
- [ ] Typography matches Poppins font family

### 9.2 User Experience
- [ ] Page load time < 3 seconds
- [ ] Mobile responsiveness score > 95%
- [ ] Accessibility score (WCAG AA) > 90%

### 9.3 Content Accuracy
- [ ] All features accurately described
- [ ] App Store links functional
- [ ] FAQ answers reflect current app functionality

### 9.4 Visual Quality
- [ ] Color contrast meets WCAG AA standards
- [ ] Typography hierarchy is clear
- [ ] Gradient effects render correctly
- [ ] Mockup images display properly

---

## 10. Dependencies & Considerations

### 10.1 External Dependencies
- **Google Fonts:** Poppins font family availability
- **App Store:** Oasis app listing (may need to keep Archie link temporarily)
- **Analytics:** Update tracking codes if brand-specific

### 10.2 Technical Considerations
- **Tailwind CSS:** May need custom color configuration
- **CDN Assets:** Mockup images may need updating
- **SEO:** Update sitemap and meta tags
- **Social Sharing:** Update Open Graph images

### 10.3 Migration Notes
- Keep "archie" in technical references (file paths, code) for continuity
- Update user-facing content to "Oasis" consistently
- Maintain existing website structure and functionality
- Preserve SEO value with proper redirects (if domain changes)

---

## 11. Open Questions & Decisions Needed

1. **Domain:** Will the website domain change from archie.com to oasis.com? (Affects redirects, DNS)
2. **App Store:** When will Oasis app be published? (Affects download links)
3. **Mockup Images:** Do we have new screenshots showing Oasis UI? (Affects visual updates)
4. **Analytics:** Do we need separate tracking for Oasis vs. Archie? (Affects implementation)
5. **Social Media:** Update social handles and profiles? (Affects footer links)

---

## 12. Appendix

### 12.1 Color Reference

**Oasis Color Palette:**
```css
:root {
  --oasis-emerald: #10B981;
  --oasis-sky-blue: #4A90E2;
  --oasis-white: #FFFFFF;
  --oasis-bg-dark: #121820;
  --oasis-bg-component: #1F2937;
  --oasis-text-primary: #F5F5F0;
  --oasis-text-secondary: #9CA3AF;
  --oasis-border: #374151;
}
```

### 12.2 Typography Reference

**Poppins Font Weights:**
- 400: Regular (body text)
- 500: Medium (headings)
- 600: SemiBold (emphasis)
- 700: Bold (display)

**Google Fonts Import:**
```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
```

### 12.3 Gradient Formulas

**Oasis Gradient (Primary):**
```css
background: linear-gradient(140deg, 
  rgba(16,185,129,0.55),   /* Emerald */
  rgba(74,144,226,0.4),     /* Sky Blue */
  rgba(255,255,255,0.35)    /* White */
);
```

**Oasis Conic Gradient:**
```css
background: conic-gradient(
  at 20% 10%,
  #10B981 0deg,      /* Emerald */
  #4A90E2 120deg,    /* Sky Blue */
  #FFFFFF 240deg,    /* White */
  #10B981 360deg     /* Emerald */
);
```

---

## Document History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | January 2025 | Product Team | Initial PRD creation |

---

**Next Steps:**
1. Review and approve PRD
2. Assign implementation team
3. Begin Phase 1: Brand Identity updates
4. Schedule design review
5. Plan launch timeline
