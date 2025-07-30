# Frequently Asked Questions (FAQ)

Below are some common questions and answers regarding CrystalEMR.

## Appointment Management

??? question "How do I create a new appointment?"
    1. Go to the **Appointments** section.
    2. Click on **New Appointment**.
    3. Fill in patient details, date, and time.
    4. Click **Save** to confirm the appointment.

??? question "Can I reschedule or cancel an appointment?"
    Yes, you can reschedule or cancel an appointment by:
    - Navigating to the **Appointments** section.
    - Clicking on the appointment you wish to change.
    - Selecting **Reschedule** or **Cancel**.

## Billing & Payments

??? question "How do I generate an invoice?"
    1. Go to the **Billing** section.
    2. Click **New Invoice**.
    3. Select the patient and add services or medicines.
    4. Click **Generate Invoice**.

??? question "What payment methods are supported?"
    CrystalEMR supports payments via:
    - Cash
    - Credit/Debit Cards
    - UPI (for supported regions)

## General Questions

??? question "How do I log in to CrystalEMR?"
    To log in, visit the [login page](https://your-login-url.com) and enter your credentials. If you forget your password, click on **Forgot Password?** to reset it.

??? question "How can I reset my password?"
    If you forgot your password, click on **Forgot Password?** on the login page. Enter your registered email address and follow the instructions sent to your email.

??? question "What are the minimum system requirements for using CrystalEMR?"
    CrystalEMR works on modern web browsers such as Chrome, Firefox, and Edge. For the best experience, we recommend using Google Chrome on a device with at least 4GB of RAM.


## Token Creation

??? question "What are toknes? Why are they required"
    Tokens are basically arrival time stamps and patients are arrived into the OPD by creating a token each time they come for OPD. 
    They are required to keep track of arrival time and the time spent by patient in the OPD/OT on that day. It’s a very essential OPD tool for patient management.
    Note: This is often confused with **Patient ID/MRD Number**. 
    Please note Patient ID is constant once generated.
    **Token number is different** for each visit of patient, as token is generate per visit.

??? question "How do I Create a blank token and assign patient to a blank token?"
    1. Creating a Blank Token : 

        - On home-screen of Crystal App, press on **NEW TOKEN** button.\n
        - A pop-up window will appear, press on **YES** to create new token.\n
        - Blank token will be visible on home screen.\n
    
    2. Assigning Patient to Blank Token:

        - Select newly created blank token
        - 'Search Contact' window will appear
        - For existing patient, search the name and select the patient.
        - For new Patient press on " + " symbol on top right, enter Name and mobile number.
        - Save the details.

??? question "What is check in and check out?"
        - Check-in Time   = Time of token generated
        - Check-out Time= Time of patient leaving the clinic

??? question "Once Token is made, can we cancel it? and how to hide it from the home screen? will it be counted towards total token count?"
        Once the token is made, we cannot delete it.

        Tokens cannot be Cancelled. 

        In case of assigned tokens, just Checkout the token. 

        In case of blank token, nothing can be done. In both case, apply filter "Active tokens only" 
        to hide blank tokens and check-out tokens.. 

        Yes, in unfiltered view, that token will be counted.


---

For more details, visit our [Support Page](https://crystalemr.freshdesk.com).
