# From Generated Assets to a Playable System

## Why I Still Need to Program

Games are often discussed as an art form because they combine images, sound, narrative, rules, space and human participation. For me, the most moving part of artistic creation is not the technical object itself, but the human feeling behind it: what someone wants to express, what they hope another person will understand, and how an audience is invited to feel something through the work.

This is why I am not learning programming to compete with AI at producing code. I am learning it to understand how an intention becomes a system that another person can actually experience.

During my final-year project, I worked as the overall game designer and producer for an AIGC-assisted turn-based tactics game with several historical and mythological factions. AI helped us explore visual ideas, generate candidate assets and produce variations quickly. It was a powerful collaborator, but its output did not automatically become a coherent game. A generated character image could be attractive but culturally inaccurate. An animation could look convincing in a video preview but become unusable after frame extraction. A piece of code could run in isolation while failing to fit the project's data structure or gameplay logic.

The production process therefore became more than prompting. An approved character reference had to remain visually consistent across actions. Motion had to be described in timed phases. Background colours had to support clean chroma-key processing. Extracted frames required stable file names and asset identifiers before they could be assembled into Unity AnimationClips and connected to unit data. As the overall designer and producer, my responsibility was to define these constraints, coordinate their use, and judge whether the result still served the intended experience. A mistake at any stage could leave us with a visually impressive result that the game could not reliably use.

The most important improvement was therefore not a more elaborate prompt. It was the introduction of constraints: locked appearance references, defined action phases, complementary keying backgrounds, naming conventions and human review gates. My project report eventually described this as a five-stage pipeline rather than one-click generation. That distinction changed how I understood both AI and programming. AI generated candidates; the production system determined whether those candidates could become part of the work.

## Constraints Are Part of Authorship

Dylan Beattie presents programming as a creative medium rather than merely a technical chore (Beattie, 2018). My experience supports that argument, but with an AIGC-era qualification. Creative control no longer exists only in the image I draw or the code I type myself. It also exists in the constraints I define: what must remain consistent, what may vary, how a result is evaluated, and what happens when it fails.

This became visible in other parts of the game as well. The factions could not simply be collections of AI-generated cultural imagery. Their visual language, music, unit abilities and tactical identity had to express the same underlying design. Even when different faction soundtracks shared one melody, their instruments, rhythm and emotional function had to reflect different gameplay mechanisms. Without formal rules, AI offered variety; with rules, the project gained coherence.

For me, empathy is the reason this coherence matters. A game may have elegant systems and beautiful assets, but without an understanding of human feeling it may not know what it wants players to experience. AI can simulate emotional language and produce expressive-looking images, but I remain responsible for deciding what the game is trying to say, whose experience it represents, and how players are invited to feel. I decide whether a faction feels dignified or stereotyped, whether a mechanic expresses its cultural identity, and whether the player's choices support the emotional direction of the work.

## AI Is Still a Valuable Collaborator

This does not mean that AI lacks creativity or usefulness. Si, Yang and Hashimoto (2024) found that AI-generated research ideas could be rated as more novel than ideas produced by human experts, although the AI ideas were slightly weaker in feasibility and the systems struggled with diversity and self-evaluation. This is a more useful distinction than saying that AI only copies. AI can produce surprising candidates, but surprise alone does not establish quality, feasibility or responsibility.

The same caution applies when AI assists research. I use it to expand search terms, interpret unfamiliar material and compare possible directions, while checking original publications and making the final judgement myself. Fluent output is a starting point for exploration, not proof that a claim or reference is correct.

## Why I Am Here

My future role is not limited to being an artist or a programmer. I want to work as a producer who can connect creative direction, research, art pipelines and technical implementation. A producer may not write every script, but must be able to question a technical proposal, recognise when a prototype only appears to work, and communicate constraints across disciplines.

Some manual coding tasks may become obsolete during my career. That does not make programming knowledge irrelevant. It changes what that knowledge is for. For me, learning programming means gaining access to the layer where artistic decisions become system behaviour. AI can expand what I can make. Empathy determines what is worth making. Programming connects the two.

## References

Beattie, D. (2018, November 15). *The art of code* [Video]. YouTube. https://www.youtube.com/watch?v=6avJHaC3C2U

Si, C., Yang, D., & Hashimoto, T. (2024). *Can LLMs generate novel research ideas? A large-scale human study with 100+ NLP researchers*. arXiv. https://doi.org/10.48550/arXiv.2409.04109
