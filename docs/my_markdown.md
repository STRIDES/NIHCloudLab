# General Features Comparison Table
The table below provides information on each codebot based on topics of general info, functionality, integration, and benchmarking. Additional notes are given in the appendix.


[!IMPORTANT]
Note: Multipurpose evaluated if the bot could conduct general LLM tasks and code development. Speed scores consisted of the max speed it took bots to provide outputs. Consistency was proven true if the output given by the bot remained the same when the same question was asked twice.
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