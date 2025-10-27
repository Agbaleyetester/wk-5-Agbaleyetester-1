# 🧪 Final Group Test Report Template — Word Puzzle Game Plus

**Level:** Intermediate QA | **Week 5:** Test Management

**Course:** Software Testing & Quality Assurance  
**Module:** Test Management (Week 5)  
**Project Type:** Group Assessment  
**Submission Date:** 2025-10-28

## Team Information

| Role | Name | Responsibilities |
|------|------|------------------|
| Test Manager | | Planning, scheduling, coordination, metric tracking |
| Risk Analyst | | Risk identification, prioritization, test design linkage |
| Test Executor | | Execution, evidence capture, defect logging |

## Group Rules

- Each student must belong to only one group.
- Duplicate membership or multiple submissions will result in invalidation.
- Every group member must contribute towards this project

## Project Overview

**System Under Test:** Word Puzzle Game Plus  
**Technology Stack:** HTML, CSS, JavaScript  
**Environment:** Chrome Browser (Desktop)

### Features Under Test

| Feature | Description | Risk Category |
|---------|-------------|---------------|
| Reset Game | Clears score and progress instantly | |
| Leaderboard | Stores top 3 scores in localStorage | |
| Bonus Round | Every 3 puzzles → doubles score | |

## Test Plan

### Objectives

- 

### Scope

**In Scope:**
- 

**Out of Scope:**
- 

### Tools & Resources

- 

### Schedule

| Phase | Planned Duration | Actual Duration | Status |
|-------|------------------|-----------------|--------|
| | | | |

## Risk Analysis

### Risks

| ID | Feature | Risk Description | Likelihood | Impact | Priority | Mitigation Strategy |
|----|---------|------------------|------------|--------|----------|---------------------|
| | | | | | | |

### Risk Coverage

- Tested Risks Percent: 
- Untested Risks Percent: 

## Test Cases

| ID | Feature | Objective | Expected Result | Actual Result | Status | Risk Link |
|----|---------|-----------|----------------|---------------|--------|-----------|
| TC01 | Leaderboard | Verify that leaderboard data persists after browser refresh | Leaderboard retains top 3 scores after reload | The Leaderboard retains top 3 scores after reload | Passed | R1 |
| TC02 | Leaderboard | Check leaderboard persistence after clearing cache or localStorage | Leaderboard data should not be cleared, backup/export option should be available | Leaderboard data is cleared, backup/export option should be available | Failed | R1 |
| TC03 | Bonus Round | Validate bonus calculation when base score = 0 | Bonus multiplier applies correctly without negative or zero output | Bonus multiplier applies correctly without negative or zero output | Passed | R2 |  
| TC04 | Reset Game | Confirm app resets score and progress instantly | Score resets to 0; all states cleared | The score resets to 0; all states cleared | Passed | R3 |  
| TC05 | Reset Game | Verify confirmation before reset | The user should receives “Are you sure?” confirmation prompt before data loss | The game reset automatically without confirmation prompt | Failed | R3 |
|TC06 | Leaderboard | Ensure leaderboard sorts correctly when multiple players have same score | Scores with same value should appear in correct order(alphabetically based on player name or number) | Score is with same value not differentiated  | Failed | R4 |  
| TC07 | Bonus Round | Confirm bonus trigger activates after every 3 puzzles | Bonus applies correctly every 3 solved puzzles | Bonus applies correctly every 3 solved puzzles | Passed | R5 |
| TC08 | Usability | Check if rules and scoring info are easily accessible to new users | Users can find rules within 1 click and understand gameplay | Users can find rules within 1 click and understand gameplay | Passed| R6 |
| TC09 | Usability | Test first-time player experience without reading the rules | Users understand how bonus works without reading long text| Users struggle to understand scoring until after first few rounds | Failed | R6|

## Defects

| ID | Issue Title | Severity | Risk ID | Status | GitHub Link |
|----|-------------|----------|---------|--------|-------------|
| D1 | Leaderboard data lost permanently after cache clear | High | R1 | Open |  |
| D2 | Reset Game lacks confirmation dialog | Medium | R3 | Open | |
| D3 | Leaderbaord sortin inconsistency when multiple identical scores | Medium | R4 | Open | |
| D4 | Bonus explanation unclear to new users | Low | R6 | Open | |


## Metrics

- Test Case Pass Percent: 
- Defect Density: 
- Risk Coverage Percent: 
- Regression Success Rate: 

### Defect Summary

- Total Defects Logged: 
- Critical High: 
- Fix Rate: 

## Test Control & Project Management

### Phases

| Phase | Deliverable | Actual Output | Variance | Owner |
|-------|-------------|---------------|----------|-------|
| | | | | |

**Progress Tracking Method:**  
**Change Control Notes:**

## Lessons Learned

- Most Defect Prone Feature: 
- Risk Analysis Impact: 
- Team Communication Effectiveness: 
- Improvements for Next Cycle: 

## Attachments

- 

## Sign Off

| Name | Role | Initials | Date |
|------|------|-----------|------|
| | Test Manager | | |
| | Risk Analyst | | |
| | Test Executor | | |

## Overall Summary

**Statement:** 

**Test Status:** ☐ Completed / ☐ In Progress / ☐ Deferred
