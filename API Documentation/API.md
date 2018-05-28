**Sample Web API**
----
  Returns JSON data about a single product or all products.

* **URL**

  /api/Product/:id

* **Method:**
  
  `GET`
  
*  **URL Params**

   **Required:**
 
   None

   **Optional:**
 
   `id=[integer]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{ Description : "A blue car", ID : 1, Name : "Blue Car" }`
 
* **Error Response:**

  * **Code:** 404 NOT FOUND <br />
    **Content:** `{ error : "The resource you are looking for has been removed, had its name changed, or is temporarily unavailable." }`

* **Sample Call:**

  `curl https://hapwebapi.azurewebsites.net/api/Product/0`