swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/quizzes/quiz_id/extensions:
    post:
      summary: Set extensions for student quiz submissions
      description: Set extensions for student quiz submissions.
      operationId: set-extensions-for-student-quiz-submissions
      x-api-path-slug: coursescourse-idquizzesquiz-idextensions-post
      parameters:
      - in: query
        name: extend_from_end_at
        description: The number of minutes to extend the quiz beyond the quiz&#39;s
          currentnending time
      - in: query
        name: extend_from_now
        description: The number of minutes to extend the quiz from the current time
      - in: query
        name: extra_attempts
        description: Number of times the student is allowed to re-take the quiz over
          thenmultiple-attempt limit
      - in: query
        name: extra_time
        description: The number of extra minutes to allow for all attempts
      - in: query
        name: manually_unlocked
        description: Allow the student to take the quiz even if it&#39;s locked for
          everyonenelse
      - in: query
        name: user_id
        description: The ID of the user we want to add quiz extensions for
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Quizzes
      - Quiz
      - Id
      - Extensions
  /courses/{course_id}/quiz_extensions:
    post:
      summary: Set extensions for student quiz submissions
      description: Set extensions for student quiz submissions.
      operationId: set-extensions-for-student-quiz-submissions
      x-api-path-slug: coursescourse-idquiz-extensions-post
      parameters:
      - in: query
        name: extend_from_end_at
        description: The number of minutes to extend the quiz beyond the quiz&#39;s
          currentnending time
      - in: query
        name: extend_from_now
        description: The number of minutes to extend the quiz from the current time
      - in: query
        name: extra_attempts
        description: Number of times the student is allowed to re-take the quiz over
          thenmultiple-attempt limit
      - in: query
        name: extra_time
        description: The number of extra minutes to allow for all attempts
      - in: query
        name: manually_unlocked
        description: Allow the student to take the quiz even if it&#39;s locked for
          everyonenelse
      - in: query
        name: user_id
        description: The ID of the user we want to add quiz extensions for
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Quiz
      - Extensions