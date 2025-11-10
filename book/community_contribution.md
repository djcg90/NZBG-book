# Contributing

This resource is a collaboratively developed reference text. It relies on the contributions from experts and practitioners across the UK bridge industry. We all recognise the need for rapid and pervasive change in attitudes and practice, and this development model has been selected to reflect this.

## What sort of contributions are welcome

The NZBG has set out what it believes is a comprehensive and structured wishlist of resources and guidance that are desperately needed to support bridge engineers in a net-zero age. The most impactful step for any contributor is to select one of these needs and to propose a draft response.

In addition we welcome constructive comments, suggestions, edits and supplements to the material released to date. These contributions can be large or small. 
- Major challenges or rewrites will be accepted gratefully and debated.
- We also value simple feedback, formatting improvements or clarifications, that incrementally improve the quality of this reference text.

## How to contribute

This is published firstly as an Executable Book. There are few aspects to understand before contributing. 

1. The contents are written as a combination of Markdown files (simple text files, with limited formatting), and Jupyter Notebooks (a file format that integrates code and its output into a single document that combines visualizations, narrative text, mathematical equations, and other rich media).
2. The contents are compiled directly into static html pages that you are viewing on this website. They can also be compiled via LateX into a typeset pdf text book.
3. The source files (the Markdown files and Jupyter notebooks) are hosted on our public [Github repository](https://github.com/djcg90/NZBG-book). Here you can view the latest raw files, and also see any ongoing development work going on. Contributors should interact with this repository directly, as this is where the community development actually happens.

### Comments
If you simply want to raise a comment about something in the book the way to do this is through an [Issue](https://github.com/djcg90/NZBG-book/issues) in the Github repository. 
1. Check if a similar issue already exists. If it does then read the existing comments, and if you still have something to offer then add this to the thread. Avoid creating duplicate issues wherever possible.
2. If you have a new comment then a  template "issue" is provided which you should use to make sure you provide some basic information that helps with actioning the comment, and tag the exact location in the content files that you would like to address.
3. If you prefer to interact with the pdf text book we still want your input. Please raise a new issue, summarise your comments at the top of the issue with clear reference to relevant heading numbers. Then attach a marked up copy or scan of the textbook containing your comments.

### Adding or editing content
If you want to suggest and then make specific changes to the content then you are encouraged to do so directly. 

>This is the most effective and productive contribution you can make. 

However you will need to become familiar with the version control workflow on github to do so ["todo reference"].

**Setup**

First you need to clone a local copy of the repository, and activate the environment in .venv.

Then you need to create a new location for your updated content, which you and the NZBG curation team can collaborate on until its ready to be incorporated into the "main branch". You also need to make others aware of what you are doing so we don't duplicate effort.

1. Check the Github repository for existing Pull Requests from the development branch, open issues, and any active working branches, to see if someone is already working on the same item.
2. If not then create a new branch from the development branch, and immediately create a new "WIP" Pull Request (PR) from your new branch back into development. Write a summary in the WIP PR that briefly explains what you are hoping to do.
3. Sync you local repository with the Github remote
Now you're ready to develop locally. Make sure you periodically pull new changes from "develop" to your branch so you stay in sync.

**Develop content**

Add your proposed changes on your new branch. Make sure you build the book locally and add appropriate unit tests before moving to the next step. Consider the following guidelines:
1. The content needs to be reliable and robust. Make sure you're happy with it, and any recommendations are realistic. If its only applicable in niche circumstances make sure this is highlighted and consider where it might be best presented.
2. The content should be readable. Take time to write in an engaging and clear manner. Provide images, figures, and interactive code with worked examples.
3. Push your work regularly to the Github repository so that others can see how you're getting on, and potentially help out.
4. Ensure commit messages are useful and descriptive.

If you need help then reach out to the NZBG curators through Github.

**Check and release**

Once you're ready you need to communicate this to the NZBG team and the additions need to go through a check process.

1. Push your working code Github and remove the "WIP" from your PR name
2. The PR then needs to be checked. It will require an NZBG curator to approve it before the new content can actually be merged into the develop branch. They will review the changes and will either wave it through if its trivial, run further checks if needed to ensure the book still operates as it should, or if the content is technical they will assign additional reviewers. The technical review should be carried out and recorded within the PR.
3. Once the review is complete and tests are passing, then the NZBG curator will merge the content into the develop branch. 
4. At regular intervals, all the updates made to develop are then pulled into "main" and a new version of the book is released.

## Acknowledgements
The NZBG team will seek to acknowledge contributions appropriately, while remaining an impartial and independently branded organisation.

We understand that for individuals this can be a useful way to demonstrate CPD, and for organisations it helps reinforce their commitment to net-zero design. As such all contributions will be transparently recorded within the pages of the book.

