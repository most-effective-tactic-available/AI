### Security Concerns
Before delving further into AI, please review and consider the OWASP (top 10) vulnerabilities related to LLM applications
* https://owasp.org/www-project-ai-security-and-privacy-guide/ 


# 'Most effective tactics available' to leverage 'AI'
Utilizing the strategies and tactics listed below will allow you to more fully leverage AI systems.

## * 'AI Coding' + 'AI Peer Review'
AI coding offers 'incredible' ease of use, but initial code quality may be subpar. However, AI systems excel at reviewing code and iteratively enhancing it. Employing multiple iterations of code written and reviewed by different AI systems has demonstrated exceptional results. Even when AI-generated code undergoes improvements by another AI system (e.g., parameterization or formatting), the original AI is often adept at identifying areas for further enhancement that might otherwise be overlooked or require extensive knowledge and time to achieve comparable outcomes.

#### Examples of entirely 'AI written' and 'AI peer reviewed' code (note: created for educational purposes only, do not use):

A reverse command shell, written in the COBOL language 
* https://github.com/most-effective-tactic-available/Reverse_Shell_Cobol

Open a .Nessus file, extract (potentially additional) host names from the SSL certs, and sort hosts by the severity of the vulnerabilities
* https://github.com/most-effective-tactic-available/Nessus_Quick_Report

Open an OpenVAS XML scan file, parse the results and sort hosts by severity of the vulnerabilities
* https://github.com/most-effective-tactic-available/OpenVAS_XML_Sorting_Report/blob/main/VAS_Quick_Report.py


## * AI Code 'Transmogrification' 
AI can often transmogrify code from one programming language to another, or at least provide strong and mostly accurate guidance when simply wanting to change from one script or programming language to another. This output can (and probably should) be AI Peer Reviewed. 

Example:
* WMIC' post-exploitation' commands can 'magically' be turned into PowerShell and/or Zsh scripts/commands

## * 'Prompt Engineering'
The task description for AI is embedded within the prompt itself. Prompt Engineering is effectively crafting well-structured and precise prompts ensures accurate and context-aware AI responses.

Reference (unaffiliated) with more detailed examples and guidelines (Browse with caution!):
* https://hackr.io/blog/prompt-engineering

## * 'Prompt Injection'
Prompt injection involves manipulating the prompt to bypass or subvert the AI's predefined limitations or guardrails. This technique can range from avoiding specific "key words" to posing alternative questions that lead to the desired answer. However, it's worth noting that prompt injection is often detected and mitigated promptly by AI systems.

Below is a (unaffiliated) website dedicated at tracking 'prompt injections' (Browse with caution!):
* https://www.jailbreakchat.com/

## * 'AI Peer Review' of information
Leveraging multiple AI systems to review information offers additional validation, context, and helps narrow down key areas for further research. Employing diverse AI perspectives enhances the overall reliability and accuracy of the information. Consider using a mixture of github copilot, chatGPT, Bard, WatsonX, and other AI LLMs or coding systems.

## * 'AI-duck debugging'
AI-duck debugging is derived from the practice of explaining a problem to a rubber duck, which is a common technique used by programmers. By verbalizing the problem, the developer can often clarifies their thoughts and identify potential errors or oversights in the code. Instead of a physical rubber duck, an AI assistant as a virtual "duck" to facilitate the debugging process.  

Here is a link to the original rubber-duck debugging technique:
* https://en.wikipedia.org/wiki/Rubber_duck_debugging
