---
name: List comments
example: octokit.teams.listDiscussionCommentsInOrg({ org, team_slug, discussion_number })
route: GET /orgs/{org}/teams/{team_slug}/discussions/{discussion_number}/comments
scope: teams
type: API method
---

# List comments

List all comments on a team discussion. OAuth access tokens require the `read:discussion` [scope](https://developer.github.com/apps/building-oauth-apps/understanding-scopes-for-oauth-apps/).

**Note:** You can also specify a team by `org_id` and `team_id` using the route `GET /organizations/:org_id/team/:team_id/discussions/:discussion_number/comments`.

```js
octokit.teams.listDiscussionCommentsInOrg({
  org,
  team_slug,
  discussion_number,
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
    <tr><td>org</td><td>yes</td><td>

org parameter

</td></tr>
<tr><td>team_slug</td><td>yes</td><td>

team_slug parameter

</td></tr>
<tr><td>discussion_number</td><td>yes</td><td>

discussion_number parameter

</td></tr>
<tr><td>direction</td><td>no</td><td>

Sorts the discussion comments by the date they were created. To return the oldest comments first, set to `asc`. Can be one of `asc` or `desc`.

</td></tr>
<tr><td>per_page</td><td>no</td><td>

Results per page (max 100)

</td></tr>
<tr><td>page</td><td>no</td><td>

Page number of the results to fetch.

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/teams/discussion_comments/#list-comments).
