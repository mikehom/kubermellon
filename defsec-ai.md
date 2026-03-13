**Q: How do defenders operate and defend at the speed of AI?**

In order to frame how defenders can operate at the speed of AI, defenders need to start by understanding the fundamental economy of cyber has shifted. Defense is no longer about stopping a few sophisticated APT actors nor tackling the next major ransomware actor. Rather, it is about managing a high volume industrialized threat landscape where the cost of offense has plummeted. There are 3 key points to be made.

1. **The threat landscape has shifted to AI-speed offense.** Defenders must operate under the assumption that sophisticated attacks one thought to be expensive and uncommon are now cheap and abundant. Key drivers include:  
   1. Drastic reduction to cost of offense – E.g., $50 for LLM-derived exploit vs $thousands  
   2. Mass customization – There will be a move from highly sophisticated, boutique attacks to AI-powered mass production of “medium sophisticated” attacks  
   3. AI-created attack surfaces – Integration of AI features and surfaces introduces new attack vectors – E.g., AI-powered “zero-click” features on devices such as auto decoding messages for transcription can lead to exploits to run without interaction, at scale  
2. **Defense benchmarking and evaluation need to be front and center.** Defenders need to **shift from content production to content supervision & verification** to assess and triage the massive influx of data. We need to evolve to a model where practitioners no longer need to be the core producers of operational content (e.g., manually creating detection content, manually crafting intent-based search queries, etc.) to supervising and verifying the autonomous generation of content (e.g., benchmarking and verifying the correctness of autonomously generated detection content). We need to build rigorous evaluations to reproducibly measure, observe, and verify AI-speed defense is effective. This means:  
   1. Leveraging agentic workflows to automate the reasoning and verification of alerts, reports, and threats, given the increase in AI-generated noise  
   2. Engender trust to our customers and the security industry by developing rigorous testing methodologies with radical transparency to our customers and the public for benchmarking.  
   3. Help customers with very clear changes to their productivity by helping them understand *the way they perform security operations* will fundamentally change  
3. **Threat intelligence will need to be applied more broadly.** Defenders will need to embrace shared signal analysis in a more automated fashion to receive the benefits of AI-speed defense. They will need to prioritize the rapid, widespread dissemination and application of threat intelligence to minimize the window of opportunity for attackers who operate at AI-speed. This looks like:  
   1. Immediate application and feedback loops with agentic workflow to assess a threat, by a vendor, across all customer environments on their behalf with 1P threat intelligence  
   2. The ability for customers to develop their own sharing circles with immediate application and feedback loops to immediately inform them with suggested courses of action  
   3. Community verification by customers, for customers, to perform crowdsourced benchmarking. Defenders need to move toward a model where they can “check each other’s work” rapidly

To defend at the speed of AI, we need to frame the problem that can be approached at agentic scale. This requires representing the problem as an end-to-end problem with feedback loops. We intend on tackling this through an agentic SecOps workflow that is made up of 7 critical questions for the customer.

1. Do I have the right data?  
2. Am I covered against today’s threats?  
3. What should I do with this alert?  
4. How do I dig deeper?  
5. How do we respond effectively?  
6. Is my operation healthy?  
7. What is my risk posture?

Each of these questions break out into critical areas and questions that can be framed as an agentic workflow. The key goal would be to encode customers’ unique business logic (e.g., their asset inventory, attack surface management results, network topology, etc.) to deliver the value they need. Delivering agentic scale requires benchmarkable performance on our end. A guiding northstar benchmark, for example, would be to aspire for 90% analytical workloads to be automated and just work; 9% of the work to require interdiction, verification, and tuning; and 1% of the work to require power user or developer activity.

We are well positioned to build these capabilities given the strong foundations in SecOps. 

**Q: How does SecOps evolve in the next two years to defend against agentic threats?**

In the Short Term (2026), we have a string of existing Agentic SOC capabilities to lay the foundation on human-led automation workflows. These workflows operated autonomously but keep humans in the loop through notifications and session tracking to detect, hunt, investigate, and response to threats at agentic scale. Specific agentic capabilities include:

1. Triage, investigation, and response agents that automatically triage alerts and recommend actions or take low-risk actions autonomously  
2. Anomaly detection agents that baseline identity (human / non human) and environment (network, devices, apps) activity to identity, predict, and detect deviations and potential attack chains in near real time  
3. Detection engineering agents that autonomously take new and emerging threats, then define, test, deploy, and tune detection rules  
4. Threat hunting agents that autonomously generate and execute hunt plans against emerging threats, then synthesize the output into actionable output to support other agentic workflows  
5. Data management and Integration agents that automate or assist users with data source onboarding, pipelining, and third-party product integrations. 

The key value is how these agents can be composed into agentic workflows that address multiple use cases and solve large classes of critical problems that require understanding of unique business logic to each customer. 

This sets the foundation for our Agentic SOC strategy as described in the previous question.

As we look at the mid-long term (2027-2028), we will continue building out our agentic capabilities that serve to answer the 7 critical questions and reach for our 90/9/1 vision where humans shift from production to supervision and verification. We have been building towards proactive defense in our product strategy and we intend on expanding that towards **anticipatory** **defense**. 

Our advantage is based on two strategic moats that we have invested towards for several years: customer trust and access to data of security value. Within our framework, we call out specific areas of investment we will make to continue compounding value within our ecosystem:

1. **The shift towards graphs.** We went to market with a form of a security graph to enable customers to bring their business logic into our product to drive context-aware detection engineering, investigations, and response. We will double down on this **dynamic Security Graph** of an organization’s environment–mapping relationships between users, devices, apps, and the network–to surface security risk to the practitioner, risk metrics to the SOC manager, and business risk to the C-Suite.  
2. **Benchmarking anomaly detection at agentic scale.** We will continue our investment in monitoring and modeling user and machine entity behavior at scale, through our API surface and now the AI layer. This will be a critical component to shifting customers towards an AI-speed world.  
3. **A model of radical transparency.** Moving customers towards a world of trust through supervision and verification requires observability from start to finish. We will sustain our investment towards a world where customers can reproducibly measure and observe all activity to verify efficacy and measurable improvements to metrics critical to their business.  
4. **Outcomes that are default on.** As we race to SecOps at AI speed, we need to recalibrate how we deploy content on behalf of our customers. We will be shifting towards an “always-on” model of content and agentic workflow that *just works* for our customers they can observe, supervise, and tune as needed.  
5. **Reinforcing our data moat.** Our ability to operational intelligence data is unparalleled to competitors. To sustain and expand this advantage, we will look at organic and inorganic opportunities to expand our visibility into external threats, then take advantage of our ability to operationalize threat intelligence and imbue critical insights across our agentic workflows.
