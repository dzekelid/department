---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get a contact department
  description: Gets a contact department. The ID of the department must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounts/contacts/departments:
    post:
      summary: Create a contact department
      description: Create a contact department.
      operationId: postRestAccountsContactsDepartments
      x-api-path-slug: restaccountscontactsdepartments-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/departments
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
  /rest/accounts/contacts/departments/{departmentId}:
    delete:
      summary: Delete a contact department
      description: Deletes a contact department. The ID of the department must be
        specified.
      operationId: deleteRestAccountsContactsDepartmentsDepartment
      x-api-path-slug: restaccountscontactsdepartmentsdepartmentid-delete
      parameters:
      - in: path
        name: departmentId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
    get:
      summary: Get a contact department
      description: Gets a contact department. The ID of the department must be specified.
      operationId: getRestAccountsContactsDepartmentsDepartment
      x-api-path-slug: restaccountscontactsdepartmentsdepartmentid-get
      parameters:
      - in: path
        name: departmentId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
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