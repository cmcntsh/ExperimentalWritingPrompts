# Experimental Writing Prompts

Other places where I have writing prompts:

* https://github.com/cmcntsh/PoWeRWritingGradStudents
* https://github.com/cmcntsh/NURS7702_WritingExpectations
* Analyzing evidence https://github.com/cmcntsh/NotesJHEvidenceBasedPractice5thEdition

## Copy Editing

Prompt: Comprehensive Copyediting Framework (from SuperHuman newsletter sent 11/07/2025 https://www.superhuman.ai/p/musk-gets-1-trillion-pay-package?utm_source=superhuman&utm_medium=newsletter&utm_campaign=musk-gets-1-trillion-pay-package&_bhlid=acb0efb36650236317e1f11bebe7c61c99cda85d)

```
Prompt: Act as a meticulous copy editor for long-form content (blog posts, newsletter articles, LinkedIn posts, YouTube scripts, marketing emails, etc.). For any text I provide, work through these steps in order—confirming with me before moving to the next step.

Step 1 – Structure
Goals: logical flow, clarity, and coherence.
Diagnose the current structure (intro → body → close, section order, transitions).
Identify gaps, repetition, and any off-topic detours.
Give specific, actionable fixes (e.g., “Move section B before A,” “Split paragraph 3 into two,” “Add a bridge sentence after X”).

Step 2 – Content
Goals: specificity, point of view, and reader value.
Flag vague claims and suggest concrete details (data points, names, timelines, definitions).
Propose quick-win upgrades: tips, reasons, mistakes to avoid, lessons learned, mini-stories, examples, citations/research.

Step 3 – Grammar & Clarity
Goals: correctness and readability.
List misspellings, punctuation errors, and style inconsistencies.
Highlight passive voice, nominalizations, filler, and hedging.

```

### Experimental Prompts (Not Ready for Prime Time Yet)

#### Paragraph and Sentence Reader Interpretation Analysis

Prompt: Paragraph and Sentence-Level Reader Interpretation Analysis (Crafted with help of ChatGPT 11/2/2205)

```

---

**Role:**
You are an expert writing analyst trained in George Gopen’s *Reader Expectation Approach* and rhetorical clarity principles. Your task is to help the writer ensure that readers will interpret the writing accurately, effortlessly, and as intended.

**Task:**
Analyze the given text paragraph by paragraph and sentence by sentence. For each paragraph, first assess the paragraph as a whole; then analyze each sentence individually for clarity, coherence, and reader expectations.

**Instructions:**

For each **paragraph**, do the following:

1. **Paragraph Overview**

   * Identify the paragraph’s *main point or purpose*.
   * State whether the topic sentence clearly signals what the paragraph is about.
   * Note whether the paragraph’s ideas progress logically and smoothly.
   * Indicate if the final sentence delivers the key takeaway or emphasis.
   * Comment on overall clarity, flow, and alignment with reader expectations.

2. **Sentence-by-Sentence Analysis**
   For each sentence in the paragraph, evaluate the following dimensions:

   **A. Reader Expectations About Structure**

   * **Topic position:** Does the sentence begin with familiar or contextual information?
   * **Stress position:** Does the sentence end with the most important or new information?
   * **Subject continuity:** Does the subject connect logically to the prior sentence’s focus?
   * **Placement in sequence:** Is this sentence’s position appropriate for the reader’s processing order?

   **B. Clarity and Coherence of Thought**

   * Does the sentence express one main idea clearly?
   * Are the logical relationships between ideas explicit (e.g., cause, contrast, result)?
   * Is any pronoun or reference ambiguous?

   **C. Information Management**

   * Is the subject concise and easy to hold in working memory?
   * Is the sentence length appropriate for clarity?
   * Are modifiers close to the words they modify?

   **D. Reader Empathy and Purpose**

   * Is the sentence’s content appropriate for the reader’s level of knowledge and interest?
   * Is the purpose (to inform, argue, guide, etc.) clear?
   * Is the tone suitable and consistent?

   **E. Language Precision**

   * Are word choices concrete and specific rather than vague or abstract?
   * Are verbs strong and active rather than nominalized or passive (when possible)?
   * Is key terminology consistent?
   * Is parallel structure used correctly (if applicable)?

3. **Summary of Paragraph Findings**

   * Identify the strongest elements contributing to clarity.
   * Identify the main barriers to correct reader interpretation.
   * Suggest specific, concrete revisions that would improve alignment with reader expectations and ensure the reader interprets the meaning as intended.

---

**Output Format Example:**

Paragraph 1 Overview:
(Main point, flow, clarity comments)

Sentence 1:
- Topic position: ...
- Stress position: ...
- Clarity and logic: ...
- Reader empathy: ...
- Suggested revision (if needed): ...

Sentence 2:
(...same structure...)

Paragraph Summary:
- Strengths: ...
- Issues: ...
- Recommendations: ...

---

**Input Example:**
“[Paste the text to analyze here.]”

---

```

#### Improve Flow and Connectedness

Prompt: Add transition words (from SuperHuman newsletter sent 10/30/2025 https://www.superhuman.ai/p/big-tech-kicks-off-earnings-season?utm_source=superhuman&utm_medium=newsletter&utm_campaign=big-tech-kicks-off-earnings-season&_bhlid=dd54f82af461cf7f1022066425b76d36e23ceb98)

```
Prompt: Your task is to improve the following text to create a seamless, engaging reading experience — while fully preserving its core message, tone, and intent.

Step 1: Enhance Flow and Readability
Apply the following flow-enhancement techniques naturally and selectively, only where they truly elevate the content:
Contrast: while, whereas, on the other hand
Reason: so, since, that’s why, therefore
Exception: but, however, alternatively
Example: like, such as, including
Detail: also, in addition, in other words

Guidelines:
Ensure every paragraph flows smoothly into the next
Strengthen logical transitions and narrative momentum
Build bridges between ideas for clarity and rhythm
Use the above connectors only when they serve the tone and context
Avoid overusing or forcing them — focus on natural readability

Step 2: Explain the Enhancements
After producing the improved version, analyze your changes using this format for each key edit:
Location/Section: [e.g., Introduction paragraph]
Before: “…”
After: “…”

Technique(s) Applied: [e.g., Contrast + Reason]
Why It Improves Flow: [brief explanation]

Text to Improve:
<TEXT>
[Your text here]
</TEXT>
```



#### Evaluate the Discourse Relations Between the Topic of a Paragraph and Each Sentence

This prompt relies on discourse relations as defined in Rhetorical Structure Theory (RST). It is a way to analyze how each sentence is related to the main topic in a paragraph. (Some paragraphs are more cohesively constructed than others.) The prompt worked in ChatGPT on its own, but it may do better if RST background information is loaded into ChatGPT first.

* RST discourse relationship definitions page: https://www.sfu.ca/rst/01intro/definitions.html

Stand-alone prompt:

```
Here is my analysis request. You are an expert in rhetorical structure theory. I need you to help me evaluate the discourse relationship between the main topic of a paragraph and each sentence in the paragraph. Please list each sentence on a separate line and number each sentence. For each sentence please assign a discourse relation. (The available relationship options are antithesis, background, concession, enablement, evidence, justify, motivation, preparation, restatement, summary, circumstance, condition, elaboration, evaluation, interpretation, means, cause, result, otherwise, purpose, solutionhood, unconditional, unless, conjunction, contrast, disjunction, joint, list, restatement, sequence, and no discourse relationship identified.) In addition, please rate the strength of the relationship between the topic and the sentence. (The available strength options are no relationship, weakly related, and strongly related.) Here is the main topic of the paragraph: "[paste topic sentence here]" Here are the sentences in the paragraph: "[paste paragraph sentences here]"![image](https://github.com/cmcntsh/PoWeRWritingGradStudents/assets/32034299/cba2fcbb-ff1e-4615-afd5-bbcfaf2784ee)
```

Prompts to load RST background information: These prompts are submitted in succession, then the stand-alone prompt (above) with the text for analysis is submitted at the end. The text for the background prompts comes from the RST definitions web page link given above.

```
I'm going to give you some background on Rhetorical Structure Theory and then I'm going to give you a request to analyze some text based on the background. Don't respond until I give you a request that begins with "Here is my analysis request:"
```

```
Here is the background about Rhetorical Structure Theory: The basic paper on RST, published in Text 8(3), was derived from an earlier report, ISI-RS-87-190. That report had, along with the relation definitions, one or more examples and some commentary for each relation. Portions of that information are available from the bibliographies section in this website, and an example has also been included for each of the four newer relations mentioned below. Some of the examples are from other sources, including the analyses in other sections of the website. To find these examples, look just below each table of relation definitions.

Each element of the definition is implicitly embedded in a constraint formula as follows: "It is plausible to the analyst that it was plausible to the author that ... ."

On terminology in definitions: N stands for nucleus, S for satellite, W for writer (author, speaker) and R for reader (hearer.) For some brevity: in many places, N and S stand for the situations presented by N and S; N and S never stand for the text of N or S. Situation is a broad cover term that ranges over propositions or beliefs, actions whether realized or not, desires to act and approval for another to act. Similarly, positive regard is a broad attitudinal term that ranges over belief, approval of ideas, desire to act, and approval for another to act, all identifiably positive. Positive regard and belief (with its cognates), and plausible above are all degree terms, not binary.

Notice that the name of the relation does not enter into the use of the definition. Finding good names for all of the relations is difficult or perhaps impossible, so some of the definitions will seem inappropriate for the name; see, for example, Justify.

The relations are classified into two main types: nucleus-satellite and multinuclear (see the Introduction). They can also be classified according to whether they are Presentational or Subject Matter. Presentational relations are those whose intended effect is to increase some inclination in the reader, such as the desire to act or the degree of positive regard for, belief in, or acceptance of the nucleus. Subject matter relations are those whose intended effect is that the reader recognizes the relation in question.

In the three tables below, we present the relation name and its definition. By clicking on the relation name, you can see further examples and comments on each relation.
```

```
Definitions of Presentational Relations
Relation Name
Constraints on either S or N individually
Constraints on N + S
Intention of W
Antithesis	on N: W has positive regard for N	N and S are in contrast (see the Contrast relation); because of the incompatibility that arises from the contrast, one cannot have positive regard for both of those situations; comprehending S and the incompatibility between the situations increases R's positive regard for N	R's positive regard for N is increased
Background	on N: R won't comprehend N sufficiently before reading text of S	S increases the ability of R to comprehend an element in N	R's ability to comprehend N increases
Concession	on N: W has positive regard for N
on S: W is not claiming that S does not hold;	W acknowledges a potential or apparent incompatibility between N and S; recognizing the compatibility between N and S increases R's positive regard for N	R's positive regard for N is increased
Enablement	on N: presents an action by R (including accepting an offer), unrealized with respect to the context of N	R comprehending S increases R's potential ability to perform the action in N	R's potential ability to perform the action in N increases
Evidence	on N: R might not believe N to a degree satisfactory to W
on S: R believes S or will find it credible	R's comprehending S increases R's belief of N	R's belief of N is increased
Justify	none	R's comprehending S increases R's readiness to accept W's right to present N	R's readiness to accept W's right to present N is increased
Motivation	on N: N is an action in which R is the actor (including accepting an offer), unrealized with respect to the context of N	Comprehending S increases R's desire to perform action in N	R's desire to perform action in N is increased
Preparation	none	S precedes N in the text; S tends to make R more ready, interested or oriented for reading N	R is more ready, interested or oriented for reading N
Restatement	none	on N + S: S restates N, where S and N are of comparable bulk; N is more central to W's purposes than S is.	R recognizes S as a restatement of N
Summary	on N: N must be more than one unit	S presents a restatement of the content of N, that is shorter in bulk	R recognizes S as a shorter restatement of N
```

```
Definitions of Subject Matter Relations
Relation Name
Constraints on either S or N individually
Constraints on N + S
Intention of W
Circumstance	on S: S is not unrealized	S sets a framework in the subject matter within which R is intended to interpret N	R recognizes that S provides the framework for interpreting N
Condition	on S: S presents a hypothetical, future, or otherwise unrealized situation (relative to the situational context of S)	Realization of N depends on realization of S	R recognizes how the realization of N depends on the realization of S
Elaboration	none	S presents additional detail about the situation or some element of subject matter which is presented in N or inferentially accessible in N in one or more of the ways listed below. In the list, if N presents the first member of any pair, then S includes the second:
set :: member
abstraction :: instance
whole :: part
process :: step
object :: attribute
generalization :: specific
R recognizes S as providing additional detail for N. R identifies the element of subject matter for which detail is provided.
Evaluation	none	on N + S: S relates N to degree of W's positive regard toward N.	R recognizes that S assesses N and recognizes the value it assigns
Interpretation	none	on N + S: S relates N to a framework of ideas not involved in N itself and not concerned with W's positive regard	R recognizes that S relates N to a framework of ideas not involved in the knowledge presented in N itself
Means	on N: an activity	S presents a method or instrument which tends to make realization of N more likely	R recognizes that the method or instrument in S tends to make realization of N more likely
Non-volitional Cause	on N: N is not a volitional action	S, by means other than motivating a volitional action, caused N; without the presentation of S, R might not know the particular cause of the situation; a presentation of N is more central than S to W's purposes in putting forth the N-S combination.	R recognizes S as a cause of N
Non-volitional Result	on S: S is not a volitional action	N caused S; presentation of N is more central to W's purposes in putting forth the N-S combination than is the presentation of S.	R recognizes that N could have caused the situation in S
Otherwise	on N: N is an unrealized situation
on S: S is an unrealized situation	realization of N prevents realization of S	R recognizes the dependency relation of prevention between the realization of N and the realization of S
Purpose	on N: N is an activity;
on S: S is a situation that is unrealized	S is to be realized through the activity in N	R recognizes that the activity in N is initiated in order to realize S
Solutionhood	on S: S presents a problem	N is a solution to the problem presented in S;	R recognizes N as a solution to the problem presented in S
Unconditional	on S: S conceivably could affect the realization of N	N does not depend on S	R recognizes that N does not depend on S
Unless	none	S affects the realization of N; N is realized provided that S is not realized	R recognizes that N is realized provided that S is not realized
Volitional Cause	on N: N is a volitional action or else a situation that could have arisen from a volitional action	S could have caused the agent of the volitional action in N to perform that action; without the presentation of S, R might not regard the action as motivated or know the particular motivation; N is more central to W's purposes in putting forth the N-S combination than S is.	R recognizes S as a cause for the volitional action in N
Volitional Result	on S: S is a volitional action or a situation that could have arisen from a volitional action	N could have caused S; presentation of N is more central to W's purposes than is presentation of S;	R recognizes that N could be a cause for the action or situation in S
```

```
Definitions of Multinuclear Relations
Relation Name
Constraints on each pair of N
Intention of W
Conjunction	The items are conjoined to form a unit in which each item plays a comparable role
R recognizes that the linked items are conjoined
Contrast	No more than two nuclei; the situations in these two nuclei are (a) comprehended as the same in many respects (b) comprehended as differing in a few respects and (c) compared with respect to one or more of these differences	R recognizes the comparability and the difference(s) yielded by the comparison is being made
Disjunction	An item presents a (not necessarily exclusive) alternative for the other(s)
R recognizes that the linked items are alternatives
Joint	None	none
List	An item comparable to others linked to it by the List relation	R recognizes the comparability of linked items
Multinuclear Restatement	An item is primarily a reexpression of one linked to it; the items are of comparable importance to the purposes of W	R recognizes the reexpression by the linked items
Sequence	There is a succession relationship between the situations in the nuclei	R recognizes the succession relationships among the nuclei.
```

#### Edit for clarity and conciseness

Prompt

```
Please review my text for clarity and conciseness. Check for any areas where the language could be clearer or more concise. If you identify any redundant or overly complex sentences, suggest specific revisions to enhance clarity and brevity. Here is the text: "[past text here in quotes]".
```

#### Edit for consistent tone

Prompt

```
Please review my text for consistent tone in academic writing. Ensure that the language is formal, objective, and avoids any elements that may be too casual or subjective. If you identify any instances where the tone may need adjustment for a more formal and scholarly demeanor, please provide specific suggestions. Here is the text: "[past text here in quotes]".
```

#### Generate a writing report and suggested revision 

Prompt: (I get inconsistent results with the report, but the revision text is not bad.)

```
Please generate a report about the following text, which is enclosed by double quotes, based on the following criteria:
Identify grammar, syntax, usage, spelling, and punctuation errors and suggest specific improvements;
in addition, Report document statistics;
in addition, Report vocabulary statistics:
in addition, Report the readability score;
in addition, Report the tone type (available options are Formal, Informal, Optimistic, Worried, Friendly, Curious, Assertive, Encouraging, Surprised, or Cooperative);
in addition, Report the intent type (available options are  Inform, Describe, Convince, or Tell A Story);
in addition, Report the audience type (available options are General, Knowledgeable, or Expert);
in addition, Report the style type (available options are formal or informal);
in addition, Report the emotion type (available options are mild or strong);
in addition, Report the domain type (available options are General, Academic, Business, Technical, Creative, or Casual);
in addition, Report the Flesch-Kincaid Grade Level.
Please provide revised text that adheres to the following instructions:
If the Flesh-Kincaid Grade level of the text is higher than 15, can you rewrite the text so that the grade level should be around 15, assuming that the audience type is Knowledgeable or Expert;
In addition, if the domain type of the text is Casual, then the text that you rewrite should have a domain type that is either academic or technical;
In addition, if the intent type of the text is Convince, then the text that you rewrite should have an intent type that is either Describe or Inform;
In addition, if the style type of the text is Informal, then the text that you rewrite should have a style type that is Formal;
In addition, if the emotion type of the text is Strong, then the text that you rewrite should have a style type that is Mild.
Here is the text: "[paste text here]"
```
