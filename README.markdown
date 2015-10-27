## Ecstatic Labs Blog

The ecstatic labs platofrm is powered by Octopress 3.0.

Note: Octopress 3.0 is in development at https://github.com/octopress/octopress

## Add a new post

Make sure you are on the source branch.  The Github setup for octopress uses the source branch for 

    bundle exec rake new_post

You can find your new post in source/_posts

## View Locally

To view your changes locally...

    bundle exec rake preview
      
## Live Deploy

To push changes into the live blog...

    bundle exec rake deploy
    
This will generate your blog, copy the generated files into _deploy/, add them to git, commit and push them up to the master branch. 
Github will serve up the master branch for site visitors automatically. 
    

    
