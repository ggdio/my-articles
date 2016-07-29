**Host your static website on Github for free**

Github( [https://github.com](https://github.com/)) is a great social coding platform, based on git-scm, with a clean and fluid interface and a lot of useful features for those who need a cloud based source versioning.

Not everyone knows, but one of its great features is the possibility of hosting your own static web page with all your static resources (css, js, img, html, ...). For this, you will need at least one free account, which you can create by following this [link](https://github.com/join?source=linkedin_pulse).

Github provides two ways of hosting a page:

**Dedicated Repository**

By following this approach, you will create a main web-page for your profile, which you be accessible through an URL like the following(&#39;username&#39; is your github user):

[_https://username.github.io_](https://username.github.io/)

**Create repository and upload files:**

- Create a repository(repositories &gt; new) with a name like above(username.github.io). For instance, if your github user is _developer_, then the repository name must be _developer.github.io_;
- After creating your repository, you must upload your webpage files, for this either you clone the repository on your local machine, either you upload the files directly to github by clicking on &quot;Upload files&quot; on repository main page:
- Now that you have successfully uploaded your webpage files to your recent created repository, you can access your _github.io_ url like we saw above(_username.github.io_).

**Custom Domain:**

If you already have a registered domain name, then you can link it&#39;s DNS to github.io server.

- Access your &#39;username.github.io&#39; repository.
- Create a file on branch MASTER called &#39;CNAME&#39;, on upper case, without any extension.
- The file must contain one single line with the name of your domain, eg.:

_mydomain.com_

- Wait for a few minutes until the DNS resolves on your internet provider, then you can access the hosted resources trough your own domain.

**Dedicated Branch**

Github permits you to host unlimited pages even after creating a dedicated repository, and you can achieve it by dedicating a branch of any repository for this purpose:

- Create a new repository with a name of your desire.
- On that repository, create a new branch called &#39;gh-pages&#39;.
- Checkout to the recent created branch, and add your webpage files, then commit and push it.
- Now you can access your branch webpage on:
- [_https://username.github.io/repository-name_](https://username.github.io/repository-name)

OBS: **username** is your github user / **repository-name** is your recent created repository name

...By the way, if you want to access your &#39;gh-pages&#39; branch through your own domain name, you can simply do the same I&#39;ve described above, by creating a CNAME file.

...That&#39;s all, I hope it was useful for you !

~Dio.