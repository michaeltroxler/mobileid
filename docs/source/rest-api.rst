REST API
=====
insert text


.. _Introduction:

Postman
------------

insert text

Getting Started
----------------

insert text. demo documentation below

.. http:get:: /api/v1/resource/<id>

   Retrieve a specific resource by its ID.

   **Example request:**

   .. sourcecode:: http

      GET /api/v1/resource/12345 HTTP/1.1
      Host: api.example.com
      Accept: application/json

   **Example response:**

   .. sourcecode:: http

      HTTP/1.1 200 OK
      Content-Type: application/json

      {
          "id": 12345,
          "name": "Sample Resource",
          "status": "active"
      }

   :param id: The ID of the resource.
   :type id: integer
   :status 200: Resource found and returned.
   :status 404: Resource not found.

