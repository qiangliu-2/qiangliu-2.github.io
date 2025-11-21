# Link free frii.site domain to GitHub pages
    A step-by-step working guide

For someone unfamiliar with DNS, it took me quite sometime to figure out the details for linking my FREE frii.site domain to my GitHub pages. Therefore, I provide this step-by-step guide so that you can save time.

For easy exposition, I use my own real domain (qiangliu.frii.site) and my GitHub account (github.com/qiangliu-2) and URL (qiangliu-2.github.io). You should replace my domain/account names, qiangliu/qiangliu-2, by your own.

1. Signup [frii.site](https://www.frii.site/).
Go to *Dashboard*, choose CNAME, type **qiangliu** (i.e., my free domain, qiangliu.frii.site) with the value **qiangliu-2.github.io** (i.e., my GitHub URL), and click *Register*

2. Add the frii domain to GitHub.\
Choose *Profile::Settings* of GitHub account **github.com/qiangliu-2**.\
Click *Pages* under *Code, planning, and automation*.\
Click *Add a domain*: type **qiangliu.frii.site**\
Your will see:
- "Create a TXT record in your DNS configuration for the following **hostname**: \
`_github-pages-challenge-qiangliu-2.qiangliu`"
- "Use this code for the **value** of the TXT record: \
`6f5246c1397968b9a7cc704662743b`"

3. Go back to *Your domains* on frii.site:\
Choose TXT and paste the **hostname** from GitHub (Step 2 above), click *Register*\
Paste the TXT **value** from GitHub (Step 2 above).
Now you will see something like this:

![qiangliu.frii](images/qiangliu.frii.png)

4. Wait for up to 24 hours.\
In *Profile::Settings::Pages* on GitHub, click ... on the right end of your domain name and choose *Continue verifying*

5. In GitHub repository **qiangliu-2.github.io**,\
Go to *settings->Pages->Custom domain*: type **qiangliu.frii.site** and save

### For using GitHub as a free web server, [see](ql_md_template.html?my.md=qpedia/github-web-server.md).
