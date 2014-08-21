#git_peer_merge

```
Merging in github can cause issues where responsibility is put on a single individual.
In addition slow maintenance can create a backlog of pull requests that will eventually invalidate each other
```
##Philosophy

```
Peer reviewing gives us transparency, a shared burden of review and a chance for discussion amongst peers.
```

##Example

- A pull request is opened and the contributor writes an opening comment stating the requirement level.

```
#PR Initial comment
PR#41 to fix broken feature and adds new functionality..
  - Alex

REQUIRED_REVIEW_VOTES:3
```

- When a reviewer notices that the pull request has been raised they can leave a vote comment if they are happy with it.

```
#PR Response comment
Hi Alex, Looks good to me
  - John
REVIEW_VOTE_ADD:1 (Developer)
```

- At this point we still require `2` more votes so need to wait for either 1 senior developer or two peer developers.

```
#PR response comment
Alex looks okay, going to merge for you
  - Sam
REVIEW_VOTE_ADD:2 (Senior developer)
```

A suggestion of scoring
```
Repo owner: 3
Senior developer: 2
Developer: 1
```


