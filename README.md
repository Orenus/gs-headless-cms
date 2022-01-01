The headless CMS arena is flourishing with plethora of solutions, some of are SaaS'ed some are hybrid (cloud + on premise), some are Open Source, some are not even freemium to try-before-you-buy... it lead me to try those 2:

[Stripi](https://strapi.io/) - Open Source, On premise + Cloud.
[GraphCMS](https://graphcms.com/) - Proprietary SaaS

I turned to evaluating ready made solutions from the obvious reasons of not wanting to reinvent the wheel, accelerating my delivery pace and **most of all** - providing a convenient yet a productive way for my system's users (internal and later even external/public) to handle content management;

- Defining a scheme and relationships
- Creating new content items
- Updating drafts and published items
- Visualizing the current items state (draft, published, unpublished and deleted)
- Managing content revisions
- Roles and Permissions
- Automatic Assets sync to cloud storage such as AWS S3 (images and other publishable types)
- Logs and stats
- Webhooks

I discovered that the aforementioned headless CMS solutions, although supporting all of or part of my requirements, lacked the most important aspect of handling content en-mass - convenience and productive publishing.

A simple use case to underline my thesis was, updating blocks of content items (ex. Products, Categories, Tags) instantaneously with as few clicks and then having it published in a sync-safe and visible way.  

I ended up writing my own using a combination of Google Spreadsheet and a simple Node.js server implementation (GraphQL/REST + SQL/NoSQL DB adapter)



![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/exb347hnyws3v9yi1xhh.png)
 
I will soon release it as an Open Source for all to use ( + examples and use cases)

If you wish to be notified, follow **[this repo ](https://github.com/Orenus/gs-headless-cms)**for announcements + instructions + code 
