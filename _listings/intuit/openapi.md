---
swagger: "2.0"
x-collection-name: Intuit
x-complete: 1
info:
  title: QuickBooks Online V3 API
  description: the-quickbooks-online-accounting-api-is-a-restful-api-that-is-used-to-access-quickbooks-companies-docs-
  version: 1.0.0
host: DefaultParameterValue
basePath: /v3/company/DefaultParameterValue
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /department:
    post:
      summary: Post Department
      description: |-
        Create a department object
        Method : POST
      operationId: postDepartment
      x-api-path-slug: department-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Department
  /reports/DepartmentSales:
    get:
      summary: Get Reports Department Sales
      description: |-
        Report - Department Sales
        Method : GET
      operationId: getReportsDepartmentsales
      x-api-path-slug: reportsdepartmentsales-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Reports
      - Department
      - Sales
  /department/1:
    get:
      summary: Get Department
      description: |-
        Read a department object
        Method : GET
      operationId: getDepartment1
      x-api-path-slug: department1-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Department
---