# UAT Playbook: GroomBook Site

## Test Environment
- **URL:** https://groombook.farh.net (demo)
- **Repository:** https://github.com/groombook/site
- **Last Updated:** 2026-05-12

---

## 1. Homepage Messaging Path C Refresh

### Purpose
Verify homepage copy aligns with Path C strategy (solo/small operator focus) with approved lead/team messages and clear anti-customer positioning.

### Pre-Conditions
- Homepage loads successfully
- User is not logged in

### Test Cases

#### TC-1.1: Hero Section Messaging
| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Navigate to homepage | Page loads without errors |
| 2 | Locate hero tagline | Displayed exactly: "Stop missing client calls. Book 24/7, groom all day." |
| 3 | Read hero paragraph | Copy emphasizes: solo groomers/small teams, 24/7 booking, automated reminders, mobile-first tools, more grooming time |

#### TC-1.2: Feature Cards Section
| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Scroll to "Reclaim 3+ Hours Every Week" section | Section heading is correct |
| 2 | Read section subtitle | Text: "Features built for solo groomers and small teams — not generic salon software." |
| 3 | Review all 9 feature cards | Each card focuses on time/revenue benefit, not feature parity |

#### TC-1.3: Comparison Section Replacement
| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Scroll to "Built for Your Reality" section | Section heading is correct |
| 2 | Read section subtitle | Text: "Not a generic salon tool. Not a feature arms race. Built specifically for how solo groomers and small teams actually work." |
| 3 | Verify workflow cards | 6 cards present: Mobile Groomers, 24/7 Booking, You Own It, Grooming-Specific, No-Show Recovery, Scales With You |

#### TC-1.4: Anti-Customer Positioning
| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Scan entire homepage for competitor mentions | No specific competitor names (MoeGo, Gingr) mentioned |
| 2 | Review comparison section | No feature parity table present |
| 3 | Check all copy | Clear "not X" positioning without naming competitors |

#### TC-1.5: No Feature Parity Claims
| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Search homepage text | No "more features than", "better than [competitor]", or comparative claims |
| 2 | Review feature cards | Each card describes benefit/value, not "more of X" |

#### TC-1.6: Content Quality and Readability
| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Read all copy aloud | Professional tone, clear grammar, no typos |
| 2 | Check mobile responsiveness | Content readable on mobile viewport |
| 3 | Verify formatting | No broken layout, proper spacing between sections |

---

## 2. Homepage Functionality

### TC-2.1: CTA Buttons
| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Click "Try the Demo" button | Navigates to https://groombook.farh.net |
| 2 | Click "View on GitHub" button | Navigates to https://github.com/groombook/groombook |

### TC-2.2: Badge Display
| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Locate hero badge | Displays: "🎉 100% Open Source — AGPL-3.0 License" |

---

## Pass/Fail Criteria

- **PASS:** All test cases execute successfully with expected results
- **FAIL:** Any test case fails or produces unexpected result

---

## Notes

- UAT should be performed on both desktop and mobile viewports
- Check browser console for JavaScript errors during test execution
- Verify all links are functional and lead to expected destinations
