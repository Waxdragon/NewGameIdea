# Meeting Action Points

## Context
This meeting discusses the direction for product development, emphasizing user feedback and innovation after technical implementation. The main topic revolves around replacing the "Bomb Squad" challenge with a new game, specifically a multiplayer car racing game, and exploring various layers of complexity and strategy that can be added to a simple baseline.

## Confirmed or Directly Requested Actions

| ID | Action | Owner | Timing/Deadline | Evidence/Timestamp |
|---|---|---|---|---|
| 1 | Prepare a replacement game for the "Bomb Squad" challenge so it can be used for user feedback. | Speaker 2 / game team | To be decided | 2:37–3:26 |
| 2 | Pull the correct code before continuing the car-game discussion. | Speaker 2 | During the meeting | 1:39–1:49 |
| 3 | Stop the recording. | Speaker 2 | End of meeting | 12:37 |
| 4 | Preserve or commit the transcript of the discussion for reference. | Speaker 2 / team | After recording | 1:15–1:36, 12:41 |

## Proposed Product/Game Work

1.  **Multiplayer Car Race Baseline:**
    *   Assume a car race game with two cars.
    *   Each car operated by a team (e.g., team of four).
    *   Car movement requires synchronized input from all team members (e.g., pressing a "speed button" simultaneously). If one person fails, the car does not move or moves less. (0:36, 3:36, 5:20)
    *   Car moves in a straight line from left to right, similar to the Chrome dinosaur game. (4:43)
    *   Two cars visible on screen, one above the other. (5:10)
    *   Competition: Which car reaches the finish line first. (5:05)
    *   Coordination: All team members must press the spacebar simultaneously to move the car forward by a certain unit (e.g., two tiles/units). (5:27)
    *   Partial input (e.g., three out of four members) results in less movement (e.g., one unit). (5:36)
    *   Two members input: Car does not move. (5:42)
    *   At 05:45, the transcript says the car would move backward when all four cooperate. Treat this as an item requiring clarification before implementation, because the intended movement rule is unclear.
    *   Opponent car movement is visible, allowing for strategic decisions. (6:18)

2.  **Adding Complexity - Boosts/Power-ups:**
    *   Introduce "boosts" or "power-ups" to make the game more interesting. (4:07, 6:37)
    *   Examples: boosted speed, obstacles. (4:07)
    *   Power-ups appear on screen for a limited time (e.g., three seconds). (7:10)
    *   Teams must type a specific letter (e.g., 'B' for Boost, 'S' for Skid) associated with the power-up. (7:18)
    *   The team whose players (e.g., 70% of the team) type the key within the time limit gets the boost. (7:30)
    *   Boosts are applied automatically (e.g., car moves forward). (7:35)
    *   **Proposed Enhancement:** Allow players to collect and save boosts to use strategically later. (8:00)
    *   Example: A "2X" boost for points or speed, to be used at an opportune moment. (8:15)
    *   **Proposed Enhancement:** Introduce boosts with varied impacts (e.g., one boost moves opponent car two lanes forward but your car ten lanes forward). (11:30)

3.  **Player Attribution and Feedback:**
    *   Display player names or images to show who is performing actions (e.g., typing keys for boosts). (9:50)
    *   Show a small message on screen indicating which player successfully activated a boost (e.g., "Subramani tested," "Prasanth tested"). (10:05)

4.  **Game Design Philosophy:**
    *   Focus on user feedback and innovation after technical implementation. (2:40)
    *   The goal is to understand how different layers of interaction (multiplayer, boosts, strategy) transform a simple game into an interesting one. (10:15, 10:30, 10:59)
    *   The exercise is to learn what impacts the game, what to add, and what to remove, rather than just copying existing popular games. (10:30)

## Follow-ups and Open Decisions

1.  The exact team size for the car game (e.g., 4v4, 10v10) needs to be decided. (0:45)
2.  The specific mechanics of car movement when four members input simultaneously (currently stated as "moves backward") needs clarification or re-evaluation. (5:45)
3.  Speaker 1 may provide a sample/demo of the game. This was offered as a possible follow-up, not a firm commitment. (12:25)
4.  Speaker 1 said further changes would be discussed and planned in the evening after the 3 o'clock meeting. (12:30)
5.  Confirm whether the game should use four-person teams, ten-person teams, or another team size. (0:36)
6.  Confirm the exact movement and scoring rules, especially the unclear four-player behavior noted at 05:45. (5:45)
