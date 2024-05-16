# Bankist | When Banking Meets Minimalist

This project implements a minimalist banking website using advanced JavaScript concepts.This project is implemented as an assignment in the course Javascript(Zero to Hero) by Jonas(Udemy Instructor). Below is a summary of the key concepts used in the project.

## Table of Contents

1. [Modal Window](#modal-window)
2. [Button Scrolling](#button-scrolling)
3. [Page Navigation](#page-navigation)
4. [Tabbed Component](#tabbed-component)
5. [Menu Fade Animation](#menu-fade-animation)
6. [Sticky Navigation](#sticky-navigation)
7. [Reveal Sections on Scroll](#reveal-sections-on-scroll)
8. [Lazy Loading Images](#lazy-loading-images)
9. [Slider Component](#slider-component)
10. [Additional Concepts](#additional-concepts)

## Modal Window

### Concepts Used:
- **Event Listeners:** Attach events to buttons to open and close the modal.
- **Class Manipulation:** Add or remove classes to show or hide the modal.

## Button Scrolling

### Concepts Used:
- **Element.getBoundingClientRect():** Get the position of elements.
- **window.scrollTo():** Scroll to a specific position.
- **Element.scrollIntoView():** Smooth scrolling to an element.

## Page Navigation

### Concepts Used:
- **Event Delegation:** Attach a single event listener to a parent element and use it to manage events for multiple child elements.
- **Event.preventDefault():** Prevent default link behavior.

## Tabbed Component

### Concepts Used:
- **Event Delegation:** Handle events for multiple child elements through a single parent.
- **Element.closest():** Find the nearest ancestor that matches a selector.
- **Guard Clauses:** Return early from a function if a condition is not met.
- **Class Manipulation:** Add or remove classes to update the UI.

## Menu Fade Animation

### Concepts Used:
- **Event Binding with Arguments:** Using the `bind` method to pass additional arguments to an event handler.
- **Element Closest:** Determine the closest parent element that matches a selector.
- **Style Manipulation:** Dynamically change the opacity of elements.

## Sticky Navigation

### Concepts Used:
- **Intersection Observer API:** Observe changes in the intersection of a target element with an ancestor element or with a top-level document’s viewport.
- **Class Manipulation:** Add or remove classes based on intersection status.

## Reveal Sections on Scroll

### Concepts Used:
- **Intersection Observer API:** Reveal elements as they enter the viewport.
- **Class Manipulation:** Add or remove classes to show or hide sections.

## Lazy Loading Images

### Concepts Used:
- **Intersection Observer API:** Load images as they enter the viewport.
- **Data Attributes:** Use custom data attributes to store the path of the high-resolution image.
- **Event Listeners:** Wait for the image to load before removing placeholder styles.

## Slider Component

### Concepts Used:
- **Element Transformations:** Use CSS transformations to create a sliding effect.
- **Event Listeners:** Navigate slides using buttons and keyboard events.
- **Dynamic Dot Navigation:** Create and activate dots corresponding to slides.

## Additional Concepts

### DOM Manipulation
- **Selecting Elements:** Use methods like `querySelector`, `getElementById`, `getElementsByClassName`, etc.
- **Creating and Inserting Elements:** Dynamically create and insert elements into the DOM.
- **Deleting Elements:** Remove elements from the DOM.

### Styles, Attributes, and Classes
- **Inline Styles:** Modify the inline styles of elements.
- **Computed Styles:** Access the computed styles of elements.
- **CSS Custom Properties:** Use and modify CSS variables.
- **Attributes:** Get and set standard and custom attributes of elements.
- **Class Manipulation:** Add, remove, toggle, and check for classes on elements.

### Event Propagation
- **Event Bubbling and Capturing:** Understand and utilize the phases of event propagation.
- **Event Delegation:** Leverage event bubbling to handle events efficiently.

### DOM Traversing
- **Navigating the DOM:** Traverse the DOM to find parent, child, and sibling elements.

### Lifecycle DOM Events
- **DOMContentLoaded:** Execute code when the initial HTML document is completely loaded and parsed.
- **Load:** Execute code when the entire page (including all dependent resources) is fully loaded.
- **Beforeunload:** Execute code when the document is about to be unloaded.

---

