# Webcam Piano - Frame Differencing Interaction

This project implements a webcam-based interaction using frame differencing to detect movement and trigger graphical effects on the screen. The assignment is based on Memo Akten's WebCam Piano 2.0 concept.

## Overview

The project utilizes the p5.js library to capture webcam input, perform frame differencing to detect movement, and visualize the detected motion using a grid of graphical elements. The main features and steps of the assignment include:

- **Frame Differencing**:
  - Utilizes frame differencing to detect changes between consecutive frames from the webcam input.
  - Compares pixel values between the current and previous frame to identify areas of movement.

- **Grid Visualization**:
  - Implements a grid structure where each cell represents a graphical element.
  - Activates specific cells in the grid based on detected movement, creating a visual representation of motion.

- **Blur Filter**:
  - Applies a blur filter to reduce noise and smoothen the input image before processing.
  - Enhances the accuracy of motion detection by minimizing false positives.

- **Graphics Customization**:
  - Provides opportunities for extending the project by customizing graphical elements within the grid.
  - Enables secondary effects or animations triggered by detected motion.

- **Sound Integration (Extension)**:
  - Extends the project by integrating sound playback based on the activated grid cells.
  - Uses p5.js sound library to generate audio feedback corresponding to detected motion.

## Development Steps

The assignment progresses through several development steps, each building upon the previous:

1. **Frame Differencing Setup**:
   - Renames and refactors code from a background subtraction example to utilize frame differencing effectively.

2. **Grid Visualization**:
   - Integrates the `Grid` class to manage graphical elements based on detected movement.

3. **Noise Reduction**:
   - Implements blur filtering and image resizing techniques to reduce noise and optimize performance.

4. **Graphics Customization (Extension)**:
   - Extends the project by customizing graphical elements and implementing secondary effects or animations.

5. **Sound Integration (Extension)**:
   - Integrates sound playback using the p5.js sound library to provide audio feedback synchronized with visual effects.

## Assignment Completion

The completion of the assignment is assessed based on the successful implementation of frame differencing, grid visualization, noise reduction, and optional extensions involving graphics customization and sound integration. Each step contributes to a comprehensive webcam interaction project inspired by Memo Akten's work.

---

This README provides an overview of the Webcam Piano - Frame Differencing Interaction project, detailing its purpose, features, and development steps. It outlines the core concepts and extensions involved in creating a dynamic and interactive webcam-based application using p5.js.

For further enhancements and customization, I will consider exploring additional graphical effects, advanced motion detection techniques, or integrating other external libraries to enrich the user experience.

