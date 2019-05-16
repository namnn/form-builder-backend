```
+) Technical cover:
    * Typescript + NestJs + Mongoose
    * MongoDB

+) Feature cover:
    * data module: provides 2 endpoints:
        - Post `api/data/submit` to create a form content as a submission.
        - Get `api/data` to retrieve current submissions from database.
    * schema module: provides 3 endpoints:
        - Post `api/schema` to save (update/create) a form schema.
        - Get `api/schema` to retrieve current form schemas from database.
        - Delete `api/schema/:formId` to delete an existing form schema from database.
```