---
name: Check if one user follows another
example: octokit.users.checkFollowingForUser({ username, target_user })
route: GET /users/{username}/following/{target_user}
scope: users
type: API method
---

# Check if one user follows another

```js
octokit.users.checkFollowingForUser({
  username,
  target_user,
});
```

## Parameters

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>username</td><td>yes</td><td>

username parameter

</td></tr>
<tr><td>target_user</td><td>yes</td><td>

target_user parameter

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/users/followers/#check-if-one-user-follows-another).
