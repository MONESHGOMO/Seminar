# JavaFX Seminar: Events and Controls

## Event Basics
- **What are Events?**
  - Actions or occurrences detected by the program (e.g., mouse clicks, key presses).
  
- **Event Handling**
  - Process of responding to events using event handlers (functions/methods).

- **Adding Event Handlers**
  - Use `setOnAction()`, `setOnMouseClicked()`, `setOnKeyPressed()`, etc.
  
  ```java
  Button button = new Button("Click Me");
  button.setOnAction(event -> {
      System.out.println("Button clicked!");
  });