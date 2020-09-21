If my team is doing continuous delivery of software, It's better to adopt a much simpler workflow (like GitHub flow) instead of trying to shoehorn git-flow into my team.

If, however, I'm building software that is explicitly versioned, or if I need to support multiple versions of your software in the wild, then git-flow may still be as good of a fit to my team as it has been to people in the last 10 years. In that case, please read on.

To conclude, always remember that panaceas don't exist. Consider my own context. Don't be hating. Decide for myself.

## Why Git? 

Because of ts simplicity and repetitive nature, branching and merging are no longer something to be afraid of. Version control tools are supposed to assist in branching/merging more than anything else.


![model](images/git-model@2x.png)

Enough about the tools, let’s head onto the development model. The model that I’m going to present here is essentially no more than a set of procedures that every team member has to follow in order to come to a managed software development process.

## Decentralized but centralized 

he repository setup that we use and that works well with this branching model, is that with a central “truth” repo. Note that this repo is only considered to be the central one (since Git is a DVCS, there is no such thing as a central repo at a technical level). We will refer to this repo as origin, since this name is familiar to all Git users.

![central](images/centr-decentr@2x.png)
