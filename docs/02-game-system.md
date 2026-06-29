
Game System

1. Purpose of the Game System

The Product Engineer Quest uses RPG-inspired mechanics to make professional growth visible, structured, and motivating.

The goal is not to create a game for entertainment.

The goal is to create a progression system that helps the player:

* know what to do next;
* see weekly progress;
* avoid vague goals;
* produce real professional evidence;
* build skills through deliberate practice;
* stay motivated through short feedback loops.

The game system exists to support learning. It must never become more important than the learning itself.

⸻

2. The Player

The player is the person following PEQ.

In PEQ v0.1, the initial player is César González.

The player starts from an existing professional identity:

Current class: Senior iOS Engineer
Target evolution: Product Engineer

PEQ does not reset the player to beginner level.

The system assumes that the player already has strong technical foundations and is now developing complementary product-oriented capabilities.

⸻

3. Player Profile

The player profile contains:

* current class;
* current level;
* target evolution;
* active Season;
* active quests;
* unlocked skills;
* achievements;
* accumulated evidence;
* weekly review history.

The player profile should be simple enough to maintain manually.

Automation may be added later, but it is not required for PEQ v0.1.

⸻

4. Levels

Levels represent visible professional progression inside PEQ.

Levels are not meant to be a precise measurement of real seniority.

They are a motivational abstraction used to show movement.

The player starts at:

Level 46

This initial level reflects the player’s real professional maturity and creates a personal connection with the system.

Future level-ups happen through XP.

A level-up should feel meaningful, but not rare enough to become demotivating.

⸻

5. XP

XP stands for experience points.

XP makes progress visible.

XP is awarded for completing quests, producing evidence, reflecting on learning, and demonstrating improved judgment.

XP should reward:

* thoughtful analysis;
* useful output;
* clear reasoning;
* applied learning;
* professional reflection;
* decision quality;
* communication clarity.

XP should not reward:

* time spent without output;
* passive consumption;
* mechanical task completion;
* shallow writing;
* fake productivity;
* overengineering the system itself.

⸻

6. XP Philosophy

XP is a motivational tool, not the final goal.

The final goal is improved professional judgment.

The system should avoid situations where the player optimizes for points instead of learning.

For this reason, some quests may require a quality check before XP is awarded.

If an activity is completed but the reasoning is weak, the result can be marked as:

Completed, but not mastered.

In that case, the player may receive partial XP and improve the deliverable later.

⸻

7. Suggested XP Scale

PEQ uses a simple XP scale.

Small Quest

A small quest is a focused task that can usually be completed in one short session.

Examples:

* read one chapter;
* write a short reflection;
* analyze one small feature;
* define one product hypothesis;
* review one AI workflow.

Reward:

10-20 XP

⸻

Standard Quest

A standard quest produces a meaningful deliverable.

Examples:

* product analysis;
* short RFC;
* decision document;
* experiment proposal;
* product teardown;
* weekly review.

Reward:

25-50 XP

⸻

Major Quest

A major quest requires deeper reasoning or combines multiple skills.

Examples:

* full product analysis;
* complete RFC;
* interview case response;
* product strategy note;
* technical/product trade-off analysis.

Reward:

75-100 XP

⸻

Boss Battle

A Boss Battle is a challenge designed to demonstrate skill under realistic conditions.

Examples:

* respond to a product-engineering scenario;
* defend a prioritization decision;
* analyze a feature with incomplete information;
* propose an MVP;
* explain a trade-off to a non-technical stakeholder.

Reward:

100-200 XP

⸻

8. Level Progression

For PEQ v0.1, the level progression is intentionally simple:

* every 500 XP = 1 level up;
* XP never goes down;
* unfinished quests do not remove XP;
* abandoned quests can be moved back to the backlog;
* revised work can earn additional XP if it becomes meaningfully better.

Example:

Level 46
XP: 320 / 500
Level 47
XP: 0 / 500

This system can be adjusted after Season 1 if it feels too slow or too easy.

⸻

9. Quests

Quests are the core unit of action in PEQ.

A quest is a clearly defined task with:

* a purpose;
* an expected output;
* an XP reward;
* one or more related skills;
* a completion condition.

Every quest should answer:

What will the player produce or demonstrate by completing this?

If a quest does not produce learning, evidence, reflection, or skill development, it should not exist.

⸻

10. Quest Types

PEQ uses several quest types.

Study Quest

A quest focused on learning from a selected source.

Examples:

* read a chapter;
* watch a talk;
* study a product case;
* summarize a concept.

Expected output:

* short summary;
* key takeaways;
* application to the player’s context.

⸻

Analysis Quest

A quest focused on analyzing a product, feature, flow, or decision.

Examples:

* analyze onboarding in Revolut;
* analyze search in Fever;
* analyze watchlist behavior in PickOne;
* analyze checkout in Amazon.

Expected output:

* problem;
* user intent;
* hypothesis;
* metric;
* trade-offs;
* improvement ideas.

⸻

Writing Quest

A quest focused on professional communication.

Examples:

* write an RFC;
* write a decision document;
* write a product brief;
* write an engineering proposal;
* write a post-mortem.

Expected output:

* clear written artifact;
* structured reasoning;
* audience-aware communication.

⸻

Reflection Quest

A quest focused on learning from experience.

Examples:

* weekly review;
* monthly retrospective;
* decision reflection;
* mistake analysis;
* learning journal.

Expected output:

* what happened;
* what was learned;
* what should change;
* next action.

⸻

AI Quest

A quest focused on using AI as a professional multiplier.

Examples:

* use AI to explore product hypotheses;
* use AI to review an RFC;
* use AI to identify edge cases;
* use AI to simulate stakeholder feedback;
* use AI to compare technical options.

Expected output:

* prompt or workflow used;
* result;
* human judgment;
* limitations;
* reusable learning.

⸻

Application Quest

A quest focused on applying PEQ to real work or a side project.

Examples:

* apply product thinking to a Fever feature;
* apply MVP reasoning to PickOne;
* use an RFC structure in a real discussion;
* improve a real technical proposal with product context.

Expected output:

* before/after reasoning;
* decision made;
* impact or expected impact;
* lessons learned.

⸻

11. Boss Battles

Boss Battles are milestone challenges.

They are designed to test whether the player can apply multiple skills together.

A Boss Battle should feel like a realistic professional situation, not an academic exam.

Boss Battles may include scenarios such as:

* a PM proposes a feature with unclear user value;
* design wants to add complexity to a flow;
* engineering wants to refactor but product wants speed;
* metrics are declining and the team needs a diagnosis;
* leadership asks whether to invest in quality or new features;
* an interviewer asks how the player would approach a product problem.

A Boss Battle should require the player to:

* identify the problem;
* ask clarifying questions;
* define assumptions;
* propose a hypothesis;
* identify success metrics;
* reason about trade-offs;
* communicate clearly;
* recommend a pragmatic next step.

⸻

12. Boss Battle Evaluation

Boss Battles are evaluated by reasoning quality.

A strong Boss Battle response should be:

* structured;
* pragmatic;
* user-aware;
* business-aware;
* technically grounded;
* explicit about assumptions;
* clear about trade-offs;
* actionable.

A weak Boss Battle response usually:

* jumps directly to implementation;
* ignores the user problem;
* ignores metrics;
* assumes too much;
* overengineers the solution;
* lacks prioritization;
* communicates only from an engineering perspective.

Boss Battles can be repeated after feedback.

Improvement is part of the system.

⸻

13. Achievements

Achievements are badges awarded for meaningful milestones.

They are not required for progression, but they make progress more visible.

Examples:

* First Product Analysis;
* First RFC;
* First Boss Battle;
* First Trade-off Analysis;
* First Product Hypothesis;
* First AI Workflow;
* First Season Completed;
* First Real Work Application;
* First Interview-Ready Answer.

Achievements should be awarded for meaningful evidence, not arbitrary activity.

⸻

14. Weekly Review

The weekly review is the main feedback loop of PEQ.

It should be short, concrete, and sustainable.

The weekly review answers:

* What quests did I complete?
* What evidence did I produce?
* What did I learn?
* What was difficult?
* What helped me stay engaged?
* What felt like busywork?
* What should I do next week?
* How much XP did I earn?
* Did I unlock any skill or achievement?

The weekly review should usually take 10-20 minutes.

If it takes too long, the system is becoming too heavy.

⸻

15. Monthly Review

The monthly review is deeper than the weekly review.

It checks whether the player is actually evolving.

The monthly review answers:

* Am I thinking differently than one month ago?
* Which skill improved the most?
* Which skill is still weak?
* Which quests created the most value?
* Which quests should be removed or redesigned?
* Is the XP system still motivating?
* Is the Season still aligned with the main goal?

A monthly review may include a Boss Battle.

⸻

16. Season Review

The Season Review determines whether the Season was successful.

It should not be based only on task completion.

The Season Review should look at:

* evidence produced;
* skills unlocked;
* Boss Battle performance;
* real-world application;
* confidence improvement;
* quality of reasoning;
* communication improvement;
* next growth area.

A Season is successful if the player can demonstrate improved judgment in the target area.

⸻

17. Evidence

Evidence is the most important output of PEQ.

Evidence can include:

* written analyses;
* RFCs;
* hypotheses;
* decision documents;
* AI workflows;
* retrospectives;
* interview answers;
* real work examples;
* project decisions;
* before/after comparisons.

The player should be able to look back after a Season and see proof of growth.

Without evidence, PEQ becomes just another learning plan.

⸻

18. Manual First

PEQ v0.1 should be manual-first.

This means:

* no database;
* no authentication;
* no automated dashboard;
* no complex progress tracking;
* no app;
* no premature productization.

Manual tracking is enough for the first Season.

The system should only be automated after it has proven useful in practice.

⸻

19. Anti-Abandonment Rules

PEQ must be designed to reduce abandonment.

The system should follow these rules:

Rule 1: Always know the next action

The player should never finish a session without knowing what comes next.

Rule 2: Keep quests small enough to start

A quest that feels too large should be split.

Rule 3: Prefer visible output

The player should produce something concrete every week.

Rule 4: Do not punish missed weeks

A missed week does not reset progress.

Rule 5: Reduce friction

Templates, examples, and predefined structures should be used whenever possible.

Rule 6: Avoid perfection traps

A useful draft is better than an imaginary perfect document.

Rule 7: Review and adapt

If a quest type consistently creates resistance, it should be redesigned.

⸻

20. Versioning

PEQ should evolve through versions.

PEQ v0.1

Manual system definition.

Focus:

* vision;
* principles;
* game mechanics;
* skills;
* Season 1;
* journal templates.

PEQ v0.2

Improved after real use.

Possible additions:

* better XP calibration;
* improved quest templates;
* refined skills;
* clearer Boss Battles;
* static website.

PEQ v1.0

Only after the system has been tested in practice.

Possible additions:

* public documentation;
* reusable framework;
* website;
* templates;
* examples;
* maybe productization.

PEQ should not become a product before it works for the first player.

⸻

21. Core Rule

The core rule of the PEQ game system is:

The system exists to help the player grow. If a mechanic does not support growth, clarity, motivation, or evidence, it should be removed.