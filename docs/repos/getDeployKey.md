---
name: Get a deploy key
example: octokit.repos.getDeployKey({ owner, repo, key_id })
route: GET /repos/{owner}/{repo}/keys/{key_id}
scope: repos
type: API method
---

# Get a deploy key

```js
octokit.repos.getDeployKey({
  owner,
  repo,
  key_id,
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
<tr><td>key_id</td><td>yes</td><td>

key_id parameter

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/repos/keys/#get-a-deploy-key).
