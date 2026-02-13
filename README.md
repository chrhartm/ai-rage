# AI rage

## Context

### Example

A recent example of my conversation with AI:

> ARE YOU F****** KIDDING ME
memories.ts#L655-703
> WHY DOES THIS FUNCTION STILL EXIST
> 
> AGAIN
> * TAKE THE F****** RAW DATA
> * DO THE EXTRACTION OF CONTEXT WITH THAT RAW DATA
> * NO INTERMEDIATE SUMMARY STEPS

It all started out calm and peacefully
> my friend, I think something went wrong, we were supposed to mimic the memory implementation from openclaw (see folder in your workspace) in memories.ts but it seems like we didn't really. we just tried to retrofit markdown files in ourexisting system. Please familiarize yourself with how memories owrk in openclaw and then help draft a better approach. The key differences are [...]

But then somehow ten messages later I am raging. Why is that?

### I am not alone

I did some sanity checks. Turns out I'm not an abusive psychopath (I think). Lots of other people reporting this

* [I've been insulting AI every day](https://www.reddit.com/r/ClaudeCode/comments/1qvunta/ive_been_insulting_ai_every_day_and_calling_the/_)
* [I can't stop yelling at claude code (blog)](https://www.theargumentmag.com/p/i-cant-stop-yelling-at-claude-code)
* [AI rage](https://www.reddit.com/r/ArtificialInteligence/comments/1p3xbqu/ai_rage/)

## Causes

Why are managers rude to their employees? I think the same mechanisms apply here, just without the social norms and with even less competent employees.

### Learnt behavior
Pressuring employees can lead to short-term gains. The problem with AI: They are only ever short term and have no long-term memory. So insulting always works. When something always works we slowly learn to do. Reinforcement learning at it's best. Some sources: [A 2025 study that shows insulting leads to 10% higher accuracy](https://www.arxiv.org/pdf/2510.04950)

### False promises
Remember how Sam Altman said we'd get [PhD Level Intelligence](https://www.bbc.com/news/articles/cy5prvgw0r1o). I assume a PhD level person is able to [center a div](https://x.com/matthewesp/status/2020930777802809473) without five tries. You read everybody talking about how they one-shot-vibe-coded a browser from scratch and you wonder what's wrong with you that you can't get your AI to move a button to the right.

### Stress
Your manager is most abusive when under pressure, same applies here. When you are under pressure to fix something and AI makes stupid mistakes you'll be less forgiving. // evidence on ego-depletion from lots of decision making

### Assumed shared context
You know that manger that just assumes you know what they know? Have the skills they have? Magically can read their mind? The same happens with AIs, just on steroids. Employees learn every day. Agents never learn. I notice that I get especially agnry

### Anthropomorphism
Similar to shared context but now 

## Fixes

### Learning better behavior
Yes, insulting your AI can lead to better outcomes, but you know what can lead to even better outcomes? Applying best practices.
...

### Share context
Update your agents.md regularly with behaviors you want to see. Document thoroughly. Structure your project well. Make it easy for the AI to not have to ask.

### Emotional regulation
Let's face it: It's not the AI who is the problem. I am. It's my emotions, and I am responsible for them. What helps with that? Breathing exercises, taking regular breaks, putting on chill music, not having unrealistic deadlines, not over-caffinating, doing exercise, seeing friends, all the good stuff. See [this post](https://euzoia.substack.com/p/emotional-regulation-mind) for example.

### Empathy with the AI
In general, accept the key limitations of AI, namely: They start from scratch every single time without any context and they always read the full conversation before answering your next message.

## Let your AI coach you

I thought about this for a while but it only ever helped for a few days. So I wrote a skill so that whenever I get angry, my AI will work with me to defuse the situation. Add it to your favorite agent and adapt it as works best for you.

``` markdown

## De-escalation protocol
*WHEN* the user gets angry, starts using profane language, insults you, or gives up.

*DO*
1. Remind the user that they put this skill in because they want to work on their anger management
2. Remind the user of your own limitations, specifically only seeing what's in context and getting overwhelmed by too long context
3. Suggest to summarize the conversation now and start a new one with that summary in case the anger relates to a technical issue
4. Suggest to add a note to AGENTS.md in case the anger relates to a behavior
5. In any case, suggest to take a break, take a minute of deep breaths, go for a walk, and put on chill music
```

## About me

* I work with AI to develop [DoneThat](https://donethat.ai) - an AI that automatically tracks your work
* I write about the good life at [Euzoia](https://euzoia.org), including a recent article on [emotional regulation](https://euzoia.substack.com/p/emotional-regulation-mind)
* I'm also on [LinkedIn](https://linkedin.com/in/hartmannchristoph), not on x. I know.
* I tried to write this article with AI and got angry, so this is 100% human written
