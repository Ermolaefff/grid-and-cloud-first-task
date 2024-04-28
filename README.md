# Grid and cloud project (Task 1)

## Description 

The project is a toy bank simulator. 

Through the web client, you can register a new user, delete an account, or log in to existing one. After you log in to the user's account, you can transfer money between users, which will be reflected on their balances.

## Implementation

The implementation consists of three modules:
- `Database module`
- `API module` for interaction with the `Database module`
- `Frontend module` for interaction with `API module`, displaying the result to the end-user 

Each of the modules runs in its own container.

## Launch instruction

To launch app use command: 
`docker compose up --build`

Web app will be available on: `http://localhost:3000/`


