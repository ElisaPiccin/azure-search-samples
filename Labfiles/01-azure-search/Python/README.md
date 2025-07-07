# Margie's Travel Demo Instructions

Follow these steps to test the application in a demo environment:

1. **Start the Application**
   - Launch the app. When it starts successfully, a message will display a link to the running web application (e.g., [http://localhost:5000/](http://localhost:5000/) or [http://127.0.0.1:5000/](http://127.0.0.1:5000/)).
   - Click the link to open the Margie's Travel site in your web browser.

2. **Perform a Search**
   - In the Margie's Travel website, enter `London hotel` into the search box and click **Search**.
   - Review the search results. Results include:
     - The file name (with a hyperlink to the file URL)
     - An extract of the file content with the search terms (e.g., *London* and *hotel*) emphasized
     - Other attributes from the index fields

3. **Refine the Results**
   - The results page includes UI elements to refine your search:
     - **Facet Filter:** Filter based on the `metadata_author` field. This demonstrates how facetable fields return a list of discrete values for filtering.
     - **Sort Order:** Order results by a specified field and sort direction (ascending or descending). The default is by relevancy, calculated as `search.score()`.
   - Select the **Reviewer** filter and the **Positive to negative** sort option, then click **Refine Results**.
   - Observe that results are filtered to include only reviews and are sorted by sentiment label.

4. **Try Additional Searches**
   - In the search box, enter `quiet hotel in New York` and review the results.
   - Try the following search terms:
     - `Tower of London` (observe this term as a key phrase in some documents)
     - `skyscraper` (this word may not appear in document content but can be found in image captions or tags)
     - `Mojave desert` (observe this term as a location in some documents)

5. **End the Demo**
   - Close the browser tab with the Margie's Travel site.
   - In the Python terminal where the app is running, press `Ctrl+C` to stop the application.

---

Enjoy exploring Margie's Travel search features!
