The data extraction form contains a column for each data item and a row for each included paper. The columns (data items) are described below. RQs refers to the research questions that are partially answered with the extracted data of the respective item.

| Data item | Description | RQs
|---|---|---|
|Extraction Assignee| Name of one of the two researchers primarily responsible for the data extraction of the paper. Can be "both". | |
|ID| S1, S2, ... (S = study)| |
|Iteration| Snowballing iteration, where one round of forward and backward snowballing is considered the same iteration. | |
|DOI| Document object identifier to link to the concrete instance of a paper. | |
|citation (in APA) | Paper citation in APA format. | |
|year | Publication year of the paper. | |
|venue | Either journal, conference, or workshop.| |
|study category | Describe what the researchers investigate by replacing X in one or more of the following three options: **(1)** X -> code comprehension **(2)** X <-> code comprehension **(3)** code comprehension -> X.<br> _Examples:_ <div>(1) identifier length -> code comprehension (impact of identifier length on CC)</div> (2) cognitive complexity metric <-> code comprehension (correlation between metric and CC, can a measure act as a proxy for CC?) <div>(3) code comprehension -> motivation of developers to debug the code (impact of CC on developer motivation).</div> We expect all included studies to fit into one of these three categories. If none is applicable, describe in short what the study is about.| 1 |
|research method and experiment design | General research method (extract only those methods related to relevant RQ concerned with measuring code comprehension/study category), e.g. controlled experiment, SW repository mining, interviews, case study, survey, ...| 2 |
|construct name | Determine the author's preferred choice to refer to the construct of source code comprehension by the following steps:<br>**(1)** Check definition **(2)** No definition? Check paper title<br>**(3)** None of the terms in the title or ambiguous? Check most frequently used term used in the paper.<br> Check the following terms: understanding / comprehension / understandability / readability / complexity / comprehensibility / analyz(s)ability / cognitive load<br>| 3 |
| construct measures | How do the researchers measure how well a participant understood code? (proxy for code comprehension; add only measures for obtaining ground truth for measuring code comprehension). E.g. time to understand code snippet, time to find  bug, percentage of correct answers given to comprehension tasks, rating of difficulty, eye tracking data, fmri data, ... | 2 |
| comprehension tasks | What exactly did the participant have to do (needs to be related to the comprehension part of the study)? E.g. determine output of a given input, provide answers to comprehension questions, find a bug, perform a cloze test, extend functionality, ... | 2 |
|#participants | Participant sample size. | 2 |
|demographics | Composition of the sample, e.g. professionals, faculty, students.| 2 |
| #snippets per participant | Number of snippets a participant had to look at (needs to be related to the comprehension part of the study). Might be a set or range of numbers if it was not the same for all participants. On the same snippet a participant might have to do several comprehension tasks. | 2 |
| snippet pool size | Pool size of snippets considered for the study and from which snippets were selected for the participants (needs to be related to the comprehension part of the study). Might be equal to #snippets per participant. | 2 |
| code snippet source |  Where did the researchers take the code snippets from? E.g. Open Source, self-made, previous study, ... | 2 |
| snippet selection criteria | What were the main criteria mentioned by the authors for the selection of their code snippets? E.g. had to be no longer than 30 lines of code, all had to be of equal cyclomatic complexity, ... If the authors describe the resulting code characteristics during selection instead of explicitly talking about selection criteria, these characteristics should also be extracted. | 2 |
| remote vs. onsite | Was the study conducted remote or onsite? | 2 |
| paper vs screen | Was the code presented to the participants on paper or on screen? | 2 |
| programming languages | Language(s) of the code snippets used in the study, e.g. C++, Java, ... | 2 |
| limitations / validity| Which study design limitations/validity threats do the authors mention? (Threats to validity considered during study design and execution.) Use classification provided by the authors. List only those relevant to the study category. | 2, 3 |
| comments | Comments on data extraction and notes for later data evaluation. | 1-4 |

