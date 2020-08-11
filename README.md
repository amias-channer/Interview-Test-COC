# Interview-Test-COC   (WIP)

[TOC]

## About 

### Introduction

This document is an attempt at a public specification of a Code of Conduct for interview technical tests.  The idea is to provide a community reference point for what is acceptable conduct for an interview technical test. This document aims to satisfy the potentially conflicting goals of technical tests. In the interests of brevity we will focus just on the tests not the wider interview process. For the same reasons this isn't the place to dwell on the politics of structural racism but in the interests of accuracy this document will acknowledge that it exists and that we all have a duty to avoid it.

### What is a Technical Test ?

Any coding exercise undertaken for the purposes of candidate evaluation for a job interview.

### Why do we need a COC ?

Lots of companies apply technical tests for job interviews, these tests can vary in quality massively and often have unwanted side effects. There is a lot of debate around the efficacy of these tests and whether they are fair or accurate, this is an attempt to normalise them to a positive community led standard we can build apon.

### Contribution

This document is an open source effort started by Amias Channer , contributions are welcome in the following forms:

pull requests :  https://github.com/amias-channer/Interview-Test-COC 
raising issues:  https://github.com/amias-channer/Interview-Test-COC/issues.  

If there is interest i will gladly build this into community project with appropriate shared governance. 





## Resources 

This section will outline what is expected for technical test and provide some sensible basic standards.

### Documents

To ensure each candidate has a fair chance of doing this on general computer, don't use word documents when text , markup or PDF is more accessible and takes less load to to display.

#### Specification

Try to make the specification follow the guidelines you would use for setting a task in your workflow, making it cryptic is rarely testing a skill that is used professionally. Try to make it self contained and ensure its tested on an non company computer before sending it out. Try it out on someone in your company at the level you are recruiting for.

#### Credentials

Ensure that any credentials required are supplied to the candidate.  Make sure they have specifically tailored access which is shutdown after the test.
Don't expect candidates to use their own resources.

### Servers

Obviously do not give access to production environments but do ensure the environments you provide are up to the task an dsimilar to production 
If you are worried that this exposes your security then your system design is probably not secure enough to start with.

### APIs

Provide candidates with approriate API keys if they are required , this is usefull for you beacuse you can watch someone learn your API and you can shut a user down quickly if they are causing damage.  

### Libraries

Unless the test specifically requires the selection of appropriate libraries then they should be provided installed and tested in the test environment.

### VMs

Don't rely on candidates to be able to host VM's , most developers are activiely discouraged from doing this in the workplace and it cuts off a lot of people who don't have powerfull hardware. Lighterweight containers such as Docker are a much better option here but be carefull you aren't testing a candidates wealth rather than skill. 

## Guidelines

### Duration

Its unfair to expect candidates to do hours of work for technical test, while some might have free time to spare others with families, disabilities or financial issues will not so they will not continue or apply.

Expecting candidates to push themselves overly hard like this will not necessarily get you balanced reliable employees.

If you do agile you should consider choosing a task that fits in your planning unit size, if you only allow tasks to be greater than 1hr and less than 4hrs long then you shouldn't be giving tests that take 8hrs.

### Complexity

Be sure to set challenges that are of appropriate complexity for the level of work candidate would be doing if they got the job. We have a a lot of ego probrlems in programming and this leads to unhealthy gate keeping. Accept that maybe you and your company aren't the be all and end all of computing but that you can provide meaningfull jobs for the majority of programmers who aren't the rockstar 1%. 

Get your lead dev to design the test but make sure you that it can be completed by someone at the same level, this is a good opportunity for pair programming. 


## Deliverables

### Background

Candidates should be able to expect their work to have to reasonable consideration before expending  effort on unpaid work. Employers must ensure they inform the candidate how many other people are doing the test and how the project will be assessed. 

### Code

Code should confirm to the functional and code sytle specifications

### Repository

Code must allways be delivered in a repository, part of the test is using version control because its essential to modern programming.

### Ownership

Any code or artefacts created during the test remain the property of the candidate, this should be enforced by the use of a GPL3 licence. This ensures the company cant use this process to get free dev time. 

## Response

If you set these tests you absolutely have an obligation to respond to everyone who takes the time to submit them as basic courtesy. 

You should inform candidates of any delays or changes to your planned response, they may have multiple applications they need to decide between.


