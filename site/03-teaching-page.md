---
title: Teaching
date: 2026-05-10
type: landing

sections:
  - block: markdown
    content:
      title: ''
      text: |
        ## Teaching Philosophy

        I consider teaching a substantive component of academic work rather than an obligation alongside research. My commitment to academia rests on the conviction that data science and AI education has become consequential for nearly every professional domain, and that careful instruction in these methods serves both individual students and the broader public that will encounter the systems they build.

        ### Active and experiential instruction

        In the classroom I draw on a range of active learning techniques to sustain engagement and encourage peer-to-peer problem solving. I use the Flipped Classroom model and Think-Pair-Share exercises alongside frequent in-class coding tasks. I bring authentic research datasets from healthcare and climate informatics into the curriculum, which gives students an opportunity to encounter the structural and ethical complications of real data rather than the cleaned versions typical of textbook exercises.

        ### Three operating commitments

        First, every topic is introduced through a concrete artifact (working code, a worked example, a small dataset) before any formal definition. The underlying principle is then derived from what students have already observed, and a student-led extension is assigned during the same class session. The sequence is diagnostic first, expository second, applied third.

        Second, I rely on frequent low-stakes assessment. Short retrieval problems open each class meeting, with answers reviewed within five minutes. This allows me to identify and address misunderstandings before the first major exam rather than after.

        Third, I maintain transparent grading. Solution rubrics are published with every assignment, which reduces grade disputes to a single exchange and helps students understand expectations in advance.

        ### Inclusive instructional design

        Data science classrooms gather students at substantially different levels of prior preparation. I design courses with multiple on-ramps: optional review modules, paired programming during lab sessions, structured office hours that I make particularly accessible to first-generation and underrepresented students, and anonymous mid-semester surveys that inform adjustments to pace, examples, and assessment format. For asynchronous content I produce shorter, modular videos rather than long single recordings, which allows students to revisit specific technical segments without scanning through extended material.

        ---

        ## Teaching Record

        Five consecutive semesters as a Graduate Teaching Assistant at UMBC across four undergraduate and graduate courses.

        - **Structured Systems Analysis and Design** (Spring 2025). Process modeling, design specifications, review sessions, grading.
        - **Advanced Database Project** (Spring 2022 to Spring 2024). Supervised graduate teams through requirements gathering, schema design, indexing, query optimization, and performance audits.
        - **Database Program Development** (Spring 2021; Spring 2022 to Spring 2024). ER modeling, normalization, indexing, transactions, SQL query optimization. Weekly recitations and lab supervision.
        - **Management Information Systems** (Spring 2022 to Spring 2024). IT systems analysis, organizational decision-making, individual and group tutoring.

        I have also delivered regular guest lectures in the UMBC Causal AI Lab (2023 to present) on causal discovery, time series modeling, and trustworthy machine learning.

        ---

        ## Courses Prepared to Teach

        ### Direct match (TA experience)
        Database Systems · Systems Analysis and Design · Software Engineering · Management Information Systems

        ### Strong match (training and research)
        Introduction to Data Science · Introduction to Programming · Data Structures · Algorithms · Discrete Mathematics · Probability and Statistics for Computer Science

        ### Graduate and advanced electives in AI, ML, and Data Science
        Artificial Intelligence · Machine Learning · Deep Learning · Data Mining · Time Series Analytics · Applied Machine Learning · Statistical Learning

        ### Specialized electives I can develop
        Trustworthy AI · Causal AI for Decision Systems · Adversarial Machine Learning · Machine Learning for Intrusion Detection · Privacy-Preserving Machine Learning

        ---

        ## Proposed New Graduate Elective: Causal AI for Decision Systems

        I have developed a complete graduate elective that is ready to offer in the first year of a faculty appointment. The course covers structural causal models, do-calculus, time series causal discovery, counterfactual reasoning, and algorithmic fairness. Project tracks draw on healthcare informatics, climate science, and security analytics, with code released as part of the open-source ecosystem associated with my research program.

        The motivation for the course is practical. Industry and academic collaborators increasingly require engineers and analysts who can recognize when a problem demands causal reasoning rather than predictive modeling. Few U.S. computer science or data science curricula offer formal treatment of these methods, and the course therefore distinguishes a graduate program while giving students a publishable project pipeline.

        Materials developed (44-slide module, ready for deployment):

        - Full lecture transcript and technical notes covering stationarity, AR and VAR models, Granger causality, and five major challenges in time series causal discovery
        - Algorithmic treatment of four paradigms: tsFCI, NOTEARS and DYNOTEARS, TCDF, TTCD, and LCM
        - Worked example applying TTCD to climate data
        - Case study applying CDANs (MLHC 2023) to ICU patient monitoring, with hands-on exercises that use the `cdans` Python package
        - Embedded quizzes for in-class assessment
        - Curated reference list

        [Sample slides (PDF)](/uploads/causal-discovery-time-series-slides.pdf) · [Lecture notes (PDF)](/uploads/causal-discovery-time-series-notes.pdf)

        > *Upload the PDFs to `static/uploads/` and verify that the links resolve.*

        ---

        ## Open-Source Software for Student Use

        The open-source software developed in my research is designed for student use without licensing or implementation barriers.

        - `pip install cdans`. Constraint-based causal discovery for autocorrelated and non-stationary time series ([GitHub](https://github.com/hferdous/CDANs)).
        - TimeGraph. Synthetic benchmark suite for evaluating causal discovery methods.
        - ClassyGlass (forthcoming). Multimodal wearable-sensor benchmark for activity and mobility analysis.

        Course projects and capstones that contribute to these packages produce student work that has currency beyond the classroom. Published code, datasets, and reproducibility audits are tangible artifacts that strengthen graduate school applications and industry resumes.

        ---

        ## Mentorship and Career Preparation

        Within the UMBC Causal AI Lab I have co-authored peer-reviewed publications with junior Ph.D. and M.S. students at venues including KDD, MLHC, AAAI, IEEE ICMLA, and IEEE PerCom. I scope literature reviews with students, draft experimental plans together, debug their pipelines line-by-line when results stall, and run mock conference presentations before submission.

        As a faculty member I will translate this pattern into structured undergraduate research and capstone supervision through several recurring practices.

        - A weekly research clinic for active student projects
        - Resume and GitHub portfolio reviews keyed to the major
        - Mock technical interview rounds twice per semester
        - A graduate school application track for students considering M.S. or Ph.D. programs

        ---

        ## Continuous Improvement

        I treat teaching as an iterative practice. I solicit student feedback through mid-semester surveys and informal check-ins so that I can adjust course design while there is still time to act on the response. Anonymous feedback is weighted equally with signed feedback. When several students share the same confusion, the responsibility for clarifying lies with me rather than with them.
    design:
      columns: '1'
---
