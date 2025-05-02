# Cloud Lab Codebot Comparison
## Document Overview and Purpose
This document provides a comprehensive comparison of five distinct codebots: Amazon Q Developer, Gemini Code Assist, GitHub Copilot, Anaconda AI Assistant, and Jupyter AI. The comparison is structured into three main sections: an overview of the key features of each codebot, a detailed feature comparison table, and a coding comparison table. By examining these aspects, the document aims to offer a thorough understanding of the capabilities and functionalities of each codebot.
The word ‘codebot’ in the document refers to tools that comprise of a user interface (UI), AI assistant, and a generative AI model (GenAI). What are AI assistants, you may ask? AI assistants are applications or systems that leverage AI technologies, including GenAI models, to assist users in performing tasks. These assistants are designed to understand user commands, provide information, and perform actions based on user input. The order of operation for these codebots is as follows: the user interacts with the user interface by submitting inquiries and viewing results. Once a user has submitted an inquiry, the AI assistant acts as an intermediary, focusing on enhancing the user experience by providing suggestions, information, and forwarding inquiries to the GenAI model. Sometimes, they even rewrite the user's inquiry to ensure the model can better understand it. The GenAI model works in the backend, focusing on generating new content and understanding patterns in data.

>[!IMPORTANT]
> **Disclaimer:** This document does not aim to discourage users from using any of the codebots mentioned. Our primary goal for this document is to showcase the merits and features offered by each codebot. The coding tests conducted use a limited number of prompts, and our observations are derived from this small subset of tests. Results may vary depending on the data and prompts given to the bots.

## Table of Contents
Codebot Overview
General Features Comparison Table
Code Development Comparison Table
Conclusion
Appendix

## Codebot Overview
This section offers a detailed introduction each codebot, highlighting their essential components, functionalities, and the significant advantages they provide. 
### Amazon Q Developer
**1. Overview** 
Amazon Q Developer is a generative artificial intelligence (AI) powered conversational assistant designed to enhance the software development process, particularly within the AWS ecosystem. It assists with various coding tasks such as providing inline code completions, generating new code, and scanning for security vulnerabilities. Amazon Q Developer can be accessed through IDEs like Visual Studio Code, JupyterLab, and the command line. It offers a companion chat extension that provides conversational AI assistance.
The models that Amazon Q utilizes are pre-trained with high-quality AWS content, allowing users to ask questions about AWS architecture, AWS resources, best practices, documentation, and support.

**2. Key Features**
- **Multi-model:** The codebot is trained on all the models available through AWS Bedrock. It uses multiple foundational models to complete its tasks and uses logic to route tasks to the model that is the best fit for the use case.
- **Quick Actions:**
  - **/fix:** Corrects errors in code.
  - **/optimize:** Suggests optimization methods.
  - **/explain:** Explains code snippets and provides enhancement suggestions.
  - **/test:** builds unit tests to evaluate and test code
- **Workspace context:** Ability to modify and interact with code within your IDE, creating inline edits.
### Gemini Code Assist
**1.	Overview**
Gemini Code Assist is an AI-powered application development tool designed to enhance software development and delivery velocity through generative AI assistance, while ensuring enterprise security and privacy protection. It offers features such as code completion, code generation, and natural language chat, making it a comprehensive solution for developers. Gemini Code Assist is integrated with multiple IDEs like Visual Studio Code and JetBrains IDEs and supports over 20 programming languages.
**2.	Key Features**
- **AI Code Assistance:** Completes your code as you write and generates whole code blocks or functions on demand. Available in many popular IDEs and supports 20+ programming languages.
- **Natural Language Chat:** Allows you to chat with Gemini Code Assist to get answers to coding questions or receive guidance on coding best practices. Available in all supported IDEs.
- **Code Transformation:** Comes with contextual smart actions and smart commands, quick shortcuts to automate tasks such as fixing code errors, generating code, and explaining code.
- **Enterprise Features:**
  - **Code Customization:** Customize Gemini Code Assist using your organization’s private codebases for more tailored assistance
  - **Local Codebase Awareness:** Generates code relevant to your application by grounding responses with context from your local codebase and current development session.
  - **Enterprise Security and Data Privacy:** Ensures enterprise-grade security and privacy for all code generation and assistance activities.
### **Jupyter AI**
**1.	Overview**
Jupyter AI is a generative AI tool integrated into Jupyter, designed to enhance productivity and creativity within JupyterLab and Jupyter Notebook environments. It transforms a Jupyter notebook into a dynamic AI playground. The AI conversational assistant can be installed through a Jupyter extension or through the `%%ai` command in a Jupyter notebook cell. 
**2.	Key Features**
- **%%ai:** The “magic ai” command transforms your Jupyter environment into an AI playground. This allows users to ask questions to the various models from a notebook cell.
- **Conversational Assistant:** A native UI in JupyterLab allows users to engage with AI models through a chat interface.
- **Generative Model Access:** Provides extensive access to models from several major providers, enabling diverse applications and experimentation. Including: AI21, Anthropic, AWS (Bedrock models), Cohere, Gemini, Hugging Face, MistralAI, NVIDIA, and OpenAI. Users can seamlessly interact with different models during use and use multiple models within the same notebook environment.
  - Access to certain models must be configured through an API key. 

> [!NOTE]
> Jupyter AI does not contain its own knowledge repository. It connects to various 3rd party models. In this comparison, we will be using Anthropic’s Claude Sonnet GenAI model hosted in AWS Bedrock (bedrock-chat:anthropic.claude-3-5-sonnet-20240620-v1:0). The performance of the different models can be expected to vary. 

### **GitHub Copilot**
**1.	Overview**
GitHub Copilot is an AI-powered code completion tool developed by GitHub in collaboration with OpenAI. It leverages machine learning models to assist developers by suggesting code snippets, completing lines of code, and even generating entire functions based on the context of the code being written. Integrated seamlessly into popular code editors like Visual Studio Code, GitHub Copilot enhances productivity by reducing the amount of boilerplate code developers need to write and helping them quickly implement complex algorithms. By learning from a vast dataset of public code repositories it provides intelligent and context-aware suggestions, making it an invaluable tool for both novice and experienced programmers. GitHub Copilot consists of two parts: AI that provides inline coding suggestions as you type and a companion chat extension that provides conversational AI assistance.

**2.	Key Features**
- **Code Completion:** Suggests code snippets and completes lines of code based on context.
- **Function Generation:** Generates entire functions or methods from comments or partial code.
- **Context-Aware Suggestions:** Provides intelligent and relevant code suggestions by understanding the surrounding code.
- **Multi-Language Support:** Supports a wide range of programming languages and frameworks.
- **Seamless Integration:** Integrates with popular code editors like Visual Studio Code.


### **Anaconda AI Assistant**
**1.	Overview**
Anaconda Assistant is an AI-powered helper specialized in Python programming and Jupyter Notebook environments. It excels at providing step-by-step guidance for code generation, debugging, and package recommendations, with a particular focus on data science and analytics tools. The assistant delivers responses with single code blocks for clarity and maintains context awareness through chat history. Key strengths include expertise in essential data science libraries (such as pandas, numpy, matplotlib, and scikit-learn), package management guidance, and best practices implementation for reproducible code. Whether you're working on data manipulation, analysis, or visualization tasks, Anaconda Assistant offers concise yet detailed support while emphasizing clear documentation and performance optimization. The assistant can be accessed through Anaconda Navigator via Anaconda Toolbox, which will launch a local JupyterLab environment.

**2.	Key Features**
- **Code Generation & Debugging:** Creates Python code on demand, provides error solutions, and offers syntax corrections using best practices.
- **Package Management & Integration:** Recommends appropriate libraries, helps with version compatibility, and provides installation guidance for the Anaconda ecosystem.
- **Interactive Learning Support:** Delivers step-by-step explanations, contextual examples, and best practices for code implementation in Jupyter Notebooks. Assists with DataFrame operations, statistical analysis, and data visualization using libraries like pandas, numpy, matplotlib, and seaborn.
- **Optimization & Performance:** Suggests code improvements, memory optimization techniques, and efficient data processing methods, particularly for large datasets and complex computations.

## General Features Comparison Table
The table below provides information on each codebot based on topics of general info, functionality, integration, and benchmarking. Additional notes are given in the [Appendix]().
>[!NOTE]
> - **Multipurpose Use** was evaluated based on whether the bot could conduct general LLM tasks (e.g., summarization) and code development.
> - **Speed scores** consisted of the maximum speed at which bots provided outputs.
> - **Consistency** was proven true if the output given by the bot remained the same when the same question was asked twice.

<table>
    <thead>
        <tr>
            <th>Topic</th>
            <th>Feature</th>
            <th>Amazon Q Developer</th>
            <th>Gemini Code Assist</th>
            <th>GitHub Copilot</th>
            <th>Anaconda AI Assistant</th>
            <th>Jupyter AI</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th rowspan=4>General Info</th>
        </tr>
            <th rowspan=1>Developer</th>
            <td>AWS</td>
            <td>Google Cloud</td>
            <td>Microsoft/OpenAI</td>
            <td>Anaconda</td>
            <td>Project Jupyter</td>
        </tr>
        <tr>
            <th rowspan=1>Version Tested</th>
            <td>1.44.0</td>
            <td>2.25.1</td>
            <td>Copilot: 1.267.0; Copilot Chat: 0.24.0</td>
            <td>4.1.0</td>
            <td>2.29.0/td>
        </tr>
        <tr>
            <th rowspan=1>FedRAMP Approved</th>
            <td>Yes</td>
            <td>No</td>
            <td>No</td>
            <td>No</td>
            <td>No</td>
        </tr>
        <tr>
            <th rowspan=8>Functionality</th>
        </tr>
            <th rowspan=1>Programming Languages</th>
            <td>Python, Java, JavaScript, TypeScript, C#, Go, Rust, PHP, Ruby, Kotlin, C, C++, shell scripting, SQL, and Scala programming language </td>
            <td> Bash, C, C++, C#, Dart, Go, GoogleSQL, Java, JavaScript, Kotlin, Lua, MatLab, PHP, Python, R, Ruby, Rust, Scala, SQL, Swift, TypeScript, YAML </td>
            <td>Python, JavaScript, TypeScript, Java, C#, C++, Ruby, Go, Swift, Kotlin, PHP, Swift, Kotlin, PHP, HTML/CSS, SQL, Bash/Shell scripting</td>
            <td> Python, Bash/Shell scripting</td>
            <td>The Programming languages are dependent on the model selected</td>
        </tr>
        <tr>
            <th rowspan=1>Multipurpose Use</th>
            <td>No</td>
            <td>Yes</td>
            <td>Yes</td>
            <td>Yes</td>
            <td>Yes</td>
        </tr>
        <tr>
            <th rowspan=1>Offline Use</th>
            <td>Requires configuration of AWS Private Link</td>
            <td>No</td>
            <td>No</td>
            <td>No</td>
            <td>No</td>
        </tr>
        <tr>
            <th rowspan=1>Local File Access</th>
            <td>Yes</td>
            <td>No</td>
            <td>Yes</td>
            <td>Yes</td>
            <td>Limited Access</td>
        </tr>
        <tr>
            <th rowspan=1>Data Security</th>
            <td>Data encryption at rest and in transit. 90 day data retention policy. Opt-out options are available to enhance security (e.g. data sharing/storage)</td>
            <td>Data encryption at rest and in transit. Opt-out options are available to enhance security (e.g. data sharing/storage).  </td>
            <td>Data encryption at rest and in transit; Restricts access. Filtering code to remove sensitive data (API, passwords). Does not save or share your data</td>
            <td>Data encryption at rest and in transit; Opt-out options are available to enhance security (e.g. data sharing/storage.)</td>
            <td>No security features mentioned </td>
        </tr>
        <tr>
            <th rowspan=1>Cross-Platfrom Knowledge</th>
            <td>No</td>
            <td>Yes</td>
            <td>Yes</td>
            <td>Yes</td>
            <td>Yes</td>
        </tr>
        <tr>
            <th rowspan=1>Pricing</th>
            <td>Free tier available (limited interactions);Paid enterprise tier at $19 per month. </td>
            <td>Standard: Monthly: $22.80 per user per month; Annual: $19 per user per month with an upfront annual commitment; Enterprise: Monthly: $54 per user per month. Annual: $45 per user per month with an upfront annual commitment </td>
            <td>Free (limited to 50 chat requests and 2,000 completions); Pro: $10/month; Business: $19/per user per month; Enterprise: $39/per user per month</td>
            <td> Free (limited to 5GM of memory); Starter: $15 per user/per month; Starter: $15 per user/per month; Business: $15 per user/per month; Enterprise: Custom</td>
            <td>Open source and free to use ; Charges associated with using the 3rd party models may be incurred.</td>
        </tr>
        <tr>
            <th rowspan=5>Integration</th>
        </tr>
            <th rowspan=1>Prerequisites</th>
            <td>Free tier: Requires a Builder profile; Pro tier: Requires an AWS account and IAM Identity Center</td>
            <td>Requires a GCP account</td>
            <td>Microsoft/OpenAI</td>
            <td>Anaconda</td>
            <td>Project Jupyter</td>
        </tr>
        <tr>
            <th rowspan=1>Installation Method</th>
            <td>Installed as a plugin on extension in various IDEs</td>
            <td>Installed as an extension in various IDEs</td>
            <td> Installed as an extension in various IDEs</td>
            <td>Installed within Navigator as Anaconda Toolbox</td>
            <td>Installed via Jupyter extension or `pip` installation</td>
        </tr>
        <tr>
            <th rowspan=1>IDE Support</th>
            <td>JetBrains, Visual Studio Code, AWS Cloud, AWS Lambda console</td>
            <td>Visual Studio Code, JetBrains IDEs (IntelliJ, PyCharm, GoLand, WebStorm), Cloud Workstations, and Cloud Shell Editor</td>
            <td>Visual Studio Code, Visual Studio, PyCharm, IntelliJ IDEA, Eclipse, Atom, Sublime Text</td>
            <td>JupyterLab via Anaconda Navigator</td>
            <td>JupyterLab, Jupyter Notebook , Google Colab, VS Code </td>
        </tr>
        <tr>
            <th rowspan=1>API Support</th>
            <td>Available</td>
            <td>Available</td>
            <td>Available</td>
            <td>None mentioned</td>
            <td>None mentioned</td>
        </tr>
        <tr>
            <th rowspan=3>Benchmarking</th>
        </tr>
            <th rowspan=1>Speed</th>
            <td>100 sec</td>
            <td>35 sec</td>
            <td>20 sec</td>
            <td>34 sec</td>
            <td>30 sec</td>
        </tr>
        <tr>
            <th rowspan=1>Consistency</th>
            <td>Yes</td>
            <td>Yes</td>
            <td>Yes</td>
            <td>No</td>
            <td>Dependent on the model</td>
        </tr>
    </tbody>
</table>











