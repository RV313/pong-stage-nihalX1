# Paddle

## Feature

This module explains all the changes based on the Paddle.

## Acceptance Criteria

### Scenario: Player wants to move paddle

Given the game is started and the system conditions are working fine

When the player wants to move paddle

Then move() method of paddle is executed for that Player.

### Scenario: Paddle checks if collided with ball when ball updates position

Given the game is started and the system conditions are working fine

When the position of the ball is updated.

Then paddle checks if it has collided with Ball.
