# GO-CRM

GO-CRM is a simple CRM (Customer Relationship Management) system built with Go and Fiber.

## Installation

1. Clone the repository
	```sh
	git clone https://github.com/Micah-Shallom/GO-CRM.git
	```
2. Install dependencies
	```sh
	go get -d ./...
	```
3. Run the application
	```sh
	go run main.go
	```
4. Access the application on `http://localhost:3000`

## Usage

GO-CRM provides a simple API for managing leads. The following endpoints are available:

- `GET /api/v1/lead`: Get all leads
- `GET /api/v1/lead/:id`: Get a specific lead by ID
- `POST /api/v1/lead`: Create a new lead
- `DELETE /api/v1/lead/:id`: Delete a lead by ID

## Contributing

Contributions are welcome. Feel free to open a pull request or submit an issue.

## License

Distributed under the MIT License. See `LICENSE` for more information.
