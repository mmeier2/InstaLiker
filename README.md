InstaLiker
========
This is a command line tool that allows you to like user content based on either hashtags or users you are following

###Like based on hashtags
``` bash
python insta_client.py tags <hash_tags>
```

If given the optional parameter, it will search and like based on the hashtags. Otherwise it will like based on the list of hashtags defined in constants.py


###Like based on popular users you follow
``` bash
python insta_client.py followers
```

This will search the followers of the popular users you follow and like the users that follow them 
