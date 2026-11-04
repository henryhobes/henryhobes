I work on LLM trade capture at a corporate-bond trading platform. I write the prompts and evals, build the frontend, and deal with it when it breaks.

## How I build

Claude Code and Cursor write most of my code. My job is everything around that: I scope the work, review the diffs, debug, test, and I don't merge anything I haven't read. Mostly TypeScript and React, and one Scala PR I'm still proud of.

Most of the accuracy gains came from reading production traces one at a time. I don't think there's a shortcut around that.

## Selected work

**[apprenticer](https://github.com/henryhobes/apprenticer)**: talk to an AI about anything, by voice, in your browser, with a board beside it that shows what is easier to see than to hear. Learn a topic, run a mock technical interview, rehearse a design review with your boss, think a problem through.

There is nothing to configure. Your coding agent writes a *space*, a plain folder, and Apprenticer serves it on localhost. The space's brief decides how the AI behaves, so none of teaching or interviewing is built in. A turn is: the voice model hears you, the server asks the mind what to say, the mind writes the reply and anything for the board, and the voice speaks it. The voice only listens and talks; every word comes from the mind. At the end of a session the mind rewrites its own notes, so next time it remembers you.

It's the piece of my work I'd most want someone to try, because it's the one where the design question is interesting: how much of a good conversation is the model, and how much is everything around it. MIT licensed, Node 24+, published on npm as `apprenticer`.

**[booey](https://github.com/henryhobes/booey)**: guided AI tools for my parents' generation. They won't type into a blank chatbot, so there isn't one. You pick a task, answer a few questions, get a result. Built in a long weekend with Claude Code, shipped to booey.ai, retired when the name got reused for something else.

**[TheFranchise](https://github.com/henryhobes/TheFranchise)**: an ESPN fantasy draft assistant. The draft room uses an undocumented WebSocket protocol, so I captured a real draft, worked out the grammar, and cross-checked the decode against ESPN's public API. A LangGraph front office recommends the pick. The two halves never got wired together in time. I drafted without it and archived the repo.

One more I can't link: my dad texts an assistant that reads his forwarded email and answers. It sits on an open-source harness. Most of my work is the containment around it, since I assume his inbox will eventually contain a prompt injection.

## Before this

In college I co-founded a drone photography business for realtors. I did the sales, the flying, the editing, and the paperwork. I also helped start Georgetown's blockchain club and put most of my time there into education, teaching students from zero. Business major, CS minor.

## Contact

henrybhobin@gmail.com · [LinkedIn](https://www.linkedin.com/in/henry-hobin)
