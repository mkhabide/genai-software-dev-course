# Generative AI Application Development: Vocabulary

This starter vocabulary collects practical terms from the [generative AI applications research report](../01-genai-applications-research/research.md). The definitions are written for discussing how GenAI applications work in real organizations; the list can grow as the course introduces new concepts.

| Term | Meaning in practice |
|---|---|
| **Generative AI (GenAI)** | AI that creates or transforms content—such as text, images, code, or audio—in response to an instruction or other input. |
| **Large language model (LLM)** | A model trained on large amounts of text to interpret and generate language. It can write fluent answers, but fluency alone does not make an answer correct. |
| **Prompt** | The instruction and supporting information given to a model to guide its response. A good prompt makes the task, context, constraints, and desired output clear. |
| **Context** | Information available to the model for a particular request, such as the conversation, relevant documents, or task details. Missing or irrelevant context can lead to poor results. |
| **Grounding** | Connecting a model's response to trusted source material—such as approved company documents—rather than relying only on what it learned during training. |
| **Retrieval** | Finding and supplying relevant information from a knowledge source, often before asking a model to answer. Retrieval quality affects whether an answer is useful and well-supported. |
| **Citation** | A reference that points to the source used for an answer. Citations help people check an answer, but they still need to verify that the source actually supports the claim. |
| **Hallucination (confabulation)** | Output that sounds plausible but is invented, inaccurate, or unsupported. In high-impact workflows, the application should make uncertainty visible and provide a safe way to verify or escalate. |
| **Access control** | Rules that determine who can view or change data and perform actions. A GenAI assistant should respect the same permissions as the systems and documents it connects to. |
| **Integration** | A connection between the AI application and other tools or data systems, such as a customer-support platform, company document store, or electronic health record. |
| **Workflow** | The sequence of steps people and software follow to complete a task. A GenAI feature works best when it fits the real workflow, including review and exception handling. |
| **Human-in-the-loop** | A design in which a person reviews, approves, or corrects the AI's work at an important point—for example, checking a generated clinical note before it enters a medical record. |
| **Escalation** | Handing a request to a person or a more appropriate process when the AI lacks enough information, encounters a sensitive case, or cannot act safely. |
| **Audit trail** | A record of relevant events, such as the input, sources consulted, output, actions taken, and approvals. It supports investigation and accountability, subject to privacy and retention rules. |
| **Provenance** | Information about where content or data came from and how it was created or changed. Provenance matters when checking rights, trustworthiness, or whether generated media could be mistaken for a real record. |
| **Evaluation** | Testing an AI application against representative tasks and agreed measures, such as answer accuracy, task completion, safety, and user experience. It should include difficult and unusual cases, not just ideal examples. |
| **Model confidence** | An estimate or signal about how certain a model or system is about an output. It is not automatically a guarantee of correctness and should be validated before using it to decide whether to trust an answer. |
| **Ambient clinical documentation** | Drafting clinical notes from a clinician-patient conversation captured in the background. The clinician remains responsible for checking the draft for missing, misattributed, or incorrect details. |
| **Generative vs. predictive AI** | Generative AI creates or transforms content; predictive AI estimates an outcome or property, such as a likely structure. Either can produce useful hypotheses, but neither result alone proves real-world performance. |
