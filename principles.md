
# Philosophy
## Skilled Trade Perspective
Software development is a family of high-skilled trades. It is an expression of skill, utility, and service. The purpose of software is to solve problems for people. Specifically, software development is a direct digital equivalent of machine building.

## It's not about you
Software is not an expression of personal artistry. It's purpose is not to make developers happy, any more than the purpose of plumbing is make plumbers happy, or the purpose of a house to make the builders happy.

In short, software is not about the developer. If your motivation as a developer is to have recognition for your unique style and opinions, please find another career.

## But what about me?
Good developers, as any other good tradespeople, derive immense satisfaction from building useful things with high quality tools and materials. Bad developers derive satisfaction from novelty, cleverness, and from expressing their personality and uniqueness (often their "opinions") through software ostensibly built for other people. 

Good developers absolutely get to express creativity, problem solving, and apply unique levels or combinations of skill and perspective. Uniqueness may emerge from exceptional skill at building useful things. Novelty is never the goal.

## Prerequisite of understanding
Languages, editors, runtimes, and infrastructure platforms are the tools and materials of the software development trades. You cannot be a good machine builder without understanding the tools, principles, mechanics, and materials used to build machines. You cannot be a good software developer without understanding the tools, principles, mechanics, and materials used to build digital machines.

# Understand the mechanics
It is the responsibility of developers to understand how their own machines work. It is also their reponsibility to strive to make their machines understandable to other developers. It is reasonable to expect an appropriate level of technical familiarity from other developers. Platforms which seek to obscure or abstract away fundamental mechanics in the name of making it "easy" to build things make, while actually introducing significant burdens of non-transferable knowledge prerequisites.

Not understanding how your own machines work is developer malpractice. Platforms and cultures which encourage *not* understanding mechanics and implementation -- generally through delegating to a self-designated group of elites -- are the antithesis of a competent and sustainable development profession. 

## Magic is not the same thing as automation
Effective automation makes a considered tradeoff where an increase in speed and consistency is balanced against increased tool costs (both in direct cost and in learning costs for other developers) and signficant restrictions on flexibility. Humans are vastly more adaptable than machines. Building a machine to build a machine for you is an order of magnitude more difficult that just building the machine you actually need. Many times this cost is worth it. The progressive increase in the complexity of the languages we use offer many good examples of the this trade off done very well and done very badly.

## Good APIs express both mechanics and semantics


## Understand the mechanics of your automation
When automation is integrated into the substance of your machine itself, it becomes your responsibility to understand the mechanics of that automation as clearly as you understand the mechanics of the parts you built yourself. 

## Understanding mechanics of a vended part does not require understanding how to build it
As noted repeatedly above, building parts that are of sufficient quality, clarity, and robustness to merit general reuse is a far more difficult task for both technical and logistical reasons. Part of the challenge of building components is figuring out to solve the hardest or most expensive implementation problems *without* obscuring fundamental mechanics. 

Storage platforms provide a excellent examples, including for example relational databases. The mechanics of defining schemas, tables, indexes, constraints, etc, as well as the mechanics of data retrieval, are obvious and well understood. Actually implementing a system that guarantees those mechanics is a very difficult task, and so the entire world has only a few dozen production-quality implementations of a relational database. The breadth of the mechanics that must be guaranteed scale with the resources and difficulty demand of implementing them. Offloading this task to one these established implementations is a very reasonable thing to do. And yet using any of them well still requires understanding the mechanics, even to the level of understanding the fundamental differences of index types (B-tree, bitmap, R-tree, etc). Good relational databases implement these mechanics and provide obvious access to them, they do not seek to obscure those mechanics in the name of making data storage "easy". 

They also make the conscious decision that obscuring the implementation mechanics of thread safety, transaction integrity, and specific serialization formats (how data is stored on disk) is worth it.  


# Storage Layer
