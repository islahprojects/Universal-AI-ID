Audio Announcements
Trigger: When content loads or enters viewport
Voice: Clear, calm, non-intrusive
Timing: Once per page load (not repeated on scroll)
Languages: Match user's system locale

Haptic Feedback (Mobile)
// Vibration pattern for AI ID detection
// Pattern: Short pulse (50ms) = gentle notification
if ('vibrate' in navigator) {
  navigator.vibrate(50);
}

Braille Display Compatibility
Use semantic HTML (role="note")
Provide full text alternative (not just emoji)
Ensure proper reading order
Test with JAWS, NVDA, VoiceOver

Audio Guide Scripts
See /guides/AUDIO-SCRIPTS/ for pre-recorded announcements in 10+ languages.

👂 For Deaf & Hard of Hearing UsersVisual Indicators (Already Implemented)
✅ Persistent visual marker (🧬)
✅ High-contrast mode support
✅ No reliance on audio cues
✅ Clear typography and spacing

Enhanced Visual Cues
/* Optional: Subtle border for high-visibility mode */
.ai-id-container[data-ai-id-visual="enhanced"] {
  border: 2px solid currentColor;
  box-shadow: 0 0 0 2px rgba(0,0,0,0.2);
}

Sign Language Integration
Future: Embed sign language video explaining AI ID
QR Code: Link to ASL/BSL/Filipino Sign Language explainer
Icon: Add sign language hand symbol alongside 🧬

🧠 For Cognitive & Neurodiverse Users
Clear, Simple Language
Avoid jargon: "AI helped make this" not "Generative AI augmentation"
Consistent placement: Always bottom-right (or RTL mirror)
Predictable behavior: No animations that could cause distraction

Reduced Motion Support
@media (prefers-reduced-motion: reduce) {
  .ai-id-container {
    animation: none !important;
    transition: none !important;
  }
}

Dyslexia-Friendly Fonts
.ai-id-container {
  font-family: 'OpenDyslexic', 'Comic Sans MS', system-ui, sans-serif;
  letter-spacing: 0.05em;
  line-height: 1.6;
}

🎮 For Motor & Mobility Impaired Users
Keyboard Navigation
// Allow focus and interaction via keyboard
.ai-id-container[tabindex="0"] {
  outline: 2px solid transparent; /* Custom focus style */
}
.ai-id-container:focus {
  outline: 2px solid currentColor;
  outline-offset: 2px;
}

Voice Control Compatibility
Use semantic HTML elements
Provide clear, unique labels
Test with Dragon NaturallySpeaking, Voice Control (iOS)

Switch Control Support
Ensure logical tab order
Provide sufficient click target (min 44×44px)
Avoid hover-only interactions

🧪 Testing Checklist
Screen Readers
NVDA (Windows)
JAWS (Windows)
VoiceOver (macOS/iOS)
TalkBack (Android)
Keyboard Navigation
Tab through all interactive elements
Activate with Enter/Space
No keyboard traps
Visual
High contrast mode (WCAG AAA)
200% zoom without breaking
Color-blind safe (don't rely on color alone)
Cognitive
Plain language test (8th grade reading level)
Consistent placement across pages
No flashing content (seizure risk)

📞 Reporting Accessibility Issues
If you encounter barriers with the AI ID implementation:
📧 Email: accessibility@ai-id.org
🐛 GitHub Issues: Use "accessibility" label
📝 Provide: Browser, assistive technology, description of issue

We commit to responding within 48 hours.

🔗 Resources
WCAG 2.2 Guidelines: https://www.w3.org/WAI/WCAG22/quickref/
ARIA Authoring Practices: https://www.w3.org/WAI/ARIA/apg/
Inclusive Design Principles: https://inclusivedesignprinciples.org/
"Accessibility is not a feature. It's a foundation."
Version: 1.0 | Last Updated: January 2026 | License: CC BY-SA 4.0

