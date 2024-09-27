# CG/WG Proposal Stages

Author: @bumblefudge, @samuelgoto
Created: 09/26/2024
Last update: 09/26/2024
Status: proposed CG charter amendment

This is a proposal to break proposals into 5 stages of maturity, with clear guidelines and requirements to advance them:

* [Stage 0](#stage0): **Exploration** of a Problem Space and/or user stories
* [Stage 1](#stage1): **Incubation** of targeted candidate solutions
* [Stage 2](#stage2): **Formalization** a preferred Proposal
* [Stage 3](#stage3): **Implementation** of the preferred Proposal
* [Stage 4](#stage4): **Publication** of a Proposed Recommendation

These stages support the W3C process.
If there is ever any question between W3C process requirements and how the groups will progress their work, the W3C process has precedent.

## Stage 0: Exploration

The purpose of Stage 0 proposals is to allow anyone to raise and explore the Problem Space without asking for permission. 

  * What's needed from individuals?
    * [ ] Typically, a detailed (but IP-safe, high-level) issue describing a user story or problem
        * Optionally, a personal repo, a blog post with examples, a mock-up, etc. 
  * Who is involved?
    * CG meeting time should be minimally requested except in the form of "announcements"
    * CG Mailing List is an appropriate place for high-level or user-story discussion.
    * It is also recommended that community venues like [SocialHub](https://socialhub.activitypub.rocks/), [Indieweb.org Brainstorming](https://indieweb.org/wiki#Brainstorming), [Fediverse Ideas](https://codeberg.org/fediverse/fediverse-ideas/), or the social web itself be used to gather more input and to poll interest.
    * Descriptive specifications of a prototype (whether as a drafting exercise or as an invitation to prototype interoperability) can be hosted on git forges, including community venues like [the Fediverse Enhancement Proposals](https://codeberg.org/fediverse/fep/)
  * What's the optimal outcome?
    * Objective, open description of a problem or user story [set] that is within scope of the CG
    * A champion to gather and synthesis feedback, from outside the CG and to coordinate with the CG for review and future stages of work

## Stage 1: Incubation (Community and/or Community Group)

The purpose of Stage 1 proposals is to explore the Solution Space and evaluate multiple candidate solutions fairly.
This is where most of the work gets done because it involves exploring alternatives, understanding tradeoffs, gathering implementation experience, incubating alternatives, gathering evidence of demand and fitness for purpose, and finally, identifying the best out of the many alternatives.

**Great care** should be taken to avoid substantial technical/design discussions happening outside the "IPR" boundary of the Community Group members if normative status beyond stage 1 is desired;
further standardization MUST be rejected if "clean IPR" cannot be achieved (e.g. by post-facto IP grants from all substantial contributors).

  * What's needed from champions?
    * [ ] Public identification of one or more [champions](https://github.com/tc39/how-we-work/blob/main/champion.md)
    * [ ] An understanding of the problem space (need not be *deeply* technical)
    * [ ] Familiarity with prior art and related parallel work
  * What's asked of the **Community Group**?
    * [ ] The Community Group consensus that the problem is worth spending the Community Group’s time working on
    * [ ] A home for incubating the proposal. Small decisions will incubate in tracking issues. If and when the champions are ready to more thoroughly document their proposal, the WG chairs will create a repo for the champions to develop a cohesive proposal (e.g., [example](https://github.com/swicg/activitypub-http-signature)). 

## Stage 2: Formalization (Community Group)

The purpose of Stage 2 Proposals is to formally specify one or more (workable) candidate solutions identified in the prior step:
handle corner cases, integrate with other parts, reconcile with other proposals, and resolve the concerns identified at the entrance.
The Proposal enters Stage 2 with a list of blocking issues to advance to the next stage and exits with all of the issues resolved and CG consensus on a CG Report.

  * What's needed from champions?
    * [ ] An [explainer](https://tag.w3.org/explainers/)
    * [ ] Alternatives and trade-offs considered (an overview of useful discussions on and off CG venues appreciated)
    * [ ] A specific preferred proposal, e.g., a Report draft, which can include code samples, examples, etc.
    * [ ] Developer implementation experience (e.g., a prototype, interop experiments, etc) 
    * [ ] Confidence of developer demand and fitness for purpose (e.g. a developer or forker of a complete implementation that needs this proposal)
  * What's asked of the **Working Group**?
    * [ ] Working Group consensus to adopt the proposal as the basis for their work as a [Working Draft](https://www.w3.org/policies/process/#RecsWD).
    * [ ] Working Group identification of the list of (seemingly resolvable) issues that have to be addressed before [Stage 3](#stage-3).
    * [ ] An [Editor's Draft](https://www.w3.org/policies/process/#editors-draft) can be used to get PRs merged between [Working Draft](https://www.w3.org/policies/process/#RecsWD) revisions.
   
## Stage 3: Implementation and Normative Draft (Working Group)

The purpose of Stage 3 Proposals is to increase implementation and deployment confidence in order to move from CG report to a complete draft of a [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR).
 
  * What's needed from champions?
    * [ ] Expanded Report (i.e. first draft of a Recommendation) and/or PR to extend or update Social Web normative specs
        * [ ] Conformance sections and initial Privacy and Security Considerations 
    * [ ] Runnable Tests and test case documentation (ideally more formal than pseudocode)
    * [ ] Further implementation experience, ideally diverse and external
  * What's asked of the **Working Group**? 
    * [ ] Working Group consensus that the [Working Draft](https://www.w3.org/policies/process/#RecsWD) sufficiently resolves all of the issues raised at [Stage 2](#stage-2)
    * [ ] Working Group consensus to publish the [Working Draft](https://www.w3.org/policies/process/#RecsWD) as the Working Group's [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR)
  
## Stage 4: Publication or Re-publication (Working Group)

 The purpose of Stage 4 Proposals is to produce a new [W3C Recommendation](https://www.w3.org/policies/process/#RecsW3C) or a new minor or major version of a prior one.
 
  * What's needed from champions?
    * [ ] Sufficient [implementation experience](https://www.w3.org/policies/process/#implementation-experience)
    * [ ] Two or more independent and complete implementations
      * [ ] Implementation reports and corresponding conformance reports for each
  * What's asked of the **Working Group**?
    * [ ] Working Group consensus that the [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR)'s implementation experience is complete and
    * [ ] Working Group consensus to publish it as a [Proposed Recommendation](https://www.w3.org/policies/process/#RecsPR)

## Prior Art

* Social CG precedents:
  * Evan Promodorou's [ActivityPub/ActivityStreams-specific Vocabulary Extension Policy](https://swicg.github.io/extensions-policy/)
  * A. Schrijver [3-stage Standardization Process Proposal](https://socialhub.activitypub.rocks/t/3-stage-standards-process-guaranteeing-an-open-and-decentralized-ecosystem/3602)
  * Indieweb [Living Standard](https://indieweb.org/specifications) Process (see [github discussion here](https://github.com/w3c/strategy/issues/435#issuecomment-1751403081))
* TC39  
  * Proposals Repo: [https://github.com/tc39/proposals](https://github.com/tc39/proposals)  
  * Stages: [https://tc39.es/process-document/](https://tc39.es/process-document/)   
  * Examples  
    * Decorators Repo: [https://github.com/tc39/proposal-decorators](https://github.com/tc39/proposal-decorators)   
    * Temporal Repo: [https://github.com/tc39/proposal-temporal](https://github.com/tc39/proposal-temporal)   
* Immersive Web CG/WG  
  * Proposals Repo: [https://github.com/immersive-web/proposals](https://github.com/immersive-web/proposals)  
  * Stage 0 Issues: [https://github.com/immersive-web/proposals/issues](https://github.com/immersive-web/proposals/issues)   
  * Examples  
    * \<model\> Repo: [https://github.com/immersive-web/model-element](https://github.com/immersive-web/model-element)  
    * Depth sensing Repo: [https://github.com/immersive-web/depth-sensing](https://github.com/immersive-web/depth-sensing)   
* WebAssembly  
  * Proposals Repo: [https://github.com/WebAssembly/proposals](https://github.com/WebAssembly/proposals)  
  * Examples  
    * Tail call Repo: [https://github.com/WebAssembly/tail-call](https://github.com/WebAssembly/tail-call)  
    * GC Repo: [https://github.com/WebAssembly/gc](https://github.com/WebAssembly/gc)