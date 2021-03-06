---
name: Delete a release
example: octokit.repos.deleteRelease({ owner, repo, release_id })
route: DELETE /repos/{owner}/{repo}/releases/{release_id}
scope: repos
type: API method
---

# Delete a release

Users with push access to the repository can delete a release.

```js
octokit.repos.deleteRelease({
  owner,
  repo,
  release_id,
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
    <tr><td>owner</td><td>yes</td><td>

owner parameter

</td></tr>
<tr><td>repo</td><td>yes</td><td>

repo parameter

</td></tr>
<tr><td>release_id</td><td>yes</td><td>

release_id parameter

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/repos/releases/#delete-a-release).
