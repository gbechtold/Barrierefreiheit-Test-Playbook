# Web Accessibility Testing Playbook

## Table of Contents
1. [Basic Analysis (Quick Check)](#1-basic-analysis-quick-check)
2. [Automated Full Analysis](#2-automated-full-analysis)
3. [Complete Manual Analysis](#3-complete-manual-analysis)
4. [Documentation Templates](#4-documentation-templates)

## 1. Basic Analysis (Quick Check)

### 1.1 Preparation
- [ ] Record domain and website scope
- [ ] Identify main functionalities
- [ ] Check sitemap access
- [ ] Check robots.txt

### 1.2 Quick Check Main Pages
- [ ] Homepage
- [ ] Main navigation
- [ ] Contact page
- [ ] A typical content page
- [ ] If available: One form
- [ ] If available: One transaction page

### 1.3 Technical Basic Checks 
- [ ] Lighthouse Accessibility Score of main page
- [ ] HTML validation of main page
- [ ] Responsive design check (3 breakpoints)
- [ ] Keyboard navigation quick check

### 1.4 Quick Check Documentation
```markdown
# Quick Check Accessibility
Date: [DATE]
Website: [URL]
Tester: [NAME]

## Summary
- Overall impression:
- Main issues:
- Recommended next steps:

## Lighthouse Score
- Performance: [X]
- Accessibility: [X]
- Best Practices: [X]
- SEO: [X]

## Main Issues Found
1. [Issue 1]
2. [Issue 2]
3. [Issue 3]

## Recommendation
[ ] No further actions needed
[ ] Automated full analysis recommended
[ ] Complete manual testing recommended
```

## 2. Automated Full Analysis

### 2.1 Preparation
- [ ] Download/generate sitemap XML
- [ ] Prepare crawler script
- [ ] Set up test environment
- [ ] Prepare logging system

### 2.2 Automated Tests

### 2.3 Aspects to Test
- [ ] HTML validation of all pages
- [ ] Lighthouse accessibility scores
- [ ] Contrast analysis
- [ ] Alt text check
- [ ] Heading structure
- [ ] ARIA attributes
- [ ] Meta information
- [ ] Responsive breakpoints
- [ ] Form accessibility

### 2.4 Automated Report Generation
```markdown
# Automated Full Analysis
Date: [DATE]
Website: [URL]
URLs tested: [NUMBER]

## Summary
- Average Lighthouse Score: [X]
- Critical issues: [X]
- Warnings: [X]
- Pages tested: [X]

## Detailed Results
### HTML Validation
- Total errors: [X]
- Total warnings: [X]
- Top 5 most frequent issues:
  1. [ISSUE] ([COUNT]x)
  2. ...

### Accessibility Issues
- Critical: [LIST]
- Important: [LIST]
- Moderate: [LIST]
- Minor: [LIST]

### Recommended Manual Checks
1. [AREA]
2. [AREA]
```

## 3. Complete Manual Analysis

### 3.1 Preparation
- [ ] Set up test environments
- [ ] Prepare test devices
- [ ] Install assistive technologies
- [ ] Define test cases

### 3.2 Assistive Technologies to Test
- [ ] NVDA Screen Reader
- [ ] JAWS Screen Reader
- [ ] VoiceOver (iOS/macOS)
- [ ] Screen Magnifier
- [ ] Voice Control
- [ ] On-screen Keyboard

### 3.3 Manual Test Scenarios
1. Navigation and Structure
   - [ ] Keyboard navigation
   - [ ] Skip links
   - [ ] Landmarks
   - [ ] Heading structure
   - [ ] Table structure

2. Content and Media
   - [ ] Alt texts
   - [ ] Video captions
   - [ ] Audio descriptions
   - [ ] Documents
   - [ ] Graphics and charts

3. Interactive Elements
   - [ ] Forms
   - [ ] Buttons
   - [ ] Custom controls
   - [ ] Error handling
   - [ ] Modals/overlays

4. Responsive Design & Zoom
   - [ ] 200% zoom
   - [ ] 400% zoom
   - [ ] Reflow
   - [ ] Touch targets
   - [ ] Viewport adjustments

### 3.4 Manual Testing Documentation
```markdown
# Manual Accessibility Testing
Date: [DATE]
Website: [URL]
Tester: [NAME]

## Tested Environments
### Browsers
- [ ] Chrome [VERSION]
- [ ] Firefox [VERSION]
- [ ] Safari [VERSION]
- [ ] Edge [VERSION]

### Assistive Technologies
- [ ] NVDA [VERSION]
- [ ] JAWS [VERSION]
- [ ] VoiceOver [VERSION]

## Detailed Test Results

### 1. Navigation & Structure
#### Keyboard Navigation
- Tested: [YES/NO]
- Issues found: [YES/NO]
- Details: [DESCRIPTION]

[ADDITIONAL CATEGORIES...]

## Issues Found
### Critical
1. [ISSUE]
   - Location: [URL/ELEMENT]
   - WCAG Reference: [X.X.X]
   - Steps to reproduce: [STEPS]
   - Recommendation: [SOLUTION]

[ADDITIONAL PRIORITIES...]

## Recommendations
1. Immediate Actions
   - [ACTION]
   - [ACTION]

2. Medium-term Actions
   - [ACTION]
   - [ACTION]

3. Long-term Optimizations
   - [ACTION]
   - [ACTION]
```

## 4. Documentation Templates

### 4.1 WCAG Conformance Statement
```markdown
# Accessibility Conformance Statement

## General Information
- Website: [URL]
- Test date: [DATE]
- Testing methodology: [METHODOLOGY]
- Conformance target: [LEVEL]

## Conformance Status
[ ] Fully conformant
[ ] Partially conformant
[ ] Not conformant

## Non-accessible Content
1. [CONTENT]
   - Reason: [REASON]
   - Alternative: [ALTERNATIVE]
   - Planned fix: [DATE]

## Creation Information
- Created on: [DATE]
- Last review: [DATE]
- Next review: [DATE]
```

### 4.2 Action Plan
```markdown
# Accessibility Action Plan

## Immediate Actions (1-4 weeks)
1. [ACTION]
   - Priority: [PRIORITY]
   - Effort: [EFFORT]
   - Responsible: [PERSON]
   - Deadline: [DATE]

## Medium-term Actions (1-3 months)
[...]

## Long-term Actions (3+ months)
[...]

## Budget & Resources
- Estimated budget: [AMOUNT]
- Required resources: [LIST]
- Training needs: [YES/NO]
```

### 4.3 Test Protocols
```markdown
# Accessibility Test Protocol

## Test Information
- Test scenario: [DESCRIPTION]
- Tester: [NAME]
- Date: [DATE]
- Test environment: [DETAILS]

## Tests Performed
1. [TEST]
   - Expected result: [EXPECTATION]
   - Actual result: [RESULT]
   - Status: [PASSED/FAILED]
   - Screenshots: [LINKS]
   - Notes: [NOTES]

## Summary
- Tests performed: [NUMBER]
- Passed: [NUMBER]
- Failed: [NUMBER]
- Critical issues: [NUMBER]
```

---

## Notes on Usage

- This playbook should be treated as a living document
- Regular updates based on new standards and experiences
- Adaptation to project-specific requirements needed
- Documentation of all modifications and improvements
- Staff training in playbook usage

## Legal Notes

- Compliance with local accessibility laws
- Adherence to WCAG 2.1 guidelines
- Consideration of EN 301 549
- Documentation according to legal requirements
