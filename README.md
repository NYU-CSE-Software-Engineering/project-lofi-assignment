## **Project Assignment: The Discovery & Design Exchange**

### **Rationale: The "Lost in Translation" Challenge**

In software engineering, the most expensive mistakes aren't made in the IDE; they are made in the conference room. A developer who builds exactly what a customer *says*—without clarifying what they actually *need*—often delivers a product that misses the mark entirely.

This assignment simulates the **Discovery Phase**. You will practice active listening and real-time technical translation. Your goal is to move from a vague concept to a visual blueprint, ensuring the "mental model" of the customer matches the "architectural model" of the developer.

---

### **Phase 1: The Discovery Session (In-Class)**

The class will be divided into paired teams. You will have two **30-minute blocks** to conduct your interviews.

* **Block 1 (35 Mins):** Team A (Customer) pitches to Team B (Developer).
* **Transition (5 Mins):** Quick stretch and role swap.  
* **Block 2 (35 Mins):** Team B (Customer) pitches to Team A (Developer).

#### **The Interview Breakdown:**

* **The Pitch (10 Minutes):** Customers present their project proposal. Focus on the user's pain points and the core "Must-Have" features. This should likely include an overview of Section 2.0 of the team's project specification. After the meeting, the customer group should likely make their project proposal available to the developer group (save as a PDF and email to the point of contact!)
* **The Deep Dive (35 Minutes):** Developers lead this portion. Interrogate the requirements. Ask about edge cases, user flow, and data constraints.  
  * *Note:* Take exhaustive notes; these are your only resources for the offline design phase.

---

### **Phase 2: The Offline Deliverables**

Working as a team, you will translate your interview notes into a visual design. **All low-fidelity diagrams must be hand-drawn** to focus on logic and structure rather than digital aesthetics.

#### **Requirement 1: Low-Fidelity Wireframes**

Sketch the **three most critical screens** of the application. Focus on UI placement, navigation elements, and content priority. Use "gray-box" techniques (boxes for images, lines for text). These images must be hand-sketched. The use of a drawing or diagramming tool will invalidate the submission, and a 0 grade will be assigned to the team. There is a significant rationale for requiring these images to be *hand-sketched*.

#### **Requirement 2: System Flowchart**

Map out the "Happy Path" of the primary user goal (e.g., from landing page to successful data submission).

* **Format:** This must be a separate, logical sequence of steps using standard symbols (Ovals for Start/End, Rectangles for Processes, Diamonds for Decisions). You are permitted to use a drawing or diagramming tool for these images.
* **Resources:** Since flowcharting is a fading art, please review these guides before drawing:  
  * [Lucidchart’s Guide to Flowchart Symbols](https://www.lucidchart.com/pages/flowchart-symbols-meaning-explained)  
  * [Visual Paradigm: Flowchart Tutorial](https://www.visual-paradigm.com/guide/flowchart/what-is-flowchart/)
* **Contributions:** A single page that details what each member of the team contributed to for this assignment. Can be a plain text listing.

---

### **Phase 3: Submission Instructions**

You will submit your work via **Brightspace**. Accuracy and legibility are key.

1. **Scanning:** Use a mobile scanning app (e.g., Adobe Scan, Microsoft Lens, or the Notes app on iOS) or a printer/scanner to capture your hand-drawn work.  
2. **Formatting:** Compile all sketches, digrams, and contribution page into **one single PDF file**.  
   * *Pages 1 to X:* The Wireframes.  
   * *Pages X+1 to Y:* The Flowchart (ensure it is captured as a clear, sequential series of images).
   * *Page Y+1:* The team contributions listing.
3. **Brightspace Upload:** Submit the PDF to the appropriate assignment in Brightspace. One team member can do this, and it will be submitted for the entire team.
4. **GitHub Repo Upload:** Add the PDF to the `docs/lofi` directory in your team's repo on GitHub. One individual can do this. A branch, pull request (PR), and code review (CR) are required. The uploader should create the branch and open the PR, and another member of the team *must* perform a code review and approve the PR. (The code reviewer should carefully ensure all images are present in the single PDF upload.) The uploader must be the person to merge the PR into the `main` branch of the repo (assuming that's the name).

---

### **Assessment Criteria**

* **Translational Accuracy:** Do the diagrams reflect the requirements discussed in the 30-minute session?  
* **Flowchart Logic:** Does the flowchart account for basic user decisions (e.g., "Is the user authenticated, or is it just a straight line?")
* **Legibility:** Can a third party (the "Customer") understand the layout and logic without your verbal explanation?

---

### Grading Rubric

The grading rubric is [available as a separate file](rubric.md) in this repository.
