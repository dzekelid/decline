---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Add Repositories Username Repo Slug Pullrequests Pull Request  Decline
  description: Post repositories username repo slug pullrequests pull request  decline
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/decline:
    parameters:
      summary: Parameters Repositories Username Repo Slug Pullrequests Pull Request  Decline
      description: Parameters repositories username repo slug pullrequests pull request  decline
      operationId: parametersRepositoriesUsernameRepoSlugPullrequestsPullRequestDecline
      x-api-path-slug: repositoriesusernamerepo-slugpullrequestspull-request-iddecline-parameters
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pullrequests
      - Pull
      - Request
      - ""
      - Decline
    post:
      summary: Add Repositories Username Repo Slug Pullrequests Pull Request  Decline
      description: Post repositories username repo slug pullrequests pull request  decline
      operationId: postRepositoriesUsernameRepoSlugPullrequestsPullRequestDecline
      x-api-path-slug: repositoriesusernamerepo-slugpullrequestspull-request-iddecline-post
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pullrequests
      - Pull
      - Request
      - ""
      - Decline
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---