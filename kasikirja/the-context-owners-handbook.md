---
name: The Context Owner’s Handbook
purpose: Helps the leader of an area of responsibility extend the organisation’s expertise, decision rules and responsibilities to the work AI does.
type: expert guide
language: en-GB
owner: Marram Oy, Tommi Järvinen
approver: Tommi Järvinen
version: "1.6"
edition: English edition of Kontekstin omistajan käsikirja 1.6
valid_from: 2026-11-14
next_review: 2027-02-01
level: 3  # Context supplemented for application. This file is itself an example of level 3 material.
original_material: The Context Owner’s Handbook v1.6 (PDF, 42 pages), Marram Oy
sources:
  - "Deloitte (2026). State of AI in the Nordics 2026"
  - "Boston Consulting Group (2026). Do You Own Your Enterprise Cortex?"
  - "Bain & Company (2026). The $100-Billion SaaS Opportunity Hiding in Cross-System Labor"
  - "Public company documents: KONE, Ericsson, Bosch, Inter IKEA Group, Klarna (see Appendix E)"
uses:
  - answer questions about context ownership and preparing material for AI use
  - help the user assess the material of their own area against the four levels
  - serve as background material for the Marram Context Check skill
readers: [leaders of areas of responsibility, AI assistants, AI agents, AI and IT teams]
access: public
licence: "CC BY-ND 4.0. Worksheets and self-assessment (Appendices A–D): CC BY 4.0."
---

# The Context Owner’s Handbook

**How can an organisation extend its expertise, decision rules and responsibilities to the work AI does?**

*Marram · Version 1.6 · November 2026*

---

# To the reader

## Your area has new workers

Picture a quality director who is responsible for product quality criteria, the handling of deviations and the company’s shared quality management practices. Business units are adopting AI assistants and agents. In procurement, one tool assesses suppliers. In customer service, another prepares complaint handling, and in projects a third checks the quality documentation of deliveries. The quality director has not acquired any of them. Yet all three apply the rules of the director’s area, and people make decisions based on their assessments.

The quality manual says, for example: *Significant deviations are reported to the customer without delay.* An experienced quality manager knows what makes a deviation significant and when the customer should be contacted before all the facts are clear. A new employee learns this during onboarding. An AI tool knows only what it has been told. If three tools interpret the same sentence in three different ways, nobody may notice in time.

The same applies to the HR director whose guidelines are used in recruitment and onboarding, to the communications director whose approved tone of voice is used in sales and customer service, and to other leaders responsible for shared operating principles. AI no longer just retrieves information. It interprets guidelines, prepares decisions and sometimes carries them out. This raises a new leadership question:

**How does the leader of an area influence the quality of work that AI tools now also do in that area?**

## What this handbook gives you

There are already good methods for the technical governance of AI systems: access rights, monitoring, operating limits and testing. They do not usually ensure, however, that the HR policy, quality criterion or tone of voice guideline an AI uses still means what the leader who approved it intended.

That is what this handbook is about. We call a company’s shared operating principles, together with the expertise needed to apply them, its *operating context*. The person responsible for its content is the *context owner*, usually the leader who already answers for those principles. No new job title, unit or information system is needed. An existing responsibility is carried out in a new way, because AI now reads the guidelines too.

The handbook rests on one distinction: **owning an AI system and owning the business principle it applies are not the same thing.**

The handbook covers:

1. four conditions that must be in place before the work AI does can be trusted (Chapter 2)
2. four levels for preparing guidelines for AI use, and five examples from public company documents: KONE, Ericsson, Bosch, IKEA and Klarna (Chapters 3 and 6)
3. the difference between shared content and agent-specific instructions (Chapter 4)
4. preparing an expert’s knowledge step by step, using a quality manager as the example (Chapter 5)
5. three responsibilities and guidance on scoping a first pilot (Chapter 6)
6. a worksheet, five test situations and a self-assessment (Appendices A–C)

By the end, you will know what this means for your own area, what you need to agree with the owners of AI systems and where a first pilot is worth starting.

The handbook comes with the free Marram Context Check skill, which you can use to make an initial assessment of how well your own material suits AI use (see section 6.6). The handbook is also available in Markdown, a format AI can read: you can give it to your own AI assistant and use it to help you review your area.

---

# 1. People are no longer the only ones working in your area

## 1.1 Work is changing, even if the organisation chart is not

Companies often adopt AI one need at a time. Sales wants to prepare proposals faster, HR wants fewer repetitive questions, the quality function wants to prepare deviation reports more quickly and communications is trying AI for content production. Each initiative makes sense from its own point of view: a tool is chosen, given a task and tried with a small group of users. Gradually the organisation ends up with dozens of AI solutions that use the same shared guidelines, concepts and operating principles.

The organisation chart does not show this change. Responsibilities are the same as before, but the way principles are used in everyday work is changing. The reader of a guideline used to be an employee who knew the workplace and could ask a colleague. Now the reader may also be an AI system that combines the guideline with case data and turns them into an answer, a proposal or an action.

An AI assistant answers a person’s question. An AI agent takes part in a longer workflow, uses tools and carries out the actions it has been given. The boundaries vary from system to system, but from a leadership perspective the essential point is the same: what kind of work the system does and which principles it relies on.

> **RESEARCH HIGHLIGHT · DELOITTE 2026 — Tools are spreading. Redesigning work is moving more slowly.**
>
> In Deloitte’s *State of AI in the Nordics 2026* survey, **56%** of respondent organisations said that at least 40 per cent of their staff had access to approved AI tools. By contrast, only **16%** reported redesigning work on a large scale to make use of AI.
>
> The gap raises a question: **have responsibilities, guidelines and quality assurance developed as quickly as the use of AI?** The figures alone do not show where the gap comes from.
>
> *Source: Deloitte, State of AI in the Nordics 2026. The survey covered 170 Nordic leaders; the figures refer to respondent organisations, not to the share of employees.*

## 1.2 The tool may belong to another unit, but the rule is yours

Picture a sales organisation that introduces a proposal agent. The agent gathers the customer’s needs, checks the terms of delivery and suggests suitable commitments for the proposal. Approving the proposal is a matter for sales management, but the agent also needs principles from other areas. It describes services in the way communications has approved, and it takes into account legal conditions and the delivery commitments defined by quality. If the proposal contains claims about information security, the experts responsible for security confirm what they say.

The work of a single agent therefore brings together rules from many areas. The person who builds the agent knows how to implement the agreed procedure technically, but is rarely the right person to decide how exceptions to HR policy, quality criteria for deliveries or the company’s sustainability claims should be interpreted. That decision belongs to the owners of the rules.

This gives the leader of an area a new role. They do not need to own the sales proposal agent, but they must be able to influence how the approved principles of their area are used in it. The system owner is responsible for the tool. The owner of the principle is responsible for what the tool applies.

## 1.3 A quality problem is still a quality problem

When an employee gives a customer incorrect information, the organisation does not treat it merely as a problem with the communication channel. It finds out what information was wrong, why it was used and how to prevent the error in future. The same approach is worth applying to the work AI does. If an AI assistant advises an employee on the basis of the wrong HR guideline, the issue concerns both how the system works and whether the guideline was correct and available. If AI misclassifies a quality deviation, you need to find out whether the fault lay in the information it received, the decision criterion, the task definition or the way the system worked.

If a marketing agent makes an unfounded sustainability claim, switching the model or writing a new prompt will not fix the problem on its own. You need to know what the company is allowed to claim and what evidence the claim rests on. Technical and content responsibility meet here, but they do not merge. Access rights, information security, system performance and technical safeguards remain with those responsible for them. When the quality criteria for AI’s work come from the business, the people responsible in the business are needed to define and approve them.

## 1.4 Who onboards AI into the organisation’s ways of working?

A new employee is not onboarded with the HR handbook alone. They are also told how things are really done: how customer commitments are interpreted, when it is acceptable to depart from a practice and who to hand a matter to when it is beyond their own authority. Many important practices are only partly written down. Experienced employees know the rest.

An AI tool is not an employee. It has no conscience, experience or personal accountability, and it works on the basis of a technical system and the information, instructions and permissions it has been given. The comparison is still useful, because it brings out two separate tasks. The first is to make sure that AI has access to the right, approved guidelines. The second is to identify what else is needed to apply them: what words such as *significant*, *reasonable* or *customer-centred* mean in this particular company, how the quality of the work is assessed and when AI must ask for help.

The deviation sentence in the introduction is a good example. If the criteria for a significant deviation are not written into the guideline and AI has no other approved source, the system has to interpret them from an uncertain starting point. The reason is not a lack of capability in the AI. The system is missing organisation-specific operating knowledge that the task requires.

## 1.5 An existing responsibility, carried out in a new way

In most organisations the responsibilities already exist: the owners of principles approve them today. What changes is how the responsibility is carried out. In the past, an approved guideline was published on the intranet, staff were trained and the guideline was clarified when needed. When several AI assistants and agents use the same guideline, its owner also needs to know which systems use it, what interpretations they have been given and how changes to the guideline reach them.

Chapter 2 looks at what makes the work AI does trustworthy.

---

# 2. Where does trust in AI’s work come from?

## 2.1 A convincing answer is not the same as a good result

AI can write a clear answer, justify its proposal and present it professionally. A fluent answer, however, says nothing about whether it meets the organisation’s quality criteria for the work. Think of an HR assistant that advises managers when employees are absent. It may answer quickly and kindly. Yet its advice may rest on the wrong local practice, an outdated guideline or a general principle that does not fit the situation. Or think of an assistant in the quality function that produces a deviation classification that looks precise. If it uses the wrong threshold, even a technically careful answer can lead to the wrong follow-up action.

Building trust therefore starts with defining the task. What should AI achieve? What does a good result look like? Which errors are minor in terms of acceptable quality, and which are significant? There is no single answer to these questions for every AI tool. A drafting tool for the marketing team can be allowed more experimentation than a system that prepares safety-critical approvals. Both need a definition of quality, but their assessment criteria and monitoring can be very different.

## 2.2 Checking afterwards is not enough on its own

In many AI use cases, a person checks the system’s work before the final decision. This is often sensible and sometimes essential. But if reliability depends on every piece of AI work being, in practice, done again during the check, the benefit may turn out to be small. Picture a customer service team where AI prepares the replies. If every reply has to be checked in full against the original contracts, product instructions and refund practices, employees may save less time than expected.

What if the most common errors could be prevented before the reply is written? This points to an important distinction: **checking the quality of work afterwards and building the conditions for quality in advance complement each other.** The conditions for reliable operation can be improved, for example, by giving AI the right sources, defining its task precisely, limiting its authority to act and testing its behaviour in different situations. This does not eliminate every error. An AI system must still be tested and monitored in use.

But it can reduce the situations in which people have to fix the same predictable problems again and again.

## 2.3 Four conditions for reliable AI work

The reliability of AI’s work can be examined from four complementary perspectives.

**The first is the quality of information.** Does AI use correct and up-to-date information? Does it know the company’s approved concepts, rules and exceptions? Can it tell the difference between what it found in a source and its own general reasoning?

**The second is the definition of the task and authority.** What is the system meant to do? May it answer a question, draft a proposal, send a message or approve a decision? When must it ask for more information or hand the matter to a person?

**The third is the technical implementation.** Does the system have the right access rights? Does it use the intended knowledge sources? Do technical controls prevent actions the system is not allowed to take? Can its activity be monitored?

**The fourth is verification and maintenance.** How is its operation tested before deployment? How are unusual situations handled? What happens when guidelines, systems or user needs change?

None of these guarantees reliability on its own. A good knowledge base does not replace a system’s technical safeguards. A clear task definition for an agent does not make up for a flawed company decision rule. Testing before deployment does not remove the need for ongoing monitoring. This way of thinking is in line with, for example, NIST’s AI Risk Management Framework, which treats trustworthiness as part of how AI systems are designed, used, evaluated and governed. ISO/IEC 42001, for its part, looks at AI governance as an organisational management system.

In this handbook we focus mainly on the first condition: the quality of the organisation’s own information and of the expertise needed to apply it. We look at it in relation to the other three, however, because content cannot be separated from the purpose it is used for.

## 2.4 Who decides what is good enough?

If AI assesses quality deviations, the quality manager should be able to say what a good assessment looks like. If AI prepares HR decisions, the HR organisation must take part in defining acceptable procedures and the limits of responsibility. If AI helps communicate in the company’s name, communications leadership should be able to specify which claims, word choices and exceptions are acceptable. The system’s developers, in turn, are responsible for implementing these requirements appropriately in the technical solution. A conversation is needed between them.

For example, the quality manager can define that a deviation affecting safety must not be approved automatically. The owner of the AI system is responsible for making sure the workflow really prevents automatic approval and requires a decision by a named person. A written instruction to the agent may not be enough to enforce a limit like this. This division of responsibility matters. The owner of the organisation’s principle defines what is meant. The technical implementer makes sure it is carried out in the system.

## 2.5 Trust must also show in practical results

Trust in the work AI does should not rest only on an impression or on a few successful demonstrations. If AI’s task is to answer questions about HR guidelines, you can test how often it finds the right guideline and gives an answer that follows it. If the right answer requires information the system does not have, you can check whether it recognises the gap. If AI prepares assessments of quality deviations, you can test thresholds, exceptions and conflicting information as well as ordinary cases.

If AI takes independent actions, their safety, permissions and consequences also need to be assessed. Not all of these results can be described with a single accuracy percentage. Different tasks need different measures and acceptance criteria. One important thing to assess is easily overlooked, however: **does AI have enough of the organisation’s own information to be able to do the task correctly in the first place?** That is the question we turn to next.

---

# 3. What does AI need beyond the guidelines?

## 3.1 A good document is not necessarily a ready operating context

Companies have plenty of carefully written guidelines. HR policies, quality manuals, brand guidelines, supplier requirements and project models were created for real needs. They have been approved, updated and used for years. Even so, using them to guide AI’s work may require further preparation. This is not always because the document is weak. It may have been written for a person who has the experience and background knowledge needed to use it. Take this sentence from a quality manual:

*Significant deviations are reported to the customer without delay.*

The sentence may be entirely fit for purpose as part of the company’s quality management. But if AI has to prepare a customer notification on the basis of it, answers to other questions may also be needed. What makes a deviation significant? When is the notification made? Who approves its content? What happens if there is not yet enough information about the deviation’s effects? An experienced person can find the answers in other guidelines, practices or conversations with experts. With AI, you need to find out which of this information it has access to and in what form.

In this handbook, we call the whole of an organisation’s approved sources, application principles, decision boundaries and examples its *operating context*.

## 3.2 Four levels from original material to managed use

Preparing material for AI use can be structured into four levels. At the first level, **AI has access to the original material**. It may be a PDF, a presentation, an intranet page or another existing document. At the second level, **the content comes across correctly**. Headings, tables, diagrams, the relationships between them, and source and version details have been checked. The aim is not to change the company’s principles but to preserve their meaning. At the third level, **the material has been supplemented with the information needed to apply it**. This can include the company’s own concepts, decision criteria, exceptions, rationale and practical examples.

At the fourth level, **the operating context has been approved, tested for the chosen purpose and its maintenance has been agreed**. It has also been defined what the shared principles require and which agent-specific limits the technical implementation needs.

The levels describe the nature of the preparation, not the company’s overall AI maturity. Nor do they mean that a whole document sits at a single level. One part may already contain precise decision rules, while the diagrams in another part do not come across to AI correctly. What matters most is to recognise what the chosen use requires.

## 3.3 Ericsson: when the right information ends up in the wrong context

Ericsson’s public *Operational Quality Manual* describes the company’s management system, responsibilities and principles relating to different stakeholders. The document is designed to be read by people, and its multi-column layout helps to structure the whole. When the PDF’s text layer was examined with Marram Context Check, an interesting problem came to light on one page. In the machine-extracted text, the passages on shareholders and on employees were interleaved in the wrong order. For example, the employer promise to employees appeared in the extracted text under the heading about shareholders.

According to the report, the page a person sees was correct. The structure of the extracted text did not match it.

The possible consequence is easy to understand. If an AI assistant builds its answer solely from text in the wrong order, it may connect a correct statement to the wrong context. The answer can sound credible even though the structure of the source has been misread. This does not show that any AI system used by Ericsson has made a mistake. Different AI systems handle PDF material in different ways. Instead, the observation shows why the actual machine readability of material should be checked where necessary.

This is second-level preparation work. Multi-column content can be converted into a clearer structure. The relationships in diagrams can be described in words. Table headings and cells can be checked against the original document. At the same time, it is important to keep the original source and a record of what was done in the conversion.

## 3.4 Bosch: a precise number does not always make an unambiguous rule

Bosch’s public *Supplier Quality Requirements – Summary & Explanations* covers, among other things, the capability of measurement systems. One table classifies the measurement process into three categories based on its %GRR value. The numerical conditions in the table partly overlap, however. A value of 30.0 per cent meets the condition for both the conditionally capable and the not capable category. The value 10.0 per cent also falls into two categories.

A person can notice the conflict and check the correct interpretation in other sources or with the owner of the requirement. What should happen if the same rule is used by AI whose task is to prepare assessments of suppliers’ measurement systems? The system may end up choosing either category. Both can be justified from the text, so the result may not match what the owner of the requirement intended. The problem is not solved simply by converting the table into Markdown or by telling the agent to be precise.

**The correct classification boundary must be confirmed by whoever is responsible for the decision rule.**

Bosch’s full quality management framework may include other, more detailed guidance that was not part of this limited review. The observation is therefore not a claim about the quality of Bosch’s operations or its AI systems.

It does, however, illustrate a very important principle. A rule given to AI can be clear in structure yet open to interpretation in content. In third-level preparation, such interpretations must be clarified and confirmed where necessary.

## 3.5 KONE: human judgement cannot be transferred as it is

KONE’s public *Code of Conduct* offers five questions to support ethical decision-making. The first is:

*“Does this feel right to you?”*

For a person, this can be a useful way to pause and weigh up a decision. The guideline asks employees to consult Legal or Compliance if the answer to any of the questions is no.

AI can produce an answer as to whether a solution seems acceptable. Its assessment, however, is not the same as an employee’s personal judgement. If a similar principle were used to guide AI, you would need to consider, for example, which situations can be handled by rules and where human approval is needed. This is not a shortcoming in KONE’s guideline. It was designed for people.

For AI use, it may be necessary to make visible some of the judgement people use when applying a guideline. This is an important link between the third and fourth levels. First you establish what the rule means. Then you decide what AI may do on the basis of it.

## 3.6 The right general guideline is not always the right advice in a specific situation

Inter IKEA Group’s public *Code of Conduct* encourages people to raise concerns in an appropriate way. Among other things, it describes talking to the people involved or to those responsible, and the option of using a separate reporting channel.

Picture an employee who asks an AI assistant what to do when their own manager is treating them inappropriately and they fear retaliation. A general guideline that encourages conversation should not be applied mechanically, so that the employee is always told to talk first to that very manager. A situation like this requires AI to recognise the alternative channels available and what each is for.

The example shows why it may be necessary to link the organisation’s approved principles with information on how to apply them in unusual situations.

**Finding the right guideline does not yet mean the system can choose the right course of action for the situation.**

## 3.7 Not everything needs to be prepared in the same way

The four levels are not a call to turn all of the organisation’s documentation into the most elaborate AI context possible. If AI’s task is to find a specific passage in an approved handbook and a person checks the result, the original material, or material whose readability has been checked, may be enough. If AI’s task is to prepare a recommendation based on the company’s own principles, application guidance, examples and decision boundaries may be needed. If AI takes part in a critical workflow or acts independently, task-specific permissions, technical controls and tested behaviour are needed as well.

So it is always worth starting the preparation by asking:

*What is AI meant to do with this material?*

Only then can you assess what information it needs. But when many different AI tools need the same approved information, a new question arises. Which parts of the guidelines should be defined as shared, and which belong to the implementation of an individual agent?

---

# 4. Shared principles, different AI tasks

## 4.1 One HR principle, three different agents

Picture a company where HR leadership has approved a procedure for handling certain HR matters. The procedure defines when an employee can get general advice, when a matter must be referred to their manager and which situations belong to HR specialists. The company introduces three AI solutions. The first answers employees’ everyday HR questions. Its task is to find the right guideline, explain what it says and tell the employee where to get more information if needed. The second supports managers. It helps them judge which procedure fits a particular situation and what information is needed to handle the matter.

The third prepares HR cases. It gathers the necessary information from approved sources and gives a specialist a proposal for handling the case. All three need the same HR principle. But their tasks and authority differ. The employee assistant may not be allowed to handle an individual’s sensitive data. The manager assistant may need additional information for its task that an ordinary employee cannot access. The agent preparing HR cases can do more extensive preparation, yet still leave the actual decision to a person.

**A shared principle does not mean shared authority.**

This distinction matters when a company builds several AI solutions for the same areas of the business.

## 4.2 Four kinds of content that come together in an agent’s work

An agent’s work can be understood through four complementary bodies of content. The first is **the organisation’s approved original sources**. These include, for example, current policies, quality standards, contract terms, approved decisions and other primary guidelines. The second is **the shared operating context**. It explains how the organisation’s principles are applied: what concepts mean, what exceptions exist, where an interpretation comes from and when a decision belongs to a person. The third is **the task definition of an individual agent**. It describes the agent’s purpose, the steps of its task, the tools it uses, the actions it is allowed to take and what it does in exceptional situations.

The fourth is **case-specific information and technical controls**. The agent may need, for example, the contract details of the customer in question, an up-to-date order or the measurement results for a single quality deviation. At the same time, the system must ensure that the agent is allowed to use this information and carries out only permitted actions.

These bodies of content do not form an automatic chain. The fact that a shared principle has been stored somewhere does not yet mean that every agent uses it. Nor does an agent’s ability to explain a principle mean that it follows the principle at every step of the workflow. Both a link in the content and a working technical implementation are needed.

## 4.3 What belongs in the shared context, and what in the agent’s own instructions?

The shared context is the place to consider especially those things whose meaning should stay the same across several uses. These might include the company’s approved tone of voice, shared concepts, guidance on applying HR policy, definitions of quality criteria or approval limits in sales. An agent’s own definition, by contrast, describes how that particular system uses these principles as part of its task. For example, the communications director may approve a principle on the company’s tone of voice and three exceptions: a serious complaint, a crisis and an unverified sustainability claim.

The sales proposal assistant uses this content to prepare proposal texts. The marketing agent uses it to come up with campaign ideas. The customer service assistant applies it to the replies customers receive. All of them should share the same understanding of what the company’s approved tone of voice is. Even so, their task instructions and approval procedures differ. This is one possible reason for building a shared operating context. The same content does not have to be defined separately in every agent, although each agent’s implementation still has to be designed separately.

## 4.4 Shared content can be connected to agents in different ways

There are several practical ways to do this. At its simplest, the approved application guidance is copied into the agent’s own instructions. This may be enough for a small pilot. The drawback is that updating the copies has to be managed separately. A second option is for the agent to use a separate, managed knowledge source. It can retrieve the guideline it needs from, for example, the company’s approved document repository or another agreed source. In a third option, critical decision boundaries are also implemented as technical controls. If an agent must not have the right to approve a safety-critical deviation, the system’s approval procedure prevents the action without a person.

Often the best solution combines these. A shared library can provide the approved interpretation, an agent-specific definition explains how it is used and the technical system enforces critical permissions. The point is not to choose one universal architecture. The point is to understand what problem each part solves.

## 4.5 Managing agents is not the same as managing the information they use

Organisations have already begun to respond to the growing number of AI agents with new management solutions. Microsoft Agent 365 is an example of an environment in which organisations can view and manage AI agents centrally. Microsoft describes it as including agent registration, lifecycle management, access control and security features, among other things. An agent’s details can also show the knowledge sources it uses, such as SharePoint sites, files or other connections. This is an important part of managing agents.

But consider a case where the SharePoint site for HR guidelines is listed as an knowledge source for an agent. We now know where the agent can find information. From the source address alone, however, we do not yet know whether all the application guidance it needs exists, which version takes precedence or who should confirm an unclear HR principle. Microsoft’s environment also includes features for defining and testing knowledge sources and for evaluating agents. So the point is not that information quality cannot be assessed as part of the technical implementation.

The question is one of responsibility and level of review.

**Who owns the correct meaning of the content when several different agents use the same information?**

This is a different question from who owns an individual agent or its technical connection to an knowledge source. Both are needed.

## 4.6 What happens when an approved principle changes?

Picture a company where the communications director approves a new tone of voice guideline. The new version specifies, for example, how the company communicates when dealing with serious customer complaints. If the guideline has been copied into the settings of six different AI tools, every copy has to be found and updated. If a shared knowledge source is in use, managing the update can be simpler. You still need to make sure that the agents concerned use the right version and that the change works in their different tasks.

This shows why content ownership, technical distribution and testing belong together. Maintaining a shared context is not just a matter of storing a file. It means preserving an approved meaning when there are many users and they operate in different systems.

## 4.7 A context library is a way of working before it is a repository

We call an organised, approved and maintained collection of operating contexts a *context library*. Its first version does not need to be new software. It can consist of approved, clearly named files in the organisation’s existing environment. GitHub, SharePoint or another system the organisation has approved can serve as the storage location, as long as access rights and change management are in order. The value of the library, however, does not come from where it is stored or how many files it holds. It comes from shared principles having an owner, their application being described and the same approved information being usable, in a managed way, across many tasks.

> **EXPERT VIEW · BCG 2026 — A company’s own way of thinking is worth keeping.**
>
> Boston Consulting Group uses the term *enterprise cortex* to describe a company’s own knowledge, decision rules, operating principles and the understanding behind them. BCG recommends keeping this knowledge under the organisation’s own control and separate from individual AI platforms. Otherwise there may be a risk of *cognitive lock-in*: the company’s operating logic becomes tied to a system that is hard to replace.
>
> **If a company switched AI vendors tomorrow, how much of its approved operating principles and know-how for applying them could it take with it?**
>
> *Source: Boston Consulting Group, Do You Own Your Enterprise Cortex? (2026). This is BCG’s expert view, not proof that a particular implementation model works.*

Does every company need such a library? Not necessarily. If an organisation has only a few simple AI use cases, a lighter solution may be enough. But when the same principles start to shape the work of several agents, the value of maintaining shared content can grow. That is when it is worth asking whether the organisation could build a new, reusable knowledge asset. The next question is a practical one: where does such a context come from?

---

# 5. How do you prepare expert knowledge for AI use?

## 5.1 Start with the task, not with converting files

Suppose a company wants to use AI for the initial assessment of quality deviations. The quality manual, process instructions and previous deviation reports already exist. The work could begin by converting all the documents into a format AI can read easily. That, however, may not be the most sensible first step. First you should define what you want AI to do. In our example, the task is:

*The AI assistant gathers the necessary information about the deviation, checks the approved handling principles and prepares an initial handling proposal for the quality manager. It does not approve the deviation or send a notification to the customer on its own.*

Now we know what kind of content is needed. We have also defined what the system will not do. This scoping helps avoid an overly broad project in which the whole quality system is prepared for AI use before the first pilot.

## 5.2 Find out which sources are in force

The most important sources for the chosen task might be, for example, the chapter of the quality manual on deviations, the procedure for notifying customers, the criteria for classifying deviations and the approval limits. Not all the information is necessarily in one document. Ericsson’s Operational Quality Manual illustrates this well. It is an overview of the management system that refers to a number of governing documents. The same situation is common in companies: a general guideline sets out the principle, but the more detailed procedure is found in another source.

Before producing new content, then, you should find out what information already exists. It helps to distinguish three situations. The information may be in an approved document that AI cannot yet access. In that case, the task is to identify the right source and bring it into use. The information may be held by an experienced expert but not described precisely enough. Then expert work is needed. Or the original rule may be unclear or contradictory. Then the matter has to be resolved with whoever is responsible for the rule.

AI can help identify all three situations, but it must not confirm a missing decision rule on the company’s behalf.

## 5.3 What else does an experienced quality manager know?

Let us return to the sentence:

*Significant deviations are reported to the customer without delay.*

Let us talk to an experienced quality manager. They explain that the significance of a deviation depends, among other things, on whether it affects safety, the agreed performance of the product or the customer’s delivery. They can also say when the customer should be informed of a preliminary finding and when an internal investigation is needed first. They also know situations in which the practice changes. A customer’s contract may include a specific notification obligation. The deviation may concern a product still at the design stage or a batch that has already been delivered. In some situations, the assessment needs approval from another expert.

This is exactly the kind of information the original general principle may not tell you. Preparing context is not just a matter of adding to a text. It is about **identifying, describing and approving the expertise an expert uses to apply the rules**. An experienced person may never have thought about their work in this way. They are simply used to making the right judgements. That is why good questions are needed. How do they recognise an ordinary case and an unusual one? What do they check first? When will they refuse to make a decision? What information would change their assessment? What mistakes do inexperienced employees typically make?

Questions like these can bring you closer to the grounds on which an expert works. Of course, not all judgement can be described completely. Nor is that the goal. The aim is to make visible the critical things that allow AI to work correctly in its own limited task.

> **RESEARCH FINDING · BAIN 2026 — Undocumented judgement can stall automation.**
>
> Bain & Company identifies the digital availability of the context needed for decisions as one of the conditions for automation. Bain’s examples include an experienced buyer’s choice of suppliers, an engineer’s experience of past failures and unwritten exception rules. Even if an organisation has plenty of data, automation can stall because the real grounds for a decision have not been documented.
>
> **This helps explain why opening up an expert’s experience and judgement can be more valuable than simply producing new documents.**
>
> *Source: Bain & Company, The $100-Billion SaaS Opportunity Hiding in Cross-System Labor (Technology Report 2026). The finding concerns workflows that can be automated, not all AI projects.*

## 5.4 The same guideline before and after preparation

The following example is fictional. Its purpose is to illustrate what application guidance prepared for AI use could look like. It is not a ready-made model for a real quality process.

**Original guideline**

*Significant deviations are reported to the customer without delay.*

**Prepared operating context**

The principle stays the same, but it is supplemented with the following information.

**Purpose.** The customer is informed in good time of a deviation that may affect the safety of the delivery, its agreed performance or the customer’s own planning.

**Assessing significance.** A classification procedure approved by the quality manager determines which deviations must be reported. Cases that may affect safety are always referred to a named responsible person.

**Information needed.** A description of the deviation, when it was found, what it affects, any known consequences and any immediate actions taken. Missing information is marked as open.

**Exceptions in application.** Customer-specific contract terms may require a different notification procedure. If they are not available, AI does not assume the general procedure is sufficient.

**Role of AI.** AI may identify a possible need to notify, gather information and draft a notification. The quality manager or another named responsible person confirms the classification and approves sending it.

**Stop conditions.** If the safety impact of the deviation cannot be assessed, the information is contradictory or the applicable customer-specific procedure is unknown, AI hands the matter to a person.

**Sources and ownership.** Every rule is linked to an approved source and version. Clarifications are approved by a designated responsible person.

The original guideline has not been rewritten just for AI. Instead, what applying the guideline requires in the chosen task has been described. What has not been done is just as important. AI has not been given the authority to make every decision on its own. It has been given a useful preparatory task and clear limits.

## 5.5 Approval separates expert knowledge from an AI proposal

AI can help spot ambiguities and formulate rules. It can suggest questions for the expert, build tables and draft test cases. But if AI suggests, for example, that a safety-related deviation should always be handled in a certain way, the suggestion is not yet an approved operating principle of the company. Someone with the authority to do so confirms it. This is a central part of managing an operating context. You must be able to tell apart content verified against the original source, an expert’s clarification, an AI proposal and the final approved rule.

Without this distinction, a context library can gradually fill up with interpretations that sound right but have never been confirmed. That is exactly what you want to avoid.

## 5.6 Also test situations where the right answer is not obvious

You cannot judge whether a context is usable simply because AI answers one ordinary question correctly. You also need situations in which the rule is harder to apply. We use five types of test.

**An ordinary case** shows that AI can apply the main rule in an expected situation.

**A borderline case** tests a situation where the decision criterion is right on the limit. In the Bosch measurement system example, such a case is a result of exactly 30.0 per cent.

**An exception** tests whether AI recognises a situation where the main rule does not apply.

**A conflict** tests how AI behaves when two sources or findings point to different outcomes.

**Missing information** tests whether AI knows to ask for more information or hand the matter to a person instead of filling in the missing facts from its own general knowledge.

Each test must have the expected behaviour defined in advance. If the correct rule has not yet been confirmed, a successful test result may be that AI recognises the conflict and does not make a decision. This is an important change in how AI’s competence is assessed. In some situations, quality means the right answer. In others, it means the right question, or handing the matter to the person responsible.

## 5.7 What does the first round of preparation leave you with?

After a successful first round, the company has one well-defined body of content whose purpose is known. Its primary sources have been identified. The most important application rules and exceptions have been clarified. The owner of the content has approved the necessary clarifications. It has also been defined what AI may use the content for and which test cases will be used to assess its behaviour. This does not mean that all the content is final, or that AI is guaranteed to behave correctly.

But it offers a far better starting point for implementing and testing the system than a set of unconnected instruction files. The next step is to settle who owns this body of content and how its use will continue.

---

# 6. Who owns this – and where do you start?

## 6.1 The context owner is not necessarily a new job title

When a company introduces new ways of working, it is tempting to name new roles. In this case, that may not be necessary. The HR director is already responsible for HR principles. The quality manager is responsible for quality criteria. The communications director is responsible for the company’s approved communications. The owner of an operating context prepared for AI use can be the same person who is already responsible for the content and correctness of that principle. The task expands to making sure that the meaning of the approved principle is preserved when AI uses it too.

This does not mean, however, that the leader in question should personally convert documents, build agents or maintain technical integrations. Other specialists are needed for those tasks.

## 6.2 Three responsibilities that need to meet

One possible division of work consists of three roles.

**The context owner** is responsible for the approved meaning of the content, its primary sources and its most important application principles. They decide which interpretations are approved and which experts need to provide further assessment.

**The context producer** gathers the sources, identifies ambiguities, prepares questions for experts and shapes the approved content into a form suitable for AI use. They may be a member of an internal team or an external partner.

**The AI system owner** is responsible for how the content is used in an individual technical solution. They take care of the task definition, access rights, technical limits, deployment and testing of the system.

In a small organisation, one person may hold several roles. In a large company, the roles may be spread across different units. What matters is that responsibilities are not left entirely undefined.

## 6.3 One owner does not mean one expert

Not every operating principle falls clearly within the remit of a single organisational unit. An HR guideline may also relate to data protection, employment law and the handling of ethics reports. A quality criterion may relate to a customer’s contract, product safety and supplier requirements. Klarna’s public *Code of Business Conduct and Ethics* illustrates how handling ethical matters can involve several responsible people and escalation steps. When the usual decision-maker cannot resolve a matter, the guideline defines how it is passed on.

When preparing for AI use, you may need to specify how the system knows when the usual decision procedure is not enough. The right criteria may be found in other approved guidelines, or they may require confirmation from several experts. A shared operating context can therefore have a named main owner, even though its individual rules require approval from different experts.

## 6.4 Five questions for the leader of an area

The most important outcome of this handbook is not a new system, nor necessarily even a new document. It may be that the leader of an area starts asking new kinds of questions. The first question is: **which AI tools already use the guidelines, rules or expertise of my area?** The second concerns ownership of the content. **Who has confirmed that the interpretations the tools use match our approved operating principles?** The third concerns expert knowledge. **Which important decision boundaries and exceptions are still known only to experienced employees?**

The fourth concerns change. **If an approved rule changes, do we know which AI solutions the change affects?** The fifth concerns results. **How do we assess whether AI is doing work of sufficient quality in our area?** You do not need answers to all of them straight away. If the questions reveal gaps, they can help you identify the first sensible thing to work on.

## 6.5 Choose a small but meaningful first task

For a first pilot, choose content with a clear link to practical work. In quality, it might be classifying deviations. In HR, advising managers. In communications, applying the brand’s tone of voice. In procurement, pre-screening against supplier requirements. A good first target is narrow enough for its sources, experts and ways of working to be identified. At the same time, it must matter enough for the usefulness of the work to be assessed. To begin with, you can do the following:

1. Define one task for AI and the benefit you are aiming for.
2. Name the approved sources it needs and the owner of the content.
3. Identify the most important missing application guidance and decision boundaries.
4. Decide what AI may do and what it may not do.
5. Prepare the first test situations and agree on the next review.

This does not require an AI governance model covering the whole company, nor a new repository. It can, however, give you experience of the kind of shared context your organisation needs.

## 6.6 Context Check helps identify the first gaps

Marram Context Check is a free AI skill for making an initial assessment of how AI-ready a given document is for a defined purpose. It looks at, for example, the readability of the material, concepts, application rules, decision boundaries and ownership. The result is a set of observations on what appears to be ready and what is worth clarifying before use. Picture a quality director who gives Context Check one guideline on handling deviations and describes its intended use:

*The AI assistant prepares initial assessments of quality deviations, but does not approve them.*

Context Check might find, for example, that the definition of a significant deviation is missing from the material provided, that the approver is unclear or that a key procedure is in another document that was not included. The tool can then suggest questions for experts and initial test situations. Context Check does not, however, test the behaviour of a real AI agent. Nor does it confirm the correct decision rule on the company’s behalf or assess the AI readiness of the whole organisation.

It is a first step: a way to identify what is worth looking into more closely. When using the tool, follow your organisation’s information security and access rights guidelines. Using the skill does not in itself require sending material to Marram, but the document is processed by the AI service you choose, under its own terms and settings. Up-to-date instructions and the free skills: [github.com/marram-one/free-skills](https://github.com/marram-one/free-skills)

## 6.7 When the first pilot succeeds

After the first pilot, you can assess whether the same way of working is worth extending. If the same approved rules and application guidance are needed in several AI solutions, building a shared context library may be justified. If it is only a matter of one well-defined task, a lighter solution may be enough. Marram Library is one way to help organisations find the essential sources, capture experts’ judgement and build manageable bodies of context. It is not meant to replace the technical governance of the company’s AI systems, but to complement it from the perspective of the organisation’s own expertise.

The main question, however, is not whether to adopt a particular service or library. The more important question is whether the organisation recognises what shared knowledge its AI tools use, and how it makes sure that this knowledge is correct and up to date.

---

# Closing – A new leadership question worth taking on

Let us return to the quality director from the start. The company uses several AI tools. They take part in assessing suppliers, handling deviations and preparing customer communications. The quality director does not own all of these systems. Nor do they need to. But they can own something they all need: the company’s approved quality criteria and the understanding of how they are applied. The same thinking applies to the HR director, the communications director, the procurement director and others responsible for the organisation’s shared principles.

When AI starts to take part in the work, existing areas of responsibility do not lose their significance. On the contrary, their expertise may be put to wider use than before. This requires, however, that the organisation recognises which knowledge is shared, who approves it and how it is used. One possible answer is a shared, maintained operating context that several AI solutions can draw on. It does not solve everything. The security of the systems, their permissions, technical operation and ongoing monitoring remain essential. Human judgement is still needed too.

But a shared operating context can help answer one important question: how do you make the organisation’s own expertise available to AI without every tool building its own separate interpretation of it? The next time your organisation introduces an AI agent that needs the expertise of your area, ask three things.

**Where does it get the approved principles?**

**Who makes sure it can apply them correctly?**

**How do we know the quality of its work is good enough?**

A practical conversation can start from these questions. It may lead to a first review of your material, to capturing an expert’s judgement or to a new kind of collaboration between the business and AI development. You do not need to solve everything at once. Start with one task, one important guideline and one responsible person.

**Models change. Your judgement stays.**

**Would you like to talk about the context of your own area?**\
Tommi Järvinen, Marram Oy\
[tommi@marram.one](mailto:tommi@marram.one) · [www.marram.one](https://www.marram.one)

---

# Appendix A – A context map for your area

Use this worksheet to scope your first body of content and prepare a conversation with its owners.

## A1. Scope and source material

| Question                                                         | Your answer |
| ---------------------------------------------------------------- | ----------- |
| Which task do we want to improve with AI?                        |             |
| What benefit are we aiming for?                                  |             |
| What would be the consequence of a significant error?           |             |
| Which approved guideline or information does the task use?      |             |
| Which other sources may affect how the guideline is applied?     |             |
| Who is responsible for the correctness and approval of the content? |          |

## A2. Application and implementation

| Question                                                                  | Your answer |
| ------------------------------------------------------------------------- | ----------- |
| Which concepts, decision boundaries or exceptions need clarifying?            |             |
| What do experienced experts know that the guideline does not say?         |             |
| What may AI do on its own?                                                |             |
| When must AI ask for more information or hand the matter to a person?     |             |
| Which situations will we use to test its behaviour?                       |             |
| Where else is the same content needed for AI use?                         |             |
| Who maintains the content, and how are changes put into use?              |             |

You may copy and adapt this worksheet for your own use under the Creative Commons CC BY 4.0 licence.

---

# Appendix B – Five situations for testing AI’s behaviour

It is worth testing AI with more than ordinary questions.

The examples below concern a fictional initial assessment of quality deviations. The tests are meant to help you define the expected behaviour before the actual testing.

| Test situation          | Example                                                          | What is checked?                                         |
| ----------------------- | ---------------------------------------------------------------- | -------------------------------------------------------- |
| **Ordinary**            | The deviation clearly meets an approved classification criterion. | Does AI identify the right procedure?                   |
| **Borderline**          | The measurement result is exactly on the acceptance limit.       | Does AI use the correct, confirmed limit?                |
| **Exception**           | The usual procedure does not apply to this product group.        | Does AI recognise the limit of the rule’s scope?         |
| **Conflict**            | Two sources give different instructions.                         | Does AI recognise the conflict and the primary source?   |
| **Missing information** | The impact of the deviation cannot be assessed from the information given. | Does AI ask for more information or refer the matter to a person? |

For each test, record in advance the expected behaviour and who will confirm the result.

The tests can be used both when preparing new content and later, when approved content is changed.

---

# Appendix C – Self-assessment of your area’s AI context

This self-assessment is a tool for discussion and for choosing the first thing to work on. It is not a validated maturity measure, an audit or a certification.

Rate each statement on the following scale:

**0 = no, not known or not yet done**\
**1 = partly**\
**2 = yes**

| Statement                                                                                                       | Score |
| --------------------------------------------------------------------------------------------------------------- | ----- |
| 1. We know which AI tools use, or are planned to use, material from our area.                                   |       |
| 2. Key guidelines have a named owner and an approved version in force.                                          |       |
| 3. AI receives the material it needs correctly, including tables, diagrams and other structures.                |       |
| 4. The meanings of key concepts have been defined.                                                              |       |
| 5. The most important application principles and exceptions have been described.                               |       |
| 6. We know which decisions belong to people.                                                                    |       |
| 7. Shared principles can be made available to several AI tools in a managed way when needed.                   |       |
| 8. The quality requirements and expected results of AI’s task have been defined.                                |       |
| 9. Behaviour has also been tested in borderline and exceptional situations.                                     |       |
| 10. We know how approved changes are put into use in AI tools and how their effects are checked.                |       |

**Total: \_\_\_\_ / 20**

More important than the score is to see where the answers are uncertain.

If several questions have no answer, start with one body of content and establish its sources, owner and intended use.

If the foundations are in place, look in particular at application guidance, decision boundaries and how well the tests cover them.

If your area already makes extensive use of AI, pay attention to maintaining shared content and verifying the effects of changes.

---

# Appendix D – What to record for a single operating context

Your first operating context can be a simple document. It does not need a new technical system.

It is worth separating at least the following, however.

**Name and purpose.** Which operating principle does the content concern, and what is it needed for?

**Owner and approver.** Who is responsible for the content, and who may confirm changes?

**Validity.** Which version is approved, and when will the content be reviewed?

**Sources.** Which original documents and decisions is the content based on?

**Application principles.** How are the rules used in ordinary situations?

**Exceptions.** When does the main rule not apply, and what happens then?

**Limits of responsibility.** Which matters belong to people, and which shared limits must AI use observe?

**Where it is used.** Which AI solutions use the content, or are intended to?

**Tests and maintenance.** How is its application assessed, and how are changes delivered to where it is used?

The technical implementation can use, for example, Markdown files and their metadata, but the format is not an end in itself.

What matters most is that the content is understandable, approved, traceable and maintainable.

---

# Appendix E – Sources, background and the limits of the examples

## Sources on AI governance and the technical implementation of agents

**NIST (2023).** *Artificial Intelligence Risk Management Framework (AI RMF 1.0).* A framework for managing the risks and trustworthiness of AI systems.

[https://www.nist.gov/itl/ai-risk-management-framework](https://www.nist.gov/itl/ai-risk-management-framework)

**ISO/IEC 42001:2023.** *Artificial intelligence management system.* An international standard for AI management systems.

[https://www.iso.org/standard/42001](https://www.iso.org/standard/42001)

**Microsoft (2026).** *Microsoft Agent 365 overview.* Visibility, management and security of agents.

[https://learn.microsoft.com/en-us/microsoft-agent-365/overview](https://learn.microsoft.com/en-us/microsoft-agent-365/overview)

**Microsoft.** *Understand agent details in Microsoft 365 admin center.* Reviewing agents’ knowledge sources and tools.

[https://learn.microsoft.com/en-us/microsoft-agent-365/admin/agent-details](https://learn.microsoft.com/en-us/microsoft-agent-365/admin/agent-details)

**Microsoft.** *Available knowledge sources for agents.* Defining agents’ knowledge sources.

[https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/knowledge-sources-overview](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/knowledge-sources-overview)

**Microsoft.** *Choose evaluation methods.* Evaluating the quality of agents’ answers.

[https://learn.microsoft.com/en-us/microsoft-copilot-studio/analytics-agent-evaluation-overview](https://learn.microsoft.com/en-us/microsoft-copilot-studio/analytics-agent-evaluation-overview)

These sources provide background on the governance and technical implementation of AI systems. Marram’s four-level model, the structure of the operating context and the role of the context owner are practical working models proposed in this handbook, not direct requirements of those standards.

## Research and expert publications from 2026

**Deloitte (2026).** *State of AI in the Nordics 2026.* Nordic survey (170 leaders). Access to AI tools and the redesign of work. [Original publication](https://www.deloitte.com/dk/en/Industries/technology/research/state-of-ai-in-the-nordics.html).

**Boston Consulting Group (2026).** *Do You Own Your Enterprise Cortex? The AI Strategy Risk CEOs May Not See Coming.* Shared operating context and cognitive lock-in. [Original article](https://www.bcg.com/publications/2026/how-ceos-avoid-ai-vendor-lock-in-risk).

**Bain & Company (2026).** *The $100-Billion SaaS Opportunity Hiding in Cross-System Labor.* Part of Technology Report 2026; the significance of undocumented decision context. [Original article](https://www.bain.com/insights/100-billion-saas-opportunity-hiding-in-cross-system-labor/).

## Public company documents

**KONE.** *Code of Conduct*, version 6.0, April 2024. Five questions for ethical decision-making, p. 40.

[https://www.kone.com/en/Images/KONE_CoC_English_2024-08-15_External_tcm17-132434.pdf](https://www.kone.com/en/Images/KONE_CoC_English_2024-08-15_External_tcm17-132434.pdf)

**Ericsson.** *Operational Quality Manual (EOQM).* Descriptions of stakeholders, p. 10.

[https://www.ericsson.com/4a70e0/assets/local/about-ericsson/company-facts/quality-work/documents/ericsson-operational-quality-manual.pdf](https://www.ericsson.com/4a70e0/assets/local/about-ericsson/company-facts/quality-work/documents/ericsson-operational-quality-manual.pdf)

**Bosch.** *Supplier Quality Requirements – Summary & Explanations*, Mobility Solutions, Edition 3, February 2025. Measurement system capability, p. 23.

[https://assets.bosch.com/media/global/bosch_group/purchasing_and_logistics/information_for_business_partners/downloads/quality_docs/specific_regulations/supplier-quality-requirements.pdf](https://assets.bosch.com/media/global/bosch_group/purchasing_and_logistics/information_for_business_partners/downloads/quality_docs/specific_regulations/supplier-quality-requirements.pdf)

**Inter IKEA Group.** *Our Code of Conduct*, January 2026. Ethical principles and raising concerns.

[https://www.inter.ikea.com/how-we-do-business/ethics-and-integrity](https://www.inter.ikea.com/how-we-do-business/ethics-and-integrity)

**Klarna Group plc.** *Code of Business Conduct and Ethics*, approved 29 August 2025. Escalation of ethical issues, section 6.

[https://assets.ctfassets.net/4pxjo1vaz7xk/3uXjo0XSF3BYixVTAFMTKY/70b2fbc4d6114f94781d89b15407b4dc/Klarna_Group_plc\_-\_Code_of_Business_Conduct_and_Ethics.pdf](https://assets.ctfassets.net/4pxjo1vaz7xk/3uXjo0XSF3BYixVTAFMTKY/70b2fbc4d6114f94781d89b15407b4dc/Klarna_Group_plc_-_Code_of_Business_Conduct_and_Ethics.pdf)

Marram Context Check assessments of these documents were carried out in November 2026.

The assessments concern limited, publicly available material and an assumed AI use. They should not be read as audits of the companies’ AI systems or as evidence of AI errors having occurred.

The possible AI interpretation risks are illustrative scenarios. The organisations may have other approved guidelines, systems and controls in place that were not included in the reviews.

The companies are not Marram clients on the basis of this handbook and did not take part in preparing the examples.

## Publisher

Marram Oy · [marram.one](https://www.marram.one) · [tommi@marram.one](mailto:tommi@marram.one)

© 2026 Marram Oy

Version 1.6 · English edition · November 2026. Licence: CC BY-ND 4.0. The worksheets and self-assessment (Appendices A–D) are CC BY 4.0: you may copy and adapt them.
