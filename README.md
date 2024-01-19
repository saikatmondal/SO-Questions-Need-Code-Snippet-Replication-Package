# Can We Identify Stack Overflow Questions Requiring Code Snippets? Investigating the Cause & Effect of Missing Code Snippets

** Abstract ** On the Stack Overflow (SO) Q&A site, users often request solutions to their code-related problems (e.g., errors, unexpected behavior). Unfortunately, they often miss required code snippets during their question submission. Such a practice could prevent their questions from getting prompt and appropriate answers. 
In this study, we conduct an empirical study investigating the cause & effect of missing code snippets in SO questions whenever required. 
In this paper, our contributions are threefold.
First, we analyze how the presence or absence of required code snippets in SO questions affects the correlation between question types (missed code, included code after requests & had code snippets during submission) and corresponding answer meta-data, such as the presence of an accepted answer.
According to our analysis, the chance of getting accepted answers is three times higher for questions that include required code snippets during their question submission than those that missed the code.
We also investigate the confounding factors (e.g., user reputation) that can affect questions receiving answers besides the presence or absence of required code snippets. We found that such factors do not hurt the correlation between the presence or absence of required code snippets and answer meta-data.
Second, we surveyed 64 practitioners to understand why users miss necessary code snippets.
About 60% of them agree that users are unaware of whether their questions require any code snippets.
Third, we thus extract four text-based features (e.g., keywords, POS-based patterns) and build six Machine Learning (ML) models to identify the questions that need code snippets. 
Our models can predict the target questions with 86.5% precision, 90.8% recall, 85.3% F1-score, and 85.2% overall accuracy, which are highly promising. 
Our work has the potential to (a) save significant time in programming question-answering and (b) improve the quality of the valuable knowledge base by decreasing unanswered and unresolved questions.
