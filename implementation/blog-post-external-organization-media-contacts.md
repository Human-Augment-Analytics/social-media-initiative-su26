# Implementation: AI-Driven Media Contact Discovery

## Related Procedure
This implementation improves Step 2 (Identify Potential Publishers and Writers) and Step 3 (Identify the Appropriate Contact Person) of the Blog Post Outreach Process created by Neelima Pandey. This document is not in the GitHub as she wrote it, and this just improves those steps. 

## Context and Participants
*   **Primary Investigator:** Jacob McGivern
*   **Model Used** - Claude - Sonnet 4.6 - Medium Effort

---

## Sourcing Changes:

To enable the blog post process, external organizations need to be contacted to create awareness of the work HAAG members do. These contacts are buried deep in websites and articles at each organization. 

### The Legacy Process (The Old Way)
Originally, finding external media contacts was tedious and manual effort.
1.  **Where to start:** Navigate deep, confusing university administrative directories trying to guess which department owned appropriate news articles.
2.  **No organization is the same:** Creating a process for this is difficult. Every organization and university has different titles and web formats.

### The Modern Process (The New Way)
To streamline this, I created AI-driven method utilizing the [HAAG External Blog Post Media Contacts Prompt](../blog-post-media-contacts-prompt.md). 
1.  **Attach the Prompt:** load the prompt into an LLM (such as Gemini, Claude, or ChatGPT).
2.  **Provide Variables:** Add the target university/organization and the specific focus of the research project.
3.  **Obtain Contacts:** The AI instantly synthesizes and filters institutional data, yielding exactly 5 highly relevant, verifiable starting contacts, complete with names, roles, direct emails, website directory verification links, and a strategic fit analysis.
4. **Verify instead of Search:** The social media coordinator should verify any LLM output for accuracy. However, this can better direct the search or find options quicker.

---

## Trial Run Evidence: Iowa State University (Computer Vision)

To test the effectiveness of this new process, we ran a live trial targeting **Iowa State University** for a **computer vision** research project. The system successfully returned the following five verifiable, contacts:

### 1. Mike Krapfl — News Writer, News Service
*   **Org/Unit:** University Marketing and Communications, News Service
*   **Verified Email & Source:** mkrapfl@iastate.edu — [ISU News Directory](https://www.news.iastate.edu/about)
*   **Role:** Covers natural sciences, engineering, and research centers/institutes university-wide. He writes the official press releases that outside media outlets pick up.
*   **Strategic Fit:** *Top-tier primary target.* His beat is literally "engineering and research." A computer vision project is squarely in his lane for a university-wide news release.

### 2. Angie Hunt — News Service Director / University Spokesperson
*   **Org/Unit:** University Marketing and Communications, News Service
*   **Verified Email & Source:** amhunt@iastate.edu — [ISU News Directory](https://www.news.iastate.edu/about)
*   **Role:** Oversees News Service operations and media relations; handles administrative coordination for release timing and media training.
*   **Strategic Fit:** *Secondary contact.* Highly useful if Mike Krapfl is unavailable or if the story needs escalation/media-training support for a faculty spokesperson.

### 3. Kristin Guess — News Writer, News Service
*   **Org/Unit:** University Marketing and Communications, News Service
*   **Verified Email & Source:** kguess@iastate.edu — [ISU News Directory](https://www.news.iastate.edu/about)
*   **Role:** Covers design, lecture series, and student success stories.
*   **Strategic Fit:** *Strong secondary fit.* Excellent target if our outreach angle emphasizes the student's personal journey (e.g., OMSCS/graduate student contributions) rather than focusing solely on the faculty PI.

### 4. Zach Clemens — Communications Specialist, ECE & Materials Science and Engineering
*   **Org/Unit:** College of Engineering, Engineering College Relations
*   **Verified Email & Source:** zclemens@iastate.edu — [Engineering College Relations Directory](https://www.engineering.iastate.edu/college-relations/) (Author Page: [Zach Clemens on ISU News](https://news.engineering.iastate.edu/author/zclemens/))
*   **Role:** Handles all print and online publicity specifically for the Electrical and Computer Engineering department, including its dedicated news site.
*   **Strategic Fit:** *Top-tier primary target.* Because our computer vision lab is closely aligned with electrical and computer engineering, he is the exact department-level gatekeeper we need to bypass central bureaucracy.

### 5. Breehan Gerleman — Senior Manager, Communications
*   **Org/Unit:** College of Engineering, Engineering College Relations
*   **Verified Email & Source:** breehan@iastate.edu — [ISU Engineering Profile](https://www.engineering.iastate.edu/people/profile/breehan/)
*   **Role:** Senior leader over the College of Engineering's communications team (overseeing photography, video, web, magazines, and e-newsletters).
*   **Strategic Fit:** *Escalation/CC target.* Best used for securing broader college-level amplification (such as the *Iowa Engineer* magazine or official college social channels) once the initial story has been drafted.

---

## Effectiveness and Evaluation

### What Worked:
*   **Massive Time Savings:** Sourcing these five highly specific contacts manually would have taken me over an hour of hunting through various department pages and news articles. The AI-driven prompt generated this comprehensive list with correct email addresses in under one minute.

*   **Strategic Analysis:** The inclusion of the "Strategic Fit" analysis gives insight to why certain contacts could be preferred in different situations.

### Challenges and Limitations (The Verification Rule):
*   **Hallucination:** LLMs can  hallucinate email addresses or mix up URLs. **The output MUST be human-verified** The social media coordinator must check the verifiable links the output provides for accuracy and make their own ultimate decision.

---

## Next Steps for Future Cohorts
* **More testing:** The Slack Blog Post Tracker list (at https://humanaugmente-e7j6563.slack.com/lists/T071VTSFLCV/F0BJAHSV814) has many HAAG members from outside Organization. Test the prompt and improve as necessary. Find what roles receieve the best responses as a feedback loop.


---

## Contributors
*   **Jacob McGivern** - Developed prompt parameters, executed Iowa State University trial run, and documented implementation