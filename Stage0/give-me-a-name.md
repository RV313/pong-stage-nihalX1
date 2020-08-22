# User Interface

## Feature

This module explains all the changes based on the UI.

## Acceptance Criteria

### Scenario: the User Interface is updated for ball position

Given the game is started and the system conditions are working fine

When the ball position moves using the move function

Then UI renders ball with the new position.

### Scenario: the User Interface is updated  for paddle position

Given the game is started and the system conditions are working fine

When the paddle position moves via  move function

Then the paddle position is updated in the UI

### Scenario: the UI is updated for the Score Board

Given the game is started and the system conditions are working fine

When the ball collides with the left wall or right wall

Then The Score Board is updated based on the player who scored.
UI Score system is also updated.