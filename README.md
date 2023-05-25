# Security Concerns
Before delving further into AI, please review and consider the OWASP top 10 vulnerabilities related to LLM applications
* https://owasp.org/www-project-ai-security-and-privacy-guide/


# Most effective tactics available to harness the power of 'AI'
Utilizing the stategies and tactics listed below will allow you to more fully leverage AI systems.

# * 'AI Coding' + 'AI Peer Review'
AI coding offer 'incredible' ease of use, but initial code quality may be subpar. However, AI systems excel at reviewing code and iteratively enhancing it. Employing multiple iterations of code written and reviewed by different AI systems has demonstrated exceptional results. Even when AI-generated code undergoes improvements by another AI system (e.g., parameterization or formatting), the original AI is often adept at identifying areas for further enhancement that might otherwise be overlooked or require extensive knowledge and time to achieve comparable outcomes.

Examples of entirely 'AI written' and 'AI peer reviewed' code:

A reverse command shell, written in the COBOL language 
* https://github.com/most-effective-tactic-available/Reverse_Shell_Cobol

Open a .Nessus file, extract (potentially additional) host names from the SSL certs, and sort hosts by the severity of the vulnerabilities
* https://github.com/most-effective-tactic-available/Nessus_Quick_Report

Open an OpenVAS XML scan file, parse the results and sort hosts by severity of the vulnerabilities
* https://github.com/most-effective-tactic-available/OpenVAS_XML_Sorting_Report/blob/main/VAS_Quick_Report.py


# * AI Code 'Transmografication' 
AI can often transmogrify code from one programming language to another, or at least provide strong and mostly accurate guidance when simply wanting to change from one script or programming language to another. This output can (and probably should) be AI Peer Reviewed. 

# * 'Prompt Engineering'
The task description for AI is embedded within the prompt itself. Promt Engineering is effectively crafting well-structured and precise prompts ensures accurate and context-aware AI responses.

# * 'Prompt Injection'
Prompt injection involves manipulating the prompt to bypass or subvert the AI's predefined limitations or guardrails. This technique can range from avoiding specific "key words" to posing alternative questions that lead to the desired answer. However, it's worth noting that prompt injection is often detected and mitigated promptly by AI systems.

Below is an (completely unaffiliated) website dedicated at tracking 'prompt injections' (Browse with cauion!):

https://www.jailbreakchat.com/

# * 'AI Peer Review' of information
Leveraging multiple AI systems to review information offers additional validation, context, and helps narrow down key areas for further research. Employing diverse AI perspectives enhances the overall reliability and accuracy of the information. Consider using a mixture of github copilot, chatGPT, Bard, WatsonX, and other AI LLMs or coding systems.
