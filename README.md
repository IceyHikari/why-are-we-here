# A Beautiful Image Is Not Yet a Game

## Why I Still Need to Program

In my final-year project, our team generated an animation for an Ifrit, a fire spirit in an Arabian-inspired faction. It looked impressive in the preview. Yet it was not ready for the game. The character changed between frames, the movement did not match the timing of an attack, and the fiery colours made background removal difficult. We had an attractive moving image, but not a reliable game asset.

I was the overall game designer and producer of this AIGC-assisted turn-based tactics game. My work crossed worldbuilding, faction design, units, heroes, spells, art direction, music specifications and production coordination. AI helped our team explore visual possibilities and generate variations quickly. The incident with the Ifrit, however, showed me the difference between generating content and directing a computational work.

To make the animation usable, the team needed more than a better prompt. We locked the approved character reference, divided the action into timed phases, selected a chroma-key background that contrasted with the character, and established file names and asset identifiers for the extracted frames. Those frames then had to become Unity AnimationClips and connect correctly to unit data and combat logic. The technical implementation was shared work, but as producer I had to define the requirements, coordinate decisions across disciplines, and judge whether the result still served the intended experience.

Programming gives me a way to turn those judgements into conditions that can be inspected and tested. Does every frame refer to the same unit? Does the attack land at the moment the combat system applies damage? What happens when an asset is missing or an AI output breaks the expected format? If I cannot read the logic behind these questions, I can describe the desired mood but cannot reliably specify the work.

This is why I am not learning programming to compete with AI at producing code. I am learning it to understand how an artistic intention becomes a system that another person can actually experience.

## Constraints Are Part of Authorship

[Dylan Beattie presents programming as a creative medium](https://www.youtube.com/watch?v=6avJHaC3C2U), not merely a technical chore (Beattie, 2018). My project led me to a related position. In an AIGC workflow, creative control exists not only in an image I draw or a script I type. It also exists in the constraints I define: what must remain consistent, what may vary, how an output is evaluated, and what happens when it fails.

The same problem appeared at the scale of the whole game. Our factions could not be collections of visually appealing cultural symbols. Their architecture, music, unit abilities and tactical identities needed to express the same design logic. A generic "desert fantasy" image might appear suitable for the Arabian faction while flattening its history into a stereotype. As the lead designer, I had to decide which references supported the world we were building and which ones merely looked familiar.

For me, this is where empathy enters technical practice. I understand games as an art form because they organise images, sound, narrative, rules, space and human participation into an experience. What moves me is the human intention behind that experience: what the creator wants to express, whose perspective is represented, and what the player is invited to feel. AI can produce emotionally suggestive images and language, but I remain responsible for those choices. Empathy does not replace technical skill. It gives the technical system a reason and a direction.

## AI Is a Collaborator, Not an Authority

My experience does not support the simple claim that AI is incapable of creativity. In a [large-scale study of research ideation](https://openreview.net/forum?id=M23dTGWCZy), Si et al. (2025) found that LLM-generated ideas were judged more novel than ideas written by human experts, although they were slightly weaker in feasibility; the researchers also identified problems with diversity and self-evaluation. This evidence changed my initial position. The important distinction is not human originality versus machine imitation. It is between generating a candidate and taking responsibility for evaluating, developing and integrating it.

That is how I now use AI in both creative practice and research. I may ask it to propose variations, expand search terms or help me interpret unfamiliar material. I do not treat fluency as proof. I compare outputs with the project intention, inspect the original sources, and make the final decision myself. In the game project, AI expanded what our small team could attempt. It did not decide what deserved to remain in the work.

## Why I Am Here

I want to become a producer who can connect creative direction, research, art pipelines and technical implementation. A producer may not write every script, but must be able to question a technical proposal, recognise when a prototype only appears to work, and communicate constraints across disciplines. Without programming knowledge, I could approve an image. With it, I can ask how that image becomes data, behaviour and player experience.

Some manual coding tasks may become obsolete during my career. That changes what programming knowledge is for; it does not make the knowledge irrelevant. **AI can expand what I can make. Empathy determines what is worth making. Programming connects the two.**

## References

Beattie, D. (2018, November 15). *The art of code* [Video]. YouTube. https://www.youtube.com/watch?v=6avJHaC3C2U

Si, C., Yang, D., & Hashimoto, T. (2025). Can LLMs generate novel research ideas? A large-scale human study with 100+ NLP researchers. In *The Thirteenth International Conference on Learning Representations*. https://openreview.net/forum?id=M23dTGWCZy
