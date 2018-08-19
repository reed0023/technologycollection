## appdApp

### Summary:

The following documentation serves as a first draft for development of an application for an Innovative Technological Agreement to comply with proposed regulation aimed at assiting new technologies in registering a new type of digital legal personality with its own set of inherent rights including but not limited to the right to exist, own assets, conduct business, enage with banks etc. Deliverables, dates, features, and functions are subject to change, based on the needs of the dApp. Please contact @reed0023, @tomtom87, or @jtianelli with any questions or concerns. 

#### Name: 

appdApp, the dApp for Applications (working title)

#### Offered by: 

The Technology Collection

#### Abstract:

AppdApp is a modular dApp that allows DAOs or other Technology Arrangements to create their own Question and Answer Applications (use cases may include, but are not limited to: contracts, registrations, applications, surveys, grants, etc.). Once a DAO’s Application is published, it may be filled out by the Organization. Completed Applications are converted into Smart Contracts and deployed to the Ethereum Virtual Machine. The specific use case of appdApp for our organization will be to create the ability described in the summary with regards to innovative tech: the ability to register as an innovative technology arrangement in Malta an EU Member State.

Developer Needs:

 - React Components for Application Creation UI
 - UX Considerations WIP

UX Benchmark: 

 - Google Forms

High Level Application Stage Flowchart:

New Application → Unpublished Application → Published Application → Completed Application

Desired Application Components:

1. Applications Homepage	
  - Create New Application → Application Builder
    - Edit Title
  - Add Page (one page default)
    - Edit Title
  - Delete Page
    - Are you sure?
      - OK/Cancel
  - Add Question
    - Text field
      - Character limit TBD
  - Delete Question
    - Are you sure?
      - OK/Cancel
  - Edit Question
    - OK/Cancel
  - Add Answer
    - Text Input field
  - Character limit TBD
    - Integers
    - Date
    - Currency
    - Multiple Choice - Radio Buttons
      - Select One
      - Select Multiple
    - Signature
    - Initial
  - Next/Previous Page
    - Skip to specific page
  - Edit Unpublished Application → Application Builder
  - Delete Unpublished Application
    - Are you sure?
      - OK/Cancel
 - View Published Application
 - Fill Out Application (from the User’s/DAO’s perspective)
    - Save Progress
    - Next/Previous Page
      - Skip to specific page
    - Publish
      - Are you sure?
        - OK/Cancel
  - View Completed Application
  - Smart Contract Details
  - TBD
