# Register and Login using web3modal with metamask for Baobab network

Steps to run the application
`cd sign`

1. **Setup backend**
    - Rename .env.example to .env
    - `cd signature-be`
    - `npm install`
    - `npm start`
    - The server should be available on `http://localhost:3001`
2. **Setup frontend**
    - Rename .env.example to .env
    - `cd signature-fe`
    - `yarn install`
    - `yarn run dev`
    - The frontend should be available on `http://localhost:3000`
3. Sign a message with metamask connected to Baobab from UI
4. Verify the message
	a) Verify Message from UI
	b) Verify Message from Backend