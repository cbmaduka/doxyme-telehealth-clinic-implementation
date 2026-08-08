
# Patient Telehealth Workflow

## Overview

A complete patient journey was tested in the CarePoint Virtual Clinic to verify that the Doxy.me configuration could support the process from virtual check-in through completion of a video consultation.

A test participant was used throughout the workflow.

## Workflow

The tested patient journey followed these steps:

1. Patient receives the appropriate Doxy.me consultation link
2. Patient accesses the virtual consultation room
3. Patient completes the required check-in process
4. Patient enters the virtual waiting room
5. Provider sees the waiting participant on the clinic dashboard
6. Provider starts the video consultation
7. Patient and provider connect through the Doxy.me video interface
8. Provider can access available clinical tools during the consultation
9. Consultation is completed
10. Completed session appears in the clinic's session history and analytics

## Patient Check-In

The patient-facing workflow provides a simple entry point into the virtual clinic.

After accessing the consultation room and completing the required check-in steps, the test participant successfully entered the waiting queue.

## Provider Waiting Queue

The provider dashboard displayed the participant under the **General Consultation** room.

From the waiting queue, the provider could view the participant and initiate the consultation using the **Start video call** option.

This allows the provider to control when the patient enters the active consultation.

## Video Consultation

The workflow was tested through an actual video connection between the provider and the test participant.

The consultation interface provided controls for:

- Camera
- Microphone
- Participant management
- Chat
- Clinical applications
- Additional session controls
- Ending the consultation

## In-Session Workflow

During an active consultation, the provider could access configured clinical applications directly from the call interface.

This demonstrated that the virtual visit can extend beyond basic video communication and support additional consultation activities within the same workflow.

## Session Completion

After the video consultation ended, the completed session was reflected in Doxy.me's History section.

Session activity was also captured within Analytics, providing information such as:

- Total sessions
- Session minutes
- Average session time

## Workflow Result

The test successfully demonstrated an end-to-end telehealth workflow:

**Patient Access → Check-In → Waiting Room → Provider Queue → Video Consultation → Clinical Tools → Session Completion → History and Analytics**

The implementation confirms that the configured environment can support an organized virtual consultation process from patient arrival through session tracking.
