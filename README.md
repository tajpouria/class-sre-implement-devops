# class SRE implements DevOps

DevOps is like an abstract class in programming, and SRE is one possible implementation of that class.

### What’s the difference between DevOps and SRE?

DevOps is a set of practices and cultures that have been designed to break down the barriers between developers, operators, and other parts of the organization.

We can break down DevOps into five key areas:

1. Reduce Organization Silos(By breaking down the barriers across the team increases the collaboration and throughput.)
2. Accept Failure as Normal
3. Implement Gradual Change(Make it easier to review and help by faster rollback on failures.)
4. Leverage Tooling & Automation
5. Measure Everything

In order to clarify the relation between DevOps and SRE, we can say: if DevOps is a philosophy, SRE is prescriptive way of implementing that philosophy and this is how it relates to the mentioned DevOps areas:

1. Reduce Organization Silos: Sharing the ownership of the production across the team, to make sure every body have the same view and approach when are working with the production.
2. Accept Failure as Normal: Making sure the failures don’t happens the exact same way more than once, and accepting the failures by encoding the concept of the error budget which defines how much a system allows to go out of the spec.(SLOs & Blameless Postmortem)
3. Implement Gradual Change: Canary things by rolling them out to small percentage of the fleet before move them out for all users.
4. Leverage Tooling & Automation: Eliminating the manual work by measure how much toil do we have and try automate them gradually.
5. Measure Everything: Measuring the toil the we have as well as the measuring the reliability and health of the system.
