#git_peer_merge

```
Merging in github is best done by a consensus of peers.
  - Greater visibility
  - Less individual burden
  - All peers get a chance to sway the vote
  - Faster review times
```

##Process

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
LGTM:1 (Developer)  `We see that a developer here has cast his 1 vote`
```

- At this point we still require `2` more votes so need to wait for either 1 senior developer or two peer developers.

```
#PR response comment
Alex looks okay, going to merge for you
  - Sam
LGTM:2 (Senior developer)
```
- Merge is now ready to be completed by whoever reviews the score total first.
###scoring
```
Repo owner: 3
Senior developer: 2
Developer: 1
```


