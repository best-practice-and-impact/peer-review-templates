## Description
<details><summary>Please include a summary of the changes</summary>

  - What is this change?
  - What does it fix?
  - Is this a bug fix or a feature and does it break any existing functionality?
  - How has it been tested?
</details>
 
*This pr introduces....*
## Type of review

*You can delete options that are not relevant.*

- [ ] Bug fix - *non-breaking change*
- [ ] New feature - *non-breaking change*
- [ ] Breaking change - *backwards incompatible change, changes expected behaviour*
- [ ] Non-user facing change, structural change, dev functionality, docs ...
- [ ] Complete code review (first time)

## Checklist:

- [ ] I have performed a self-review of my own code
- [ ]  I have commented my code appropriately, focusing on explaining my design decisions (explain why, not how)
- [ ] I have made corresponding changes to the documentation (comments, docstring, etc.. )
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] I have updated the change log
- [ ] I have checked the pipeline runs with test data

<br>

# {{ date of review yyyy-mm-dd }} - {{ product title }} peer review

{{ name of reviewer }}

## Scope of review

{{ delete as appropriate 

- [ ] Code review
- [ ] Documentation review
- [ ] Test / Quality review
- [ ] Working practices of team
- [ ] Validity of method to question
- [ ] Verification of methods }}

Give details about what you have been asked to review.

## General comments

Consider the following questions:
- has the product been reviewed before? If so, what changes have been made since the last review?

## Detailed comments

### Code review

- Does code run without errors?
- How does the product manage dependencies on software and data?
- How is the product tested?
- Are function documentated correctly and clearly?
- Are code comments used correctly?
- Naming conventions follow pep8?
- Can code be easily followed? If you had to make a change now could you? If not why?
- Is there repetition which can be generalised?

### Documentation review

- Can you run code with current documentation without support?
- Does README follow best practice?
- are there accompanying documentation around method and use of method?
- Is it easy to find out why decisions have been made?
- Does the product have an assumptions log, a data register, a list of roles and responsibilities?

### Test / Quality review
- Are there any unit tests and do they pass?
- If no unit tests: How is the product tested?
- Is [quality assurance](https://best-practice-and-impact.github.io/qa-of-code-guidance/checklists.html) appropriate to complexity and risk of analysis / code

### Working practices of team

- Is the product version controlled?
- Are the team appropriately skilled given the complexity of the work?
- Do team members have a good understanding of the limitations of the inputs, methods and 
- Is there pressure on the team to deliver to timelines at the expense of accuracy, quality or calculation/communication of uncertainty?
- Do managers of the product allow for open and transparent discussions of concerns and risks, escalated when appropriate?

## The next two apply for methodology and method reviews

### Validity of method

- Is there evidence of user need for this output?
- Is there evidence of user research regarding the approach taken to create this output?
- What alternative methods were considered and why were they rejected?
- What techniques have other people used to measure a similar output?

### Verification of methods

- How easy was the product to reproduce by you? Was there enough documentation to do so?

### Things to consider
Suggestions should be tailored to the code that you are reviewing. Provide context.
Be critical and clear, but not mean. Ask questions and set actions.
<details><summary>These might include:</summary>

- bugs that need fixing (does it work as expected? and does it work with other code
  that it is likely to interact with?)
- alternative methods (could it be written more efficiently or with more clarity?)
- documentation improvements (does the documentation reflect how the code actually works?)
- additional tests that should be implemented
  - Do the tests effectively assure that it
  works correctly? Are there additional edge cases/ negative tests to be considered?
- code style improvements (could the code be written more clearly?)
</details>
<br>

*Further reading: [code review best practices](https://best-practice-and-impact.github.io/qa-of-code-guidance/peer_review.html)*

