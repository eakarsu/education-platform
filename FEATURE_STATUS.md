# Feature status — Education, assessment & training

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 425 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Reports & analytics | report | 4 | 0 | Native records/view |
| Activity & audit trail | audit | 3 | 0 | Native records/view |
| Provider connections | integration | 3 | 0 | Provider request records only |
| Accreditation Cycle | records | 1 | 0 | Native records/view |
| Accreditation Standard | records | 1 | 0 | Native records/view |
| Standard Evidence | records | 1 | 0 | Native records/view |
| Assessment Measure | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Self Study Section | records | 1 | 0 | Native records/view |
| Site Visit Request | records | 1 | 0 | Native records/view |
| Accreditation Finding | records | 1 | 0 | Native records/view |
| Improvement Action | records | 1 | 0 | Native records/view |
| Committee Meeting | records | 1 | 0 | Native records/view |
| Operational Task | records | 4 | 0 | Native records/view |
| Rule Version | records | 4 | 0 | Native records/view |
| Document Requirement | records | 4 | 0 | Native records/view |
| Standard evidence mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assessment gap review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Self-study section drafting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site visit response preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Finding response draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Improvement narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Transfer Application | records | 1 | 0 | Native records/view |
| Source Course | records | 1 | 0 | Native records/view |
| Target Course | records | 1 | 0 | Native records/view |
| Syllabus Evidence | records | 1 | 0 | Native records/view |
| Articulation Agreement | records | 1 | 0 | Native records/view |
| Equivalency Proposal | records | 1 | 0 | Native records/view |
| Faculty Evaluation | records | 1 | 0 | Native records/view |
| Credit Award | records | 1 | 0 | Native records/view |
| Transfer Appeal | records | 1 | 0 | Native records/view |
| Syllabus outcome comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Course evidence extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Articulation term review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Faculty review preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit award explanation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appeal evidence summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assessments | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Evidence & Scoring | records | 1 | 0 | Native records/view |
| Outcomes | records | 1 | 0 | Native records/view |
| Quality | records | 1 | 0 | Native records/view |
| Rater | records | 1 | 0 | Native records/view |
| Assessment Event | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recording | records | 1 | 0 | Native records/view |
| Peer Evaluation | records | 1 | 0 | Native records/view |
| Behavioral Evidence | records | 1 | 0 | Native records/view |
| Scoring Rubric | records | 1 | 0 | Native records/view |
| Competency Report | records | 1 | 0 | Native records/view |
| Badge | records | 1 | 0 | Native records/view |
| Calibration | records | 1 | 0 | Native records/view |
| Transcript | records | 1 | 0 | Native records/view |
| Dispute | records | 1 | 0 | Native records/view |
| Framework | records | 1 | 0 | Native records/view |
| Draft: Assessment Designer | integration | 1 | 0 | Provider request records only |
| Draft: Evidence Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Competency Report Writer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Student Case | records | 1 | 0 | Native records/view |
| Student Document | records | 1 | 0 | Native records/view |
| Enrollment Event | records | 1 | 0 | Native records/view |
| Employment Request | records | 1 | 0 | Native records/view |
| Student Request | records | 1 | 0 | Native records/view |
| Dso Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reporting Event | records | 1 | 0 | Native records/view |
| Reporting Receipt | records | 1 | 0 | Native records/view |
| Student Communication | records | 1 | 0 | Native records/view |
| Document date extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Enrollment event reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employment evidence gaps | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Student request response draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DSO review brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reporting queue summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exams | records | 2 | 0 | Native records/view |
| Authenticity | records | 1 | 0 | Native records/view |
| Results | records | 2 | 0 | Native records/view |
| Programs | records | 1 | 0 | Native records/view |
| Examinee | records | 1 | 0 | Native records/view |
| Exam Session | records | 1 | 0 | Native records/view |
| Question | records | 1 | 0 | Native records/view |
| Verbal Response | records | 1 | 0 | Native records/view |
| Authenticity Finding | records | 1 | 0 | Native records/view |
| Submission | records | 1 | 0 | Native records/view |
| Inconsistency | records | 1 | 0 | Native records/view |
| Proctor Note | records | 1 | 0 | Native records/view |
| Score Report | records | 1 | 0 | Native records/view |
| Appeal | records | 1 | 0 | Native records/view |
| Exam Blueprint | records | 1 | 0 | Native records/view |
| Program | records | 1 | 0 | Native records/view |
| Draft: Adaptive Question Selector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Authenticity Auditor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Score Justifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Apprenticeship Program | records | 1 | 0 | Native records/view |
| Apprentice | records | 1 | 0 | Native records/view |
| Work Process | records | 1 | 0 | Native records/view |
| Work Hour Entry | records | 1 | 0 | Native records/view |
| Instruction Course | records | 1 | 0 | Native records/view |
| Instruction Attendance | records | 1 | 0 | Native records/view |
| Mentor Attestation | records | 1 | 0 | Native records/view |
| Wage Step | records | 1 | 0 | Native records/view |
| Completion Packet | records | 1 | 0 | Native records/view |
| Training evidence mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Work-process gap summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mentor review preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wage progression brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Instruction plan draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Completion packet narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Learners | records | 1 | 0 | Native records/view |
| Curriculum | records | 2 | 0 | Native records/view |
| Assessment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Cohort | records | 1 | 0 | Native records/view |
| Learner | records | 1 | 0 | Native records/view |
| Learning Path | records | 2 | 0 | Native records/view |
| Module | records | 1 | 0 | Native records/view |
| Assignment | records | 1 | 0 | Native records/view |
| Mentor Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Readiness Score | records | 1 | 0 | Native records/view |
| Credential | records | 1 | 0 | Native records/view |
| Placement | records | 1 | 0 | Native records/view |
| Skill Benchmark | records | 1 | 0 | Native records/view |
| Coaching Note | records | 1 | 0 | Native records/view |
| Draft: Learning Path Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Assignment Builder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Readiness Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Candidates | records | 1 | 0 | Native records/view |
| Simulations | records | 1 | 0 | Native records/view |
| Evaluation | records | 1 | 0 | Native records/view |
| Candidate | records | 1 | 0 | Native records/view |
| Simulation | records | 1 | 0 | Native records/view |
| Team Scenario | records | 1 | 0 | Native records/view |
| Competency Rating | records | 1 | 0 | Native records/view |
| Evidence Artifact | records | 1 | 0 | Native records/view |
| Portfolio | records | 1 | 0 | Native records/view |
| Communication Eval | records | 1 | 0 | Native records/view |
| Leadership Signal | records | 1 | 0 | Native records/view |
| Assessor Note | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hiring Signal | records | 1 | 0 | Native records/view |
| Simulation Template | records | 1 | 0 | Native records/view |
| Peer Feedback | records | 1 | 0 | Native records/view |
| Draft: Simulation Designer | integration | 1 | 0 | Provider request records only |
| Draft: Competency Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Portfolio Reviewer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Students | records | 3 | 0 | Native records/view |
| Interventions | records | 1 | 0 | Native records/view |
| Escalations | records | 1 | 0 | Native records/view |
| Classrooms | records | 1 | 0 | Native records/view |
| Classroom | records | 1 | 0 | Native records/view |
| Student | records | 1 | 0 | Native records/view |
| Engagement Signal | records | 1 | 0 | Native records/view |
| Learning Gap | records | 1 | 0 | Native records/view |
| Exercise | records | 1 | 0 | Native records/view |
| Intervention | records | 1 | 0 | Native records/view |
| Motivation Campaign | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Teacher Alert | records | 1 | 0 | Native records/view |
| Guardian Contact | records | 1 | 0 | Native records/view |
| Outcome Measure | records | 1 | 0 | Native records/view |
| Class Heatmap | records | 1 | 0 | Native records/view |
| Resource | records | 1 | 0 | Native records/view |
| Draft: Gap Triage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Intervention Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Guardian Letter Drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Career Assessment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Career Recommendation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Career Paths | records | 2 | 0 | Native records/view |
| Skills Gap Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Course Recommendations | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Job Market Trends | records | 1 | 0 | Native records/view |
| Interview Prep | records | 1 | 0 | Native records/view |
| Mentorship | records | 1 | 0 | Native records/view |
| Scholarships | records | 1 | 0 | Native records/view |
| Networking Events | records | 1 | 0 | Native records/view |
| Resume Builder | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio Builder | records | 1 | 0 | Native records/view |
| Learning Roadmaps | records | 1 | 0 | Native records/view |
| Industry Insights | records | 1 | 0 | Native records/view |
| Salary Insights | records | 1 | 0 | Native records/view |
| AI Career Chat | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Career Compatibility Match | records | 1 | 0 | Native records/view |
| Salary Negotiation Coach | records | 1 | 0 | Native records/view |
| Scholarship Eligibility | records | 1 | 0 | Native records/view |
| Personalized Roadmap | records | 1 | 0 | Native records/view |
| Peer Mentor Match | records | 1 | 0 | Native records/view |
| Company Culture Fit | records | 1 | 0 | Native records/view |
| Mock Interview | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Resume Bullet Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Run History | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Industry Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Generate Roadmap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mentor Match | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Event Suggestions | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Salary Estimate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scholarship Finder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gap Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Webhooks | integration | 3 | 0 | Provider request records only |
| Application deadline risk | records | 1 | 0 | Native records/view |
| Work simulations | records | 1 | 0 | Native records/view |
| Rubric drift | records | 1 | 0 | Native records/view |
| Essay Improvement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Study Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cohort Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Teacher Cohort Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quiz Generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Next-Lesson Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Essay Grader | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Music Teacher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Quiz Maker | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Reading Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Learning Paths | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Progress | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Feedback | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Verify email | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Admin | records | 1 | 0 | Native records/view |
| Tutor chat | records | 2 | 0 | Native records/view |
| Mastery intervention | records | 1 | 0 | Native records/view |
| Proctors | records | 1 | 0 | Native records/view |
| Institutions | records | 1 | 0 | Native records/view |
| Sessions | records | 1 | 0 | Native records/view |
| Incidents | records | 1 | 0 | Native records/view |
| Face Verification | records | 2 | 0 | Native records/view |
| Behavior Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Audio Monitoring | records | 2 | 0 | Native records/view |
| Plagiarism Detection | records | 2 | 0 | Native records/view |
| AI Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Browser Security | records | 1 | 0 | Native records/view |
| Live Monitoring | records | 1 | 0 | Native records/view |
| Accommodation Audit | records | 1 | 0 | Native records/view |
| Chemistry Lab | records | 1 | 0 | Native records/view |
| Physics Lab | records | 1 | 0 | Native records/view |
| Biology Lab | records | 1 | 0 | Native records/view |
| Lab Equipment | records | 1 | 0 | Native records/view |
| Lab Reports | records | 1 | 0 | Native records/view |
| Safety Training | records | 1 | 0 | Native records/view |
| Student Progress | records | 1 | 0 | Native records/view |
| Data Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Molecular Viewer | records | 1 | 0 | Native records/view |
| Collaborations | records | 1 | 0 | Native records/view |
| Lab Schedules | records | 1 | 0 | Native records/view |
| Research Papers | records | 1 | 0 | Native records/view |
| Virtual Labs | records | 1 | 0 | Native records/view |
| Student Misconception Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Real-time Safety Monitor (advisory) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lab Equipment Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reagent depletion planner | records | 1 | 0 | Native records/view |
| Vocabulary Builder | records | 1 | 0 | Native records/view |
| Grammar Lessons | records | 1 | 0 | Native records/view |
| Conversation Practice | records | 1 | 0 | Native records/view |
| Pronunciation Guide | records | 1 | 0 | Native records/view |
| Flashcards | records | 2 | 0 | Native records/view |
| Quizzes & Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Translation Tool | records | 1 | 0 | Native records/view |
| Writing Practice | records | 1 | 0 | Native records/view |
| Reading Comprehension | records | 1 | 0 | Native records/view |
| Listening Exercises | records | 1 | 0 | Native records/view |
| Cultural Notes | records | 1 | 0 | Native records/view |
| Idioms & Phrases | records | 1 | 0 | Native records/view |
| Language Courses | records | 1 | 0 | Native records/view |
| Progress Tracking | records | 1 | 0 | Native records/view |
| Grammar Correction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Personalized Lesson Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pronunciation Feedback | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Idiom Explanation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Study | records | 1 | 0 | Native records/view |
| Daily lesson | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Forgetting curve review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employees | records | 1 | 0 | Native records/view |
| Learning Tracks | records | 1 | 0 | Native records/view |
| Skill Gap Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Succession Plans | records | 1 | 0 | Native records/view |
| Certifications | records | 1 | 0 | Native records/view |
| Learning Resources | records | 1 | 0 | Native records/view |
| Knowledge Base | records | 1 | 0 | Native records/view |
| Mentorship Programs | records | 1 | 0 | Native records/view |
| Training Events | records | 1 | 0 | Native records/view |
| Onboarding Plans | records | 1 | 0 | Native records/view |
| Compliance Training | records | 1 | 0 | Native records/view |
| Wellness Programs | records | 1 | 0 | Native records/view |
| ROI Measurement | records | 1 | 0 | Native records/view |
| Performance Reviews | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Feedback Surveys | records | 1 | 0 | Native records/view |
| Learning Budgets | records | 1 | 0 | Native records/view |
| Competency Frameworks | records | 1 | 0 | Native records/view |
| Team Goals | records | 1 | 0 | Native records/view |
| Transition OS | records | 1 | 0 | Native records/view |
| Peer / Mentor Match Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training Effectiveness Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Succession Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Skill adjacency mobility map | records | 1 | 0 | Native records/view |
| Misconception Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Difficulty Adapt | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Teacher | records | 2 | 0 | Native records/view |
| Accommodation planner | records | 1 | 0 | Native records/view |
| Teachers | records | 1 | 0 | Native records/view |
| Instruments | records | 1 | 0 | Native records/view |
| Lessons | records | 1 | 0 | Native records/view |
| Rooms | records | 1 | 0 | Native records/view |
| Rentals | records | 1 | 0 | Native records/view |
| Recitals | records | 1 | 0 | Native records/view |
| Practice Logs | records | 1 | 0 | Native records/view |
| Grades | records | 1 | 0 | Native records/view |
| Attendance | records | 1 | 0 | Native records/view |
| Music Library | records | 1 | 0 | Native records/view |
| Families | records | 1 | 0 | Native records/view |
| Makeup Lessons | records | 1 | 0 | Native records/view |
| Summer Camps | records | 1 | 0 | Native records/view |
| Ensembles | records | 1 | 0 | Native records/view |
| Competitions | records | 1 | 0 | Native records/view |
| Theory Classes | records | 1 | 0 | Native records/view |
| Payroll | records | 1 | 0 | Native records/view |
| Substitutes | records | 1 | 0 | Native records/view |
| Trial Lessons | records | 1 | 0 | Native records/view |
| Waiting List | records | 1 | 0 | Native records/view |
| Report Cards | records | 1 | 0 | Native records/view |
| Certificates | records | 1 | 0 | Native records/view |
| Merchandise | records | 1 | 0 | Native records/view |
| Practice Plan Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Progress Report Writer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recital Program Creator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Skill Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lesson Plan Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketing Campaigns | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Schedule makeup | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Student matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retention risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Event promotion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ensemble assignment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Practice evaluation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parent summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Learning Paths | records | 1 | 0 | Native records/view |
| AI Tutor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Math Solver | records | 1 | 0 | Native records/view |
| Learning Style | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quiz Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Progress Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Concept Explainer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Study Scheduler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Homework Helper | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Math Tutor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| History Explorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Science Lab | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Flashcard Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Study materials | records | 1 | 0 | Native records/view |
| Practice problems | records | 1 | 0 | Native records/view |
| Video lessons | records | 1 | 0 | Native records/view |
| Goals | records | 1 | 0 | Native records/view |
| Vocabulary | records | 1 | 0 | Native records/view |
| Writing assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Learning style recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Spaced repetition | records | 1 | 0 | Native records/view |
| Adaptive quiz | records | 1 | 0 | Native records/view |
| Parent dashboard | records | 1 | 0 | Native records/view |
| Achievements | records | 1 | 0 | Native records/view |
| adaptive quiz engine | records | 1 | 0 | Native records/view |
| parent insights | records | 1 | 0 | Native records/view |
| content recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| automated tutoring | records | 1 | 0 | Native records/view |
| progress prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| peer | records | 1 | 0 | Native records/view |
| dedicated routes directory all routes inline | records | 1 | 0 | Native records/view |
| limited frontend only 3 pages despite rich backend | records | 1 | 0 | Native records/view |
| real lms integration canvas blackboard adapter | integration | 1 | 0 | Provider request records only |
| payment billing for parent subscriptions | records | 1 | 0 | Native records/view |
| limited rbac student parent teacher separation unc | records | 1 | 0 | Native records/view |
| Roleplay chat | records | 1 | 0 | Native records/view |
| Leaderboard page | records | 1 | 0 | Native records/view |
| Coaching plans page | records | 1 | 0 | Native records/view |
| My sessions | records | 1 | 0 | Native records/view |
| Conversation analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deal stage progressor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitive intelligence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Objection database | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Team performance analytics | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Stalled deal clinic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| realtime coaching during calls | records | 1 | 0 | Native records/view |
| postcall analysis coaching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| competitor battlecard generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| deal probability scorer | records | 1 | 0 | Native records/view |
| playbook learner | records | 1 | 0 | Native records/view |
| negotiation simulation with multiple persona | records | 1 | 0 | Native records/view |
| objectiondatabase learn from past objecti | records | 1 | 0 | Native records/view |
| conversationanalysis real call transcript | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| competitiveintelligence retrieval | records | 1 | 0 | Native records/view |
| dealstageprogressor nextbestaction | records | 1 | 0 | Native records/view |
| realtime call coaching live audio | records | 1 | 0 | Native records/view |
| sales pipeline opportunity management | records | 1 | 0 | Native records/view |
| deal tracking with stages | records | 1 | 0 | Native records/view |
| collateralcontent repository case studies | records | 1 | 0 | Native records/view |
| sales enablement content library | records | 1 | 0 | Native records/view |
| crm integration salesforce hubspot | integration | 1 | 0 | Provider request records only |
| call recording ingestion | records | 1 | 0 | Native records/view |
| notifications or audit log | records | 1 | 0 | Native records/view |
| Generate scenario | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Grade assessment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Adaptive path | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Performance prediction | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Incident simulation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Skill gap identification | records | 1 | 0 | Native records/view |
| Scenario randomization | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Skill gap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| adaptive learning paths adjusting scenario difficulty by performance | records | 1 | 0 | Native records/view |
| scenario randomization generating training variations from domain rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| performance prediction forecasting certification pass fail | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| skill gap identification with targeted remediation | records | 1 | 0 | Native records/view |
| real world incident simulation generated from incident reports | records | 1 | 0 | Native records/view |
| scorm xapi export for enterprise lms integration | integration | 1 | 0 | Provider request records only |
| adaptive difficulty personalized learning paths | records | 1 | 0 | Native records/view |
| scenario auto generation from incident data | records | 1 | 0 | Native records/view |
| native vr platform integration unity unreal webxr | integration | 1 | 0 | Provider request records only |
| instructor dashboard with student progress views | records | 1 | 0 | Native records/view |
| completion certificate pdf generation | records | 1 | 0 | Native records/view |
| multi language support | records | 1 | 0 | Native records/view |
| payment subscription integration for b2b sales | integration | 1 | 0 | Provider request records only |
| scorm xapi lms export | records | 1 | 0 | Native records/view |
| Rules & Jobs | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 425 feature pages were visited in the browser; 423 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 149 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

149 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
