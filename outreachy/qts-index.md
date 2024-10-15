# QuickStatements 3.0 - HomePage Feature Documentation
## Table of content
- [QuickStatements 3.0 - HomePage Feature Documentation](#quickstatements-30---homepage-feature-documentation)
  - [Table of content](#table-of-content)
  - [Overview](#overview)
  - [Elements](#elements)
    - [1. **Header Section**](#1-header-section)
    - [2. **Main Content Section**](#2-main-content-section)
    - [3. **Batch Search Section**](#3-batch-search-section)
  - [Notes](#notes)
  - [Additional Details](#additional-details)

## Overview

This document explains the features available on the home page
of the QuickStatements 3.0 web application. The design is simple 
and primarily focuses on user accessibility and ease of use.

![Homepage Overview](screenshot2.jpg)
*Overview of the QuickStatements 3.0 homepage.*

## Elements

### 1. **Header Section**

- **QuickStatements 3.0**: this button is displayed at the top left corner
    of the application in bold, blue text and dims a little when 
    hovered upon by a mouse pointer.
  - URL: http://localhost:8765
- **Navigation Links**:
  - ***New Batch***: Navigates to the section where users can create
        a new batch.
    - URL: http://localhost:8765/batch/new/
  - ***Last Batches***: This button points nowhere currently, however,
    it's supposed to direct users to a view of the most recently processed
    batches but this feature is yet to be implemented.
    - URL: Currently not linked to any url yet
  - ***Git***: This button links to the original github repository hosting
    the source code and other related resources for this application.
    - URL: https://github.com/WikiMovimentoBrasil/quickstatements3

- **User Information**:
  - Shows the current logged-in user (e.g **User:Okay-michael**).
    - URL: Currently not linked to any url yet
  - **Your last batches**: this button is currently a placeholder. In the
    future, it will allow users to quickly view their submitted batches.
    This functionality is still under development.
    - URL: Currently not linked to any url yet

### 2. **Main Content Section**

- **Welcome Message**: The page displays a greeting message, **Welcome to
    QuickStatements 3.0**, effectively introducing the user to the application.
- **Primary Action Button**:
  - A large blue button labeled **New batch** for users to create a
    new batch easily. This is the most prominent button on the interface
    and also dims a little when hovered upon with a mouse pointer.
    - URL: http://localhost:8765/batch/new/

### 3. **Batch Search Section**

This section allows users to search for specific batches by either batch ID
or username. It consists of:

- **Batch ID Input Field**:
  - A text input box with a placeholder, **Batch ID...**, where users can
    enter the batch ID they want to search.
  - A blue button labeled **See batch details** that fetches and displays
    details about the batch when clicked.

- **Username Input Field**:
  - A text input box with a placeholder, **Username...**, where users can
    enter the username to search for batches associated with that user.
  - A blue button labeled **See batches by user** that displays all 
    batches related to the entered username.

## Notes

- The interface prioritizes clarity and functionality, with all essential
    actions (creating and searching batches) easily accessible through
    prominent buttons.
- The header provides quick navigation links, improving user accessibility
    and streamlining interaction.
- This document provides an overview of the QuickStatements 3.0 homepage's
  current features. Some functionalities, such as user information links
  and batch views, are planned for future development and not yet
  implemented. We will continue to enhance the application with these
  additional features in upcoming updates.

## Additional Details

- **Color Scheme**: The interface uses a clean white background with blue
    elements (buttons, text) to highlight actionable items
    and navigation elements.
- **Responsiveness**: The page layout is designed to accommodate different
    screen sizes, ensuring usability across various devices.

[Back to Top](#quickstatements-30---homepage-feature-documentation)
