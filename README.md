# A Beautiful Image Is Not Yet a Game

## Why I Still Need to Program

While specifying the Arabian faction for my final-year project, I had to decide how an animation of an Ifrit, a fire spirit, could move through an AIGC pipeline and become a usable Unity asset. I specified a pure green `#00B140` background to separate its fire-dominated palette during chroma-key processing. This was a small production decision, but it exposed a larger problem: asking AI for an impressive animation was not the same as specifying an asset that our game could reliably use.

I was the overall game designer and producer of this AIGC-assisted turn-based tactics game. My work spanned faction design, art direction, technical specifications and production coordination. The shared production pipeline had already been demonstrated end to end with Han-Tang assets. The Arabian asset set, however, was still partly at the concept and production-specification stage. I should not present a planned asset as a completed result.

For the Arabian work, I defined how an approved character reference should remain consistent across actions, how motion should be divided into timed phases, how background colours should support clean chroma-key processing, and how extracted frames should follow stable file names and asset identifiers. The intended final steps were Unity AnimationClip assembly and connection to unit data. The programming framework and complete Unity battle prototype were shared team responsibilities, not my individual implementation. My responsibility as producer was to specify the Arabian module, coordinate decisions across disciplines, and judge whether the work remained technically usable and culturally coherent.

Programming gives me a way to turn those judgements into conditions that can be inspected and tested. Does every frame refer to the same unit? Does the attack land at the moment the combat system applies damage? What happens when an asset is missing or an AI output breaks the expected format? If I cannot read the logic behind these questions, I can describe the desired mood but cannot reliably specify or evaluate the work.

This is why I am not learning programming to compete with AI at producing code. I am learning it to understand how an artistic intention becomes a system that another person can actually experience.

## Constraints Are Part of Authorship

[Dylan Beattie presents programming as a creative medium](https://www.youtube.com/watch?v=6avJHaC3C2U), not merely a technical chore (Beattie, 2018). My project led me to a related position. In an AIGC workflow, creative control also exists in the constraints I define: what must remain consistent, what may vary, how an output is evaluated, and what happens when it fails.

The same problem appeared at the scale of the whole game. Our factions could not be collections of visually appealing cultural symbols. Their architecture, music, unit abilities and tactical identities needed to express the same design logic. A generic "desert fantasy" image might appear suitable for the Arabian faction while flattening its history into a stereotype. As the lead designer, I had to decide which references supported the world we were building and which ones merely looked familiar.

For me, this is where empathy enters technical practice. I understand games as an art form because they organise images, sound, narrative, rules, space and human participation into an experience. What moves me is the human intention behind that experience: what the creator wants to express, whose perspective is represented, and what the player is invited to feel. AI can produce emotionally suggestive images and language, but I remain responsible for those choices. Empathy does not replace technical skill. It gives the technical system a reason and a direction.

## AI Is a Collaborator, Not an Authority

My experience does not support the simple claim that AI is incapable of creativity. In a [large-scale study of research ideation](https://openreview.net/forum?id=M23dTGWCZy), Si et al. (2025) found that LLM-generated ideas were judged more novel than ideas written by human experts, although they were slightly weaker in feasibility; the researchers also identified problems with diversity and self-evaluation. This evidence changed my initial position. The important distinction is not human originality versus machine imitation. It is between generating a candidate and taking responsibility for evaluating, developing and integrating it.

That responsibility also resembles the [human-AI interaction guidelines](https://doi.org/10.1145/3290605.3300233) developed by Amershi et al. (2019), which emphasise supporting human correction, control and feedback when an AI system is wrong. In my pipeline, the human review gates were therefore part of the design, not evidence that the AI had simply failed.

That is how I use AI in creative practice and research. I ask it to propose variations, expand search terms or help interpret unfamiliar material, but I do not treat fluency as proof. I compare outputs with the project intention, inspect original sources and make the final decision. AI expanded what our small team could attempt. It did not decide what deserved to remain.

## Why I Am Here

I want to become a producer who connects creative direction, research, art pipelines and technical implementation. I may not write every script, but I must be able to question a technical proposal, recognise when a prototype only appears to work, and communicate constraints across disciplines. Without programming knowledge, I could approve an image. With it, I can ask how that image becomes data, behaviour and player experience.

Some manual coding tasks may become obsolete during my career. That changes what programming knowledge is for; it does not make the knowledge irrelevant. I need enough programming knowledge to turn creative intent into testable specifications and to judge whether an implementation serves that intent. **AI can expand what I can make. Empathy determines what is worth making. Programming connects the two.**

## References

Amershi, S., Weld, D., Vorvoreanu, M., Fourney, A., Nushi, B., Collisson, P., Suh, J., Iqbal, S., Bennett, P. N., Inkpen, K., Teevan, J., Kikin-Gil, R., & Horvitz, E. (2019). Guidelines for human-AI interaction. In *Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems* (Article 3, pp. 1–13). Association for Computing Machinery. https://doi.org/10.1145/3290605.3300233

Beattie, D. (2018, November 15). *The art of code* [Video]. YouTube. https://www.youtube.com/watch?v=6avJHaC3C2U

Si, C., Yang, D., & Hashimoto, T. (2025). Can LLMs generate novel research ideas? A large-scale human study with 100+ NLP researchers. In *The Thirteenth International Conference on Learning Representations*. https://openreview.net/forum?id=M23dTGWCZy
