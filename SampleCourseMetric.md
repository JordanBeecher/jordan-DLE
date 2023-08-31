# Sample course metric 

## 1. Provide a description of the desired metric and what you intend to measure

The Difficulty Alignment Score (DAS) is a proposed metric that intends to measure the perceived difficulty of a course. “Alignment” here refers to the level of difficulty and appropriateness of a course, in relation to a learner’s existing level of understanding and comprehension.

Courses that are too basic or too difficult for a learner could lead to frustration and disengagement. Courses should be appropriately challenging, though different learners have different levels of ability and appetites for challenge. While frameworks may exist for managing course content and defining levels of complexity, this is not immediately apparent to learners prior to beginning a course. Descriptors such as beginner, immediate, or advanced might not be well understood. It is therefore important that courses align with learner expectations and serve their target learners with an appropriate level of difficulty.

The DAS offers a simple quantifiable measure to ensure that the content and difficulty of a course are aligned to a learner and their likely expectations, and that course content is appropriately challenging, fostering a positive and productive learning experience.

In the simplest terms, the DAS can answer the questions, "Are beginner courses too easy? Are advanced courses too hard?

## 2. Explain what actions you would take as a result of this metric. Is it a proactive or reactive measure?

The DAS can be used as both a proactive and reactive measure. It can be used to evaluate the extent to which courses are targeting the intended audience, identify necessary course adjustments, and help inform future course design. 

_For learners_ it could be used to recommend courses that are suited to their needs. If a learner consistently produces low scores, then a lower-difficulty course might be recommended to them. Conversely, learners producing high scores regularly might be targeted for higher-difficulty courses.

_For content creators_, at a course level, good scores could indicate that a course is well-targeted and reaching its intended audience. Poor scores could indicate that a course's content is not appropriate for its intended learners, or that learners are not finding best-fit courses. For example if a course on the basics of data literacy aimed at beginner learners is found to be difficult by a significant number of learners, then it might be prudent to introduce a more basic course, or adjust the level of difficulty. If learners can themselves be classified, either by self scoring, or by other means, the DAS can become richer. Table A below illustrates some idealised DAS scores for three courses, across three levels of learner, where “0” represents a neutral difficulty, not too easy, not too difficult.

### Table A. Example DAS scores
<table>
  <tr>
   <td>
   </td>
   <td>Beginner course
   </td>
   <td>Intermediate course
   </td>
   <td>Advanced course
   </td>
  </tr>
  <tr>
   <td>Beginner learner
   </td>
   <td>0
   </td>
   <td>1
   </td>
   <td>2
   </td>
  </tr>
  <tr>
   <td>Intermediate learner
   </td>
   <td>-1
   </td>
   <td>0
   </td>
   <td>1
   </td>
  </tr>
  <tr>
   <td>Advanced learner
   </td>
   <td>-2
   </td>
   <td>1
   </td>
   <td>0
   </td>
  </tr>
</table>

Note: Values based on following scoring system: -2 = very easy; -1 = easy, 0= neutral; 1 = difficult; 2 = very difficult.

The DAS could also complement other measures such as completion rate and the number of hints taken across lessons and courses and help content creators to identify difficulty spikes and or gaps across a curriculum. 

## 3. Detail what data and in what form (transactional/summary/etc) you would need to calculate this metric.

To produce a DAS we rely on some primary data to inform how difficult a given user found a course. 

While perceived difficulty is subjective, the use of a likert scale helps to quantify a subjective experience. Though feedback is welcomed at several stages during a DataCamp course, for the DAS I propose to routinely pose the question upon completion of a course: “How difficult did you find this course?”. Learners will be prompted to answer on a 5-point likert scale: very easy, easy, neutral, difficult, very difficult, each with a corresponding value ranging from -2 (very easy) to 2 (very difficult). 

Scores can be collated by course, from which means and other measures can be calculated to describe the perceived difficulty. Scores can also be collated by learner, which can be used to infer if a user is accessing content appropriately challenging for them personally.

For new learners who are yet to complete a course, a preliminary DAS may be generated during the onboarding process, from a self-scoring exercise based on their current abilities. The DAS could also be triangulated with existing (or otherwise) measures of learners' competency for a given subject to further improve course targeting. 

## Summary 

By revealing how the difficulty level of courses are perceived by learners, the DAS supports DataCamp to detect and remediate difficulty-related issues with new and existing courses, maximise learner satisfaction and offer more personalised learner journeys, potentially supporting longer-term engagement with the platform.
