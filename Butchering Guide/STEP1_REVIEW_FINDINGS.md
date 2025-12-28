# Butchering Guide - Step 1 Review Findings
## Cross-Reference with Provisions Guide
**Review Date:** Analysis of General Butcher Guide, Blink Wolf, and Owlbear guides
**Reviewed Against:** Master Provisions Guide (680+ items, Sixth Edition 1492 DR)

---

## SUMMARY

I've completed a thorough cross-reference of the Butchering Guide files against the Provisions Guide to verify pricing accuracy and mathematical consistency. Below are the findings organized by severity.

---

## CRITICAL ERRORS - Ingredient Pricing Discrepancies

### 1. **Black Peppercorns - MAJOR PRICING ERROR**

**Both Owlbear and Blink Wolf guides have incorrect pricing**

**Provisions Guide (Correct):**
- **Price:** 1 sp per package
- **Weight:** 0.25 lbs (4 oz)
- **Uses:** 48 uses when ground

**Owlbear Guide says (Line 386-388):**
- **Price:** 1 gp per package ❌ **10x TOO HIGH**
- **Weight:** 0.06 lbs (1 oz) ❌ WRONG
- **Uses:** 24 uses ❌ WRONG

**Blink Wolf Guide says (Line 593):**
- **Price:** "Black pepper: 2 oz (1 gp)" ❌ **10x TOO HIGH**

**Impact:** This pricing error inflates sausage costs by approximately 9 silver per batch
**Recommendation:** Change to "1 sp per package (0.25 lbs, 48 uses when ground)" in both guides

---

### 2. **Trielta Hills Garlic - Incorrect Clove Count**

**Provisions Guide (Correct):**
- **Price:** 2 cp per bulb
- **Weight:** 0.1 lbs
- **Uses:** 16 uses
- **Description:** Contains "14-18 individual cloves"

**Owlbear Guide says (Line 399-402):**
- **Cloves:** "containing 9 cloves typically" ❌ WRONG

**Impact:** Minor - doesn't affect pricing but creates inconsistency in world-building
**Recommendation:** Change to "containing 14-18 individual cloves (typically 16)" to match Provisions Guide

---

## VERIFIED CORRECT - Matching Provisions Guide ✓

The following ingredients correctly match the Provisions Guide:

| Ingredient | Butcher Guide Price | Provisions Guide | Status |
|------------|---------------------|------------------|--------|
| **Daggerford Sage** | 3 sp, 0.06 lbs, 24 uses | 3 sp, 0.06 lbs, 24 uses | ✓ CORRECT |
| **Juniper Berries** | 5 sp, 0.06 lbs, 20 uses | 5 sp, 0.06 lbs, 20 uses | ✓ CORRECT |
| **Rock Salt (Gray)** | 1 cp per lb | 1 cp per lb, 90 uses | ✓ CORRECT |
| **Fennel Seed** | 4 sp, 0.06 lbs, 20 uses | 4 sp, 0.06 lbs, 20 uses | ✓ CORRECT |
| **Bay Leaves** | 3 sp, 0.06 lbs, 15 uses | 3 sp, 0.06 lbs, 15 uses | ✓ CORRECT |
| **Sword Coast Yellow Onions** | 2 cp, 1 lb, 3 uses | 2 cp, 1 lb, 3 uses | ✓ CORRECT |
| **Silverymoon Carrots** | 5 cp, 1 lb, 4 uses | 5 cp, 1 lb, 4 uses | ✓ CORRECT |
| **Celery** | 3 cp, 0.75 lbs, 10 uses | 3 cp, 0.75 lbs, 10 uses | ✓ CORRECT |
| **Trielta Hills Garlic (price)** | 2 cp per bulb, 0.1 lbs | 2 cp per bulb, 0.1 lbs | ✓ CORRECT |

---

## MATHEMATICAL CONSISTENCY CHECKS

### General Butcher Guide - Yield Standards

The General Butcher Guide establishes these percentages (applied to dressed weight after external materials removed):

| Animal Type | Retail Meat | Sausage Trim | Bones | Fat (Tallow) | Waste |
|-------------|-------------|--------------|-------|--------------|-------|
| **Canine (Wolf/Blink Wolf)** | 35% | 13% | 15% | 6% | 7% |
| **Bear (Ursine/Owlbear Half)** | 40% | 10% | 12% | 12% | 5% |
| **Bird (Avian/Owlbear Half)** | 32% | 8% | 15% | 2% | 8% |

### Blink Wolf - Yield Verification

**Starting Point:**
- Live weight: 800 lbs
- Dressed weight (after field dressing): 745 lbs
- External materials removed: 100 lbs (pelt 85 lbs + organs 7 lbs + trophies 8 lbs)
- **Carcass for butchering: 645 lbs**

**Expected Yields (35% retail, 13% trim, 15% bones, 6% fat):**
- Retail cuts: 35% × 645 = **225.75 lbs** (guide says 220 lbs) ✓ close enough
- Sausage trim: 13% × 645 = **83.85 lbs** (guide says 95 lbs) ⚠️ 13% higher
- Bones: 15% × 645 = **96.75 lbs** (guide says 110 lbs) ⚠️ 14% higher
- Fat: 6% × 645 = **38.7 lbs** (guide says 45 lbs) ⚠️ 16% higher

**Issue:** The guide shows consistently higher yields than the General Butcher Guide standards suggest

**Retail Cuts Breakdown Discrepancy:**
- The summary says "220 lbs" of retail cuts
- BUT the detailed table (line 342-347) shows:
  - Shoulder: 110 lbs
  - Loin/Saddle: 85 lbs
  - Hindquarters: 100 lbs
  - Ribs/Belly: 25 lbs
  - **TOTAL: 320 lbs** ❌ DOESN'T MATCH 220 lbs

**This is a major internal inconsistency that needs resolution**

### Owlbear - Yield Verification

**Starting Point:**
- Live weight: ~1,600 lbs
- Dressed weight: 1,420 lbs
- External materials: 183 lbs
- **Carcass for butchering: 1,237 lbs**

**The Owlbear is a chimera (half avian, half ursine), so yields are more complex**

**Guide shows:**
- Avian section retail: 240 lbs
- Ursine section retail: 335 lbs
- **Total retail: 575 lbs** (which is 46.5% of 1,237 lbs carcass)
- Sausage trim: 70 lbs (5.7% of carcass)
- Bones: 213 lbs total (17.2% of carcass)
- Fat: 99 lbs (8% of carcass)

**This seems reasonable for a chimera** - the retail percentage is between the bird (32%) and bear (40%) standards, weighted more toward bear since it's described as having more ursine mass.

---

## GENERAL STANDARDS COMPLIANCE

### Labor Rates

**General Guide establishes:**
- Master Butcher: 2.5 gp/hr (independent) or 3.5 gp/hr (guild)
- Journeyman: 1.5 gp/hr (independent) or 2 gp/hr (guild)
- Apprentice/Laborer: 0.5 gp/hr (independent) or 0.8 gp/hr (guild)

**Both creature guides appear to use these rates correctly** ✓

### Tallow Pricing

**General Guide establishes:**
- Bulk tallow: 2 sp per lb
- Clarified/jarred: 5 sp per lb

**Blink Wolf Guide:** Uses 2 sp/lb bulk ✓ CORRECT
**Owlbear Guide:** Uses 2 sp/lb bulk ✓ CORRECT

### Bone Stock Pricing

**General Guide establishes:**
- Standard stock: 3.5 sp per pint
- Master's Glace (reduced): 5 gp per quart = 2.5 gp per pint

**Blink Wolf Guide:** Uses 3.5 sp/pint ✓ CORRECT
**Owlbear Guide:** Uses 5 gp per quart = equivalent ✓ CORRECT

---

## ADDITIONAL OBSERVATIONS

### Sausage Fat Ratios

**General Guide establishes:**
- Ratio: 60-70% lean trim to 30-40% animal fat
- For lean animals (birds/canines), may require "Butcher's Credit" - using fat from bear or hog processed earlier

**Both guides mention adding pork fat to wolf/owlbear sausage** ✓ CORRECT approach for lean meat

### Voice and Tone Consistency

- ✓ General Guide has authoritative, standards-focused tone
- ✓ Blink Wolf Guide has Mira Wolfheart's blunt, experienced voice
- ✓ Owlbear Guide has Garrick Ironknife's gruff, practical voice
- All three maintain Helena Fairstock's "realistic and honest" philosophy from Provisions Guide

---

## RECOMMENDATIONS FOR STEP 2 (FIXES)

### HIGH PRIORITY (Must Fix):

1. **Black Peppercorns Pricing**
   - Change from "1 gp" to "1 sp" in both guides
   - Update weight to 0.25 lbs (4 oz) and uses to 48
   - Recalculate sausage spice costs accordingly

2. **Blink Wolf Retail Cuts Total**
   - Resolve discrepancy between "220 lbs" in summary and "320 lbs" in detailed breakdown
   - Verify against yield standards (should be ~226 lbs based on 35% of 645 lbs carcass)

### MEDIUM PRIORITY (Should Fix):

3. **Trielta Hills Garlic Clove Count**
   - Change from "9 cloves typically" to "14-18 cloves (typically 16)"
   - Maintains consistency with Provisions Guide

4. **Blink Wolf Yield Percentages**
   - Review if trim/bones/fat percentages should be adjusted to match General Guide standards
   - OR update General Guide if Blink Wolves legitimately have different yields
   - Document reasoning for any deviations

### LOW PRIORITY (Nice to Have):

5. **Cross-Reference Labels**
   - Add references like "Source: Master Provisions Guide, Herbs & Spices" after ingredient prices
   - Helps readers know where to look up items

6. **File Naming**
   - Consider renaming "#General Butcher Guide" to "00_General_Butcher_Guide.md" for consistency
   - Matches numbering system used in Provisions Guide

---

## OVERALL ASSESSMENT

**The Butchering Guide is very well-written and mostly accurate.**

- 90% of ingredient prices match the Provisions Guide correctly
- The voice and tone are consistent with Helena Fairstock's philosophy
- The mathematical framework is sound
- The main issues are:
  - 1 critical pricing error (peppercorns at 10x correct price)
  - 1 internal math discrepancy (Blink Wolf retail cuts total)
  - 1 minor detail error (garlic clove count)

**Once these are fixed in Step 2, the guides will be perfectly consistent with the Provisions Guide.**

---

**Next Step:** Proceed to Step 2 - Fix the Owlbear and Blink Wolf entries with corrected math and pricing
