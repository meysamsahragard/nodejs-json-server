Source:
- https://www.techiediaries.com/fake-api-jwt-json-server/
# Quick Start
run json-server with:
- `json-server --watch db.json`
## Data pagination
You can query paginated data from your API endpoint by adding a page parameter to your endpoint. For example:
- `curl -X GET "http://localhost:3000/products?_page=1"`