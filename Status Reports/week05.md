1. Project Members:
    - [Sarthak Jain](https://github.com/sarthakjdev)
    - [Fernando RC](https://github.com/zFernand0)
2. Accomplishments for the week
    - Migrated the diff utility fucntion from the command handler's of Zowe CLI to the Imperative Frameworks.
    - Made changes in the zowe files ds compare command as per the changes in imperative framework. 
    - [Zowe CLI PR#1460](https://github.com/zowe/zowe-cli/pull/1460)
    - [Imperative PR#851](https://github.com/zowe/imperative/pull/851)
3. List of Milestones to be completed
    - To transfer the fucntionaity of getting differnces between two files into [Imperative framework](https://github.com/zowe/imperative) from Zowe-CLI to reduce the burden on command handler for generating the html and opening up of diffs into browser. 
    - To modify the code in this [Pull Request](https://github.com/zowe/zowe-cli/pull/1460) , where we will reducing the code burden from command handlers, and wil be calling the functions from the imperative instad of having logic in command handlers. 
4. List of issues, problems, or concern(s)
    - Problem : 
        1. Facing issues in writing test cases, for newly written classes in the imperative framework.
    - Concern : ---