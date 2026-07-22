# Week 7 – Issue Selection

**Issue link:**
https://github.com/ascheri/pathreview/issues/18

**Issue title:**
Add end-to-end ingestion test with a sample resume fixture

**Tier:**
Tier 2

**Selection reasoning:**
I selected this Tier 2 issue because I have previous experience contributing to larger codebases through CodePath projects, and I want to continue improving my testing and debugging skills. The issue has a clear description, identifies the relevant files, and has a well-defined scope, making it a realistic project to complete within the module timeline.

**Problem summary:**
This issue requests an end-to-end integration test for the resume ingestion pipeline. While the project already includes unit tests for individual parsers, there is no test that verifies the complete workflow from uploading a resume through processing and storing the resulting data. A successful fix will add an integration test using the provided sample resume fixtures so the entire ingestion pipeline can be validated automatically.

## "Is this right for me?" checklist reasoning

I understand the goal of this issue and can explain what needs to be implemented in my own words. The issue description identifies the relevant file (`tests/integration/test_ingestion_pipeline.py`), which provides a clear starting point for exploring the codebase. Since I have prior experience contributing to large repositories, I am comfortable working on a Tier 2 issue. The issue has a defined scope, no listed blockers, and I believe it is realistic to complete before the Week 9 deadline.

**Branch name:**
docs/18-week7-journal

**Setup confirmation:**
- [ ] App runs locally at localhost:5173

**Cohort ledger:**
- [ ] Issue added to cohort ledger