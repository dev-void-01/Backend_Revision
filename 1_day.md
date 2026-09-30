## Backend

It is a program that runs on the server and response to the Frontend request.

1. **Real-Life Example : Restaurant**

- Customer -> Frontend
- Waiter -> Request/Response
- Kitchen -> Backend
- Fridge/Storage -> Database

2. **Backend main work**

- To store the data.
- Make the logic work.
- Security
- Provide data to the frontend.

## Client aur Server

Client is who sends the request and wants something whereas the server is the one who receive the request and send some request.

Client (Browser) ──── Request ────► Server
◄─── Response ────

         fetch("https://jsonplaceholder.typicode.com/users/1")
         .then((res) => res.json())
         .then((data) => console.log(data));


                    fetch(url)
                        ↓
        Client (tumhara browser) server ko request bhej raha hai .then(res => res.json())
                        ↓
         Server ka response aaya, usse JSON se JS object mein badal rahe hain.then(data => console.log(data))
                        ↓
          Wo data console mein print kar rahe hain
