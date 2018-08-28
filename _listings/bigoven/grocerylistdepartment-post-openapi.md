---
swagger: "2.0"
x-collection-name: BigOven
x-complete: 0
info:
  title: Big Oven Departmentalize a list of strings -- used for ad-hoc grocery list
    item addition
  description: Departmentalize a list of strings -- used for ad-hoc grocery list item
    addition.
  termsOfService: Please see our [terms of service](http://api2.bigoven.com/web/documentation/termsofuse
  version: partner
host: api2.bigoven.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /grocerylist/department:
    post:
      summary: Departmentalize a list of strings -- used for ad-hoc grocery list item
        addition
      description: Departmentalize a list of strings -- used for ad-hoc grocery list
        item addition.
      operationId: GroceryList_Department
      x-api-path-slug: grocerylistdepartment-post
      parameters:
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Grocerylist
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