# Metadata for Junior Seminar Research Group Member

## Researcher Name

A research group member should type their name below.

- **Researcher Name**: `Joseph Oforkansi`

## Reading Syllabus Pledge

A research group member should add an X-mark to the box to indicate that they
have carefully read and understood the Junior Seminar Research Project Syllabus
and that they are ready to complete their Junior Seminar Research Project.

- [X] I read the Junior Seminar Research Project Syllabus and am ready to begin
  the completion of my Junior Seminar Research Project.

## Honor Code Pledge

A research group member should add an X-mark to the box to indicate that they
agree to adhere to the Allegheny College Honor Code during the completion of
their Junior Seminar Research Project.

- [X] I agree to adhere to the Allegheny College Honor Code during the
  completion of my Junior Seminar Research Project.

## GitHub Username

A research group member should type their GitHub username below.

- **GitHub Username**: `josephoforkansi`

## GitHub Repositories

### GitHub Repository for Research Report and Research Journal

- **Repository URL**: [URL of GitHub Repository for Research Report and Journal](https://github.com/Allegheny-Computer-Science-580-S2026/junior-seminar-project-journal-and-research-report-chapters-josephoforkansi)

### GitHub Repository for Research Prototype

- **Repository URL**: [URL of GitHub Repository for Research Prototype](https://github.com/josephoforkansi/jct-semantic-code-search)

### GitHub Repository for Research Data

- **Repository URL**: [URL of GitHub Repository for Research Data](https://github.com/josephoforkansi/jct-research-data)

## Research Project Title

A research group member should type the title of their junior seminar research
project into the following fenced code block.

```text
JCT: A Semantic Search Engine for Python Codebases Using Vector Representations of Behavioral Concepts
```

## Research Group Contributions

As a member of the Junior Seminar research group, document how you contributed
to the research community beyond your individual project. This section reflects
the collaborative nature of research work and your engagement with fellow
researchers.

### Peer Research Feedback

Document significant feedback you provided to other research group members
during presentations, demonstrations, or informal discussions. Include:

- **Researcher Name / Project**: [Logan Greer(CaddySense: Local AI-Powered Golf Performance Assistant)]
- **Feedback Provided**: [\In the GitHub issue review of the Introduction chapter, I answered the required template questions (clarity, background, definitions, assumptions/limitations, ethics, sourcing) with Yes/No responses and detailed descriptions. Key suggestions included: reducing repetition across sections (minor), strengthening differentiation from existing tools by addressing recent AI features in apps like Arccos (AI Strategy for on-course advice), TrackMan's Tracy (AI swing insights), DeepSwing (on-device AI coach with drills), and Sportsbox AI (3D motion analysis) (moderate), and adding explicit discussion of assumptions, limitations, and scope boundaries such as reliance on user-entered data quality, Phi-3 model accuracy risks, synthetic data only so far, and no real-user evaluation yet (major). Emphasized tightening flow and boosting credibility through honest scoping.\]
- **Impact**: [The feedback highlighted ways to make the "gap" argument more current and robust against 2025–2026 competitors (many now offer personalized AI feedback, some on-device). This could prompt Logan to refine competitor comparisons, deepen limitations coverage, and improve academic rigor potentially leading to a more balanced, defensible introduction in revisions.]
- **Reference**: [https://github.com/Allegheny-Computer-Science-600610-25-26/senior-comprehensive-project-journal-and-chapters-greer01/issues/9]

- **Researcher Name / Project**: [Evan Nelson / WorkoutTracker: iOS Fitness Application with Progress Tracking and Personalized Feedback]
- **Feedback Provided**: [\In the GitHub issue review of the Introduction chapter, I completed the required template questions (project clarity: Yes with summary; background: Yes with citation notes; definitions/terminology: Yes; assumptions/limitations: No, needing more explicit treatment; ethics: Yes with expansion suggestions; sourcing: Yes). Key recommendations included: reducing repetition and tightening flow across overlapping sections like personal motivation and app features (minor), better differentiating the project's "concise feedback" emphasis by acknowledging and contrasting recent AI-driven advancements in competing fitness apps such as Fitbod (AI-adapted strength plans), Zing Coach (AI-personalized programs with body scan integration), Freeletics (AI-generated coaching), and apps like Future/Caliber (data-driven customization) to bolster claims of uniqueness (moderate), and formally expanding discussion of assumptions, limitations, and scope e.g., dependence on accurate user-entered data, simplicity of rule-based (not ML/AI) feedback potentially limiting nuance, use of only synthetic/AI-generated data for testing so far, iOS-only platform, no wearable/sensor integration, and absence of real-user validation ideally in a dedicated subsection for stronger critical reflection and academic rigor (major). Overall, emphasized enhancing credibility through honest, upfront scoping and a more objective tone to align with CS senior thesis standards.\]
- **Impact**: [The feedback aims to help strengthen the introduction’s academic quality, clarity, and critical self-reflection. Addressing the major revision (explicit limitations/assumptions section) and moderate revision (tone) would significantly improve the chapter’s scholarly tone and demonstrate stronger research awareness, key expectations for a senior comprehensive project. The minor edits would make the writing more concise and reader-friendly without major restructuring. Overall, implementing these suggestions should make the introduction more polished, defensible, and aligned with computer science thesis standards.]
- **Reference**: [https://github.com/Allegheny-Computer-Science-600610-25-26/senior-comprehensive-project-journal-and-chapters-EvanNelson04/issues/10]

Example entries:

- **Student Name One / Machine Learning Bias Detection**: Suggested examining
  fairness metrics beyond accuracy; Jane incorporated demographic parity analysis
  into her evaluation framework
- **Student Name Two / Distributed Caching System**: Asked about handling
  network partitions during demo; led to important discussion about consistency
  models
- **Student Name Three / Graph Algorithm Visualization**: Recommended adding
  real-time performance comparison; Alex added this feature in Week 12

### Technical Discussions and Problem-Solving

- **Discussion Topic / Problem**: Semantic search vs keyword search limitations  
- **Your Contribution**: I explained how embedding-based similarity allows retrieval based on meaning rather than exact text matching, using examples from my JCT prototype. I demonstrated how cosine similarity enables ranking of code snippets based on intent.  
- **Outcome**: This helped clarify for other researchers how modern search systems differ from traditional approaches like grep, influencing how they thought about retrieval problems in their own projects.

- **Discussion Topic / Problem**: GitHub Actions and testing integration using uv  
- **Your Contribution**: I shared my setup for running tests using `uv run pytest` and discussed how dependency management with uv simplifies reproducibility across environments.  
- **Outcome**: This helped multiple researchers better understand how to structure automated testing workflows and improve reliability of their repositories.

- **Discussion Topic / Problem**: AST-based code analysis  
- **Your Contribution**: I discussed how Abstract Syntax Trees can be used to extract structured representations of code, and demonstrated how my system uses `FunctionDef` nodes to create semantically meaningful chunks.  
- **Outcome**: This contributed to a broader understanding within the group of how structural code analysis can be applied beyond simple text parsing.

### Research Group Meeting Participation

- **Meeting Date / Topic**: Week 6 – Prototype Design Discussion  
- **Contribution**: I shared my approach to combining AST-based chunking with semantic embeddings and explained the reasoning behind separating indexing and query processing.  
- **Value to Group**: This provided a concrete example of how to design a modular research prototype, helping others think more clearly about system architecture.

- **Meeting Date / Topic**: Week 9 – Evaluation and Metrics  
- **Contribution**: I discussed the importance of using multiple evaluation metrics such as Precision@K, Success@1, and NDCG@K to capture both retrieval accuracy and ranking quality.  
- **Value to Group**: This helped reinforce the importance of rigorous evaluation and influenced how other researchers approached their experimental design.

- **Meeting Date / Topic**: Week 11 – Code Review and Repository Structure  
- **Contribution**: I shared strategies for organizing repositories, including separating source code, evaluation data, and results into distinct directories.  
- **Value to Group**: This improved overall repository clarity and helped others align with best practices expected in research projects.

### Research Resources Shared

- **Resource**: Sentence-Transformers Documentation  
- **Shared With**: Entire research group  
- **Purpose**: Provided guidance on how embedding models work and how they can be used for semantic similarity tasks, directly relevant to multiple projects.

- **Resource**: AST Visualization Tool (https://dhv.davep.dev/)  
- **Shared With**: Entire research group  
- **Purpose**: Demonstrated how code is parsed into Abstract Syntax Trees, helping others better understand structural code analysis.

- **Resource**: Cosine Similarity Explanation (vector similarity concepts)  
- **Shared With**: Multiple researchers  
- **Purpose**: Helped clarify how similarity scoring works in embedding-based systems, which supported understanding of ranking algorithms.

## Additional Project Information

Throughout the development of this project, I actively collaborated with
Professor Luman outside of scheduled class time to refine both the
technical implementation and the research presentation of JCT. These
discussions focused on improving the structure of the repository,
strengthening the methodology in Chapter 3, and ensuring that the system
aligned with the expectations of a junior-level research prototype.

This collaboration significantly improved the clarity, depth, and
technical rigor of both the prototype and the written research report.
It also helped guide decisions related to evaluation design, system
architecture, and documentation, ultimately resulting in a more
complete and academically sound project.
