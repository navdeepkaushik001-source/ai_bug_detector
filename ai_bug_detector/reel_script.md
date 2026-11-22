# 🎥 120-Second Video Reel Script: Prompt Pirates
## Project: AI-Powered Code Review & Bug Detection System
**Team Name:** Prompt Pirates | **Team ID:** `PE-B65-19` | **Batch Group:** `B65-80`  
**Prompt-Engineering Use Case:**  
*"Design effective prompts to identify bugs and style issues in beginner-level code and provide clear hints and structured explanations without revealing the complete solution."*  
**Course:** SCSE4041 Prompt Engineering — Milestone 2 Submission  
**Required Video Length:** 90 – 150 seconds (Target: **120 seconds / 2 minutes**)  
**Sharing Setting:** Set Google Drive / unlisted YouTube video to **"Anyone with the link can view"**

---

### ⏱️ Time Breakdown & Visual Storyboard

| Timestamp | Visual on Screen | Speaker & Script |
| :--- | :--- | :--- |
| **00:00 – 00:20** <br/> *(20 sec)* | **Title Slide & Team Intro:**<br/>Prompt Pirates banner, Team ID (`PE-B65-19`), Batch (`B65-80`), and names of all 5 team members.<br/>*Camera: Teammate on webcam or voiceover.* | **Speaker 1 (Team Leader - Himanshu):**<br/>"Hello everyone! We are Team Prompt Pirates, Team ID PE-B65-19 from Batch B65-80. For SCSE4041 Prompt Engineering Milestone 2, our project is the **AI-Powered Code Review and Bug Detection System**. Our core prompt engineering challenge is to identify syntax bugs, logic flaws, and style issues in beginner-level code, and provide structured Socratic hints *without revealing the complete solution*." |
| **00:20 – 00:45** <br/> *(25 sec)* | **Architecture & Prompt Strategy:**<br/>Display the 3-stage prompt pipeline diagram (Diagnostics $\rightarrow$ Mental Model Explanation $\rightarrow$ 3-Tier Scaffolded Hints) powered by **Google Gemini 2.5 Flash**. | **Speaker 2 (Navdeep Kaushik):**<br/>"Generic AI tutors fail beginners by immediately blurting out the complete code answer. Through 5 iterative prompt engineering cycles, we evolved our prompts by applying strict negative constraints against code leakage and implementing a 3-tier Socratic hinting scaffold: Level 1 Conceptual Nudge, Level 2 Location Clue, and Level 3 Guiding Question. This transformed our baseline 53% F1 and 0% solution-withholding into a 100% leak-proof pedagogical copilot." |
| **00:45 – 01:18** <br/> *(33 sec)* | **Live Prototype Demonstration:**<br/>Screen recording of the local web interface (`http://localhost:8000` or `index.html`).<br/>1. Load **T-03: Infinite while loop** $\rightarrow$ Click 'Review Code' $\rightarrow$ Show Level 1, 2, 3 hints and conceptual explanation.<br/>2. Load **T-07: PEP8 style naming** $\rightarrow$ Show style feedback.<br/>3. Load **T-10: Adversarial attempt** demanding the solution $\rightarrow$ Show refusal and pedagogical guardrail. | **Speaker 3 (Shivansh Chauhan):**<br/>"Here is our live prototype. When a beginner submits an infinite while loop, Prompt Pirates AI analyzes the code in 1.3 seconds, flags the defect at line 2, and provides a clear conceptual explanation. Crucially, the solution code is strictly withheld! Instead, it reveals three progressive hints: a conceptual nudge, a clue about variable `count`, and a guiding question. Next, testing beginner style issues like PascalCase function names instantly flags PEP8 conventions. Even when a student inputs an adversarial prompt demanding the full code, our guardrail upholds the pedagogical constraint!" |
| **01:18 – 01:42** <br/> *(24 sec)* | **Test Table & Terminal Execution:**<br/>Display terminal execution of `python3 test_runner.py` showing `Summary: Total=12, Passed=12, Pass Rate=100.0%` and `Solution Withholding Compliance: 12/12 (100.0%)`. | **Speaker 4 (Joy Mandal):**<br/>"We validated the system against 12 comprehensive beginner test cases covering syntax colons, indentation, off-by-one ranges, runtime type errors, index out of bounds, and clean code baselines. Across all 12 tests, Prompt Pirates AI achieved **100% precision, 100% recall, 100% valid JSON, and 100% solution withholding compliance** with zero false alarms." |
| **01:42 – 02:00** <br/> *(18 sec)* | **Closing Slide & Academic Sign-Off:**<br/>Display Section 7 Contribution Table showing all 5 members agreed at 20% each, GitHub repo link, and Google AI Studio prototype link. | **Speaker 5 (Shravan Kumar):**<br/>"All modules—from pre-filtering to Socratic hint generation—are 100% working right now. All 5 team members have contributed equally and agreed with the Section 7 contribution table in our Milestone 2 PDF. Thank you!" |

---

### 🎥 How to Record Easily (Mac / Windows):
1. **Double-click `index.html`** in your browser (`file:///Users/sunnykaushik/.gemini/antigravity/scratch/ai_bug_detector/index.html`) or run `python3 server.py`.
2. Use **QuickTime Player** (`Cmd + Shift + 5` on Mac $\rightarrow$ Record Selected Portion) or **OBS Studio** / **Loom**.
3. Follow the 5-speaker storyboard above.
4. Total duration must be between **90 and 150 seconds** (e.g. 120 seconds).
5. Upload to Google Drive or YouTube (Unlisted), and set permissions to **"Anyone with the link can view"**.
