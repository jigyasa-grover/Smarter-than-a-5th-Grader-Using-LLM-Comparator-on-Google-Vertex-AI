# **Smarter than a 5th Grader? Using LLM Comparator on Google Vertex AI to find out 🎓**

![image](https://github.com/user-attachments/assets/0c7721f6-0980-4c98-8321-3010253e3159)

Ever wondered which Large Language Model (LLM) stands out not just for providing accurate responses, but also for being clear, respectful, and detail-oriented?

With the ever-expanding list of LLMs, each boasting different configurations and capabilities, it is crucial to have a way to quantitatively assess their performance. The goal is to help us select the best model for building applications that prioritize precision, safety, and ethical considerations.

Here, we shall embark on an exciting exploration using the [LLM Comparator](https://github.com/PAIR-code/llm-comparator), a cutting-edge tool from Google's Responsible Generative AI Toolkit. This tool is designed to offer a comprehensive evaluation of LLMs, allowing us to compare their ability to handle various tasks with clarity and thoroughness. By testing these sophisticated AI models against questions typically aimed at a 5th Grader (inspired by the American quiz game show called ["Are You Smarter than a 5th Grader?"](https://www.imdb.com/title/tt9845152/)), we aim to uncover which models not only perform accurately but also align with high standards of communication and respect.

![image](https://github.com/user-attachments/assets/2d3b6867-dd4c-4523-aa81-2e0862290d88)

## LLM Comparator
The [LLM Comparator](https://github.com/PAIR-code/llm-comparator) is an advanced interactive tool designed for in-depth evaluations of large language models (LLMs). It facilitates side-by-side comparisons of model responses, focusing on both the quality and safety of outputs.

This tool offers a dual-layered approach, wherein it provides:
- Quantitative assessments through numerical scores.
- Qualitative insights through detailed feedback.

![image](https://github.com/user-attachments/assets/504e6bed-4713-4c47-9fb3-c5a9a40bfcfa)

## LLM Comparator: Features
One of the standout features of the LLM Comparator is its capacity to deliver comprehensive feedback on individual responses. Developers can dive into specific responses, gaining a deeper understanding of how and why a model produces certain answers, and uncovering the nuances behind the metrics.

Beyond just numerical scores, it offers qualitative descriptions that highlight the strengths and weaknesses of each answer. This detailed analysis allows developers to pinpoint exact areas where a model excels or falls short, whether they are comparing different models, evaluating multiple versions of the same model, or testing various prompting strategies. This capability is crucial for iterative development, helping developers fine-tune models to enhance their performance and safety.

## LLM Comparator: Value Addition
The tool is particularly valuable for developers working on refining LLMs. It provides a clear, visual interface to compare model outputs across different categories, making it easier to assess how each model performs in various contexts. This feature helps users analyze performance based on criteria set by developers, facilitating a more targeted and effective evaluation process.

The LLM Comparator enables users to analyze performance via categories created by developers and shows, side-by-side, how well each model did within each category.

By leveraging the power of another LLM to evaluate the results, the LLM Comparator adds an additional layer of analysis, allowing users to explore and validate findings with greater accuracy. This approach ensures that the feedback and insights provided are robust and actionable, aiding developers in their quest to create more reliable and useful AI models.

## Educational Experiment
To assess these models, let us conduct a series of tests using questions across a variety of subjects that are common in a fifth-grade curriculum. This includes math problems that challenge numerical reasoning, science questions that test comprehension of basic concepts, and language arts inquiries that gauge grammar and reading comprehension skills. By covering such a broad range of topics, we want to ensure a well-rounded evaluation of each model’s capabilities.

Our goal is to determine if AI can achieve or surpass the problem-solving abilities of a young student. This comparison is not just about seeing if the AI can answer questions correctly; it’s about understanding how effectively it handles different types of queries and whether its responses demonstrate a level of insight and coherence comparable to that of a fifth-grader.

In addition to comparing different AI models, we will also explore how various prompting strategies influence their performance. This aspect of our analysis helps identify which models are most adept at handling specific types of questions and provides insights into how to fine-tune prompts for optimal results.

Essentially, this evaluation will help pinpoint which models excel in educational scenarios, guiding future developments in AI to enhance its effectiveness and reliability. Through this detailed comparison, we aim to uncover the true extent of AI’s capabilities in an engaging and educational context.

Check out the [step-by-step tutorial here](https://github.com/jigyasa-grover/Smarter-than-a-5th-Grader-Using-LLM-Comparator-on-Google-Vertex-AI/blob/main/smarter_than_a_5th_grader_llm_comparator.ipynb) and the results embedded or [here](https://github.com/jigyasa-grover/Smarter-than-a-5th-Grader-Using-LLM-Comparator-on-Google-Vertex-AI/blob/main/json_for_llm_comparator.json) in raw form.

## Bottom Line
While AI tools like the LLM Comparator offer powerful automated evaluations, they can’t always anticipate the specific needs or interests of developers Ultimately, having a human in the loop is crucial, especially when dealing with issues that are delicate, nuanced, or related to safety concerns. For instance, certain nuances in language or context might be missed by the AI but are essential for particular use cases. This is where human oversight becomes invaluable, allowing developers to address specific concerns and tailor evaluations to their needs.

The LLM Comparator enhances this human-AI collaboration by allowing users to define custom functions to check for particular elements in model responses. This customization ensures that the evaluation is not just a one-size-fits-all process but is adapted to the unique requirements of each project. It enables developers to probe deeper into the responses, uncovering insights that standard metrics might overlook.

As LLM performance continues to advance, it is crucial for developers to move beyond aggregated benchmark scores and perform more granular assessments of model capabilities. The human-in-the-loop approach facilitated by tools like the LLM Comparator allows for a detailed analysis of model behavior. By integrating human judgment into the evaluation process, developers can more accurately gauge how well a model performs in real-world scenarios, ensuring that it meets both technical and contextual requirements. This nuanced analysis helps in refining models to better align with specific needs and addresses any potential gaps that automated systems might miss.













