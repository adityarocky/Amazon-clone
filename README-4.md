# Web_Development_with_React_and_Python_Flask_Long_Term_Module_4_Assignment_2

# IELTS Speaking Test Platform - Question Display Component

## Objective

Develop a reusable QuestionCard React component to dynamically fetch and display test questions. This component will serve as the primary interface for test takers to view their questions.

## Scenario

The IELTS Speaking Test platform requires a flexible component to display test questions fetched from a backend API. Your task is to create the QuestionCard component, ensuring it is dynamic, reusable, and capable of displaying question text and additional metadata.

## Requirements

1. **Component Functionality**:

   - Fetch test questions from a backend API endpoint (e.g., /api/questions).
   - Display the question text, question number, and any additional metadata (e.g., question category).

2. **Reusability**:

   - Pass data to the component via props for flexibility in different contexts.

3. **Dynamic Rendering**:

   - Dynamically update the question content based on the API response.

4. **Styling**:

   - Add basic styles for visual clarity and responsiveness.

5. **Integration**:
   - Render the QuestionCard component in the TestTakerDashboard component.

## Deliverables

- A React file (QuestionCard.tsx) containing the implemented component.
- An updated TestTakerDashboard.tsx file integrating the QuestionCard.
- Backend endpoint setup for fetching questions (if applicable).

## Submission Guidelines

1. Submit the QuestionCard.tsx and updated TestTakerDashboard.tsx files.
2. Include sample API responses and screenshots or recordings of the component in action.

# Evaluation Criteria

1. **Functionality (40%)**:
   - The component dynamically fetches and displays questions.
   - Handles edge cases like loading states or API errors.
2. **Reusability (30%)**:
   - Component accepts props for question data and integrates seamlessly.
3. **Styling (20%)**:
   - The component is visually appealing and responsive.
4. **Submission Completeness (10%)**:
   - Includes all required files and testing evidence.
