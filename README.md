#.env file copy 

PORT=8080
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=""
DB_NAME=""
JWT_SECRET=""
API_KEY=""

User API Endpoints:
1. Register a new user
HTTP Method : POST
Endpoint : http://localhost:8080/user/register

2. Login
HTTP Method : POST
Endpoint : http://localhost:8080/user/login

3. Check train availability
HTTP Method : GET
Endpoint : http://localhost:8080/user/availability?source=Howrah&destination=Asansol

4. Book Ticket :
HTTP Method : POST
Endpoint : http://localhost:8080/user/book

5. Booking Details
HTTP Method : GET
Endpoint : http://localhost:8080/user/getAllbookings

Admin API Endpoints :
1. Add a new train
HTTP Method : POST
Endpoint : http://localhost:8080/admin/addTrain

2. Update seat availability :
HTTP Method : PUT
Endpoint : http://localhost:8080/admin/update-seats/trainId  //trainId is the integer train id.

