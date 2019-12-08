---
layout: post
title: "REST API"
date: 2019-12-04 09:35:00 +0900
categories: [CSFundamentals]
---

## REST API

What is REST API? When to use:

1. @PathParam
   `/employees/{emp_id}`
2. @QueryParam
   `/employees?firstname=joe`
   `/departments/123/employees?sort_by=salary`
3. @RequestBody

```
{
"id": student_id,
"name": "student name",
"school_name": "school name"
}
```

- Usually it's a POST, PUT or PATCH http verb with which we will send the requestbody.
- Why it's a bad idea to send requestbody with http GET and DELETE

4. @RequestHeader

```
Request URL: https://blabla.com
Request Method: GET
```

5. @Matrixparam, @CookieParam, etc

## References

[https://stackoverflow.com/questions/48346325/rest-api-when-to-use-pathparam-queryparam-requestbody-and-or-requesthead](https://stackoverflow.com/questions/48346325/rest-api-when-to-use-pathparam-queryparam-requestbody-and-or-requesthead)
