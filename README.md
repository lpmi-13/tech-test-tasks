# Tech Test Tasks (and how we can make them better)

A lot of times, tech tests in interviews tend to focus more on pure logic puzzles than actually authentic tasks that engineers need to able to do in their roles.

## Practical considerations

There are good historical reasons for this:

- It's easy to set up (there are no materials to create, and you only need a prompt)
- You don't need to customize it for different jobs
- It's easy to assess (even if the construct validity is questionable)

Additionally, pedagogical and psychometric concepts are relatively new to computer science in general. The research on this particular area of teaching and assessing computer science concepts is _very_ new (around 10 years old in terms of serious scholarship), and it hasn't fully diffused yet into industry practices.

## Future directions

Given the above, and since we don't really have any good research on what engineers actually _do_ in their jobs, it's difficult to create an assessment framework to actually test competence in authentic tasks (because we don't really know what they are). However, we can make a few guesses (which I'm going to do below), and hopefully these can be validated or refuted in future research.

- SRE/DevOps engineers need to automate tasks that are usually done manually. So this would be things like upgrading servers, provisioning servers, automating cleanup of resources, etc.
- Application developers need to be able to debug, add features, and refactor to reduce complexity.
- Security engineers need to be able to demonstrate/reproduce vulnerabilities and then create a plan to remediate them.

All of these tasks involve more reading of code than writing code, and so the assessments, if they're going to have sufficient construct validity, should incorporate more reading than writing.

## Possible objections

Similar to persisting arguments for learning subjects like Latin, given its relative lack of real-world application, a lot of times things like abstract algorithms are proposed as ways to measure critical thinking and problem solving. Similarly, live coding without any prior context is defended as measuring ability to solve a problem without context under pressure.

Creating customized tasks (see: Thoughtworks open source examples of tech test task frameworks) is very costly, in terms of engineering time, and also requires maintenance. It also would require a different task without a single company to assess competence at different job functions, and even perhaps levels within the same job.


