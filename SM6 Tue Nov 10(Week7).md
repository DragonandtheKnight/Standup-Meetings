## Key Takeaways

- This is the 6th stand-up meeting, held on Tuesday, November 10th (Week 7), and also the kickoff meeting for Sprint 2.
- Each member reported what they completed in Sprint 1 and confirmed their work plan for Sprint 2.
- The parameters of the card and deck system are under discussion; the hand limit and the deck limit may be increased.
- The combat module (owned by Eric) has many interface dependencies on the UI and the card system, and needs collaboration across members.
- The handling of duplicate cards needs to be decided.

---

## Team Updates

| **Speaker** | **Completed** | **In Progress** | **Plan** | **Blockers** |
|-------------|---------------|-----------------|----------|--------------|
| **Lizi**    | - Main menu UI, settings, game over screen and key hints (PR #42, open)- Basic card mock UI | N/A | - Implement the map UI- Implement the battle UI (#15) | - Needs the combat module header files from Eric- Needs the map module header files before the UI implementation can move forward |
| **Nathan**  | - Updated the Player class based on the team's review comments (PR #21, merged; closes #12 and #13)- Added maximum HP increase- Added maximum energy management- Added block reset- Added total gold tracking- Fixed the bug in healing the player | N/A | - Implement the Shop, Rest, Event and Entertainment levels (#44) | N/A |
| **Tony**    | - Mostly completed the basic implementation of the card and deck system (PRs #40 and #41, merged)- Implemented three different card piles- Implemented drawing cards, getting the hand, and destroying/discarding cards- Completed the basic card functions (get cost, get value, etc.)- Started writing some of the functions for adding effects | - Discussing with teammates to finalize the deck parameters | - Implement different types of cards and card effects (#8)- Work with Eric on how card effects apply in combat and how multi-turn effects are handled | - The handling of duplicate cards needs to be decided |
| **Ink**     | - Submitted PR #43 for basic floor navigation and map generation (#6) | - Fixing the issues raised in the PR #43 review | - Implement level generation- Complete the branching structure and node connection logic of the floor map | - PR #43 has review issues that need to be fixed |
| **Eric**    | - Completed the Enemy class (PR #39, merged; closes #10) | N/A | - Develop the combat module code (#11)- Provide the combat class header files to teammates as early as possible | - The combat module interacts heavily with several classes, so the interface design needs thorough discussion with teammates |

---

## High Risks

- **Combat module interface dependencies**: Lizi's UI implementation is blocked until Eric provides the header files for the combat class and the map class.
- **High complexity of cross-module collaboration**: The combat module involves interactions between several classes, so Eric needs to align the interface design with multiple members.
- **Duplicate card handling undecided**: Tony pointed out that duplicate cards may appear in the same run, and no handling approach has been decided yet.

---

## Action Items

- **Lizi**
    - [ ] Implement the map UI (#15)
    - [ ] Implement the battle UI (#15)
    - [ ] Work with Eric on the UI callbacks and the combat call logic
- **Nathan**
    - [ ] Implement the Shop, Rest, Event and Entertainment levels (#44)
- **Tony**
    - [ ] Implement different types of cards and their effects (#8)
    - [ ] Work with Eric on how card effects apply in combat and how multi-turn effects are handled
    - [ ] Talk with teammates to finalize the hand limit and deck limit parameters
    - [ ] Decide the handling of duplicate cards
- **Ink**
    - [ ] Fix the issues in the map generation PR (#43)
    - [ ] Implement level generation (#6)
    - [ ] Complete the branching structure and node connection logic of the floor map
- **Eric**
    - [ ] Provide the combat class header files as early as possible to unblock Lizi's UI development
    - [ ] Align the combat module interface design with each member
    - [ ] Develop the core code of the combat module (#11)
