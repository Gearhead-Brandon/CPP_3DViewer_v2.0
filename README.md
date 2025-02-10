# 3DViewer v2.0 - 3D Model Viewer Application

## Contents

1. [Introduction](#introduction)
2. [Information](#information)
3. [Implementation Details](#implementation-details)
   1. [Part 1: 3DViewer v2.0](#part-1-3dviewer-v20)
   2. [Part 2: Bonus - Settings](#part-2-bonus-settings)
   3. [Part 3: Bonus - Record](#part-3-bonus-record)

## Introduction

In this project, you will develop an application to view 3D wireframe models in C++. The application should support loading, transforming, and rendering wireframe models from an `.obj` file.

## Information

The application should follow object-oriented programming principles and utilize design patterns, such as MVC (Model-View-Controller), and others like facade, strategy, and command. The user interface should allow interaction with 3D models and provide real-time transformations.

**Design patterns**: MVC, facade, strategy, command.
**Performance**: The program should handle large models with up to 1,000,000 vertices without interface freezing.

## Implementation Details

### Part 1: 3DViewer v2.0

- **Language**: C++17
- **Libraries**: Choose any GUI library (GTK+, Qt, CEF, JUCE, etc.)
- **Functional Requirements**:
  - Load wireframe models (obj files with vertices and surfaces).
  - Implement affine transformations: translation, rotation, scaling.
  - Display a single model at a time, with model details (file name, number of vertices, edges).
  - Provide UI for file selection, transformations (translation, rotation, scaling).
  - The program must be responsive, handling models with up to 1 million vertices without freezing.

- **Design**:
  - MVC architecture with separate domains for UI and business logic.
  - Use at least three design patterns for modularity and maintainability.

### Part 2: Bonus - Settings

- **Projection Type**: Allow switching between parallel and central projections.
- **Model Settings**: Customize edge type (solid, dashed), color, thickness, and vertex display settings.
- **Background**: Allow selecting the background color.
- **Persistence**: Settings should persist between program restarts.

### Part 3: Bonus - Record

- **Image Capture**: Enable saving rendered images in BMP or JPEG formats.
- **Screencasting**: Allow recording GIF screencasts (640x480, 10fps, 5s) of the model transformations.
