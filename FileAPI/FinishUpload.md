# Finish Upload

This is to finish an upload to a file

!> I was facing some problems testing the File API, so it is best not to use it

## Request Method 
PUT

## Endpoint
https://api.vrchat.cloud/api/1/file/:id/:version/:type/finish

id - the id of the file
version - the version of the file
type - the file type

### File Types

    - file
    - delta 
    - signature

## Requires Authentication
Yes

## Returns

