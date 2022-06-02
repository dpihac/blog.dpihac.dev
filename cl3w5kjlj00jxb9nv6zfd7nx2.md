## Clean Code

## What is Clean Code?

Clean Code is set of rules and principles that will help you write code that is easy to read, understand and maintain. 

Here is a list of things you should avoid or improve in your code.

### Bad naming

How often have you seen poorly named variables, functions, and classes? I have seen them quite a lot.

Good naming can make it easier to read code and understand what it does, so you don't need to use comments as much (or at all).

Here is the general rule of thumb on naming variables, methods/functions, and classes.

- 👉 variable: noun, adjective ("user")
- 👉 method/function: verb ("GetUser")
- 👉 class: noun ("User")

You can apply this rule to any programming language. If in doubt, follow language conventions.

### Comments

Some love them; others hate them - they could be helpful or misleading.

Good code doesn't need comments to explain how something works.

You might need comments to explain why you did something or point to something that is not obvious.

### Code repetition

Repeated code is often a mistake of beginners or people on tight deadlines. While some duplication might be okay, you would usually want to have code in a single place, so it's easier to change. Be careful and don't follow this rule blindly!

### Zombie code

There is nothing worse than code that is commented out. Why was it commented out? Should it do something? It will create too many questions and make you wonder about its purpose.

There is also code that is unreachable or not used at all. When in doubt, delete commented or unreachable code. You can find it in source control later.

### Long methods

What makes the method too long? As a general rule of thumb, it's too long if it doesn't fit on the screen. Now, there are screens with high resolution, and one might say - my 100-line method still fits on the screen.

Why are long methods bad?

- It often means that the method is doing too many things at once
- Hard to read and understand
- Harder to test

Often you can split one big method into more, smaller methods that focus on specific things. Long methods often have many arguments in the signature.

### Methods with too many arguments

Some people say that a method shouldn't have more than 3-4 arguments. While I try to be reasonable, too many arguments are a bad sign.

Often it means that method is doing more than it should.

You can group arguments and introduce a new type (class or record). Instead of passing "first name", "last name", "date of birth" and "email", you can create a new Person type with those properties.

### Nested (arrow) code

Not only that it is very hard to read and reason about, but it's also very often bad performing code. It's called arrow code because the indentation often resembles the arrow's tip.

What can you do about it?

- Try to simplify the code
- Use guard clauses and early returns
- In the case of long loop bodies, extract them into the separate method

A nested loop is the worst offender I have seen. Even worse, loop bodies are often very long, so it's hard to read and understand what the code does. While refactoring those long loops, keep in mind tips one and two.

### God classes

Classes that have very low cohesion (to quote Wikipedia: "[...] the degree to which the elements inside a module belong together") try to do too many things at once.

There is only one solution here - split the class up. And don't try to cheat with partial classes here.

## How do we end up with bad code in the first place? 

People don't write bad code because they want to. 
Here are some of the most common reasons:

- ❌ no mentorship
- ❌ no code reviews
- ❌ lack of skills
- ❌ just get it done culture
- ❌ deadlines

Mentoring is very effective, yet time consuming way to improve code quality, especially when it comes to junior developers.

Maybe the company or team don't use code reviews (PRs, pair programming)? Trusting people to write good code is nice, but having more than one pair of the eyes on the code is even better.

Some companies value profits over anything else. Tight deadlines and small budgets might force developers to make some unpopular choices.

Every developer should be a responsible individual that cares about their craft. As a developer, you should:

- ✅ apply engineering principles
- ✅ invest in knowledge
- ✅ not be afraid to ask for help
- ✅ learn from mistakes
- ✅ think critically

It takes time to become good in any craft. The same is true for software development. So, don't worry - I'm sure you can do it as long as you are persistent.
