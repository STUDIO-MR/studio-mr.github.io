# $threadAddMember
Adds a member to a thread.

## Usage
```
$threadAddMember[threadID;userID]
```

### Breakdown
- `threadID` - The ID of the thread channel to add this user to.
- `userID` - The user to add to the thread.

## Example
```
$nomention
$var[thread;$startThread[Cool Thread;$channelID;;60;yes]]
$threadAddMember[$var[thread];$authorID]
$c[Adds the author to the newly created 'Cool Thread']
```
![example1](https://user-images.githubusercontent.com/69215413/130260166-768cb59f-2377-49e3-9588-6425028484d9.png)

![example2](https://user-images.githubusercontent.com/69215413/130260148-0c6b54ec-96ea-4f94-9aee-8a583667d80d.png)