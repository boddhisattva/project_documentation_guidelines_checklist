# Project documentation guidelines checklist


**What are these guidelines**: A set of guidelines/checklist that could potentially help one make a better README/Getting Started guide for a new/existing project so that the people who were not previously involved in the project in anyway can get up and running with the project in no time.

1. **Help the reader identify the project**
- Project's name at the very top of the README. If multiple projects are part of one README and repository, consider linking them at the very top so that a new reader to the project knows that the README talks about multiple projects without them having to realise this only by scrolling down further in the README.
- Add a URL(like a homepage URL) for the project if applicable and available(in case of multiple projects - add the URL at each appropriate sections in the README which talks about each project).

2. **Identify the readers/users of this project document**

- **Who are my users?**: Kindly consider kick starting things by first asking who are going to be the potential users (freshers, intermediate level knowledge or more experienced people or could be all of the three types of readers as well who could be looking at this project over a period of time! :)) of this project and in case if the project can be used by people with varied levels of experience, do consider that the choice of words used in each section cater to people who may or may not have any experience/idea of things you are planning to touch upon as part of this document, thereby if additional context/reference links have to be provided, please do consider adding that wherever applicable so that those who may be unfamiliar with certain terms due to lack of prior experience can read more about the relevant context through those additionally provided links. A few guidelines around identifying your project users include:
    - The important thing to remember is that **you** **do** **choose** and thereby your right choice here can go a long way where **people could even appreciate the effort you've put in** to ensuring that the document is catering to people from 0 to x years of experience in the related field of work that the document touches upon.
    - The decision you make here changes what you decide to include, how you decide to explain things. And the wider you go, the more accessible and inclusive your work is. You can’t teach every possible thing, and that’s okay. It is up to you! But the important thing is to be **aware** who can understand what you’re writing. As you’re writing things, you can check your assumptions, you can think about what someone would need to understand beforehand. And the more things there are, the more helpful the document can be to those who may not have any prior background/knowledge on the things you're planning to touch upon as part of this document.
    - Lastly, another thing worth keeping in mind **it's** **finally your call** to include the information that’s relevant, and leaving out the bits that aren’t. **People are going to trust your judgement** and the various decisions that you make around this - **your making it count will definitely be appreciated by future readers of your work :)**

3. **Help the reader evaluate the project**

- Describe the project in terms of what the project does or achieves, not what it's made out of. **Focus on why not what.**
    - Here you can touch upon questions like -
        - 'Why should someone use your add-on/library'?
        - 'What are they trying to do with this?'
    - Potential ways one can write this section of the documentation:
        - `With <PROJECT NAME> you can <VERB> <PLURAL NOUN>…`
        - `<PROJECT NAME> helps you _____…`
        - `If you use <PROJECT NAME> then you _____…`
        - `You'll like <PROJECT NAME> because you can _____…`
        - `<PROJECT NAME> is better than <ALTERNATIVE PROJECT> because you can _____…`
        - `<PROJECT NAME> is related to <OTHER PROJECT> because _____…`

    Coming up with a `why` could be the hardest part of writing a `README`, if any of the above ways aren't helpful, you could find some other relevant tips [here](https://github.com/ddbeck/readme-checklist/blob/master/checklist.md#help-the-reader-evaluate-the-project)

4. **Help the reader use/set up the project**

- This section touches upon the question - 'What information do they need to do it?'
- Here one can list the project's prerequisites.
- List the steps to install and use the project one time.
- A good thing to additionally consider doing: Test your install and setup steps to be sure what you've written already works.

**Side note:** No matter how your project runs, however, stop once the project works once. Extended usage instructions belong in dedicated documentation files, not your README.

5. **Help the reader engage with the project**

- In short this section touches upon the question - what the users are trying to do with this?
    - The thing that a user tries to do with a project can be termed as **user's tasks**
    - **Why user's tasks?**
        - A lot of documentation that isn’t very usable is so for totally understandable reasons: people proud of what they’ve built and want to talk about it. But for end-user docs, the design and implementation usually may not be relevant to actually using the thing.
        - Thinking from someone else’s perspective is hard. Especially if you’re the person building the thing, your mind is at the place about the implementation and design. So user tasks are one of the ways you’re going to get out of your head, and focus on someone else’s goals.
    - These user tasks can be basically categorised into 3 types - Discovery, trying it out for the first time & day-to-day usage
    - For each of these user tasks the information that can go into each of these tasks can be potentially modelled around a concept called WIFT which stands for 'What's in it for them' by asking 3 q's below:
        - Why should someone read this?
        - Why should they care?
        - What will it do for them?

- Some potential ideas that can be worth exploring that could give a better idea of what can possibly go into this section include
    - A high level architecture overview diagram to understand how the different components connect with each other as part of the application
- Tell your audience where to go for more project documentation.

    Describe any additional documentation and where to find it.

    This may include your project's:

    - Website
    - Documentation files like links to API docs etc.,
    - Man Page
    - Helpful/Handy command(s)
    - Sharing Additional context of 1 to 1 discussions that happen through email or other forms with regard to the project in relevant places like PRs or even wiki pages that are accessible for all team members of the organisation for one to get additional context
    - Main software related business domain specific information & it's connection with another project that it is integrated with(if any)
- Tell your audience where to go for help.
    - This may include descriptions and links to mailing lists, issue trackers, forums, email addresses, or other support avenues (like Stack Overflow tags).

6. **Final checks:**

**Good practices for writing a README in general**

- Always write for readability: **be clear and concise**
- **Writing for readability: edit yourself. This is similar to refactoring code over a period of time** when you revisit a README, you'll potentially find things you can update in the same to make the contents more precise and simple.

**Good practices over a period of time as one's README evolves**

- If your **README is long, add a table of contents** after your project description.
- If your **README is very long, move content to other documents** wherever you potentially could.
- **Set a reminder to review your README and this checklist in a few weeks in the due course of your building the new project** instead of having to do all of this at once - so that new things are added as and when there's more work done with regard to the project.
