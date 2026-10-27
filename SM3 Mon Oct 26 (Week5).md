## Key Takeaways

- The team is in Sprint 1 (Phase 2) and held their third stand-up meeting to sync on progress.
- A global random seed system is being discussed to unify map and monster generation, replacing system-time-based seeding.
- TDD (Test-Driven Development) has been adopted as the team's development strategy: write header/test files first, then implementation.
- GitHub Actions have been set up to automatically enforce Google Style formatting and run unit tests on every push/commit.
- A separate AI Transparency repository has been created; team members must log AI usage (inputs/outputs) when using AI to write unit tests.
- Team members are reminded to update their task status on the project Kanban board (move items to "In Development").
- VS Code workspace settings will be configured to auto-format code on save according to Google Style.

---

## Team Updates

|  **Speaker**  |                                                                                                      **Completed**                                                                                                       |                                   **In Progress**                                    |                                      **Plan**                                       |                                  **Blockers**                                  |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| **Lizi Luo**  | - Set up GitHub Actions for Google Style verification- Set up automated unit test runs on push/commit- Adopted TDD strategy for the project- Created AI Transparency repository- Discussed UML and UI design for Phase 2 | - Basic Phase 2 setup                                                                | - Continue working on UI framework- Create basic user interface for the game        | N/A                                                                            |
| **Ink**       | - Started development on map and level branching paths- Discussed random level design and content                                                                                                                        | - Simple branching path test (near completion)- Thinking through random level design | - Finish simple branching path test                                                 | - Still finalizing random level design approach                                |
| **Nathan**    | - Finished implementing the player status system- Updated player class in UML diagram- Added class diagram description to README                                                                                         | N/A                                                                                  | - Apply TDD to test existing functions- Fix code to comply with Google Style format | N/A                                                                            |
| **Eric Qian** | - Completed basic design of the enemy class- Completed implementation of the Goblin Monster                                                                                                                              | - Reformatting code to Google Style (in progress)                                    | - Create additional enemy types based on existing work                              | - Admin skill files currently use Microsoft style format and need reformatting |
| **TNY**       | - Planned the card system design- Finalized several card functions and card effects                                                                                                                                      | N/A                                                                                  | - Implement the card system and card access this week                               | - Had a bad fever last week, resulting in limited contribution                 |

---

## High Risks

- **Random seed unification**: The global random seed system for map and monster generation is more complex than initially anticipated; Eric Qian noted difficulty using a fully global random approach and is currently relying on time + address as a fallback.
- **Google Style compliance**: Multiple team members (notably Eric Qian) have code that does not yet conform to Google Style, which is causing GitHub Actions check failures. This needs to be resolved before PRs can be merged.
- **TNY's delayed progress**: Due to illness last week, TNY's card system implementation is behind and carries risk of not being completed on time.
- **Kanban board not updated**: Several team members have not been moving their tasks to the correct status on the project board, reducing visibility into actual progress.

---

## Action Items

- **Lizi Luo**
    - [ ] Configure VS Code workspace settings to auto-format code on save using Google Style
    - [ ] Set up the `.vscode` directory in the repository with shared formatting rules
    - [ ] Continue development of the UI framework and basic game user interface
- **Eric Qian**
    - [ ] Reformat all existing code (including admin skill files) to comply with Google Style
    - [ ] Complete implementation of additional enemy types
    - [ ] Resolve GitHub Actions check failures on current branch
- **Nathan**
    - [ ] Fix existing code to comply with Google Style format
    - [ ] Write TDD-based unit tests for implemented player status functions
    - [ ] Log AI usage in the AI Transparency repository if AI is used
- **Ink**
    - [ ] Complete the simple branching path test for map/level generation
    - [ ] Finalize the random level design approach
    - [ ] Log AI usage in the AI Transparency repository if AI is used
- **TNY**
    - [ ] Implement the card system and card access this week
    - [ ] Log AI usage in the AI Transparency repository if AI is used
- **All Team Members**
    - [ ] Update task status on the project Kanban board (move active tasks to "In Development")
    - [ ] Ensure all commits and PRs follow Google Style formatting before submission
    - [ ] Follow TDD workflow: write header/test files first, then implementation, and document AI usage in the AI Transparency repository
