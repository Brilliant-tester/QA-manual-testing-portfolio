# Login Test Cases

## TC_001 – Login with valid credentials
**Pre-condition:** User is on login screen and has stable internet  
**Steps:**
1. Enter valid email
2. Enter valid password
3. Tap login

**Expected Result:** User is logged in and redirected to home screen  
**Actual Result:** User logged in and saw home screen  
**Status:** Pass

---

## TC_006 – Invalid email format
**Steps:**
1. Enter "briegmail.com"
2. Enter valid password
3. Tap login

**Expected Result:** Error message should be displayed  
**Actual Result:** User was able to login  
**Status:** Fail  
**Severity:** High
