## Overview 

[StackOverflow Posts archive data](https://ia800107.us.archive.org/view_archive.php?archive=/27/items/stackexchange/stackoverflow.com-Posts.7z) - downloaded on the 9th of February 2021. 

#### Data schema:
```
- Format: 7zipped
- Files:
  - **posts**.xml
       - Id
       - PostTypeId
          - 1: Question
          - 2: Answer
       - ParentID (only present if PostTypeId is 2)
       - AcceptedAnswerId (only present if PostTypeId is 1)
       - CreationDate
       - Score
       - ViewCount
       - Body
       - OwnerUserId
       - LastEditorUserId
       - LastEditorDisplayName="Jeff Atwood"
       - LastEditDate="2009-03-05T22:28:34.823"
       - LastActivityDate="2009-03-11T12:51:01.480"
       - CommunityOwnedDate="2009-03-11T12:51:01.480"
       - ClosedDate="2009-03-11T12:51:01.480"
       - Title=
       - Tags=
       - AnswerCount
       - CommentCount
       - FavoriteCount
```

Full archive available at: https://archive.org/download/stackexchange


## Initial data pre-processing: 

### Dependencies 

### 1. File handling 
### 3. XML header and tag 
### 4. XML Parsing
### 5. Filtering Criteria

