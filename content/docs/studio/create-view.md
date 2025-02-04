# Create a View

You can create views from your Git repositories, just like the `Demo` view you
saw in the last section. To create a new view, follow these steps.

1. Sign in to your [DVC Studio](https://studio.iterative.ai/) dashboard using
   GitHub, GitLab or Bitbucket.

2. Click on `Add a View`. All the organizations that you have access to will be
   listed.

> To create views from your GitHub repositories, you must install the DVC Studio
> GitHub app. Refer to the section on
> [GitHub app installation](#dvc-studio-github-app-installation) for more
> details.

3. Open the organization whose repository you want to connect to. You can also
   use the search bar to directly look for a repository.

   ![](https://static.iterative.ai/img/studio/select_repo_v2.png)

4. Specify additional connection settings if required.

   ![](https://static.iterative.ai/img/studio/view_settings_v2.png)

> In most scenarios, you can skip these additional view settings. Refer to the
> [View Settings](/doc/studio/view-settings) section for more details.

You should now see that a view has been added in your dashboard.

If your project requires any of the advanced settings, then remember to
configure them by opening the view settings. Otherwise, your view may not work
as expected. To go to view settings, click on the
![](https://static.iterative.ai/img/studio/view_open_settings_icon_v2.png) icon
in the view. In the menu that opens up, click on `Settings`.

![](https://static.iterative.ai/img/studio/view_open_settings_v2.png)

## Share a view

You can share your views on the web. Simply click on the button labelled
`Private` next to the name of the view. In the menu that pops up, turn on
`Share to Web`.

![](https://static.iterative.ai/img/studio/view_share_v2.png)

You can change a shared (public) view and make it private by turning off
`Share to web`.

## DVC Studio GitHub app installation

If you are using a GitHub account, you will have to install the DVC Studio
GitHub app on the GitHub repositories/organizations that you want to use with
DVC Studio. When you try to create a view, if the app is not already installed,
DVC Studio will not be able to fetch the list of your GitHub repositories. In
this case, you will be prompted to configure Git integrations as shown below.

![](https://static.iterative.ai/img/studio/configure_git_integrations.png)

Click on the link to `Configure Git integrations settings`. This will open the
`Git integrations` section of your profile page.

![](https://static.iterative.ai/img/studio/configure_github.png)

Click on the `Configure` button, and you will be redirected to the GitHub page
to install and authorize the DVC Studio GitHub app.

> Note that you do not have to authorize DVC Studio on all the repositories in
> your GitHub organization. You can limit access to only repositories that you
> want to use with DVC Studio.
