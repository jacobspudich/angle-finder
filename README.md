Angle Finder – README.md 

Product Brief 

Reporters gather lots of information through meetings and recordings. Much of the time, reporters are at an interview/meeting for one storyline while others get missed or ignore at the pace of the newsroom. There’s also a lot of time to miss by manually reviewing meeting transcripts, interview recordings and press conference notes to identify these story angles and extract key information in the first place. It overall prevents journalists from going out and doing actual reporting. 

This solution -- Angle Finder -- uses AI to automate the overall note process outside of a transcript. Journalists paste transcript text and receive tessential outputs within seconds that include possible story Ideas, key takeaways and next steps for the reporter that could include specific sources to contact, documents to request and research actions needed 

The target users for this buildout would be all news reporters tasked with multiple meetings and interviews in one week 

Angle Finder is effective because it focuses on operational efficiency without compromising editorial integrity. The AI handles time-consuming content analysis and pattern recognition, but all story decisions, source verification and editorial judgment remain with human journalists.  

The tool addresses a specific, measurable pain point with time spent on transcript analysis and provides a clear value proposition with the same analysis done in less time, making it practical for resource-constrained newsrooms. 

How to Use (for actual use) 

Upload audio transcript (copy and paste) to interface 

Click "Analyze Content" to process your text 

Review three sections of AI-generated analysis: 

Story Ideas with headlines and newsworthiness 

Key Takeaways organized by importance 

Next Steps with specific reporting actions 

After looking through the text, users can: 

Copy individual sections with copy buttons 

Export complete analysis as Text or Markdown 

Click "Analyze Another" to process new content 

Tech Stack 

Frontend: 

HTML for structure 

CSS for design 

JavaScript 

Google Fonts 

Coded with assistance from Claude 

Utilized Claude API 

“Easiest” (oh how silly I was) to use while coding with Claude 

This was provided by my professor and felt like the most logical one for the use I wanted, didn’t need a transcript out of audio instead analysis from an already prepared transcript 

It’s deployed online through GitHub, or at least the demo is. 

Reflection 

At the very start, I was dead set on making a better version of Otter.AI. I knew it was a bit beyond what was asked for in the assignment description, but I felt confident with other buildout projects that I was going to get over the hump. And as you can see from my demo that I included and lack thereof an API in my code, I couldn’t get it to work. I started with an audio upload option, after days of trying to configure it, that didn’t work. Then, on Saturday, I switched to transcript text upload thinking it’d be easier for Claude’s API to handle. Still, the API couldn’t fire correctly, and I was left reverting to the demo for submission and work to correct it in the future. In the process of writing this I asked Claude to explain to me why this didn’t work: 

“Why Direct API Integration Wasn't Possible 

During development, I encountered a fundamental browser security limitation that required adjusting the project scope. The original design called for direct integration with Anthropic's Claude API to process user-uploaded audio files or pasted transcripts in real-time. However, modern browsers implement CORS (Cross-Origin Resource Sharing) policies that prevent client-side JavaScript from making authenticated API requests to external services.” 

Is Claude overrated? People are asking. I kid, I kid. 

On a real note, I’m very happy with the visual layout, I think with some improvements the output could be improved and there could be a real way for this to be useful for audio and text files.  

Overall, using Claude as a coding assistant really transformed the development process. It was extremely useful for coding, yes, but also just for usability and improvements on what can be better about this.  

Version 2.0, and there will be a Version 2.0 will be much better and hopefully utilize the API i already have. I’d also want to include more user-friendly options like storage, audio upload, and more information as well as a fact checking feature. 
