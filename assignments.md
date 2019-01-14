---
layout: default
title: Assignments
active_tab: assignments
---


<table class="table table-striped">
  <tbody>
    <tr>
      <th>Date</th>
      <th>Assignment</th>
      <th>Due On</th>
      <th>Solutions</th>
    </tr>
    {% for assignment in site.data.assignments %}
    <tr>
      <td>{{ assignment.date | date: "%b %d" }}</td>
      <td>
        <a href="{{ assignment.pdf }}">{{ assignment.title }}</a>
      </td>
      <td>
        {{assignment.due}}
      </td>
      <td>
        <a href="{{ assignment.solution }}">Solutions</a>
      </td>
    </tr>
    {% endfor %}
</tbody>
</table>

### <font color="blue">Instructions for Presentation</font>

* 30 minutes (20 min + 10 min for discussion)

* Send Dan the slides no later than 2 days before the presentation (if you are presenting on Tuesday.Thursday, send the slides to us by Sunday/Tuesday evening)

* You will be asked to grade the presentation of all other students.

### <font color="blue">Instruction for Critical Reading Essays</font>

There will be 4 critical reading essays.

Tentative deadlines for the fours critical reviews are:

* **First review**: Sep 26
* **Second review**: Oct 17
* **Third review**: Nov 14
* **Fourth review**: Dec 12

Please send the reviews to Dan and Shyam by email whenever you want. Make sure you send all four essays before the deadline listed above.
Ensure the email has the subject:

``
CIS700 Review #k, studentid
``

#### Rules
* You can choose any of the papers listed on the class' web page, but **NOT** the paper you will present in class.
* If you choose a paper that is presented in class you must send the critical essay **BEFORE** it is presented. <font color="red">You cannot send a review for a paper that has been already presented.</font>
* This does not hold for the last, long review; given the amount of work expected there, it's okay if you review a paper presented earlier.

You are encouraged to read more papers from the list, and follow up on the references in the papers listed (in some cases, you will have to do it in order to understand the paper).

In addition to get you better acquainted with key ideas and applications, the goal is to train you in reading a research paper both quickly and effectively.

#### Late Submission Policy

We allocate each student a **budget of four days** worth of late submission for the **entire semester**. Late submissions made after you have exhausted your budget will **not be graded** and you shall receive a zero. For instance, if you submitted Review 1 one day after the deadline, and Review 2 three days after the deadline, then you cannot make any more late submissions.

#### Requirements

There are two types of critical reviews; three of the four will be short reviews, and the fourth one will be a longer critical review.

##### Short Review:
Your essay should not exceed 2 pages (1 is ideal). Spend only 1-2 paragraphs introducing the problem and the approach taken. The rest of your writing should be devoted to critic, where you can address any issue you feel is important in the context of this paper.
Examples might be:
*  assumptions made in the paper;
*  technical issues (model, algorithms)
*  evaluation;
*  generality of the proposed method (is it applicable for other problems?) etc.

##### Long Review:
One of the critical reviews will longer, almost like a paper. In this case your essay should not exceed 10 pages but needs to be at least 5 pages long. As described above, the point is not to tell me what the paper is about -- spend only only 1-2 paragraphs introducing the problem and the approach taken in the paper. Instead, try to extend the paper in some way. Suggest a variation of the model, combine it with another model, analyze it in some way or, otherwise, say something interesting about it. You can also do some experiments with your extensions of the model if this is your preferred choice. Note that this essay could take you a lot more time to complete than the other three, so please plan accordingly.

### <font color="blue">Instructions for Project Proposal and Report</font>

#### Project Proposal
You need to submit a project proposal describing in 1-3 pages the following,

* What is the problem you will solve? (eg. POS tagging)
* What resources will you need? (eg. datasets)
* What structured prediction approach you plan to apply? (eg. Latent Structured SVM)
* You must have references to relevant papers on the problem and the technique you plan to use.

You should strive to make the project interesting. The project proposal should serve as a skeletal version of the final project report, and also help you identify what you will need to do.

#### Final Project Report
The final report should be 5-6 pages in 11pt font. Try to make it look like a published article. You can download the latex format files from [here](http://naacl.org/naacl-pubs/) (or any other conference).

Below are some guidelines on how to structure your report (these are just guidelines, feel free to restructure to suit your project's needs)

1. **Introduction** -- What is the problem? Why is it important? What is your approach? What is the goal of your paper?
2. **Problem Definition** --
   * Task Definition - Introduce the model and/or problem you are studying and define the notation you are going to use.
   * Algorithm Definition - If you study learning algorithm(s) experimentally this is the place to present it.
   * Expectations - How do you expect each algorithm to behave and why.
3. **Experimental Evaluation (and/or) Theoretical Evaluation** --
   * Methodology - explain the setup, the hypothes(i/e)s you want to test, evaluation metrics etc.
   * Results - quantitative results, graphs and histograms are frequently better than tables. Are the results statistically significant?
   * Discussion - Is your hypothesis supported? What conclusions can you draw?

   Try to make it clear what parts of the work are presentation of known work, what is given a new look by your presentation and what is novel in your view of the problem.
4. **Related Work** -- discuss related work and how your problem and method are different.
5. (Optional) **Future Work**
6. **Conclusion** -- summarize results. What are the key take-aways?
