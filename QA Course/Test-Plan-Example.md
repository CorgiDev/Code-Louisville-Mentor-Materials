# GoodMaps Explore Test Plan

## Product Information

Fill in any fields applicable to the test. This is some of the less technical information about the product and who owns it.

- **Product Name:** GoodMaps Explore
- **Product Version:** 
  - **Android Version:** 1.8.1.97 v707 Internal
  - **iOS Version:** 1.8.1.6 v1205 Internal
- **Product Owner/Vendor:** GoodMaps
- **Location:** Mobile app
- **Additional Notes:**
  - *Add any additional notes about the product here. Could also include information on who the report is for if you want.*

### Testing Information

Fill in any fields applicable to the test. These items deal with who is testing, the scope of the test, and information necessary to perform the test.

- **Test Date(s):** 10/12/2022
- **Tester Name:** Erissa Duvall
- **Tester's Company:** GoodMaps
- **Tester Email:** PretendEmail@Corgidev.com
- **Access Information (if applicable)**
  - **Credentials:** N/A
  - **Additional Access Information:**
- **Testing Scope:** Testing the Getting Warmer feature Outdoors on a mapped Campus.
- **Assumptions:** Tester on a campus map like UofL.

### Test Environment

Fill in any fields applicable to the test. These are things specific to the testing environment.

- **Browser:** N/A
- **Operating System (OSX, Windows, Android, iOS):**
  - iOS 15.5
  - Android 13 (TP1A.221005.002)
- **Test Device Model/Type:**
  - iPhone 12 Pro (3H535LL/A)
  - Pixel 5 (MP1.0)

## Test Cases

### Test Case 1

- **Test Steps:**
  1. Enter the campus when prompted by the app.
  2. Set an unmapped, building/location as your getting warmer destination.
  3. Follow the Getting Warmer prompts to your destination.
- **Expected Result:** 
  - Distance and direction should update as I approach the Getting Warmer destination. Direction will update in 15 degree increments.
- **Actual Result:** 
  - *What actually happened when you completed the test? Was it the same as the expected result?*

### Test Case 2

- **Test Steps:**
  1. Enter the campus when prompted by the app.
  2. Set a mapped, building/location as your getting warmer destination.
  3. Follow the Getting Warmer prompts to your destination.
- **Expected Result:** 
  - Distance and direction should update as I approach the Getting Warmer destination. Direction will update in 15 degree increments.
- **Actual Result:** 
  - *What actually happened when you completed the test? Was it the same as the expected result?*

### Test Case 3

**Not necessary for test plan, but doing to see if I can spot any issues.**

- **Test Steps:**
  1. Enter the campus when prompted by the app.
  2. Approach a mapped building on campus.
  3. Enter the building once prompted.
  4. Set an indoor location on the same floor as you as your Getting Warmer destination.
  5. Get your location when prompted using CPS.
  6. Observe the "Getting Warmer destination" portion of the "My Location" screen.
  7. Follow the Getting Warmer prompts to your destination.
  8. Occassionally reobtain your location with CPS by tilting the device down and back up.
- **Expected Result:** 
  - Distance and direction should update as I approach the Getting Warmer destination. Direction will update in 15 degree increments.
    - You may need to force an update to your recognized location by tilting the phone down and then back up to reset CPS.
  - My Location should display distance and direction to Getting Warmer.
  - Floor should not be displayed since you are on the same floor as your Getting Warmer Destination.
- **Actual Result:** 
  - *What actually happened when you completed the test? Was it the same as the expected result?*

### Test Case 4

- **Test Steps:**
  1. Enter the campus when prompted by the app.
  2. Approach a mapped building on campus.
  3. Enter the building once prompted.
  4. Set an indoor location on a different floor as you as your Getting Warmer destination.
  5. Get your location when prompted using CPS.
  6. Observe the "Getting Warmer destination" portion of the "My Location" screen.
  7. Follow the Getting Warmer prompts to your destination.
  8. Occassionally reobtain your location with CPS by tilting the device down and back up.
  9. Reobtain your location whenever you switch to being on the same floor as the Getting Warmer Destination.
- **Expected Result:** 
  - *While on a different floor from your Getting Warmer destination*, the floor should be listed and no distance or direction.
  - *Once on the same floor as your Getting Warmer Destination*, distance and direction should update as I approach the Getting Warmer destination.
    - Direction will update in 15 degree increments.
- **Actual Result:** 
  - *What actually happened when you completed the test? Was it the same as the expected result?*