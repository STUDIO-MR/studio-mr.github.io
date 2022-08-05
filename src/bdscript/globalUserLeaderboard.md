# $globalUserLeaderboard
Returns the top ten user's username and value for the given global-user variable.

## Usage
```
$globalUserLeaderboard[variableName;sortType (asc/desc)]
```

### Breakdown
- `variableName` - The variable to create the leaderboard for.
- `sortType` - Whether to sort the leaderboard in ascending (`asc`) or descending (`desc`) order.

> 🧙‍♂️ `$globalUserLeaderboard` automatically generates a description. So, `$description` should not be used in the code.

## Example
```
$nomention
$globalUserLeaderboard[Money;asc]
```
