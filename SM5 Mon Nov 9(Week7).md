## Key Takeaways

- This is the 5th SANA meeting, held on November 9th.
- Sprint 1 work has been largely completed, with code merged into main; Sprint 2 planning is pending due to Nathan's absence.
- Enemy code (5 monster types) is complete and merged into main.
- Card and deck system implementation is complete with TDD tests uploaded to GitHub.
- Floor map and level navigation logic have been implemented.
- UI mock and random number generation are complete; UI implementation is ongoing.
- Pull request reviews were conducted; Nathan's PR requires additional comments and unit tests.

---

## Team Updates

| **Speaker** |                                                                        **Completed**                                                                         |      **In Progress**       |                                                        **Plan**                                                         |                            **Blockers**                            |
|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| **Lizi**    | - UI mock- Random number generator- Main menu and settings preview- Reviewed PRs from Nathan, Tony, and Eric                                                 | - Map UI implementation    | - Continue UI implementation- Conduct testing- Follow up with Nathan on PR comments and unit tests for player class     | - Nathan was absent; Sprint 2 planning meeting has not yet started |
| **Eric**    | - Enemy code for 5 monster types (slime, goblin, shaman, giant, dragon)- Code merged into main                                                               | N/A                        | - Begin working on combat code- Break down combat code into smaller tasks- Study card code and player code dependencies | - Combat code is complex and depends on card code and player code  |
| **Tony**    | - Implemented all basic functions in CARD.CC- Implemented deck system- Completed TDD test files for CARD and DECK- Uploaded all code to GitHub               | N/A                        | - Implement full comprehensive card effects- Implement different types of cards- Test all card functions in-game        | - No blockers reported                                             |
| **Ink**     | - Implemented floor map and level navigation- Implemented level connection storage and checking- Implemented basic navigation logic- Used TDD for each class | - Map regeneration feature | - Continue map regeneration to support player level restarting                                                          | - No blockers reported                                             |

---

## High Risks

- **Combat code complexity**: Eric identified the combat code as a large and complex task that depends on both the card code and player code. Further breakdown and coordination are needed before implementation begins.
- **Nathan's PR**: Nathan's pull request requires additional comments and unit tests for the player class. Since Nathan was absent, follow-up will be conducted asynchronously.
- **Sprint 2 planning not started**: The Sprint 2 planning meeting has not taken place due to Nathan's absence, which may delay task assignments and sprint kickoff.

---

## Action Items

- **Lizi**
    - [ ] Continue implementing the map UI
    - [ ] Conduct testing for implemented UI components
    - [ ] Add comments and request additional unit tests on Nathan's pull request
    - [ ] Follow up with Nathan asynchronously regarding PR updates
    - [ ] Schedule and conduct the Sprint 2 planning meeting once Nathan is available
- **Eric**
    - [ ] Break down the combat code into manageable subtasks
    - [ ] Review and understand the card code and player code before starting combat implementation
    - [ ] Begin implementing the combat code in the next sprint
- **Tony**
    - [ ] Implement full comprehensive card effects
    - [ ] Implement different types of cards into the game
    - [ ] Test all card functions within the game environment
- **Ink**
    - [ ] Complete the map regeneration feature to support players restarting levels
