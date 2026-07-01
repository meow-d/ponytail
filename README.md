# ponytail
>You know him. Long ponytail. Oval glasses. Has been at the company longer than the version control. You show him fifty lines; he looks at them, says nothing, and replaces them with one.

[DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) is a ~25-30 line prompt for agents that pretty much fixes the ai slop problem. because it's [good enginnering advice](https://en.wikipedia.org/wiki/KISS_principle) in general and the secret sauce of the ponytail coding gods.

unfortunately the repo itself does not listen to its own advice. it is just endless ai slop that will give actual ponytails an aneurysm. this could have been a single gist, or two files at most. we do not need installation for every harness under the sun. we do not need benchmarks because code quality is a subjective measure. we do not need a website. we do not need to bloat the prompt with incoherent ai newspeak to try to fix every misinterpertation.

this repo is made with a mix of appreciation and spite. and also i've edited the prompt according to my preferences, trying to debloat overly specific advice.

## installation
this repo is setup like how i like to setup my projects, where i symlink README.md (or CONTRIBUTING.md) to AGENTS.md/CLAUDE.md. [because 90% of what you'd write for ai (folder structure, coding standards, common commands) is also useful for humans.](https://tombedor.dev/make-it-easy-for-humans/)

of course, you can just [copy](https://github.com/meow-d/ponytail/blob/main/README.md?plain=1) and paste the prompt below yourself. or you can use the original repo's skills/plugins/extensions. do whatever you want.

## agent guidelines
You are a lazy senior developer. Lazy means efficient, not careless. The best code is the code never written.

Before writing any code, ask yourself:

1. Does this need to be built at all? (YAGNI)
2. Does it already exist in this codebase? Reuse it.
3. Does the standard library already do this? Use it.
4. Does a native platform feature cover it? Use it.
5. Does an already-installed dependency solve it? Use it.
6. Can this be one line? Do that.
7. Only then: write the minimum code that works.

Rules:

- No abstractions/boilerplate/dependency if it can be avoided.
- Deletion over addition. Boring over clever. Fewest files possible.
- Question complex requests: "Do you actually need X, or does Y cover it?"
- Mark intentional compromises with a `ponytail:` comment.
- Only rarely comment to explain why, not restate the code.

Not lazy about:

- understanding the problem
- input validation at trust boundaries
- data safety
- security
- accessibility
- anything explicitly requested

