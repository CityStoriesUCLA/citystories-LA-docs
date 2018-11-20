---
title: "Module 5: Setting up your GitHub repository"
permalink: /docs/mod5/
---

#### Fork the lyrical map site
Now it's time to make your own copy of the repo/site (or "fork" it) so you can add your own content to the map!

##### What's a fork?
> Forking is at the core of social coding at GitHub. - [Forking Projects](https://guides.github.com/activities/forking/)

Creating a *fork* produces your own personal copy of someone else’s code. This allows you to edit your copy and test out your changes before submitting them back to the original code repository. After you test out your changes, you can submit a *Pull Request* to submit your changes up to the original project. We will walk you through the process!

![](../img/github-forking-merging-animation.gif)

* **Essential: Only one person in your group should fork the site**. Start by choosing who in your group should fork the site. The others will be added as collaborators and will be able to work directly on the site that way. 
* While logged in to your GitHub account, visit the `lyricalmap` repository: `https://github.com/CityStoriesUCLA/lyricalmap`
* See the "Fork" button in the top right corner? Click on it. ![](https://www.linode.com/docs/assets/github-fork.png)
* You'll see an animation letting you know that GitHub is copying the site over to your account.
* Once that's done, you should see the `lyricalmap` repository, with all the folders and files, in your own GitHub account. Check the top of the page and make sure it has `[youraccountname] / lyricalmap`.
* Do you see the `_posts` folder from the "[Prepare for Lab session 1](../mod4/)" assignment?

#### Visit your live page
_We want to make sure everything is working correctly, so let's visit your live project page. To do this:_
* Click on "Settings" in the right-hand column. (next to graphs)
![](https://pages.github.com/images/repo-settings@2x.png)
* Scroll down to the box titled "GitHub Pages" and under **Source** choose "**master branch**" from the pull-down menu, then click the **Save** button.
* The page will refresh. Scroll back down to the "GitHub Pages" section. If there is a blue box that says "Your site is ready to be published at:...", refresh the page until the box is green and says "Your site is published at ..."
* The URL there should look something like `http://[githubusername].github.io/lyricalmap`
* Click on the link. You should see your version of _Los Angeles:The City and the Library_ project site. **If you see "Error 404 Site not found", don't panic!** Sometimes GitHub takes a while to build a new GitHub Pages site. Just refresh the page until you see the site. If you have another issue, let us know!

#### Add your teammates as collaborators
Now let's add your teammates as collaborators to your forked site so they can contribute!
* **Essential: Only the one team member that forked the site needs to add collaborators.**
* Back in your GitHub repository (not the live project site), go to "Settings" again.
* In the left navigation, there is a menu item for "Collaborators" - click it. ![](https://help.github.com/assets/images/help/repository/repo-settings-collaborators.png)
* In the text box, enter the GitHub usernames of your teammates, one by one, clicking on the "Add collaborator" button after each one.
* Go ahead and add your instructors as collaborators (using their GitHub usernames). This will come in handy if your instructors need to help you troubleshoot down the road.
* You should now see each of your teammates listed here.
* Your collaborators will receive an email letting them know they can contribute to your new forked repository.
* **Collaborators should log in to their GitHub accounts** and see `lyricalmap` in their list of repositories once they have accepted the invite. Collaborators should get an email, but can also check their [Notifications](https://github.com/notifications) in GitHub.

#### Add your project site link to your GitHub repository
* For easier access, you can add the URL to your published site to the top of your repository page.
* Navigate to the main repository page by clicking on the "Code" tab. Just under the tabs you'll see the URL to the main site here (`http://citystoriesucla.github.io/lyricalmap`). We want to replace it with a link to our own fork.
* Click on "Edit".
* Add the URL from "Settings : GitHub Pages" to the "Website" field. Click "Save".
* Now you can quickly visit your live page from your main repository page!

Once you've completed the steps above, your group should be all set to start your encoding project!
