# spimy.url

A URL Shortener web application.

I have decided on a relatively simple project because I wanted to give Rust a try. As such, the backend is built on Rust.

Moreover, I have always avoided React because I am not a fan of bringing HTML into JS throught JSX, but I have finally decided that it's about time I give it a try.

In other words, this project is for me to learn React and Rust. I do, however, plan to make use of this project once it is complete.

Unfortunately, there was no way to get a `spi.my` domain for this project. That's why I ended up with `spimy.url`. Using a subdomain from my `spimy.dev` domain would defeat the purpose of a short url.

## Project Stack

Subject to changes as I am still experimenting and figuring things out.

- Frontend: [React](https://react.dev/) (create-react-app)
- Backend: [Rust](https://www.rust-lang.org/)
- Database: [MongoDB](https://www.mongodb.com/)
- Payments: [Stripe](https://stripe.com/en-my)

## Feature Implementation

- [ ] User authentication through https://account.spimy.dev
- [ ] Authentication through API key
- [ ] Shorten URL to `https://spimy.url/{id}`
- [ ] Dashboard for list of links from users
- [ ] Number of use tracking
- [ ] Donation (with benefits)
