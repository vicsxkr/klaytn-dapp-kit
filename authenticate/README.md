# Sign and Verify a message using web3modal with metamask for Baobab network

Steps to run the application

`cd authenticate`

1. **Setup backend**
    - Rename .env.example to .env
    - `cd authentication-be`
    - `npm install`
    - `npm start`
    -  The server should be available on `http://localhost:3001`
	
2. **Setup frontend**
    - Rename .env.example to .env
    - `cd authentication-fe`
    - `yarn install`
    - `yarn run dev`
    - The frontend should be available on `http://localhost:3000`
3. Connect and Register with metamask connected to Baobab from UI
4. Login

![Authentication Flow](https://github.com/klaytn/klaytn-dapp-kit/blob/dev/authenticate/docs/authentication_flow.png?raw=true)